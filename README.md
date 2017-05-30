# Full-Browser Youtube Bookmarklet!

This is a browser bookmarklet that you can use to make any youtube video take up the entire browser window, but not go to 'fullscreen' mode.

It's really good for tiling window managers, like Spectacle for OSX, or anyone who cares about trying to use screenspace efficently.


Just make a bookmark with this code as the ```URL```, and click it on any Youtube video !

```javascript:(function(){find="watch?";replace="watch_popup?";if(window.location.href.indexOf(find)!=-1){window.location.replace(window.location.href.replace(find,replace));}}());```

It works by changing your youtube window into the 'popup window' youtube format, which uses the entire browser window.

PS if you're having trouble making a bookmark with a custom url, try editing an existing bookmark and replacing the url!
