# ダイアログ

`window` オブジェクトにはモーダルダイアログを扱うためのメソッドが用意されています。
モーダルという性質上、ユーザーにストレスを与える可能性があるため、Web サイトでの利用には注意が必要です。

- [モーダルウィンドウ](https://ja.wikipedia.org/wiki/%E3%83%A2%E3%83%BC%E3%83%80%E3%83%AB%E3%82%A6%E3%82%A3%E3%83%B3%E3%83%89%E3%82%A6)

## alert

メッセージ付きダイアログを表示します。

```javascript
alert('error!');
```

## confirm

確認ダイアログを表示します。

ダイアログの選択結果が true/false で渡されるため、以下のように if 文に組み込むことが可能です。

```javascript
if (confirm('たけのこの里派ですか？')) {
  // ...
} else {
  // ...
}
```

## prompt

ユーザーの入力を受け付けるダイアログを表示します。
戻り値には入力値が返ります。

```javascript
console.log(prompt('好きな食べ物は？'));
```
