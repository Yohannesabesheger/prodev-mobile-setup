# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.


The following occurred:

- 📁 **/app-example directory created**
- ➡️ Existing folders moved:
  - `/app → /app-example/app`
  - `/components → /app-example/components`
  - `/hooks → /app-example/hooks`
  - `/constants → /app-example/constants`
  - `/scripts → /app-example/scripts`
- 📁 **New `/app` directory created** with fresh structure:
  - `app/index.tsx` created
  - `app/_layout.tsx` created

---

#### ✅ Why It's Useful:

- Keeps a **backup** of your original project under `/app-example`.
- Provides a **clean scaffold** for fresh development using Expo Router.
- Useful when your routing, structure, or logic becomes too complex or broken to debug.
- Makes it easy to **compare old vs new** setup side-by-side before deleting the backup.

---

#### 📌 Next Steps After Reset:

1. Run `npx expo start` to launch the development server.
2. Edit `app/index.tsx` to modify the main screen.
3. Review or delete the `/app-example` directory once it’s no longer needed.
