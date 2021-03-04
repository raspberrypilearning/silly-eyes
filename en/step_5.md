# Sprite effects

You can make your character sprite and googly eye sprites change their `Looks`{:class="block3looks"} when you click on them. 

## Googly eye effects

What code blocks would you use to change your sprite's eye colour when you click on them?

--- task ---

Add a `when this sprite clicked`{:class="block3events"} block to your sprite. Can you work out what code block you would put underneath?

--- collapse ---

---
title: Change graphic effects when clicked
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

What else do you want to do to change the graphic effects of the eyes?

--- task ---

**Choose** what other effect you want to use by selecting it from the drop-down box in the `change colour efect`{:class="block3looks"} code block. Experiment with the numbers until you have the change you like.   

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

**Tip:** A colour effect of 225 is the same as a colour effect of 25 so you can keep changing the colour. For other effects nothing will happen after you reach the maximum number for the effect. You can click on `clear graphic effects`{:class="block3looks"} in the `Looks`{:class="block3looks"} Blocks menu or click on the green flag to start again.

--- /collapse ---

--- /task ---

**Tip**: To reset your graphics effects at any point, click on the `clear graphic effects`{:class="block3looks"} block in the `Looks`{:class="block3looks"} Blocks menu. Clicking the green flag also clears graphic effects.

```blocks3 
clear graphic effects
```

## Character effects

You can also make your character sprite change colour or add other graphic effects, when you click on it. 

--- task ---

Add graphic effects to your character like you did with the Googly eyes

--- /task ---

Now add an accessory that changes when you click on it using the `next costume`{:class="block3looks"} block. This is how we got Gobo's hat to change.

--- task ---

Add an accessory or costume changeof your choicee.

--- collapse ---

---
title: Make a sprite change costume when clicked
---

** Gobo with costume accessories **: [See inside](https://scratch.mit.edu/projects/496334057/editor){:target="_blank"}
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/496334057/?autostart=false" frameborder="0"></iframe>
</div>

Some sprites already have a choice of costumes.

To change the costumes, add code to change to the `next costume`{:class="block3looks"} when you click on a sprite:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---


If your sprite doesn't have a choice of costumes, or you want to add more, you can add any costume to a sprite.

--- collapse ---

---
title: Add costumes to a sprite
---

Click on the Costumes tab and then 'Choose a costume' to add any costume to the sprite. 

![Choose a costume menu highlighted](images/choose-a-costume.png)

You will need to position and resize the added costumes in the Paint editor to match your other costumes.


**Tip:** If you position a sprite on the Stage and then switch costume the sprite might appear to 'jump' or change size. You will need to position and resize the costumes in the **Paint editor** so that they all appear in the right position on the Stage. 


--- /collapse ---


--- /task ---

--- task ---

**Test** Work on your sprites until they interact in the way that you want. Try one change at a time and test what it does so you can easily spot the change and undo anything you do not like.  

--- /task ---

--- save ---

