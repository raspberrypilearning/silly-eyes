## ステージ効果

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
**ステージ**をクリックすると、プロジェクトに何かを実行させることもできます。
</div>
<div>

![グラフィック効果のあるステージ]( images/stage-effects.png){:width="300px"} 
{:width="300px"}  

</div>
</div>

--- task ---

ステージペインをクリックしてから、 **コード**タブで **ステージ**のコードを追加します。

**選択：** **ステージ**をクリックしたとき、 あなたは変更したいものを選択してください。

--- collapse ---
---
title: ステージがクリックされたときのグラフィック効果を変更する
---

```blocks3
when stage clicked
change [color v] effect by [25]
```

--- /collapse ---

--- collapse ---
---
title: ステージがクリックされたときに背景を切り替える
---

```blocks3
when stage clicked
next backdrop
```

--- /collapse ---

--- /task ---

--- task ---

**テスト：** **ステージ**をクリックし、背景が切り替わるか、グラフィック効果が変化することを確認します。

--- /task ---

--- task ---

**テスト：** プロジェクトをもう一度テストしますが、今回は全画面表示にして、プロジェクトを見ている人にどのように表示されるかを確認します。

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
プロジェクトを全画面表示にすることで、プロジェクトで遊んでいるユーザーの視点から作成したものを確認できます。 **ユーザーインタラクション**はデジタル制作において重要です。 
</p>

--- save ---
