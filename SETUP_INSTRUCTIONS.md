# Setup Instructions for Sri Senthil Andavar Motors Website

## Prerequisites Installation

### Step 1: Install Node.js and npm

1. **Download Node.js**:
   - Go to https://nodejs.org/
   - Download the LTS version (recommended)
   - Run the installer and follow the setup wizard
   - This will install both Node.js and npm

2. **Verify Installation**:
   Open Command Prompt or PowerShell and run:
   ```bash
   node --version
   npm --version
   ```

### Step 2: Install Project Dependencies

1. **Navigate to project directory**:
   ```bash
   cd "c:\Users\ADMIN\OneDrive\Desktop\ramya\car service website full stake"
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

### Step 3: Configure Environment Variables

1. **Create .env file**:
   ```bash
   copy .env.example .env
   ```

2. **Edit .env file** with your email credentials:
   - Open `.env` in any text editor
   - Update `EMAIL_USER` with your Gmail address
   - Update `EMAIL_PASS` with your Gmail app password
   - Update `BUSINESS_EMAIL` with the email where you want to receive bookings

### Step 4: Start the Website

1. **Development mode** (with auto-restart):
   ```bash
   npm run dev
   ```

2. **Production mode**:
   ```bash
   npm start
   ```

3. **Open your browser** and go to:
   ```
   http://localhost:3000
   ```

## Quick Start (Alternative Method)

If you prefer to test the website without Node.js initially:

1. **Open index.html directly** in your web browser
2. The frontend will work, but forms won't submit (backend required for email functionality)

## Email Configuration for Forms

To enable contact and booking forms:

1. **Gmail Setup**:
   - Enable 2-factor authentication on your Gmail account
   - Generate an app password: https://support.google.com/accounts/answer/185833
   - Use this app password in the `.env` file

2. **Alternative Email Providers**:
   - Update the nodemailer configuration in `routes/api.js`
   - Refer to Nodemailer documentation for other providers

## Troubleshooting

### Common Issues:

1. **Port already in use**:
   - Change PORT in `.env` file to a different number (e.g., 3001)

2. **Email not sending**:
   - Check your Gmail app password
   - Ensure 2-factor authentication is enabled
   - Check spam folder for test emails

3. **Website not loading**:
   - Ensure all dependencies are installed
   - Check console for error messages
   - Verify Node.js version (16.0.0 or higher)

## Features Available

✅ **Working Features**:
- Responsive design (mobile, tablet, desktop)
- Multi-language support (English/Tamil)
- Interactive navigation
- Service catalog display
- Pricing information
- Contact information
- Booking modal interface

✅ **Backend Features** (when server is running):
- Contact form submissions
- Booking form submissions
- Email notifications
- Form validation
- API endpoints

## Next Steps

1. **Test the website** on different devices
2. **Customize content** as needed
3. **Set up email** for production use
4. **Deploy to hosting** service (Netlify, Vercel, or VPS)

## Support

If you encounter any issues:
1. Check the console for error messages
2. Refer to the main README.md file
3. Ensure all prerequisites are properly installed
