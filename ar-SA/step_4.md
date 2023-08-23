## تأثيرات الشخصية

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
يمكنك جعل ** الطابع الخاص بك ** شخصية و **عين مضحكة ** شخصيات يغيران مظهرهما {: class = "block3looks"} عند النقر فوقهما.
</div>
<div>

! [شخصية وعينان بتأثيرات رسومية.] (images / character-Graphic-effects.png) {: width = "300px"}    

</div>
</div>

### آثار العين المضحكة

--- task ---

أضف `عند نقرا هذا الكائن`{: class = "block3events"} إلى كائن **مقلة العين**

هل يمكنك تحديد التعليمات البرمجية التي ستضعها تحتها لتغيير لون عين الكائن عند النقر فوق كائن**مقلة العين**؟

--- collapse ---
---
title: تغيير تأثيرات الرسوم عند النقر فوق الكائن
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

إذا كنت تريد أن يكون لكل من مقل العيون نفس التأثير ، فستحتاج إلى نسخ التعليمة البرمجية الخاص بك إلى كائن **مقلة العين2**

[[[scratch3-copy-code]]]

--- /task ---

### تأثيرات الشخصية

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
title: اصنع مظهر تغيير كائن عند النقر عليه
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

**تصحيح:**

إذا أضفت تعليمة برمجية إلى الكائن الخطأ ، فيمكنك إصلاح ذلك:

[[[scratch3-copy-code]]]

إذا كنت بحاجة إلى ذلك ، يمكنك إعادة تعيين تأثيرات الرسوم:

--- collapse ---
---
title: لا أريد هذه التأثيرات الرسومية
---

لإعادة تعيين التأثيرات الرسومية في أي وقت ، انقر فوق `تأثيرات الرسوم الواضحة`{: class = "block3looks"} في قائمة المقاطع البرمجية`الهيئة`{: class = "block3looks"}. يؤدي النقر فوق العلم الأخضر أيضًا إلى مسح تأثيرات الرسوم.

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


