# Vagrant + concrete5 (Japanese / 日本語)

宮内さんが作成した vagrantfile に修正を加えて concrete5 日本語パッケージをインストールできるようにしたものです。

## 使い方

1. VirtualBoxをインストール
 * [https://www.virtualbox.org/](https://www.virtualbox.org/)
2. Vagrantをインストール
 * [http://www.vagrantup.com/](http://www.vagrantup.com/)
3. Chef Development Kit をインストール
 * [https://downloads.chef.io/chef-dk/mac/](https://downloads.chef.io/chef-dk/mac/)
4. 下記コマンドをいれて vagrant pluginsをコマンドラインからインストール
 * `vagrant plugin install vagrant-omnibus`
5. このレポジトリをローカルにクローン
 * `git clone https://github.com/katzueno/vagrant-concrete5-ja.git`
6. ディレクトリーに移動
 * `cd vagrant-concrete5-ja`
7. cookbooks をインストール
 * `berks vendor cookbooks`
8. Vagrant 環境を起動.
 * `vagrant up`
9. アクセス先は [http://192.168.33.35/](http://192.168.33.35/)
10. ログイン後[管理画面 (Dashboard)]-[システムと設定(System & Setting)]-[言語(Language)]メニューより、日本語を設定すると日本語化されます。

## 設定

各属性の説明は下記を参照

[https://github.com/Launch-with-1-Click/concrete5](https://github.com/Launch-with-1-Click/concrete5)

デフォルトユーザーは

- ID:admin
- Pass: concrete5
- Email: admin@example.com

です。`Vagrantfile` をテキストエディタで開いて変更可能です。

## クレジット

* [@miya0001](https://github.com/miya0001/) * 作者
* [@katzueno](https://github.com/katzueno/) * 日本語版作成
* [@ixkaito](https://github.com/ixkaito/)
* [@mahm](https://github.com/mahm/)
