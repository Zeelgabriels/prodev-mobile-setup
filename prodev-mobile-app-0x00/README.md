# Task 0

# Mobile Development Setup

## Environment Details
- **Operating System**: [Your OS - macOS/Windows/Linux]
- **Node.js Version**: [Run `node --version`]
- **VS Code Version**: [Run `code --version`]
- **Expo Go**: Installed on [iOS/Android]

## Setup Process
1. Verified Node.js LTS installation
2. Confirmed VS Code is working
3. Downloaded Expo Go app on my [device type]
4. Created Expo account: [your-email]

## Challenges Faced
[Document any issues you encountered and how you solved them]

## Next Steps
Ready to create first React Native app using Expo framework.

# Task 1:

# First Mobile App Creation

## Scaffolding Process
1. Used `npx create-expo-app@latest .` to create app in current directory
2. Modified welcome text in `app/(tabs)/index.tsx`
3. Successfully ran app with `npx expo start`
4. Tested on device via QR code scan

## File Structure Understanding
- `app/` directory contains all screens
- `(tabs)` creates tab-based navigation
- `_layout.tsx` files control navigation structure
- `constants/` holds app-wide constants like colors

## Reset Project Observations
When running `npm run reset-project`:
- the expore.tsx file and the (tabs) folder was removed.
- _layout.tsx and index.tsx were the files remaining
- The previous display has been cleared. The new display now shows: Edit app/index.tsx to edit this screen.

## Key Learnings
- Expo Router uses file-based routing
- ThemedText adapts to device appearance settings
- Hot reloading updates app instantly