# テクノロジー（藤原）11/22授業

## ミニレポート

下記は `asagao/config/routes.rb` の内容です。

```ruby
Rails.application.routes.draw do
  root "top#index"
  get "about" => "top#about", as: "about"
end
```

この設定について、表を埋める形で次を答えてください：

- 受け付けるパスの形（下記の表「パスの形」）
- 呼びだすコントローラの名前（下記の表「コントローラ」）
- 呼びだすアクションの名前（下記の表「アクション」）

## 回答

- 「★」の部分に記入してください。
- `config/routes.rb`の1行(`do`と`end`の内側)が、表の1行に対応します

| パスの形 | コントローラ | アクション | ソースコード |
| --- | --- | --- | --- |
| ★    | ★    | ★    | `root "top#index"`                        |
| ★    | ★    | ★    | `get "about" => "top#about", as: "about"` |
