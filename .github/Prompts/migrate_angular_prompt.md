Migrate this Angular 7 project to Angular 8.

Steps:
1. Update Angular core and related dependencies from version 7 to 8
2. Update Angular CLI to version 8 if required
3. Update RxJS, TypeScript, and zone.js to Angular 8 compatible versions
4. Enable and configure Ivy compiler only if required (keep default behavior unless explicitly needed)
5. Replace deprecated APIs and fix breaking changes
6. Update configuration files (angular.json, tsconfig.json, etc.) if required for Angular 8
7. Fix compilation errors and runtime issues
8. Ensure the application builds and runs successfully

Commands to consider:
- ng update @angular/cli@8 @angular/core@8
- npm install
- ng build
- ng serve

Output:
- List of updated files
- Commands executed
- Summary of changes
- Any remaining warnings or manual fixes required