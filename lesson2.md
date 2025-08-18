## Step 1

Instructions for step 1 of activity 1 here...


```blocks
let strip = neopixel.create(DigitalPin.P0, 24, NeoPixelMode.RGB_RGB)
while (true) {
   let x = input.acceleration(Dimension.X) / 2;
   let y = input.acceleration(Dimension.Y) / 2;
   let z = input.acceleration(Dimension.Z) / 2;
   strip.shift(1);
   strip.setPixelColor(0, neopixel.rgb(x, y, -z));
   strip.show();
   basic.pause(100);

```


## Step 2


Instructions for step 2 of activity 1 here...

```package
neopixel=github:microsoft/pxt-neopixel


```


<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
