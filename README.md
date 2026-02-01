# Giveth – Transparent Charity Donations

A hackathon project that demonstrates transparent charity donations using blockchain technology, designed for non-technical users and hackathon judges.

## 🎯 Project Goal

Create a simple, beginner-friendly website that shows how charity funds are used in a decentralized and transparent way, without confusing users with blockchain jargon.

## 🛠 Tech Stack

- **Frontend**: React + Vite + TypeScript
- **Styling**: Tailwind CSS
- **Routing**: React Router
- **Blockchain**: ethers.js (integration ready)
- **Design**: Mobile-first, responsive design

## 🌟 Key Features

### 1. **Home Page**
- Hero section with clear value proposition
- 3 feature cards explaining the core benefits
- Trust indicators and social proof
- Demo mode activation

### 2. **Donate Page (3-Step Flow)**
- **Step 1**: Connect Wallet (simplified wallet connection)
- **Step 2**: Enter Amount & Select NGO
- **Step 3**: Confirm and Donate with success animation

### 3. **Transparency Dashboard**
- Real-time fund tracking
- Progress bars showing fund allocation
- Visual flow diagram
- Recent activity feed

### 4. **Fund Usage Timeline**
- Package delivery-style tracking
- Step-by-step donation journey
- Status badges and timestamps
- Proof document links

### 5. **NGO Profile Page**
- Credibility scoring system
- Trust badges and indicators
- Proof history
- Success metrics

### 6. **Demo Mode**
- Auto-animating donation flow
- Mock data for judge demonstrations
- Real-time status updates
- One-click demo activation

## 🎨 Design Principles

- **Simple Language**: Avoid blockchain jargon
  - "Smart Contract" → "Secure Lock"
  - "Transaction Hash" → "Donation ID"
  - "Wallet Address" → "Secure Account"

- **Trust Colors**: Green, blue, and white for safety
- **Large Elements**: Big buttons and readable fonts
- **Visual Clarity**: Icons and emojis throughout
- **Mobile-First**: Responsive design for all devices

## 🚀 Getting Started

### Prerequisites
- Node.js 20+ 
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd giveth
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 📱 Pages & Routes

- `/` - Home page with hero and features
- `/donate` - 3-step donation flow
- `/dashboard` - Transparency dashboard
- `/timeline` - Fund usage timeline
- `/ngo/:id` - NGO profile page

## 🎭 Demo Mode

Perfect for hackathon presentations! Click "Try Demo" on the home page to:
- Auto-fill donation data
- Animate the complete fund flow
- Show donation → proof → release process
- Demonstrate all features in 30 seconds

## 🔧 Future Enhancements

- **Blockchain Integration**: Connect to real smart contracts
- **Real Wallets**: MetaMask and WalletConnect integration
- **IPFS Storage**: Decentralized proof document storage
- **NGO Verification**: Real NGO onboarding process
- **Notifications**: Email/SMS donation updates

## 🏆 Hackathon Ready

This project is designed specifically for hackathon success:
- ✅ **Quick Setup**: Runs in 2 minutes
- ✅ **Judge Friendly**: Clear value proposition
- ✅ **Demo Ready**: One-click demo mode
- ✅ **Visually Appealing**: Modern, clean design
- ✅ **Complete Flow**: End-to-end user journey

## 📂 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Navbar.tsx      # Navigation bar
│   ├── Footer.tsx      # Footer component
│   ├── ProgressBar.tsx # Custom progress bar
│   ├── TrustBadge.tsx  # NGO credibility badge
│   ├── EmptyState.tsx  # Empty state component
│   └── ...
├── pages/              # Page components
│   ├── HomePage.tsx    # Landing page
│   ├── DonatePage.tsx  # Donation flow
│   ├── DashboardPage.tsx # Fund dashboard
│   ├── TimelinePage.tsx # Donation timeline
│   └── NGOProfilePage.tsx # NGO profiles
├── hooks/              # Custom React hooks
│   └── useDemoMode.ts  # Demo mode logic
├── data/               # Mock data
│   └── mockData.ts     # Sample donations and NGOs
└── utils/              # Utility functions
```

## 🤝 Contributing

This is a hackathon project. Feel free to fork and enhance for your own projects!

## 📄 License

MIT License - feel free to use this project for learning and development.
