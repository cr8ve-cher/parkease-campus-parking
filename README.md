🚗 ParkEase - Smart Campus Parking System
An intelligent IoT-based parking management solution designed to solve parking congestion in college campuses through real-time monitoring, smart booking, and seamless user experience.

🌐 Live Demo
View Live Application →

📱 Features
Core Functionality
✅ Real-time Availability Tracking - Live updates of available parking spots across campus
🚪 Gate-wise Management - Monitor parking at multiple entry points
📍 Location-based Information - Distance and zone details for each gate
🎫 QR Code Booking System - Instant booking with QR code generation
🔐 Helmet Locker Integration - Secure storage for helmets
💳 Digital Wallet - In-app payment and transaction history
🧭 GPS Navigation - Turn-by-turn directions to assigned parking spot
🏷️ RFID Vehicle Tracking - Automated entry/exit with RFID tags

User Interface
📊 Dashboard with live parking statistics
🎨 Modern, intuitive design with smooth animations
📱 Fully mobile-responsive
🌙 Clean color scheme with excellent readability
⚡ Fast, single-page application architecture

🛠️ Technology Stack
Category	Technology
Frontend	React.js 18
Styling	Tailwind CSS
Icons	Lucide React (Custom SVG implementation)
Deployment	GitHub Pages
IoT Concept	RFID, IR Sensors, Camera Systems

📐 System Architecture
┌─────────────────┐
│   User Device   │
│  (Mobile/Web)   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│   React App     │
│  (Frontend UI)  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  IoT Sensors    │
│ RFID | IR | GPS │
└─────────────────┘

🚀 Quick Start

For Users
Visit the live application
Browse available parking gates
Select your preferred gate and book a spot
Show QR code at entry gate
Navigate to your assigned parking spot
For Developers
Clone Repository
bash
git clone https://github.com/cr8ve-cher/parkease-campus-parking.git
cd parkease-campus-parking
Local Development
Simply open index.html in your browser - no build process needed!

bash
# Using Python's built-in server
python -m http.server 8000

# Or using Node.js http-server
npx http-server
Then visit http://localhost:8000

📂 Project Structure
parkease-campus-parking/
│
├── index.html          # Main application file (standalone React app)
├── README.md           # Project documentation
└── assets/             # Optional: images, icons (if needed)
🎯 Use Cases
For Students
Check real-time parking availability before arriving
Book spots in advance during peak hours
Avoid circling around looking for parking
Track parking expenses through digital wallet
For Campus Administration
Monitor parking utilization across different zones
Identify peak hours and congestion patterns
Reduce unauthorized parking through RFID system
Generate revenue reports from parking fees
For Security
Track vehicle entry/exit times
Monitor through integrated CCTV feeds
Identify unauthorized vehicles
Emergency vehicle tracking

💡 Key Screens
1. Home Dashboard
Live availability counter (127/360 spots)
Gate-wise parking information
Quick access to all features
Real-time updates
2. Gate Details
Available vs Total spots
Distance from user location
Peak hours alert
Amenities list (covered parking, CCTV, lockers)
3. Booking Confirmation
QR code for gate entry
Spot assignment details
Parking fee information
Navigation option
4. My Vehicle
Vehicle registration details
RFID status tracking
Insurance expiry reminder
Parking history (127 times)
5. Helmet Locker
Available locker locations
QR code unlock system
Step-by-step usage guide
6. Payments
Digital wallet balance (₹450)
Monthly pass status
Transaction history
Quick recharge option

🔧 Technical Implementation
React Components
HomeScreen - Main dashboard with live data
GateDetailScreen - Individual gate information
BookingScreen - QR code and booking confirmation
VehicleScreen - User vehicle management
HelmetLockerScreen - Locker rental interface
PaymentScreen - Wallet and transactions
NavigationScreen - Turn-by-turn directions
MapScreen - Interactive campus map
State Management
javascript
const [currentScreen, setCurrentScreen] = useState('home');
const [selectedGate, setSelectedGate] = useState(null);
const [bookingConfirmed, setBookingConfirmed] = useState(false);
Mock Data Structure
javascript
parkingData = [
    {
        gate: 'Gate A - Main Entrance',
        available: 45,
        total: 120,
        distance: '200m',
        zone: 'North'
    },
    // ... more gates
]

🎨 Design Philosophy
User-First Design - Intuitive navigation with minimal clicks
Real-Time Updates - Live data for informed decisions
Mobile Responsive - Optimized for smartphones (primary use case)
Accessibility - High contrast, readable fonts, touch-friendly buttons
Performance - Fast loading, smooth animations
🏆 Problem Solved
Before ParkEase
❌ Students waste 10-15 minutes finding parking
❌ Uncertainty about spot availability
❌ Manual payment and tracking
❌ No helmet storage leading to theft
❌ Traffic congestion at entry gates

After ParkEase
✅ Real-time availability check
✅ Pre-booking reduces search time by 80%
✅ Digital payments and automated tracking
✅ Secure helmet lockers
✅ Faster entry with QR/RFID system

📊 Impact Metrics (Projected)
Metric	Improvement
Time Saved	10-15 min → 2-3 min
User Satisfaction	85%+ positive feedback
Revenue Collection	95%+ efficiency
Parking Utilization	+25% optimization
Helmet Theft	-90% incidents

🔮 Future Enhancements
Phase 2 Features
 AI-powered parking prediction
 Multi-campus support
 EV charging slot booking
 Voice assistant integration
 Automated fine system
 Car wash booking
 Visitor parking management
Phase 3 Features
 Mobile app (iOS/Android)
 License plate recognition
 Integration with campus ID cards
 Analytics dashboard for admin
 Multi-language support
📱 Screenshots
Add screenshots of your application here

[Home Screen]     [Gate Details]     [Booking QR]     [Mobile View]
🐛 Known Issues
Currently, this is a frontend prototype. Backend integration required for:

Real sensor data integration
Live database updates
Payment gateway integration
QR code validation system
🤝 Contributing
This is an academic project. For suggestions or improvements:

Fork the repository
Create feature branch (git checkout -b feature/improvement)
Commit changes (git commit -m 'Add improvement')
Push to branch (git push origin feature/improvement)
Open a Pull Request
📄 License
This project is an academic submission for SRMIST.
Educational Use Only - Not for commercial purposes.

📞 Contact
For queries related to this project:

Email: [ce1870@srmist.edu.in]
GitHub: @cr8ve-cher

🙏 Acknowledgments
SRMIST - For providing resources and guidance
Faculty Mentors - For technical support
Tailwind CSS - For the amazing utility-first CSS framework
React Community - For excellent documentation
Lucide Icons - For beautiful, consistent icons
📚 References
Smart Parking Systems: A Survey - IEEE
IoT-based Parking Management - Research Paper
React Documentation - https://react.dev
Tailwind CSS - https://tailwindcss.com
GitHub Pages Documentation - https://pages.github.com
<div align="center">
⭐ Star this repository if you found it helpful!
Made with ❤️ by The Ide4tors 
(My ideation team)

View Live Demo • Report Bug • Request Feature

</div>
# parkease-campus-parking
Smart Campus Parking Management System
