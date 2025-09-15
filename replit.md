# Personal Portfolio Website

## Overview

This is a personal portfolio website for Omar Abdel Tawab Saleh, built as a static website with Arabic language support (RTL layout). The project features a modern loading page with animations and serves content through a simple Python HTTP server. The website appears to be designed to showcase personal information, skills, and projects in a professional manner.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static HTML/CSS/JavaScript**: Single-page application built with vanilla web technologies
- **RTL Layout Support**: Configured for Arabic language with right-to-left text direction
- **Responsive Design**: Uses viewport meta tags and CSS for mobile-first responsive layout
- **External Font Libraries**: Leverages Google Fonts (Poppins, Muli) for typography
- **Icon Libraries**: Integrates Font Awesome and Bootstrap Icons for visual elements
- **Loading Page**: Features a custom loading screen with CSS animations and transitions

### Styling and UI Framework
- **CSS-in-HTML**: Embedded styles within the HTML document for simplicity
- **Animation System**: Custom CSS animations for loading states and transitions
- **Color Scheme**: Dark theme with primary background color `#1f293a`
- **Font Strategy**: Multi-font approach using web fonts for better typography

### Server Architecture
- **Python HTTP Server**: Simple static file server using Python's built-in `http.server` module
- **No-Cache Headers**: Configured to prevent browser caching for development purposes
- **Port Configuration**: Runs on port 5000 with binding to all network interfaces (0.0.0.0)
- **Static File Serving**: Serves files directly from the current directory

## External Dependencies

### CDN Resources
- **Font Awesome 6.0.0-beta3**: Icon library for UI elements
- **Bootstrap Icons 1.10.5**: Additional icon set for enhanced visual design
- **Google Fonts API**: 
  - Poppins font family (multiple weights: 300-900)
  - Muli font family for additional typography options

### Runtime Dependencies
- **Python 3**: Required for the development server
- **Standard Library Modules**:
  - `http.server`: For serving static files
  - `socketserver`: For TCP server functionality
  - `os`: For file system operations

### Browser Compatibility
- Modern web browsers with CSS3 and HTML5 support
- RTL language support for Arabic text rendering
- Font loading and web font compatibility