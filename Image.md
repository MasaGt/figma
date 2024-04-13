### Figma での画像

画像を配置する方法 (結果は同じ)

- オブジェクトの Fill に画像ファイルを指定する
- 画像ファイルを直接配置する

---

### 画像に fill を追加する (Adding anther fill)

画像オブジェクトにさらに fill を追加することで画像に色を重ねることができる

*色のレイヤーが画像レイヤーの上になっていること (レイヤの順番に注意)

1\. 画像オブジェクトに fill を追加する
<img src="./img/image_another_fill.png" />

<br>

2\. 色をグラデーションにしたり、ブレンドモードを指定することで、より細かく重ねる色を設定することができる

<img src="./img/image_another_fill2.png" />
<img src="./img/image_another_fill3.png" />

[4-3. オブジェクトに色を塗る](https://chot.design/figma-beginner/f64023a95af9/)

---

### 画像のマスキング (Masking)

オブジェクトを好きな形に切り抜くことができる

*トリミングと違い、マスキングするとマスクオブジェクトが作成される

*<font color="red">下のオブジェクトの形に沿って、上のオブジェクトが切り抜かれる</font>

<br>

例: 画像を星型に切り抜く

1\. 画像と星型のオブジェクトを設置する

<img src="./img/image_masking1.png" />

<br>

2\. 画像を星型オブジェクトの上に配置する

<img src="./img/image_masking2.png" />

<br>

3\. 画像と星型オブジェクトの両方を選択し、上のツールバーもしくは右クリックから "Use as Mask" を選択

<img src="./img/image_masking3.gif" />

<br>

4\. レイヤーを確認すると Star1 がその上のオブジェクトをマスクしていることがわかる

<img src="./img/image_masking4.png" />

<br>

[マスク(Figma公式)](https://help.figma.com/hc/ja/articles/360040450253-マスク)

---

### トリミング (Trimming)

画像のいらない部分を切り落とす機能

画像を配置後、上のツールバーにある crop image を選択し好きな部分を切り取る

<img src="./img/image_trim.gif" />

---

### 画像から色を抽出する

fill のスポイトツールを利用することで選択した箇所の色を抽出することができる

<img src="./img/image_eyedropper.gif" />