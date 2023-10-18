# SpotifyMixer_Flask

About: SpotifyMixer_Flask is a simple framework for accessing Spotify user metadata. The code is very begginer friendly, this file will guide you through setup. The program uses Spotify API to access data and flask in order to handle Spotify's http response with an access token. 

See document below to:
- Get started.
- Access user data.
- Add users.

**Getting started:**
1. Download server_api.py from the repository. You can alternatively just clone the whole repository. 
2. Go to [Spotify Developer](https://developer.spotify.com/) and create a developer account out of an existing Spotify account. 
3. Go to Dashboard and create an app. 
4. After creating an app, go to app->settings->client id and client secret.
5. In the same directory (folder) where you stored server_api.py, create a file named ".env". Add the following to .env:
    ```
    CLIENT_ID="Enter your client id here"
    CLIENT_SECRET="Enter your client secret here"
    ```
6. Install all python libraries used in the server_api.py in the command line using [pip](https://www.w3schools.com/python/python_pip.asp).
7. You can now run server_api.py. Go to the terminal and click the link it will print out. This link will prompt you to authorize access to your Spofity account. After authorization, the program should print out a list of your top songs. Remember to terminate the flask server by going to the terminal and hitting "Control C" on your keyboard. 
