# Pep-end-evaluation


URL Shortener
This is a simple URL shortener that uses MongoDB to store the shortened URLs.

How to use
Run the following command to start the server:
node url.js
The server will start on port 3000.
You can shorten a URL by sending a POST request to /shorten with the following body:
{
  "destinationUrl": "https://www.example.com/"
}
The server will respond with the shortened URL.
You can redirect to the original URL by sending a GET request to the shortened URL.
Endpoints
/shorten - Shortens a URL.
/:shortCode - Redirects to the original URL for the given short code.
/update - Updates the destination URL for a short code.
/expiry - Updates the expiry date for a short code.
Dependencies
Express
Mongoose
Author
Deepak Yadav
