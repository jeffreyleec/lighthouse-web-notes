### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.


```javascript
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry == false) {
    console.log("Get back to work! You're not even hungry");
  } else if (hungry == true) {
    if (availableTime < 20) {
      console.log("Quick snack, eat it in the lab!");
    } else if (availableTime > 19 && availableTime < 30) {
      console.log("try a nearby place!");
    } else if (availableTime > 30) {
      console.log("You're in a bootcamp! Grab a snack and get back to work!!!! Reconsider your free time.");
    }
  }
}
```