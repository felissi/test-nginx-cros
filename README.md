This tests the CROS request on browser, if the server required authorization, "Access-Control-Allow-Headers" should include "Authorization". And the "OPTIONS" request shouldn't be blocked, and should return success for browser to send the CROS request next.

The username and password for basic auth is `abc`
