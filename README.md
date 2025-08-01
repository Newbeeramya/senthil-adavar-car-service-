# Sri Senthil Andavar Motors - Professional Car Service Website

A comprehensive full-stack website for Sri Senthil Andavar Motors, a professional car service center located in Trichy, Tamil Nadu.

## 🚗 Features

### Frontend
- **Responsive Design**: Mobile-first approach with Flexbox layout
- **Multi-language Support**: English and Tamil (தமிழ்)
- **Modern UI/UX**: Following brand guidelines with black background and action orange accents
- **Interactive Elements**: Smooth scrolling, animations, and hover effects
- **Service Catalog**: Comprehensive display of all automotive services
- **Online Booking System**: Easy appointment scheduling with modal interface
- **Contact Forms**: Multiple contact points for customer inquiries
- **Pricing Display**: Transparent pricing with special offers

### Backend
- **Node.js/Express**: RESTful API architecture
- **Email Integration**: Automated email confirmations using Nodemailer
- **Form Validation**: Server-side validation with express-validator
- **Security**: Helmet.js, CORS, rate limiting, and input sanitization
- **Performance**: Compression, caching, and optimized responses

### Services Offered
- Rubber Polish Double Coating
- Head Light & Windshield Glass Polish
- Interior Cleaning
- General Check-up
- AC Foam Cleaning
- Brake Cleaning
- Water/Foam Wash
- Under Chase Painting

### Additional Facilities
- Cashless Accidental Repairs
- Insurance Renewals
- 24/7 Breakdown Services
- Tyre & Battery Services
- Original Spare Parts
- Car Beauty Care
- Painting Booth

## 💰 Pricing

### Comprehensive Service Package
- **Original Price**: ₹6,900
- **Offer Price**: ₹4,800
- **Savings**: ₹2,100

### Vehicle-Specific Services
- Small Vehicle: ₹1,000
- Large Vehicle: ₹1,300

### Engine Oil Services
- Small Vehicle: ₹2,399
- Medium Vehicle: ₹2,499
- Large Vehicle: ₹3,499

## 🛠️ Installation & Setup

### Prerequisites
- Node.js (v16.0.0 or higher)
- npm (v8.0.0 or higher)

### Quick Start

1. **Clone/Download the project**
   ```bash
   cd "car service website full stake"
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Edit `.env` file with your actual configuration values.

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

### Production Deployment

1. **Build for production**
   ```bash
   npm run build
   ```

2. **Start production server**
   ```bash
   npm start
   ```

## 📁 Project Structure

```
sri-senthil-andavar-motors/
├── css/
│   ├── style.css          # Main stylesheet with brand guidelines
│   └── responsive.css     # Mobile-first responsive design
├── js/
│   └── main.js           # Frontend JavaScript functionality
├── routes/
│   └── api.js            # Backend API routes
├── index.html            # Main HTML file
├── server.js             # Express server configuration
├── package.json          # Dependencies and scripts
├── .env.example          # Environment variables template
└── README.md             # Project documentation
```

## 🎨 Brand Guidelines

### Colors
- **Primary Background**: Black (#000000)
- **Action Color**: Orange (#FF6B35)
- **Hover Effect**: Green (#28A745)
- **Text**: White (#FFFFFF)

### Typography
- **Headings**: Montserrat (Bold, 700)
  - H1/H2: 56px desktop, 36px mobile
  - H3: 24px desktop, 18px mobile
- **Body Text**: Open Sans
  - Paragraphs: 16px desktop, 15px mobile

### Buttons
- **Font**: Montserrat, Bold
- **Size**: 16px desktop, 15px mobile
- **Border Radius**: 5px
- **Padding**: 16px top/bottom, 32px left/right
- **Hover Effect**: Green background

## 🌐 API Endpoints

### Public Endpoints
- `GET /` - Main website
- `GET /health` - Health check
- `GET /api/services` - Get all services
- `GET /api/services/:id` - Get specific service
- `GET /api/pricing` - Get pricing information
- `GET /api/business-info` - Get business information
- `GET /api/availability/:date` - Get available time slots

### Form Endpoints
- `POST /api/contact` - Contact form submission
- `POST /api/booking` - Service booking submission

## 📧 Email Configuration

The website uses Nodemailer for email functionality:

1. **Gmail Setup** (recommended):
   - Enable 2-factor authentication
   - Generate an app password
   - Update `EMAIL_USER` and `EMAIL_PASS` in `.env`

2. **Business Email**:
   - Update `BUSINESS_EMAIL` in `.env` to receive booking notifications

## 🔒 Security Features

- **Helmet.js**: Security headers
- **CORS**: Cross-origin resource sharing protection
- **Rate Limiting**: Prevents spam and abuse
- **Input Validation**: Server-side form validation
- **XSS Protection**: Content Security Policy

## 📱 Mobile Optimization

- Mobile-first responsive design
- Touch-friendly interface
- Optimized for various screen sizes
- Fast loading on mobile networks
- Accessible navigation

## 🌍 Multi-language Support

- **English**: Default language
- **Tamil**: தமிழ் language support
- Easy language switching
- Persistent language preference

## 🚀 Performance Optimizations

- **Compression**: Gzip compression enabled
- **Caching**: Static file caching
- **Minification**: CSS and JS optimization
- **Lazy Loading**: Images and content
- **CDN Ready**: Font Awesome and Google Fonts

## 📞 Contact Information

**Sri Senthil Andavar Motors**
- **Proprietor**: E. Nirmal Kumar
- **Address**: No:6, Karur Bye Pass Road, Opp Kalaignar Arivalayam, Mala Chinthamani, Trichy - 620 002
- **Phone**: 76399 80839, 86678 75755
- **Working Hours**: 
  - Mon - Sat: 8:00 AM - 8:00 PM
  - Sunday: 9:00 AM - 6:00 PM

## 🤝 Support

For technical support or business inquiries:
- Email: info@srisenthilandavarmotors.com
- Phone: 76399 80839, 86678 75755

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🔄 Version History

- **v1.0.0** - Initial release with full-stack functionality
  - Responsive website with brand guidelines
  - Online booking system
  - Multi-language support
  - Email integration
  - Security features

---

**Built with ❤️ for Sri Senthil Andavar Motors**
