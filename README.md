# 🎵 Streamlabs Spotify Widget 🎵

Elevate your live streaming experience with this widget, effortlessly displaying the track you're currently playing on Spotify through OBS/Streamlabs.

---

## 🚀 Initial Setup:

1. **📂 Extract the ZIP File**: 
   Start by extracting the provided ZIP file.

2. **🔗 Spotify Developer Dashboard**:
   - Visit the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard).
   - Log in and create a new app.
   - In your app settings, set the redirect URI to `http://localhost:3000/callback`.

3. **🔧 Configure the `.env` File**:
   - Open the `.env` file with Notepad or a similar text editor.
   - Update the placeholder values with the client ID and client secret from your newly created Spotify app.
     ![Environment File Preview](https://github.com/qtirl/streamlabs-spotify-widget/assets/22341222/8e137f22-8402-4d7f-9539-35c29a05e66f)
     ![Spotify App Credentials](https://github.com/qtirl/streamlabs-spotify-widget/assets/22341222/9796b122-917b-414d-b729-7e2838571631)

4. **🎮 Run the Application**: 
   - Launch the provided `.exe` file. 
   - On your first run, you'll need to sign in to Spotify. Your login details will be stored for subsequent uses.

---

## 🎙 Connecting to OBS/Streamlabs:

1. **🎬 Add a New Scene**: 
   - In OBS/Streamlabs, create a new scene.
   - Choose "Browser Source" as your source.

2. **⚙️ Configure Browser Source**: 
   - Adjust the "Browser Source" settings to match the provided setup.
     ![Browser Source Settings](https://github.com/qtirl/streamlabs-spotify-widget/assets/22341222/b0e74a5f-49dc-4ac5-a902-837489b0e36b)

3. **🎤 Test the Widget**: 
   - Play a song on Spotify. 
   - On your stream, you should see the track details displayed. Feel free to customize the widget's size and position to suit your stream's aesthetics. Enjoy streaming! 🎉
  
   - ![image](https://github.com/qtirl/streamlabs-spotify-widget/assets/22341222/c52be294-a8cc-42ed-8c68-9a40a7a0f98d)

