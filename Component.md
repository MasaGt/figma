### コンポーネントとは

- よく使い回す UI パーツをコンポーネントとして登録しておき、再利用を可能にするもの

---

### コンポーネントの作り方

1\. 登録したい UI パーツを作成する

2\. UI パーツを選択し、画面上のツールばーより "Create component" を選択する

3\. 左の layer パネルにて、コンポーネントとして登録されていることを確認  
        -> 登録したコンポーネントはメインコンポーネントと呼ばれる

---

### コンポーネントから UI の複製

方法はいくつかある

1\. 右のパネルを Asset に切り替え、複製したいコンポーネントをドラッグし、画面上でドロップする

2\. 画面上のツールバーより、 "Resources" を選択し、複製したいコンポーネントをドラッグし、画面上でドロップする

3\. 画面上のコンポーネントを選択し、 option + shift を押しながらドラッグ&ドロップする

-> コンポーネントの複製は instance と呼ばれる

---

### メインコンポーネントとインスタンスの関係

メインコンポーネントのプロパティを変更すると

->インスタンスのプロパティも変更される


インスタンスのプロパティを変更すると

-> そのインスタンスのプロパティのみ代わり、他のインスタンスやメインコンポーネントには影響を及ぼさない


---

### メインコンポーネントの管理方法

セクションをフレーム外に作成し、その中にメインコンポーネントを配置することで、どれがメインコンポーネントでどれがインスタンスなのかが一目瞭然になる
