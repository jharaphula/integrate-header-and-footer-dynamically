# Tricks to integrate Header and Footer dynamically in Web Application

I noticed to integrate header footer dynamically in a Web Application we follow many ways. Such as JQUERY load method. Do you ever thought to load header or footer if you are using JQUERY then jquery CDN link getting loaded. Which takes time as well as in Google pagespeed it make the page rendering slow. Like this there are several ways many developers follows.

Here I am using the most easiest way to integrate header and footer dynamically. Which not only load faster but also performance wise it is much rich compare to JQUERY load method.

# Technical details to integrate Header and Footer dynamically

Create JS files like header.js and footer.js. Store your header file code to header.js using the way we shown in this app. Keep noted before placing your HTML code to header.js file replace double quotes with single quotes.

Once your header and footer files are ready. In HTML define a div with id="header" or id="footer" then embed the line of js script we did in this app.

Developed by [https://jharaphula.com/jquery-string-functions/]jquery 
