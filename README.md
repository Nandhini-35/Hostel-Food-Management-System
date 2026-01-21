# Hostel Mess Management System

A modern, responsive web application for managing hostel mess operations, tracking food wastage, and generating reports.

## Features

- **Meal Management**: Track morning, afternoon, snacks, and dinner sessions
- **Food Wastage Tracking**: Monitor and reduce food wastage
- **Photo Documentation**: Upload and view food photos
- **Analytics Dashboard**: Visualize wastage trends and meal statistics
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Offline Support**: Data is stored in the browser's localStorage

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher) or Yarn

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Hostel-Management
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

### Development Mode

1. Start the development server:
   ```bash
   npm run dev
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Production Mode

1. Build the application:
   ```bash
   npm run build
   ```
2. Start the production server:
   ```bash
   npm start
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Usage

1. **Home Dashboard**:
   - View meal cards for each session
   - See at-a-glance statistics
   - Navigate to specific meal forms

2. **Adding/Editing Meals**:
   - Click on any meal card
   - Fill in the details (people count, food quantities)
   - Upload food photos
   - Save the record

3. **Reports**:
   - View wastage trends over time
   - Analyze meal-specific statistics
   - Export data as needed

## Data Storage

All data is stored in the browser's localStorage. Clearing browser data will result in data loss. For production use, consider implementing a backend service.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Tailwind CSS](https://tailwindcss.com/)
- Icons by [Font Awesome](https://fontawesome.com/)
- Charts by [Chart.js](https://www.chartjs.org/)
