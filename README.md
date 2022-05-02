# mysql_ju_slit
jupyterlabとMySQL&amp;phpMyAdminとstreamlitがセットになったdocker-composeのディレクトリです。

## 使い方

- ターミナルでgit clone https://github.com/keikois/mysql_ju_slit.git を実行
- cd mysql_ju_slit　をターミナルで実行
- docker-compose up -d を実行
- localhost:8888でjupyterlabが起動
- localhost:8080でphpMyAdminが起動
- streamlit run 「app.pyのパス」でstreamlitが起動

- streamlitはcontrol + C で終了します。
- docker-compose down　でdocker-composeを終了できます。

docker-composeのdatabase名の初期値はtest_databaseです。
docker-composeの中の名前やパスワードを変えてください。
