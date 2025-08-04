Responsive React Navbar with Theme Toggle

This is a responsive React `Navbar` component that supports light/dark theme toggling, mobile sliding menu, and navigation links using React Router.

Features

- Responsive navigation bar
-  Light/Dark mode toggle
-  Slide-in mobile menu
-  Navigation handled with `react-router-dom`
-  Dynamic logo changes with theme
-  Separate buttons for Login and Dashboard (visible both desktop and mobile)

Technologies Used

- React
- React Router
- Context API (for Theme)
- CSS

Folder Structure

src/
├── assets/
│ ├── logo.png
│ └── logo-white.png
├── components/
│ └── Navbar.jsx
│ └── Navbar.css
├── context/
│ └── ThemeContext.jsx