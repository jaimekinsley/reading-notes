### THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS
(http://diveinto.html5doctor.com/storage.html)

All of the early solutions were either specific to a single browser or reliant on a third-party plug-in.  
HTML5 set out to provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.  
HTML 5 Storage is a way for web pages to store named key/value pairs locally, within the client web browser.  
From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object.  
HTML5 Storage is based on named key/value pairs. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.  
You can trap a storage event to programmatically keep track of when the storage area changes.
HTML5 Storage is limited to 5 megabytes and you can't get more storage space.  
