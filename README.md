Rails Bootstrap サンプル
========================

Rails で Bootstrap を使ったサンプル

[![Build status][shield-build]](#)
[![MIT licensed][shield-license]](#)
[![Rails](https://img.shields.io/badge/-Rails-CC0000.svg?logo=rails&style=flat)][rails]
[![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791.svg?logo=postgresql&style=flat)][postgresql]
[![Bootstrap](https://img.shields.io/badge/-Bootstrap-563D7C.svg?logo=bootstrap&style=flat)][bootstrap]

## Table of Contents

* [Technologies](#technologies)
* [Demo](#demo)
* [Getting started](#gettting-started)
* [Deployment](#deployment)
* [Usage](#usage)
* [References](#references)
* [License](#license)

## Technologies

* [Rails][rails] 5.x
* [PostgreSQL][postgresql]
* [Bootstrap][bootstrap] 4.x
* [Slim][slim]

## Demo

* [Heroku](https://sample-rails-bootstrap.herokuapps.com)

## Getting started

### Rails アプリケーション作成

```sh
$ rails new sample-rails-bootstrap -d postgresql --skip-turbolinks
$ cd sample-rails-bootstrap
$ git add .
$ git commit -m "Initial commit"
```

### GitHub

- GitHub に sample-rails-bootstrap という名前でリポジトリ追加

```sh
$ git remote add origin git@github.com:kyuuki/sample-rails-bootstrap.git
$ git push -u origin master
```

### Slim 導入

コミットを参照

### トップページ作成

```sh
$ rails g controller StaticPages home
```

## Deployment

Heroku にデプロイ

```sh
$ heroku create sample-rails-bootstrap
$ git push heroku master
$ heroku run rake db:migrate
```

## Usage

* [Slim README.md (日本語)](https://github.com/slim-template/slim/blob/master/README.jp.md)
* [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

## References

* https://yakst.com/ja/posts/3859
* https://qiita.com/s-yoshiki/items/436bbe1f7160b610b05c

## License

This is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.  
Copyright &copy; 2019, kyuuki



[rails]: https://rubyonrails.org/
[postgresql]: https://www.postgresql.org/
[bootstrap]: https://getbootstrap.com/
[slim]: http://slim-lang.com/

[shield-build]: https://img.shields.io/badge/build-passing-brightgreen.svg
[shield-license]: https://img.shields.io/badge/license-MIT-blue.svg
