# Particles HP (Android app)

A glowing particle heart that reacts to your music. Tap to burst, hold to scatter, let go and it re-forms.

## Get the APK (about 10 minutes, once)

1. Make a free account at github.com and create a new repository named `particle-heart`. Choose **Public** so you can share a download link.
2. On a computer, unzip this folder. In your new repository choose **Add file > Upload files** and drag in everything inside the folder, including the hidden `.github` folder. Press **Commit changes**.
   If the `.github` folder does not upload, choose **Add file > Create new file**, type `.github/workflows/build-apk.yml` as the name and paste in the contents of that file.
3. Open the **Actions** tab. The **Build APK** job starts by itself and takes about 5 to 8 minutes. A green tick means it worked.
4. Download the APK from **Releases** (right side of the repository page): `Particles-HP.apk`. It is also under the finished job as an artifact.
5. Send the file to your Android phone and open it. Android asks you to allow installing from this source. Allow it, then install.

If the job shows a red cross, open it, copy the error text and send it to Claude.

## Built-in songs

Songs inside the APK travel with it, so anyone you send the APK to gets them.
Upload your MP3 files to the `www/songs` folder in the repository (**Add file > Upload files**). The app rebuilds by itself and the new APK includes them.
Only share music you have the right to share.

## Songs from your phone

In the app, tap **Songs > Add songs** and pick audio files. These stay on that phone only and are not part of the APK.

## Notes

- Music pauses when the app is minimised.
- This is a debug-signed APK. It installs fine but is not for the Play Store.
