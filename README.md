# モーダルウィンドウを作ってみよう

## 課題

後述する仕様の通りに動作するように ```js/app.js``` を編集しましょう。  
穴埋めになっているので ```/* Insert code here... */``` の箇所にコードを足してください。

HTML と CSS は出来ているので変更しません。  
ただし重要なヒントですのでよく確認してください。

## モーダル機能の仕様

### 開く

```data-modal-open``` 属性を付与した要素をクリックすると、```data-modal-open```  の属性値を id に持つ要素をモーダルウィンドウとして表示します。

```html
<button data-modal-open="myModal">Open Modal</button>

<div id="myModal"><!-- Content --></div>
```

### 閉じる

モーダル内の、```data-modal-close``` 属性を持つ要素をクリックするとそのモーダルウィンドウを閉じます。

```html
<div id="myModal">
  <button data-modal-close>Close Modal</button>
</div>
```
