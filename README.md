# youtube-clone
Overview:
A YouTube-like clone, focused on the core functionalities of video uploading/viewing, user authentication, and transcoding. Developed using Next.JS and soon to be hosted on cloud run.

Design:
Video-storage: Google Cloud Storage.
Async Video Processing: Cloud Pub/Sub messages to process videos asynchrously using ffmpeg.
Video Metadata/Api: Firebase functions power the API, for uploads and metadata retrival (Firestore).
Authentication: Managed via Firebase Auth.

Limitations:
Current limitations, cloud run request max timeout of one hour, Pub/sub will resend a message within at most 600 seconds.

Progress:
Currently in development. Connecting firebase to allow users to sign in/out using their Google account and upload videos while signed in as well as store video metadata in Firestore. 

