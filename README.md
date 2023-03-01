# Welcome to kakedashi-art-engine ⚡

ハッシュリップさんが一向に更新しないのでAIに叩き直してもらいました。

```sh
git clone https://github.com/kakedashi3/kakedashi-art-engine.git
```

プロジェクトフォルダに移動。

```sh
cd kakedashi-art-engine
```

依存関係をインストール。

```sh
yarn
```


VScodeを起動。（好みのeditorでよい）
```sh
code .
```

layerフォルダで自分なりにアレンジ。

```js
const layerConfigurations = [
  {
    growEditionSizeTo: 100,
    layersOrder: [
      { name: "Head" },
      { name: "Mouth" },
      { name: "Eyes" },
      { name: "Eyeswear" },
      { name: "Headwear" },
    ],
  },
];
```

生成コマンドを実行。

```sh
node index.js
```

buildフォルダで結果を確認。

