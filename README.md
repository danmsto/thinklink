# thinklink

Server Application: This will run on your old Thinkpad. It will need to:
  - Serve a list of available files.
  - Handle file upload requests and save the uploaded files to the appropriate location.
  - Handle file download requests and send the requested files.

Client Application: This will run on your personal laptop. It will need to:
  - Request and display a list of available files from the server.
  - Handle user input to select a file for download.
  - Send a download request to the server and save the downloaded file to the appropriate location.
  - Handle user input to select a file for upload.
  - Send an upload request to the server along with the file to be uploaded.

Here are some specific C# libraries and technologies you might find useful:
  - ASP.NET Core: This is a framework for building web applications in C#. You can use it to build the server application. It includes features for routing, authentication, session management, and more.
  - HttpClient: This is a class in the System.Net.Http namespace that you can use to send HTTP requests from the client application to the server.
  - FileStream: This is a class in the System.IO namespace that you can use to read from and write to files. You’ll need this for handling file uploads and downloads.
  - SignalR: This is a library for ASP.NET Core that you can use to enable real-time communication between the client and server. This could be useful if you want the server to be able to push updates to the client (for example, to notify the client when a new file is available for download).
