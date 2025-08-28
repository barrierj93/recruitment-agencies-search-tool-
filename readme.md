# Irish Recruitment Agency Dashboard

A clean, professional web-based dashboard for exploring and filtering recruitment agencies across Ireland. Built with vanilla HTML, CSS, and JavaScript for easy deployment and usage.

## Features

- 📊 **Interactive Filtering**: Filter by county, specialization fields, agency name, and available contact methods
- 📧 **Email Export**: Copy all filtered email addresses to clipboard in email client format
- 📱 **Responsive Design**: Works on desktop and mobile devices
- 🎯 **Contact Filtering**: Filter agencies that have specific contact information (email, phone, website)
- 📈 **Real-time Stats**: Live statistics showing total agencies, filtered results, counties, and specializations

## Quick Start

1. **Download the files**:
   - `index.html` - The dashboard application
   - `enriched_recruitment_v10_with_fields.csv` - Sample data file

2. **Open the dashboard**:
   - Open `index.html` in any modern web browser
   - No server required - runs entirely in the browser

3. **Load your data**:
   - Click "Upload File" or drag and drop the CSV file
   - The dashboard will automatically populate with your data

## Usage

### Uploading Data
- Click the "Upload File" button in the header
- Select your CSV file (must be semicolon-separated)
- The dashboard will parse and display your data automatically

### Filtering Options
- **County**: Filter agencies by Irish county
- **Covered Fields**: Filter by recruitment specialization
- **Agency Name**: Search by agency name (real-time search)
- **Contact Information**: Filter agencies that have email, phone, or website information

### Copying Emails
- After applying filters, click "Copy All Emails" in the results header
- All unique email addresses from filtered results will be copied to clipboard
- Format is email client ready (semicolon-separated)

## CSV Format

Your CSV file should be semicolon-separated (`;`) with the following columns:
- `Agency_Name` - Name of the recruitment agency
- `County` - Irish county location
- `Covered_Fields` - Specialization areas (comma or pipe-separated for multiple)
- `Email` - Email address(es) (pipe-separated for multiple)
- `Phone` - Phone number
- `Website` - Website URL
- `Address` - Physical address

## Browser Compatibility

Works on all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+



## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).