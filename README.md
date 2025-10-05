# QR Event Check-In System

A modern, event management system with QR code ticket generation, email notifications, and real-time attendance tracking.

## Features

- Create and manage multiple events
- Generate digital tickets with unique QR codes
- Modern gradient-based UI with smooth animations
- Email notification simulation
- Staff scanner interface for check-ins
- Real-time attendance dashboard with live metrics
- Duplicate check-in prevention
- Glass morphism design effects
- Responsive layout for mobile and desktop

## Live Demo

[daneen975.github.io/QR-Event-Checkin-System/](https://github.com/daneen975/QR-Event-Checkin-System)

## How to Use

### Admin Tab
1. Fill in event details (name, date, time, location, capacity)
2. Click "Create Event" to add it to the system

### Generate Tickets
1. Select an event from the dropdown
2. Enter attendee name and email
3. Click "Generate & Send Ticket" to create a QR-coded ticket

### Tickets Tab
View all generated tickets with their QR codes and check-in status

### Scanner Tab
1. Copy a ticket ID from the Tickets tab
2. Paste it into the scanner input
3. Press Enter or click the search button to check in
4. System prevents duplicate check-ins

### Dashboard Tab
Monitor real-time statistics including:
- Total events
- Tickets issued
- Check-in count
- Check-in percentage
- Event-specific progress bars
- Recent email activity

## Technologies Used

- React 18
- Tailwind CSS
- Canvas API for QR code generation
- CSS animations and gradients
- Glass morphism effects

## Installation

No installation required. Simply open `index.html` in any modern web browser.

For local development:
1. Download or clone the repository
2. Open `index.html` in your browser
3. Start creating events and generating tickets

## Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Future Enhancements

- Camera integration for real QR code scanning
- Backend database for persistent storage
- Email service integration (SendGrid, AWS SES)
- User authentication and role management
- PDF ticket generation
- Export attendance reports to CSV/Excel
- Multi-language support
- Dark mode toggle

## License

MIT License

## Author

Created by daneen975
