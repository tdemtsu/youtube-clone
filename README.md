# youtube-clone
Overview:
A YouTube-like clone, focused on the core functionalities of video uploading/viewing, and user acesibility.

Progress:
Currently in development. Connecting firebase to allow users to sign in/out using their Google account and upload videos while signed in as well as store video metadata in Firestore. 

Limitations:
Current limitations, cloud run request max timeout of one hour, Pub/sub will resend a message within at most 600 seconds.
