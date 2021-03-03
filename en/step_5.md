# Sprite effects

You can make your character sprite and googly eye sprites change their `Looks`{:class="block3looks"} when you click on them. 

--- task ---

Add a `when this sprite clicked`{:class="block3events"} block to your sprite. **Choose** to add a `change color effect by`{:class="block3looks"} block or a `set color effect`{:class="block3looks"} block underneath.

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

or

```blocks3
when this sprite clicked  
set [color v] effect to (25)
```

--- /task ---

--- task ---

**Choose** the effect you want to use by selecting it from the drop-down box. Experiment with the numbers until you have the change you like.   

--- collapse ---
---
title: Graphic effects in action
---
**Rooster effects**: [See inside](https://scratch.mit.edu/projects/435730522/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/435730522/?autostart=false" frameborder="0"></iframe>
</div>

+`color`{:class="block3looks"}: From 0 to 199 (bigger numbers will wrap around, so 200 is the same as 0)
+`fisheye`{:class="block3looks"}: 0 is no effect, bigger numbers give a bigger ‘bulge’ effect
+`whirl`{:class="block3looks"}: 0 is no effect, big number gives a big whirl to the left, big negative number gives a big whirl to the right
+`pixelate`{:class="block3looks"}: 0 is no effect, bigger numbers create more pixels
+`mosaic`{:class="block3looks"}: 0 is no effect, bigger numbers create more copies
+`brightness`{:class="block3looks"}: 0 is no effect, bigger numbers up to 100 make the sprite lighter, and negative numbers down to -100 make the sprite darker
+`ghost`{:class="block3looks"}: 0 is no effect, bigger numbers up to 100 make the sprite more transparent

--- /collapse ---

--- /task ---

--- task --- 

Add a new script to `clear graphic effects`{:class="block3looks"} when you start your project.

```blocks3
when green flag clicked  
clear graphic effects
```

--- /task ---

--- task ---

**Test** Work on your sprites until they interact in the way that you want. Try one change at a time and test what it does so you can easily spot the change and undo anything you do not like.  

--- /task ---