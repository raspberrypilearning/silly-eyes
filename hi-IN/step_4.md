## स्प्राइट प्रभाव

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
जब आप अपने **character** स्प्राइट और **silly eyes** स्प्राइटस पर क्लिक करते हैं तो वो अपना `Looks`{:class="block3looks"} बदल सकें।
</div>
<div>

![ग्राफिक प्रभाव के साथ एक पात्र और ऑंखें.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### नासमझ आँख प्रभाव

--- task ---

एक `when this sprite clicked`{:class="block3events"} खंड को अपने **Eyeball** स्प्राइट में जोड़ें।

क्या आप यह पता लगा सकते हैं कि किस कोड खंड से, **Eyeball** स्प्राइट पर आपके द्वारा क्लिक होने पर स्प्राइट की आंखों का रंग बदलेगा?

--- collapse ---
---
title: स्प्राइट पर क्लिक करने पर ग्राफिक प्रभाव बदलें
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

यदि आप चाहते हैं कि दोनों आईबॉल्स का प्रभाव समान हो, तो आपको अपनी स्क्रिप्ट को **Eyeball 2** स्प्राइट में कॉपी करना होगा।

[[[scratch3-copy-code]]]

--- /task ---

### पात्र प्रभाव

--- task ---

Click on your **character** sprite in the Sprite list, then click on the **Code** tab.

Add the same script as you used to change the eye colour. Which graphic effects do you want to change for your **character**?

**Choose:** Choose an effect in the drop-down menu within the `change color effect by`{:class="block3looks"} block. Experiment with the numbers and effects until you have a change that you like.

[[[scratch3-graphic-effects]]]

--- /task ---

### An accessory

Now, add an **accessory**, such as a hat, that changes when you click on it — use the `next costume`{:class="block3looks"} block.

--- task ---

**Choose:** Add an accessory change or costume change of your choice.

![Sprites with accessories.](images/accessory-sprite.png)

--- collapse ---
---
title: क्लिक करने पर स्प्राइट की पोशाक चेंज हो
---
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Some sprites already have a choice of costumes.

You can add code to make a sprite's costume change to the `next costume`{:class="block3looks"} when you click on the sprite:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

If your sprite does not have a choice of costumes, or you want to add more, you can add any costume to a sprite.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Test:** Work on your sprites until they interact in the way that you want.

**Tip:** Try one change at a time and test what it does so that you can easily spot each change and undo anything that you do not like.

--- /task ---

--- task ---

**डीबग:**

यदि आप गलत स्प्राइट में कोड जोड़ते हैं, तो आप उसे ठीक कर सकते हैं:

[[[scratch3-copy-code]]]

यदि आवश्यकता है, तो आप ग्राफिक प्रभावों को रीसेट कर सकते हैं:

--- collapse ---
---
title: मुझे ये ग्राफिक प्रभाव नहीं चाहिए
---

ग्राफिक प्रभावों को किसी भी समय रीसेट करने के लिए, `Looks`{:class="block3looks"} खंड मेन्यू के `clear graphic effects`{:class="block3looks"} खंड पर क्लिक करें। हरे झंडे पर क्लिक करने से ग्राफिक प्रभाव भी साफ हो जाता है।

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- task ---

**Test:** Test your project again, but this time, make it full-screen so that you can see how it will appear to someone looking at it.

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
By making your project full-screen, you are seeing what you have made from the perspective of a user who is playing with your project. **User interaction** is important in digital making. 
</p>


