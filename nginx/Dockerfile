# 元となるコンテナイメージを FROM で指定する
FROM nginx

# ラベルを付ける
LABEL handson-nginx=

# カレントディレクトリに存在する index.html をコンテナの /usr/share/nginx/html/ に追加する
ADD index.html /usr/share/nginx/html/index.html
