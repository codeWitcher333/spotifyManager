You need to have Spotify account to be able to use this tool as authorization is required.


You can see already builded app by me here: https://spotify-manager.surge.sh/

Alternatively to make this app work you need to perform the following steps:

1. Create an account https://developer.spotify.com/
2. Create new app using app dashboard https://developer.spotify.com/dashboard/applications
3. Edit redirect URI of your app to 'localhost:3000/'
4. Copy Client ID and assign it to REACT_APP_CLIENT_ID variable in .env file (main folder)
5. Navigate to project directory and run 'npm start'
6. Open http://localhost:3000 to view it in the browser
