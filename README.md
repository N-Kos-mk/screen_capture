# screen_capture
htmlページの\<body\>の中身をまるっと持ってきて写真としてダウンロードするjs

## 使い方

次のコードをブックマークレットとしてブラウザに登録してください。

```js
javascript:(function(url){s=document.createElement('script');s.src=url;document.body.appendChild(s);})('https://N-kos-mk.github.io/screen_capture/capture.js');
```

実行すると"screenshot.png"が端末にダウンロードされます。

## どんなの
[html2canvas.js](https://cdnjs.cloudflare.com/ajax/libs/html2canvas/0.4.1/html2canvas.js)とかいうまんまのjsが転がってたので、そいつをevalした結果をダウンロードしてるだけ

## 注意
ブックマークレット自体でよく起きること
![image](https://github.com/N-Kos-mk/screen_capture/assets/82209854/9db28f85-420b-419b-bfbc-b96b9dcdb513)
特定のサイトでは使えません！githubも。

## LICENSE
MIT
