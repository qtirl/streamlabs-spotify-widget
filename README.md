# streamlabs-spotify-widget
Enhance your live stream with our widget that seamlessly showcases your currently playing Spotify track via OBS/Streamlabs.

After extracting the ZIP file you will need to navigate to https://developer.spotify.com/dashboard, log in and create an app.
Once the app is created, open the settings and change your redirect URI to: http://localhost:3000/callback

You will need to then open the .env file (can use notepad for this) and you will see the below:
![image](https://github.com/qtirl/streamlabs-spotify-widget/assets/22341222/8e137f22-8402-4d7f-9539-35c29a05e66f)

You will need to change these values to the client ID and client secret located in your newly created spotify webapp.
![image](https://github.com/qtirl/streamlabs-spotify-widget/assets/22341222/9796b122-917b-414d-b729-7e2838571631)

Once this step is completed save the file and run the .exe file. For your first time running the app you will need to login to spotify with your account information. It will be remembered for any uses afterwards.

Your app should now be connected to spotify, you can now connect it to OBS/Streamlabs by adding a new scene and selecting "Browser Source".

![image](https://github.com/qtirl/streamlabs-spotify-widget/assets/22341222/802425c8-8b37-4859-88d8-d9ee91420fb5)


Edit the "Browser Source" to look like the below:
![image](https://github.com/qtirl/streamlabs-spotify-widget/assets/22341222/b0e74a5f-49dc-4ac5-a902-837489b0e36b)

Open Spotify and play a song if you aren't already and you should be able to see the currently playing track on stream. You can resize this however you want and move it wherever :)
