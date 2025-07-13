# prodev-mobile-app-0x00

## Objective

Set up my first mobile application using the Expo Router template. Understand the file structure of a React Native application built with Expo and document the setup and reset process.

## Steps Followed for Scaffolding

1. Opened terminal and navigated to my parent project directory:

   cd prodev-mobile-setup

2. Created and moved into the project directory:

   mkdir prodev-mobile-app-0x00
   cd prodev-mobile-app-0x00

3. Initialized a new Expo project using the latest Expo Router template by running:

   npx create-expo-app@latest .

4. Opened the home screen file at:

   app/(tabs)/index.tsx

5. Located the default text:

   <Text className="text-2xl font-bold">Welcome!</Text>

   ```

   ```

6. Changed the text to:
   <Text className="text-2xl font-bold">** First App Created**</Text>

7. Saved the file.

8. Started the Expo development server by running:

   npx expo start

9. Scanned the QR code with my physical device using:

   - **Android:** Expo Go app

10. Verified the app runs successfully and displays the updated home screen text.

---

## Observations from Running `npm run reset-project`

1. Ran the reset command:

   npm run reset-project

2. When prompted:

   Do you want to move existing files to /app-example instead of deleting them? (Y/n):

   ```

   Chose **Yes (Y)** to move files instead of deleting.

   ```

3. The script created a new directory `/app-example`.

4. The existing source folders, including `/app`, `/components`, `/constants`, `/hooks`, and `/scripts`, were moved into `/app-example`.

5. This preserved the original source code safely in `/app-example` for reference or backup.

6. A fresh minimal `/app` folder with starter files was created for a clean slate.

7. After reset, I ran the development server again using:

   ```bash
   npx expo start
   ```

8. Noted that the new `/app` folder contains only basic starter files (`index.tsx` and `_layout.tsx`).

9. To continue development, I can reference or restore code from `/app-example`.
