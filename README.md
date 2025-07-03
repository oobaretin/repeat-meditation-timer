# REPEAT: Mindfulness Meditation Timer

A minimalist, AI-powered meditation timer for repetitive affirmation or mantra practice. Built with React Native and Expo for cross-platform mobile experience.

## 🧘‍♀️ Features

### Core Functionality
- **Customizable Repetition Counter**: Set target repetitions (1–1,000,000+)
- **Central Timer Controls**: Large tappable interface for start, pause, resume, restart
- **Adjustable Delay Interval**: User-configurable seconds between counts
- **Immersive Audio Experience**: Choose from mala bead, gong, quartz, or other subtle sounds

### User Experience
- **Minimalist, Calming UI**: Clean interface with smooth transitions and gentle animations
- **Progress Visualization**: Track total repetitions, streaks, milestones, and session history
- **AI-Driven Personalization**: Adaptive session suggestions and context-aware reminders
- **Accessibility Features**: Voice/gesture controls, adjustable font size/colors

## 🏗️ Architecture

### Frontend (Mobile App)
- **Framework**: React Native with Expo
- **State Management**: Redux Toolkit
- **Navigation**: React Navigation
- **UI Components**: Custom components with Expo Linear Gradient
- **Audio**: Expo Audio for sound feedback
- **Haptics**: Expo Haptics for tactile feedback

### Backend (API)
- **Runtime**: Node.js with Express
- **Database**: MongoDB for user data and session tracking
- **AI Integration**: OpenAI API for personalization features
- **Authentication**: JWT-based user authentication

### Development & Deployment
- **Version Control**: GitHub with automated workflows
- **Design**: Figma for wireframes and UI design
- **Project Management**: Notion for task tracking
- **Deployment**: Netlify for web components, Expo for mobile builds

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Expo CLI
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/oobaretin/repeat-meditation-timer.git
   cd repeat-meditation-timer
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Run on device/simulator**
   - iOS: `npm run ios`
   - Android: `npm run android`
   - Web: `npm run web`

## 📱 App Structure

### Screens
- **Onboarding**: Introduction and feature overview
- **Timer**: Main meditation interface with circular progress
- **Settings**: Customization options for duration, repetitions, sounds
- **Progress**: Statistics, streaks, and achievement tracking

### Key Components
- `TimerCircle`: Circular progress indicator with time display
- `RepetitionCounter`: Current/target repetition display
- `SoundSelector`: Audio feedback options
- `ProgressChart`: Visual progress tracking
- `AIInsights`: Personalized recommendations

## 🎨 Design System

### Color Palette
- **Primary**: #6B73FF (Calming Blue)
- **Secondary**: #9B59B6 (Mindful Purple)
- **Accent**: #FFFFFF (Pure White)
- **Background**: Linear gradients for depth

### Typography
- **Headers**: Bold, clean sans-serif
- **Body**: Readable, accessible font sizes
- **Timer**: Large, prominent display

### Animations
- Smooth transitions between states
- Gentle breathing animations during sessions
- Subtle feedback for user interactions

## 🤖 AI Features

### Personalization
- **Adaptive Suggestions**: Session recommendations based on usage patterns
- **Context-Aware Reminders**: Intelligent notification timing
- **Progress Insights**: AI-generated meditation insights
- **Habit Formation**: Personalized guidance for building consistency

### Implementation
- OpenAI GPT integration for natural language processing
- User behavior analysis for pattern recognition
- Privacy-first approach with local data processing where possible

## 📊 Progress Tracking

### Metrics
- Total meditation sessions
- Total time meditated
- Current streak
- Weekly/monthly goals
- Achievement milestones

### Visualizations
- Progress rings and bars
- Calendar heat maps
- Trend charts
- Achievement badges

## 🔧 Development Workflow

### Project Management
- **Planning**: Notion workspace for feature planning
- **Design**: Figma for wireframes and prototypes
- **Development**: GitHub for version control and collaboration
- **Testing**: Automated testing with Jest and Detox
- **Deployment**: Continuous deployment with GitHub Actions

### Code Structure
```
src/
├── components/          # Reusable UI components
├── screens/             # Screen components
├── redux/               # State management
│   ├── slices/          # Redux slices
│   └── store.js         # Store configuration
├── services/            # API and external services
├── utils/               # Helper functions
├── assets/              # Images, sounds, fonts
└── styles/              # Global styles and themes
```

## 🧪 Testing

### Testing Strategy
- **Unit Tests**: Component and utility function testing
- **Integration Tests**: Screen and flow testing
- **E2E Tests**: Full user journey testing
- **Performance Tests**: Memory and battery usage optimization

### Running Tests
```bash
# Unit tests
npm test

# E2E tests
npm run test:e2e

# Performance tests
npm run test:performance
```

## 🚀 Deployment

### Mobile App
- **iOS**: App Store deployment via Expo Application Services (EAS)
- **Android**: Google Play Store deployment via EAS
- **Testing**: TestFlight (iOS) and Internal Testing (Android)

### Web Components
- **Hosting**: Netlify for documentation and web interface
- **CDN**: Global content delivery for optimal performance
- **SSL**: Automatic HTTPS with custom domain support

## 🤝 Contributing

We welcome contributions to make REPEAT even better! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests for new functionality
5. Submit a pull request

### Code Style
- ESLint configuration for consistent code style
- Prettier for automatic code formatting
- Conventional commits for clear commit messages

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Meditation community for inspiration and feedback
- Open source contributors and maintainers
- Design inspiration from mindfulness and wellness apps
- React Native and Expo teams for excellent development tools

## 📞 Support

For support, feature requests, or bug reports:
- **Issues**: [GitHub Issues](https://github.com/oobaretin/repeat-meditation-timer/issues)
- **Discussions**: [GitHub Discussions](https://github.com/oobaretin/repeat-meditation-timer/discussions)
- **Email**: support@repeat-meditation.app

---

**Start your mindful journey today with REPEAT** 🧘‍♀️✨