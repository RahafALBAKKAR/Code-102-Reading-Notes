# Web Application Storage
_________
 What we really want is
- a lot of storage space
- on the client
- that persists beyond a page refresh and isn’t transmitted to the server.

## HTML Storage 
_______
 
 *It’s a way for web pages to store named key/value pairs locally, within the client web browser.*
 
 From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it. 

 function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}

* **Using HTML5 Storage**
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype. 

![tracing](https://images.slideplayer.com/13/3738484/slides/slide_46.jpg)

![html storage](https://image2.slideserve.com/4041342/using-html5-storage4-l.jpg)

The storage event is not cancelable. From within the handle_storage callback function, there is no way to stop the change from occurring. It’s simply a way for the browser to tell you, “hey, this just happened. There’s nothing you can do about it now; I just wanted to let you know.” 

### HTML5 Storage in Action
__________
if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected. 

[Back to homw page](https://rahafalbakkar.github.io/Code-201-Reading-Notes)
