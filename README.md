## Date

* setInterval(fn, int)
```
setInterval(function(){
    alert('Hi')
  }, 3000)
```

* new Date()
new date object with the current date and time
```
new Date()
new Date(milliseconds)
new Date(dateString)
new Date(year, month, day, hours, minutes, seconds, milliseconds)

today = new Date();
today.toDateString();
```

```
function printTime() {
    var d = new Date();
    var hours = d.getHours();
    var mins = d.getMinutes();
    var secs = d.getSeconds();
    document.body.innerHTML = hours+":"+mins+":"+secs;
}
```
