# Business Ratio Dashboard

## Overview

A web-based financial dashboard application that calculates and visualizes key business financial ratios and metrics. The application provides an interactive interface for users to input financial data and receive real-time calculations of important business performance indicators. Built as a single-page application with a focus on simplicity and immediate feedback for financial analysis.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-page application (SPA)** built with vanilla HTML, CSS, and JavaScript
- **Responsive design** using Tailwind CSS framework for consistent styling across devices
- **Component-based layout** with distinct sections for input forms and data visualization
- **Real-time calculation engine** that updates metrics as users input financial data
- **Chart.js integration** for interactive data visualization and graphical representation of financial ratios

### Data Management
- **Client-side data processing** with no backend dependencies
- **Form-based input system** for collecting financial metrics like revenue, expenses, and other key business indicators
- **Immediate calculation and display** of derived financial ratios without server round-trips
- **Local state management** through JavaScript for maintaining form data and calculated results

### User Interface Design
- **Grid-based layout** separating input controls from visualization areas
- **Responsive grid system** that adapts from single-column on mobile to multi-column on desktop
- **Card-based component design** with shadow effects and rounded corners for visual hierarchy
- **Color-coded theming** with primary, secondary, success, danger, and warning color schemes for different data states

### Calculation Engine
- **Real-time computation** of financial ratios as users modify input values
- **Form validation** to ensure data integrity and prevent calculation errors
- **Dynamic updates** to charts and displays without page reloads

## External Dependencies

### CSS Framework
- **Tailwind CSS** (via CDN) - Utility-first CSS framework for rapid UI development and consistent styling

### Data Visualization
- **Chart.js** (via CDN) - JavaScript charting library for creating interactive financial ratio visualizations and graphs

### Browser APIs
- **HTML5 Form API** - For input validation and form handling
- **DOM Manipulation** - Native JavaScript for dynamic content updates and user interaction handling

The application is designed to be lightweight and self-contained, requiring only a modern web browser to function without any server-side infrastructure or database dependencies.