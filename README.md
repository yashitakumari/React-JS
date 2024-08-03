# OCHI Design - Dark Mode
This project is a React.js implementation of the OCHI Design with dark mode. It includes several components to structure the web page and uses `locomotive-scroll` for smooth scrolling.

## Overview
The OCHI Design in dark mode aims to provide a visually appealing and user-friendly interface. The main features include a responsive navbar, landing page, marquee, about section, eyes section, featured works, gallery, and footer. All components are styled to fit a dark theme using Tailwind CSS.

## App Component
The `App` component is the main component of your React application. It acts as a container that holds all other components and applies the dark mode theme to the entire application. It also initializes a smooth scrolling effect using the `locomotive-scroll` library.
Component Breakdown
1. **Import Statements**:
   - The component imports React and several custom components: `Navbar`, `LandingPage`, `Marquee`, `About`, `Eyes`, `Featured`, 
     `Gallery`, and `Footer`.
   - It also imports `locomotive-scroll` for smooth scrolling.
2. **Locomotive Scroll Initialization**:
   - Inside the `App` component, `locomotive-scroll` is initialized. This library helps achieve smooth scrolling effects across the page.
3. **Component Structure**:
   - The `App` component returns a `div` element that wraps all the other components. This `div` is styled with Tailwind CSS classes to ensure it covers the full width and height of the screen and uses a dark theme (dark background and white text).
4. **Child Components**:
   - **Navbar**: This component represents the navigation bar at the top of the page.
   - **LandingPage**: This component is likely the main landing section of your website.
   - **Marquee**: This component might display a scrolling text or image marquee.
   - **About**: This component provides information about the website or the organization.
   - **Eyes**: This component might contain a unique design element or feature related to the "Eyes" theme.
   - **Featured**: This component showcases featured works or items.
   - **Gallery**: This component displays a gallery of images or other media.
   - **Footer**: This component represents the footer section at the bottom of the page.
### Styling and Theme
- The `div` element containing all components has the classes `max-w-screen`, `h-full`, `bg-zinc-900`, and `text-white`.
  - `max-w-screen`: Ensures the `div` spans the full width of the screen.
  - `h-full`: Ensures the `div` spans the full height of the screen.
  - `bg-zinc-900`: Applies a dark background color.
  - `text-white`: Sets the text color to white, maintaining a dark theme.
### Functionality
- The main purpose of the `App` component is to serve as the root container for all other components and to apply the dark theme to the entire application.
- By including `locomotive-scroll`, it ensures that smooth scrolling is applied throughout the page, enhancing the user experience.

In summary, the `App` component sets up the overall structure, theme, and smooth scrolling for your React application, ensuring that all child components are displayed correctly and consistently within a dark mode theme.

## Usage
The App.jsx file imports all the necessary components and applies the dark mode theme using Tailwind CSS classes.
The locomotive-scroll library is used for smooth scrolling effects across the page.
Each component (Navbar, LandingPage, Marquee, About, Eyes, Featured, Gallery, Footer) is organized in the Components directory.
Feel free to explore and modify the components to suit your needs!
