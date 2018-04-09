# JS Big Picture Basic

### Setup

Clone this repository in your `~/muktek/warmups` directory.


### Tasks

1. Create a `js` folder and create a `main.js` file inside

2. Link the `main.js` file in your `index.html` in a `<script src="..."></script>` just _before_ the end of the `</body>` tag.

3. Pop an alert box that says 'hello hello'
  ```js
  alert('hello hello!')
  ```

4. Log the following value to the console: `'teatime'` (note the quotes), `33` (no quotes), `true` (no quotes). Open the developer's console in firefox and what do you notice?

  ```js
  console.log('teatime')
  // ...and you need to input then the rest of the values
  ```

5. Create an event listener on the button to see how html + javascript connect. (you only need to type the code below)

  ```js
  document.querySelector('button').addEventListener( 'click',function(){
    alert('Important msg 4 u')  
  })
  ```
