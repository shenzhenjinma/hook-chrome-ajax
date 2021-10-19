

A chrome extension for modifing response text of ajax requests easily. You can use it to debug errors.


## Notes
1. You may have to restart chrome or refresh the current page after you added this extension.
2. It is recommended that you turn off this extension(the icon should be gray) when you are not using it.
3. This extension only overrides the response data in the XMLHTTPRequest object as well as the fetch method. The "real" response which you can see in DevTools' "Network" panel will not be changed.

code reference https://raw.githubusercontent.com/YGYOOO/ajax-interceptor/master/