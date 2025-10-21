# AGENTS.md

## Build/Lint/Test Commands
- Start dev server: `npm start` or `npx expo start`
- Build Android: `npm run android`
- Build iOS: `npm run ios`
- Build web: `npm run web`
- Lint: `npm run lint`
- No tests configured

## Architecture
- Expo React Native app using expo-router for file-based routing
- Main directories: app/ (routes), components/, hooks/, constants/, assets/
- Tabs layout: Home and Explore screens
- Uses React Navigation with theme provider
- New architecture enabled, React Compiler enabled

## Code Style Guidelines
- TypeScript with strict mode enabled
- Import alias: `@/*` for root-relative imports
- Naming: PascalCase for components, camelCase for variables/functions
- Colors and fonts in constants/theme.ts
- ESLint with expo-config-expo
- Components in components/ui/ for reusable UI
- Hooks in hooks/ for custom logic
