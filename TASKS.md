### Tasks / User Stories
As required follows the series of steps to be taken to build this app and its estimations.

1) Scaffolding (4h)
   - Scaffold the monorepo and generating essential development environment and folders. Eg: App, services, typescript/linter, and design system.
2) Implement generic error handlers (1h)
3) add storybook, fonts and theme (3h)
4) Scaffold routes (1h)
5) Implement List + Forecast screens (8h)
   1) Setup services(API), types etc.
   2) Write down components in the design system library
   3) Assemble previous items in List and forecast screen with its rendering conditions.
6) Offline Mode (1h)*
7) Make Splash screen and app icon (1h)
8) setup route restauration (0h)
9)  write unit/integration tests, comments and documentation (3h)
10) enable dark-mode (0h)

#### Disclaimer:
6) (offline mode) I tried using Realm as DB, but it broke the build. Due my limited time i had little to invest in fixing it. Normally developing on windows, scripts are often frail but quickly inspecting i assume think is version mismatch and duplicated dependencies. Therefore Offline mode works through ReactQuery instead, which works fine **as long data is cached previously**
