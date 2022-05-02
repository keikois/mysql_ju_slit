# mysql_ju_slit
jupyterlabとMySQL&amp;phpMyAdminとstreamlitがセットになったdocker-composeのディレクトリです。

## 使い方

- mysql_ju_slitをForkする
- cd mysql_ju_slit　をターミナルで実行
- docker-compose up -d を実行
- localhost:8888でjupyterlabが起動
- localhost:8080でphpMyAdminが起動
- streamlit run 「app.pyのパス」でstreamlitが起動

- streamlitはcontrol + C で終了します。
- docker-compose down　でdocker-composeを終了できます。
