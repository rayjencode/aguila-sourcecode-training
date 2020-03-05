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

# Wow Animate.css
Website: https://daneden.github.io/animate.css/

<!-- Wow JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/wow/1.1.2/wow.min.js"></script>

<!-- Wow JS Initialize -->
<script>
  new WOW().init();
</script>

# Some CSS Snippet
```css
/*Color Scheme*/
 :root {
  --primary: #3c21a3;
  --secondary: #81389c;
  --content: #626262;

  --learnMore: #5689df;
  --btn30days: #6e44de;
  --socialBG: #172947;
  --sectionTitle: #172947;
  --navFooter: #afafaf;
  --hrLine: #d8d8d8;

  --btnGetStarted: #0cd57d;
  
/* Smooth bottom Shadow */
box-shadow: 0px 2px 20px 8px rgba(0,0,0,0.07); /*lefright - topbottom - blur - spread*/

/* Smooth Top Shadow */
box-shadow: 0px -2px 20px 8px rgba(0, 0, 0, 0.07); /*lefright - topbottom - blur - spread*/
 
  /* Media Queries */
@media (max-width: 991.98px)
@media (max-width: 767.98px)
@media (max-width: 575.98px)
@media (max-width: 414.98px)
@media (max-width: 375.98px)  
@media (max-width: 320.95px)
  
  /* Slide up hover  */
.team__card:hover {
  transform: translateY(-20px);
}
  
 /* Floating Apply */
.header__right--img {
  width: 100%;
  animation: floating 3s ease-in-out infinite;
}
  /* Floating */
@keyframes floating {
  0% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-30px);
  }
  100% {
    transform: translateY(0px);
  }
}

/* Spin Apply*/
.features__card:hover .features__img {
  animation-name: spin;
  animation-duration: 500ms;
}
/* Spin */
@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
}
```
