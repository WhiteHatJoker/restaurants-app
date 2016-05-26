# Online media library #
This web based application stores and displays the catalog of movies, books, music with detailed desription of each category. The app is built using PHP and it allows users to mail their suggestions. 

## Consists of ##
* `/css` folder with all CSS stylesheets
* `/img` folder with all the necessary images
* `/inc` folder contains the header and footer templates, our main media data file, functions and phpmailer class
* `catalog.php` serves as the full or dedicated catalog webpage
* `details.php` webpage that displays specific details of one media item
* `index.php` - main page
* `suggest.php` - the suggestion webpage which allows users to send their suggestions to the site owner

## Getting ready to run the website ##
* All the additional books, movies or music and their details should be stored into `/inc/data.php` file. 
* We also need to configure the lines 40-52 in suggest.php depending on how you would like to receive the suggestion mail. If you want to use Gmail as the means to send email to your preferred address update lines 48,49 to Gmail login details and line 52 to the email address, where you would like to receive the email.
* Now, move the items to the hosting account
