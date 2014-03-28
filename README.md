Usage: embed the contents of demo.html into your project, probably torwards the bottom.
I embedded all the styles to avoid conflicts.

make sure you comment/uncomment the line below for testing/production:

// uncomment the line below for testing:
browserSNICompatibility = 0;


NOTE: Demo.html can also be deployed as index.html on a non SSL vhost, then use user agent sniffing in mod_rewrite, or nginx, or whatever to send impacted browsers to a nice page saying "hey dude - you need to upgrade your browser".

