# HTML-CSS-JavaScript
Website which uses AJAX to make a RESTful API call to dynamically populate the site with news articles from The Guardian.

This code was written entirely by myself to demonstrate my coding abilities using HTML, CSS, and Javascript. The primary focus of the website is to dynamically populate itself with news articles from www.TheGuardian.com. The website does so by using AJAX (a coding technique) to make an API call to the website. The website responds with a JSON file containing an array of JSON-formatted news articles. Their topics are extracted and presented as 'ul' elements. Each element is capable of running the request again for articles tagged with that particular topic, which dynamically populates the news page with those articles. The articles, upon their creation, are also embedded with their corresponding URLs that take the user to that article onThe Guardian.

Additionally the website contains four more hyperlinks. The topics page contains a hyperlink to The Guardian. The Homepage contains links to my personal LinkedIn and Github account, as well as my Wordpress website. These links however have been removed from this file.

An API key is also required to make the API call. I obtained my key by applying to The Guardian at: https://open-platform.theguardian.com/access/. After which, my personal API key was emailed to me. This key is equivalent to a password and must not be shared or made public, which is why I have also removed this from my code.

***IMPORTANT***
My personal API key has been removed from this file and thus the API call to the website will not work.
I have also removed the links to my LinkedIn and Wordpress for security.
