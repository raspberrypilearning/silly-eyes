## Make googly eyes

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Each eye needs to be a sprite so it can move separately.
</div>
<div>
![Large character ready for googly eyes](images/character.png)  
</div>
</div>

--- task ---

Create an eye costume in the Paint editor. You can either draw your eye **or** start from a round sprite.

It's really important that:
- the costume has the black pupil and coloured iris facing to the right
- the eyeball costume is centered


--- collapse ---

---
title: Draw an eye in the Paint editor
---

Select the oval tool.

You need to draw a perfect circle otherwise the whole eye will wobble around (instead of it being a Googly eye). 

To draw a perfect circle, press and hold the `Shift` key on the keyboard while you draw with the oval. If you are on a tablet, try and get as close to a perfect circle as possible.

This is the outline of the eye so in the example we made it black. Make sure the circle is in the centre.

![centred circle](images/eyeball_circle_centre.png)

Draw a smaller perfect circle and position it in the first circle.

You can either change the outline colour and thickness and make the outline the iris:

![two circles, the middle one with a red outline 40 thickness](images/eyeball_two_circles.png)

Or, you can change the colour of your second circle and draw a third perfect circle as the pupil:

![3 circles, the second one red and the third one black, the second and third positioned to the right of the centre](images/eyeball_three_circles.png)

--- /collapse ---


--- collapse ---

---
title: Turn a round costume into an eye
---

There are costumes in Scratch that can be edited to make googly eyes for your character. Examples of these are 'Ball' and 'Button1' though there are many others you can choose from.

Use the Paint editor to change the costumes to add circles, choose a different fill colour or remove parts of the costume to turn it into a googly eye. 

**Tip**: The costume will need to be centered in the Paint editor using the crosshair so that it rotates smoothly as it turns. The black pupil and coloured iris need to be positioned to the right side of the costume so that it follows the mouse pointer.

![Existing Scratch costumes as eyes](images/costume-eyes.gif)

![Paint editor with edited button1 sprite](images/button-eye.png)

--- /collapse ---

--- /task ---

Now you have the eyes, add code to make them googly.

--- task ---

Add a script to `set the rotation style`{:class="block3motion"} to make the eye `point towards the mouse pointer`{:class="block3motion"} `forever`{:class="block3control"}. 

--- collapse ---

---
title: Make a sprite point towards the mouse pointer
---

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

--- /collapse ---


--- /task ---

--- task ---

Drag the eye into position on the Stage and change its size to fit your character.

--- /task ---

If your character is a cyclops then you are done. 

--- task ---

Otherwise, right-click (or tap and hold on a tablet) on the sprite in the Sprite list and choose 'duplicate' to create more eyes.

[[[scratch3-duplicate-sprite]]]

--- /task ---

--- task ---

**Test:** Click the green flag and try your project out, do the googly eyes follow you as you move the mouse around?

**Tip:** You don't have to keep the mouse pointer on the Stage. The eyes will follow you as you carry on coding in Scratch.

--- /task ---

--- task ---
**Debug:** 

--- collapse ---
--- 
title: The eyes don't move
---

Make sure you have added the code to the eye sprite(s) and **clicked the green flag**. Your code won't run until you click the green flag.

--- /collapse ---

--- collapse ---
--- 
title: The eye(s) point away from the mouse
---

Check that the pupil is on the right (past the blue cross in the middle) in the eye costume(s). 

The eyeball has the `all around`{:class="block3motion"} `rotation style`{:class="block3motion"} so it can rotate in any direction. 

When the eyeball rotates to `point towards`{:class="block3motion"} the `mouse pointer`{:class="block3motion"}, the pupil will be closest to the mouse pointer. 

![An eye costume with the pupil on the right](images/eye-right.gif)

![An eye costume with the pupil on the right](images/eye-costume.png)

--- /collapse ---

--- collapse ---
--- 
title: The eyes jump around the Stage
---

Check that the costume is centered. Drag the costume so that the blue cross lines up with the grey cross in the Paint editor.

![An eye costume centered in the Paint editor](images/eye-centered.gif)

![An eye costume centered in the Paint editor](images/eye-costume.png)

--- /collapse ---

If you drag your character sprite then it will go in front of the eyes.

--- collapse ---

--- 
title: Keeping a sprite at the back
---

When you drag a sprite to position it on the Stage it moves in front of the other sprites. 

To get a sprite to stay at the back use:

```blocks3
when green flag clicked
forever
go to [back v] layer // behind all other sprites
```

--- /collapse ---

--- /task ---

--- save ---
