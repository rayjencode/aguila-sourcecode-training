# aguila-sourcecode-training

# Add VS Code Extensions:
- Bootstrap 4
- Bracket Pair Colorizer
- Live Server
- Material Theme
- Material Icon
- Prettier

# Import Head
- Google Font
- Bootstrap CDN 
- Fontawesome
- css Style


# Countdown JS Script

```javascript
/* Timer Countdown */
var countDate = new Date("March 15, 2020 00:00: 00").getTime();

function newEvent() {
  var now = new Date().getTime();
  gap = countDate - now;

  var second = 1000;
  var minute = second * 60;
  var hour = minute * 60;
  var day = hour * 24;

  var d = Math.floor(gap / day);
  var h = Math.floor((gap % day) / hour);
  var m = Math.floor((gap % hour) / minute);
  var s = Math.floor((gap % minute) / second);

  document.getElementById("day").innerText = d;
  document.getElementById("hour").innerText = h;
  document.getElementById("minute").innerText = m;
  document.getElementById("second").innerText = s;
}

setInterval(function() {
  newEvent();
}, 1000);

```

# Wow Animate 
<!-- Wow JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/wow/1.1.2/wow.min.js"></script>

<!-- Wow JS Initialize -->
<script>
  new WOW().init();
</script>

