## Sprite effects

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
You can make your character sprite and googly eye sprites change their `Looks`{:class="block3looks"} when you click on them. 
</div>
<div>
![Character and eyes with graphic effects.](images/character-graphic-effects.png){:width="300px"}    
</div>
</div>

### Googly eye effects

--- task ---

Add a `when this sprite clicked`{:class="block3events"} block to your **Eyeball** sprite. 

Can you work out what code block you would put underneath to change your sprite's eye colour when you click on them?

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

--- task ---

If you want both Eyeballs to have the same effect then you will need to copy your script to 'Eyeball 2'.

[[[scratch3-copy-code]]]

--- /task ---

### Character effects

If you want to, you can also make your **Character** sprite change colour and other graphic effects when you click on it. 

--- task ---

Click on your character sprite and then the **Code** tab.

Add the same script you used to change the eye colour. Which graphic effects do you want to do to change on your character?

**Choose** an effect by selecting it from the drop-down box in the `change color effect`{:class="block3looks"} block. Experiment with the numbers until you have the change you like.   

[[[scratch3-graphic-effects]]]

--- /task ---

Now add an accessory sprite, such as a hat, that changes when you click on it using the `next costume`{:class="block3looks"} block. 

--- task ---

Add an accessory or costume change of your choice.


![Sprites with accessories.](images/accessory-sprite.png)

--- collapse ---

---
title: Make a sprite change costume when clicked
---

**Gobo with costume accessories**: [See inside](https://scratch.mit.edu/projects/496334057/editor){:target="_blank"}
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

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Test:** Work on your sprites until they interact in the way that you want. Try one change at a time and test what it does so you can easily spot the change and undo anything you do not like.  

--- /task ---

--- task ---

**Debug:**

If you add code to the wrong sprite you can fix that:

[[[scratch3-copy-code]]]

--- collapse ---

---
title: I don't want these graphic effects  
---

To reset your graphics effects at any point, click on the clear graphic effects block in the `Looks`{:class="block3looks"} Blocks menu. Clicking the green flag also clears graphic effects.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- save ---

