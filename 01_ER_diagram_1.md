# ER図1
## 全体
- 作成日時、更新日時のカラムがない
- 管理人がログインするのは一つのidで良い
- 現住所以外の配送先を登録できない
- 決済をしないとカートにある商品がわからない

## エンドユーザ
- 論理削除を考慮していない

## 商品
- 商品名がない
- 販売ステータスが判断できない
- ジャンルを変更しづらい
- 税率が変わった時にめんどくさい
- 

## 購入履歴
- 主キーがない
- 商品がどれだけ減ったかわからない
- 合計金額がわからない

## カート
- ステータスがどの段階かわからない
- アーティスト名、ジャケット画像、アルバム名は商品テーブルから持ってくる


# 注意
* マークダウン形式で記入してください。
* 全体を通しての指摘事項の場合、テーブル名の部分を「全体」「共通」などとしてください。

