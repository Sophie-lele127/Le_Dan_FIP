# Couples Resort Website

## Project Overview

The Couples Resort website is a multi-page web project designed to showcase the luxury and charm of Couples Resort. It includes pages for showcasing rooms, packages, spa activities, and reservations while maintaining an elegant and user-friendly interface.

---

## Features

- **Home Page (`index.html`)**: Overview of the resort's offerings, including a hero section with dynamic content.
- **About Page (`about.html`)**: Detailed insights into the history, features, and luxury amenities of Couples Resort.
- **Rooms Page (`rooms.html`)**: Showcase of available room categories such as Chateaus, Villas, and Masters.
- **Chateaus Page (`chateaus.html`)**: In-depth information about premium Chateaus accommodations.
- **Events Page (`desktops_events.html`)**: Highlight special offers, such as the Valentine's Special Retreat and Winter Escape Package.
- **Reservations Page (`reservations.html`)**: Functional booking form for users to schedule their stay.

---

## File Structure

```
/
├── index.html                 # Home Page
├── about.html                 # About the resort
├── rooms.html                 # Overview of rooms
├── chateaus.html              # Detailed Chateaus page
├── desktops_events.html       # Events and special offers
├── reservations.html          # Booking page
├── css/                       # Stylesheets
│   ├── grid.css               # Layout grid styles
│   ├── menu_header.css        # Header and navigation styles
│   ├── styles_desktop.css     # Desktop-specific styles
│   ├── main.css               # General styles
└── images/                    # Images used across the site
    ├── hero-images            # Hero section images
    ├── room-images            # Room-specific images
    ├── logo_CR.jpg            # Logo
    └── other-assets           # Icons and additional graphics
```

---

## Technologies Used

- **HTML5**: Semantic structure for better accessibility and SEO.
- **CSS3**: Modern design techniques using Grid, Flexbox, and custom styling.
  - `grid.css`: Defines grid layouts for responsive design.
  - `menu_header.css`: Styles for the navigation and header.
  - `styles_desktop.css`: Styles optimized for desktop displays.
  - `main.css`: General styles for fonts, buttons, and utility classes.
- **Google Fonts**: Fonts like `Poppins` and `Playfair Display` for professional typography.
- **FontAwesome**: Icons for navigation and content.

---

## Development Workflow

### Branch Naming Convention

- **Design Branches**:
  - `des.dl.home` - For the Home Page design.
  - `des.dl.rooms` - For the Rooms Page design.
- **Development Branches**:
  - `dev.dl.home` - For Home Page development.
  - `dev.dl.rooms` - For Rooms Page functionality.

### Workflow

1. **Design**: Start with `des.<branch>` to create the layout and styles for each page.
2. **Development**: Switch to `dev.<branch>` for integration and adding interactivity.
3. **Testing**: Validate and optimize for mobile (412px) and desktop (1200px).
4. **Merge**: Push completed work to the `main` branch.

---

## Accessibility

- Designed for **WCAG 2.1** compliance.
- Includes semantic HTML, ARIA labels, and responsive layouts.
- Tested for HTML and CSS validity using the W3C validators.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd couples-resort
   ```
3. Open `index.html` in your preferred browser to preview the website.

---

## Future Enhancements

- Implement dynamic elements with JavaScript for enhanced interactivity.
- Add animations and transitions to improve user experience.
- Integrate backend systems for real-time reservations.

---

## Credits

- **Developer**: Dan Le
- **Images**: Provided by Couples Resort design team.
- **Typography**: Powered by Google Fonts.
- **Icons**: FontAwesome.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
