# Realtime Markdown Editor

### What is this?

Type your markdown into the box on the left and immediately see if on the box on the right. If you send a friend a link to this URL you both can edit the document at the same time!

### How to use this?

Type anything after the slash in "https://realtimemarkdown.herokuapp.com/" and just start typing. If you don't feel typing in the address bar, feel free to go to one of these markdown pads:

- [https://realtimemarkdown.herokuapp.com/sample](https://realtimemarkdown.herokuapp.com/sample)
- [https://realtimemarkdown.herokuapp.com/my_project](https://realtimemarkdown.herokuapp.com/my_project)
- [https://realtimemarkdown.herokuapp.com/whatever](https://realtimemarkdown.herokuapp.com/whatever)

### How was this built?

This website uses the following to work:

 - [Markdown](https://github.com/showdownjs/showdown) - Converts markdown text to beautiful HTML
 - [ShareJS](http://sharejs.org/) - allows for realtime editing of this textbox
 - [Node.js](https://nodejs.org/) - backend framework 
 - [Redis](http://redis.io/) - where we store our markdown documents
 - [Twitter Bootstrap](http://getbootstrap.com/) - makes everything a little prettier