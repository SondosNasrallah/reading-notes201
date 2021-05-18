## LOCAL STORAGE FOR WEB APPLICATIONS

* ersistent local storage is one of the areas where native client applications have held an advantage over web applications

* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).

* Cookies are limited to about 4 KB of data,  enough to slow down your application (see above), but not enough to be terribly useful

* From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it.

* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key.
The named key is a string.

 **TRACKING CHANGES TO THE HTML5 STORAGE AREA** 

* If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.




