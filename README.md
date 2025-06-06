# Weather App - Reli Frontend Assessment

A weather application built with React Native and Expo that demonstrates clean UI implementation and thoughtful UX design.

## Features

- Current weather display for any city
- Detailed weather information
- Intuitive tab navigation
- Responsive design for all screen sizes
- Dark/light mode support

## Technologies Used

- React Native
- Expo
- TypeScript
- Expo Router
- React Navigation
- Fetch for API calls
- date-fns for date formatting

## Design Rationale

The app focuses on providing weather information in the most accessible way possible. Key design decisions:

- Clear hierarchy of information (temperature as most prominent)
- Consistent styling throughout
- Immediate feedback for user actions
- Thoughtful error handling
- Accessibility considerations (contrast, text sizes)

## Usability Heuristics Focus

The implementation pays special attention to:

1. **Visibility of system status**: Loading states and error messages
2. **Match between system and real world**: Weather icons match user expectations
3. **User control and freedom**: Easy navigation between views
4. **Consistency and standards**: Follows mobile UI conventions
5. **Error prevention**: Input validation and helpful defaults

## How to Run

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the development server: `npx expo start`
4. Scan the QR code with the Expo Go app or run on a simulator

## Building for iOS

To build for iOS:

1. Install EAS CLI: `npm install -g eas-cli`
2. Login: `eas login`
3. Build: `eas build --platform ios`
