# googleOauth
 Google OAuth is a widely used authentication and authorization framework provided by Google. It allows third-party applications and websites to access certain user data or perform actions on behalf of a user without needing their username and password.


## steps
  1. Go to the **Google Developer Console:** https://console.cloud.google.com/apis/dashboard/
  2. Create a new project or select an existing one
  3. Enable the Google APIs:
     ```
      - In your project, navigate to "APIs & Services" > "Dashboard."
      - Click on "+ ENABLE APIS AND SERVICES."
     - Search for the specific Google API you want to use (e.g., Google Drive API, Google Calendar API), and enable it.
     ```
 4. Create OAuth 2.0 Credentials:
    ```
    In the Google Developer Console, go to "APIs & Services" > "Credentials."
    Click on "+ CREATE CREDENTIALS" and select "OAuth client ID."
    Choose the application type (Web application, Mobile application, etc.).
    Configure the authorized redirect URIs where Google will send the user after authentication.
    These URIs should match the callback URLs in your application.
    After configuring, click "Create" to generate your OAuth client ID and secret.
    
    ```
