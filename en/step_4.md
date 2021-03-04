## Make googly eyes

Each eye needs to be a sprite so it can move separately.

--- task ---

You will create an eye costume in the Paint editor. You can either draw your eye or start from a round sprite.

It's really important that:
- the costume has the pupil facing to the right
- the eyeball costume is centered

--- collapse ---

---
title: Draw an eye in the Paint editor
---

--- /collapse ---

--- collapse ---

---
title: Turn a round costume into an eye
---

--- /collapse ---

**Tip:** To draw a perfect circle (or square), hold down the Shift key on the keyboard while you draw with the oval (or rectangle) tool.

--- /task ---

--- task ---

Add code to make the eye point towards the mouse pointer:

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

--- /task ---

--- task ---
Drag the eye into position on the Stage and change its size tofit your character.15px

--- /task ---

--- task ---
If your character is a cyclops then you are done. 

Otherwise, you can right-click on the sprite in the Sprite list and choose 'duplicate' to create more eyes.

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

Check that the pupil is on the right ([past the blue cross in the middle) in the eye costume(s). 

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