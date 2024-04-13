### レイアウトグリッドとは

フレーム内に、 grid / column / row 状のデザインガイドラインを表示する機能

あらゆるフレームに設定できるので、子フレームにも設定できる

<img src="./img/layout-grid3.png" />

---

### 使い方

1\. レイアウトグリッドを表示したいフレームを選択し、右のパネルから "Layout grid" を選択する

<img src="./img/layout-grid1.png" />

<br>

2\. 追加したレイアウトグリッドを右のパネルから選択することで、レイアウトグリッドの設定を変更することができる

<img src="./img/layout-grid2.png" />

---

### Grid

Size: マス目のサイズ

- Size: 10 の場合 1つのマス目の大きさは 10px * 10px

<img src="./img/layout-grid_grid1.png" />

<img src="./img/layout-grid_grid2.png" />

---

### Columns, Rows


Count: カラム(ロウ)の数

Gutter: 各カラム(ロウ)間の間隔 (px)

Type: カラム(ロウ)の配置方法

- stretch:　フレームのサイズに合わせて、カラム(ロウ)のサイズも変わる

    <img src="./img/layout-grid_stretch1.png"/>

    <img src="./img/layout-grid_stretch2.png"/>


<br>

- right / left / center (columns): フレームのサイズとは独立してカラムのサイズがある。また、カラムの場所はフレームのサイズ関係なく固定される

- top / center / bottom (rows): right / center / left のロウバージョン

    <img src="./img/layout-grid_top1.png" />
    <img src="./img/layout-grid_top2.png" />

<br>

width (right / left / centerの時のみ有効): カラム(ロウ)のサイズ

---

### 1つのフレームに複数のグリットを設定できる

<img src="./img/layout_grid_multi.png" />