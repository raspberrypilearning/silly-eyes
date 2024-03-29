--- question ---
---
legend: 質問2/3
---

ロケットをインタラクティブにするために、 **ロケット** スプライトには次のスクリプトがあります。

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

ロケットの上部がマウスポインタの方を向くように、どの **ロケット**を使うべきでしょうか？

--- choices ---

- ( ) ![左側を指すロケット。](images/rocket_left.png)

  --- feedback ---

ロケットが左側を向いている場合、ロケットは回転したときにマウスポインタとは反対の方向を向いています（離れています）。

  --- /feedback ---

- ( ) ![下向きのロケット。](images/rocket_down.png)

  --- feedback ---

ロケットが下を向いている場合、ロケットが回転すると、マウスポインタとは異なる方向を向きます。

  --- /feedback ---

- (x) ![右側を指すロケット。](images/rocket_right.png)

  --- feedback ---

ロケットが右側を向いている場合、回転方法が`自由に回転`{:class="block3motion"}に設定されていれば、ロケットはマウスポインタを正しく指すためのデフォルトの位置にあります。

  --- /feedback ---

- ( ) ![上向きのロケット。](images/rocket_up.png)

  --- feedback ---

ロケットが上を向いている場合、ロケットが回転すると、マウスポインタとは異なる方向を向きます。

  --- /feedback ---

--- /choices ---

--- /question ---
