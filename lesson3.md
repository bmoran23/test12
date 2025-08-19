## Step 1

Instructions for step 1 of activity 1 here...picture

![Agent building a tower](/Clubhouse_RoboPet1 8x6.jpeg)

## Step 2
How to you add a link? 


[Video](https://studio.youtube.com/video/0tpOJQNxNQY/)

## Step 3


Instructions for step 2 of activity 1 here...

```blocks
forever(function() {
    strip.shift(1);
    strip.setPixelColor(0, neopixel.rgb(x, y, -z));
    strip.show();
    basic.showNumber(input.temperature())
    basic.pause(1000)
})
```



```package
neopixel=github:microsoft/pxt-neopixel
```



<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

