This website is built using Firebase. It allows users to sign up with a valid email and any password of their choice, storing this information securely in Firebase. For signing in, it verifies the credentials against the Firebase database, ensuring proper security measures.

After signing in, the website requires users to enter their phone number to verify that they are not a robot. An OTP (one-time password) is generated and sent to the provided number only if the email associated with that number is valid and logged into the device. This process ensures multifactor authentication.

The web application utilizes HTML, CSS, and JavaScript to create a secure environment, while Firebase handles the backend operations, including authentication and database management.

This website operates effectively when launched through a live server, accessed via a URL like eg. `localhost:1010/index.html`. Running it through a live server is crucial for its functionality, allowing proper execution of the code and seamless integration with Firebase services for user authentication and OTP generation. This setup ensures that all features, including user sign-up, sign-in validation, and multifactor authentication via phone number verification, work as intended in a secure web application environment.
