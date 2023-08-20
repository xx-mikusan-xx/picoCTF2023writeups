# ReadMyCert(100pt)
## 問題
How about we take you on an adventure on exploring 
certificate signing requests
Take a look at this CSR file here.
## 解法
`cat`コマンドでファイルの中身を見るとbase64でデコードされたっぽい文字列が現れるので[このサイト](https://tool-taro.com/base64_decode/)でエンコードするとflagが得られる
## flag
picoCTF{read_mycert_a7163be8}