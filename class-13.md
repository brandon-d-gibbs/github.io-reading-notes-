# Reading Notes Class 13
## Local Storage

### Local Storage - Browswer Edition
Every time you visit a webpage in a browser, a bit of data is stored. You have cookies, images, and other data pertaining to your visit on that page, depending on what the site deems it needs or maybe what you've submitted through various means such as interaction, form submisstion, etc.

Where does this go? It's a magical little folder that your browser has in it's back pocket. It's great for storing persistent data ...but then agian in many cases it is not.

This data is by no means secure, so you don't want to be storing any personal information in there that you don't want getting out. It can also be easily destroyed with a simple line of code....and poof. gone. But then again, it's not storing things that will end your whole world if they are gone...at least it shouldn't.

This data is stored, changed and removed through a process called CRUD. 
**C**reate
**R**ead
**U**pdate
**D**elete/Destroy

These are accomplised in JS with simple commands.

```js
// Create an item in Local Storage
localStorage.setItem('key', 'value')

// Read or get and item in Local Storage
.localStorage.getItem('key')

//Update or change an item's value in Local Storage
localStorage.setItem('Key that already exists', 'new data to replace the previously set data')

// Delete / Destroy. 
localStorage.removeItem(key);

```

_If you find a spider in your data, you obviously need to kill it with FIRE! So to set fire to your data in that localStorage you would simply type `localStorage.clear()`. There, now the spider AND your code are gone._