# Language Translator

## Overview

A modern web-based language translation tool that provides real-time text translation between multiple languages. The application features a clean, responsive interface with support for auto-language detection, character counting, and file upload capabilities. Built as a client-side application using vanilla web technologies and powered by the Google Translate API for accurate translations.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single Page Application (SPA)**: Built with vanilla HTML5, CSS3, and JavaScript ES6+ without any frameworks
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox for layout management
- **Component-based Structure**: Modular JavaScript with separate files for languages data and main application logic
- **Event-driven Architecture**: DOM event listeners handle user interactions and real-time updates

### UI/UX Design Patterns
- **Card-based Layout**: Clean interface with input and output sections organized in card components
- **Dropdown Components**: Custom dropdown menus for language selection with active state management
- **Dark/Light Theme**: CSS custom properties (variables) enable dynamic theme switching
- **Character Counting**: Real-time input validation with 5000 character limit display

### Data Management
- **Static Language Data**: Comprehensive language list stored in separate JavaScript module with language codes, names, and native scripts
- **Local State Management**: Application state managed through DOM manipulation and JavaScript variables
- **File Handling**: Client-side file upload and processing for document translation

### Translation Integration
- **Google Translate API**: External API integration for translation services
- **Auto-detection**: Automatic source language detection capability
- **Real-time Translation**: Immediate translation as user types or selects different languages

## External Dependencies

### APIs and Services
- **Google Translate API**: Core translation service requiring API key configuration and Google Cloud Console project setup
- **Ionicons**: Icon library (v5.5.2) loaded via CDN for UI icons including globe, chevron, and swap icons

### Browser Dependencies
- **Modern Browser Support**: Requires ES6+ support for modern JavaScript features
- **File API**: For document upload functionality
- **DOM API**: Extensive use of modern DOM manipulation methods

### Development Tools
- **No Build Process**: Direct browser execution without compilation or bundling
- **CDN Dependencies**: External resources loaded via unpkg CDN for icons
- **Static Hosting**: Can be deployed on any static file hosting service