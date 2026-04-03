# TaxiHighlandsApp

A taxi service app for the Aviemore area in the Scottish Highlands.

## Apps

- **Driver App**: React Native app for taxi drivers to manage rides, navigation, and earnings.

## Features

### Driver App
- **Authentication**: Secure login system with persistent sessions
- **Intuitive Navigation**: Bottom tab navigation with Dashboard, Profile, and Earnings
- **Smart Status Management**: Online/offline toggle with confirmation dialogs
- **Real-time Ride Requests**: Modal alerts for incoming rides with accept/reject
- **Trip Lifecycle**: Complete ride management (accepted → arrived → started → completed)
- **Enhanced Navigation**: Context-aware pickup/dropoff navigation with maps integration
- **Earnings Dashboard**: Comprehensive earnings tracking with activity history
- **Profile Management**: Complete driver information with approval status
- **User-Friendly UX**: Large touch targets, clear visual feedback, confirmation dialogs

## Navigation Structure

### Bottom Tabs
- **Dashboard**: Main control center with online toggle, active rides, and quick actions
- **Profile**: Driver information, vehicle details, and account settings
- **Earnings**: Income tracking, activity history, and financial reports

### User Flow
1. **Login** → Clean authentication screen
2. **Dashboard** → Status overview and ride management
3. **Go Online** → Start receiving ride requests
4. **Accept Rides** → Modal popup with ride details
5. **Navigate** → Turn-by-turn directions to pickup/dropoff
6. **Complete Trips** → Automatic earnings calculation
7. **Track Earnings** → Detailed financial overview

## Design Principles

### Intuitive Interface
- **Visual Hierarchy**: Most important actions (online toggle) prominently displayed
- **Status Clarity**: Color-coded states throughout the app
- **Touch-Friendly**: Large buttons and adequate spacing for mobile use
- **Context Awareness**: UI adapts based on driver status and current activity

### User Experience
- **Confirmation Dialogs**: Prevent accidental actions (going offline, completing trips)
- **Loading States**: Clear feedback during state changes
- **Error Prevention**: Disabled states when actions aren't available
- **Progressive Disclosure**: Information revealed as needed

### Accessibility
- **High Contrast**: Clear text on colored backgrounds
- **Large Touch Targets**: Minimum 44px touch areas
- **Screen Reader Support**: Semantic elements and descriptive labels
- **Color Independence**: Status conveyed through multiple visual cues

## Getting Started

### Driver App

1. Navigate to the `DriverApp` directory.
2. Install dependencies: `npm install`
3. For iOS development, open the `ios/DriverApp.xcworkspace` in Xcode on a Mac.
4. For Android: `npx react-native run-android`
5. For iOS: `npx react-native run-ios` (requires macOS and Xcode)

### Demo Credentials
- Email: `driver@aviemore.com`
- Password: `password`

## Development Notes

- Mock ride requests are generated automatically when driver is online
- Navigation buttons are currently placeholders (integrate with maps API for production)
- Earnings are tracked in-memory (integrate with backend for persistence)
- Driver profile is hardcoded (integrate with backend for dynamic data)

## Design Documentation

See `DESIGN.md` for complete design system documentation including:
- Color palette and usage guidelines
- Typography scale and hierarchy
- Component patterns and spacing
- User experience flow descriptions
- Accessibility considerations
- Password: `password`

## Development Notes

- Mock ride requests are generated automatically when driver is online
- Navigation buttons are currently placeholders (integrate with maps API for production)
- Earnings are tracked in-memory (integrate with backend for persistence)
- Driver profile is hardcoded (integrate with backend for dynamic data)

## Design Documentation

See `DESIGN.md` for complete design system documentation including:
- Color palette and usage guidelines
- Typography scale and hierarchy
- Component patterns and spacing
- User experience flow descriptions
- Accessibility considerations