# To Do List — Native Android Build

This folder is ready to become a real, fully offline Android app — no live URL
dependency, no Netlify, nothing needed at runtime except the phone itself.

## How to get your APK (no Android Studio needed)

1. Create a free account at github.com if you don't have one.
2. Create a new **public** repository (any name, e.g. `todo-native`).
3. Upload every file and folder in this zip into that repository
   (drag-and-drop works on github.com — make sure the `.github` folder
   comes through too; some drag-and-drop uploaders hide dot-folders, so if
   it doesn't appear, use "Add file → Upload files" and select the whole
   folder, or use GitHub Desktop instead).
4. Once uploaded, go to the **Actions** tab of your repository.
5. You should see a workflow called **"Build Android APK"** — click it,
   then click **"Run workflow"**.
6. Wait a few minutes while it builds in the cloud.
7. When it finishes (green checkmark), click into that run, scroll down to
   **Artifacts**, and download **todo-list-apk** — that's your APK, unzip
   it and install directly on your phone.

No local Gradle, no Android Studio, no waiting on downloads that time out —
GitHub's own servers have full, fast internet access and do the whole build
for you.
