## Step 1

```blocks
// @highlight
basic.showNumber(6)

while (true) {
   let x = input.acceleration(Dimension.X) / 5;
   let y = input.acceleration(Dimension.Y) / 2;
   let z = input.acceleration(Dimension.Z) / 2;
```
```blocks
   strip.shift(1);
   strip.setPixelColor(0, neopixel.rgb(x, y, -z));
   strip.show();
   strip.shift(1);
   basic.pause(100);
```
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
