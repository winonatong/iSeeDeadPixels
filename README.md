iSeeDeadPixels
========================

This is a utility to test the screen on Google Glass for defective pixels.

If you want to use this software, simply go to http://cremeglass.com/iseedeadpixels/ and sign in with the Google account that you are using with Glass.

If you would like to run a version of this software on your own server, you will need to create a config.php file containing:

```
$api_client_id = "<your glass API client ID>";
$api_client_secret = "<your glass API client secret>";
$api_simple_key = "<your glass API simple key>";

$base_url = "<URL where you are running iSeeDeadPixels>";

$sqlite_database = "<location of your sqlite database>";
```