# Android-application-development-NIT3213-
![image](https://github.com/user-attachments/assets/bdcce296-4f16-49fd-9697-dddadf5f3652) (This is how login page looks like)
![image](https://github.com/user-attachments/assets/b82e41f9-38c4-4c14-a600-e25e28297e02) (This is the main dashboard where it will display all the entities from the API)
![image](https://github.com/user-attachments/assets/7b980aab-1add-43fd-a20f-ce81b6ec282b) (This is the example of the detail page which shows more information of the entity that was clicked)


## Prerequisites
- **Android Studio** (latest stable version recommended)
- **Android SDK** (API 28 or higher)
- **Internet connection** (for API access)

## Dependencies
- [Kotlin](https://kotlinlang.org/)
- [AndroidX](https://developer.android.com/jetpack/androidx)
- [Material Components](https://material.io/develop/android)
- [Hilt (Dependency Injection)](https://dagger.dev/hilt/)
- [Retrofit & Gson](https://square.github.io/retrofit/)
- [Navigation Component](https://developer.android.com/guide/navigation)

All dependencies are managed via Gradle and will be downloaded automatically.

## Setup & Build Instructions
1. **Clone the repository:**
   ```
   git clone <your-repo-url>
   ```
2. **Open the project in Android Studio:**
   - Go to `File > Open` and select the project folder.

3. **Sync Gradle:**
   - Android Studio will prompt you to sync Gradle. If not, click `File > Sync Project with Gradle Files`.

4. **Build the project:**
   - Click `Build > Make Project` or use the Gradle sidebar.

5. **Run the app:**
   - Connect an Android device or start an emulator.
   - Click the green Run button or use `Run > Run 'app'`.

## Project Structure
- `app/src/main/java/com/example/myassssmentapplication/`
  - `ui/` — Fragments and adapters for Login, Dashboard, and Details
  - `data/` — API models, repository, and custom deserializer
  - `di/` — Hilt dependency injection setup
- `app/src/main/res/layout/` — XML layouts for all screens
- `app/src/main/res/drawable/` — Icons and background gradients

## Customization
- The app is fully dynamic: it displays all fields returned by the API for any entity.
- To change the API base URL, edit `NetworkModule.kt`.
- To update the UI theme, edit colors and styles in `res/values/`.
