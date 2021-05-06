# Heroku Minimal PHP Server

Basic skeleton of a PHP server running on Heroku.
This is the easiest way to serve a frontend (HTML/JS) site that has no build steps (no frameworks bullshit, just vanilla js etc).

## Setup

1. Clone this repo, which provides:

	+ `.gitignore` to exclude the `vendor` folder which composer generates
	+ `composer.json` which defines the PHP version, in this case 7.4 or higher
	+ `Procfile` to tell Heroku to serve the website from the `web` folder
	+ `web/index.php` to directly serve `index.html`
	+ `web/index.html` your site goes here!