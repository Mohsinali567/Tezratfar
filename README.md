# Tezraftar Delivery App

A cross-platform delivery management application built with React Native and Expo, supporting both mobile and web platforms.

## 🚀 Features

### Cross-Platform Support
- **Mobile**: iOS and Android native apps
- **Web**: Responsive web application
- **Responsive Design**: Adapts to different screen sizes
- **Platform-Specific Optimizations**: Tailored experiences for each platform

### Core Features
- **Order Management**: Track and manage delivery orders
- **Real-time Updates**: Live order status updates
- **Emergency Contacts**: Quick access to emergency services
- **Wallet Management**: COD tracking and financial management
- **Profile Management**: Rider profile and settings

## 📱 Platform Support

### Mobile (iOS/Android)
- Native performance
- Touch-optimized interface
- Platform-specific navigation
- Camera and location services
- Push notifications

### Web
- Responsive design
- Desktop and tablet optimized
- Keyboard and mouse support
- Browser-based features
- Progressive Web App (PWA) ready

## 🛠️ Technical Stack

- **Framework**: React Native with Expo
- **Navigation**: Expo Router
- **UI Components**: Custom responsive components
- **State Management**: React Context + Zustand
- **Icons**: Lucide React Native
- **Styling**: Platform-specific responsive styles

## 📦 Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for web
npm run build:web

# Build for mobile
npx expo build
```

## 🌐 Running on Different Platforms

### Web Development
```bash
npx expo start --web
```

### Mobile Development
```bash
npx expo start
```

### iOS Simulator
```bash
npx expo start --ios
```

### Android Emulator
```bash
npx expo start --android
```

## 📁 Project Structure

```
project/
├── app/                    # Expo Router pages
│   ├── (tabs)/            # Tab navigation screens
│   └── _layout.tsx        # Root layout
├── components/            # Reusable components
│   ├── CrossPlatformCard.tsx
│   ├── ResponsiveContainer.tsx
│   └── ResponsiveGrid.tsx
├── contexts/              # React Context providers
├── utils/                 # Utility functions
│   ├── platform.ts        # Platform detection
│   └── responsiveStyles.ts # Responsive styling
├── services/              # API and external services
└── types/                 # TypeScript type definitions
```

## 🎨 Responsive Design

The app uses a responsive design system that adapts to different screen sizes:

### Breakpoints
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

### Platform-Specific Features

#### Mobile
- Bottom tab navigation
- Touch-optimized buttons
- Native shadows and elevation
- Gesture support

#### Web
- Fixed bottom navigation
- Hover effects
- CSS shadows
- Grid layouts
- Keyboard navigation

## 🔧 Configuration

### Environment Variables
Create a `.env` file with:
```
EXPO_PUBLIC_WHATSAPP_API_URL=your_whatsapp_api_url
EXPO_PUBLIC_WHATSAPP_API_TOKEN=your_whatsapp_token
EXPO_PUBLIC_WHATSAPP_PHONE_NUMBER_ID=your_phone_number_id
EXPO_PUBLIC_GOOGLE_MAPS_API_KEY=your_google_maps_key
EXPO_PUBLIC_APP_NAME=Tezraftar
EXPO_PUBLIC_API_URL=your_api_url
```

## 📱 Building for Production

### Web Build
```bash
npm run build:web
```

### Mobile Build
```bash
# iOS
npx expo build --platform ios

# Android
npx expo build --platform android
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test on both mobile and web
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support and questions:
- Create an issue in the repository
- Check the documentation
- Review the code examples

---

**Built with ❤️ using React Native and Expo**