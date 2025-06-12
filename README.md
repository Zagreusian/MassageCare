# Care Massage Website

A modern, responsive website for Care Massage, featuring online booking and SMS notifications.

## Features

- Responsive design for all devices
- Online booking system
- Google Maps integration
- SMS notifications via Twilio
- Google Sheets integration for booking management
- Customer testimonials
- Service pricing display

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Apps Script
- Twilio API
- Google Maps API
- GitHub Actions for deployment

## Setup

1. Clone the repository
2. Set up GitHub Secrets:
   - `TWILIO_ACCOUNT_SID`: Your Twilio Account SID
   - `TWILIO_AUTH_TOKEN`: Your Twilio Auth Token
   - `TWILIO_PHONE_NUMBER`: Your Twilio phone number
   - `OWNER_PHONE_NUMBER`: Your notification phone number
   - `SPREADSHEET_ID`: Your Google Sheet ID
   - `DEPLOYMENT_ID`: Your Google Apps Script deployment ID

3. Enable necessary Google services:
   - Google Sheets API
   - URL Fetch API

## File Structure

- `index.html` - Main website file
- `styles.css` - Styling and responsive design
- `appscript.js` - Google Apps Script for form handling and SMS notifications
- `.github/workflows/deploy.yml` - GitHub Actions workflow for deployment

## Development

1. Make changes to the code
2. Commit and push to GitHub
3. GitHub Actions will automatically deploy to Google Apps Script

## Security

Sensitive information is stored in GitHub Secrets and is never exposed in the code or repository.

## License

This project is private and confidential.

## Contact

Care Massage
209 S Broadview St
Cape Girardeau, MO 63703
(573) 225-7807 