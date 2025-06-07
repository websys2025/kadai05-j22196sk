## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能：https://zipcloud.ibsnet.co.jp/api/search
  郵便番号から住所を検索できる
* リクエストとレスポンスのフォーマット
  リクエスト形式：GET　　例：https://zipcloud.ibsnet.co.jp/api/search?zipcode=1000001
  レスポンス形式：JSON　　内容：address1都道府県　address2市区町村　address3町域
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL：名称Nominatim API　　URL: https://nominatim.org/release-docs/latest/api/Search/
* エンドポイントと機能：エンドポイント: https://nominatim.openstreetmap.org/search
  機能：郵便番号から経度と緯度を検索できる
* リクエストとレスポンスのフォーマット：形式JSON　　レスポンス内容：lat緯度　lon経度　display_name住所
### Q3-3. 感想
* 今回の課題で苦労したこと　APIを探したりレスポンス内容を理解するのに苦労した
* 演習を通して理解できたこと　レスポンス内容はいくつかに分かれている
* Web APIの利便性や課題など　利便性は外部のデータに頼れる　　課題は無料のAPIには制限がある
