# mysql_ju_slit
jupyterlabとMySQL&amp;phpMyAdminとstreamlitがセットになったdocker-composeのディレクトリです。

## 使い方

- ターミナルで下記のコードを実行
```
git clone https://github.com/keikois/mysql_ju_slit.git
```
```
cd mysql_ju_slit　
```
```
docker-compose up -d
```

- localhost:8888でjupyterlabが起動
- localhost:8080でphpMyAdminが起動
- streamlit run <app.pyのパス> でstreamlitが起動

- streamlitはcontrol + C で終了します。
- docker-compose down　でdocker-composeを終了できます。
