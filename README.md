# 概要
本プロジェクトはGitHub Flow をベースにwebアプリケーションでCI/CDを行う練習です。

GitHub ActionsとArgoCDを使用する予定です。

Djangoの[チューとリアル](https://docs.djangoproject.com/ja/4.2/intro/)を作る形で進めます。


CICDパイプラインは以下の画像です。
![Django_CICD](https://github.com/yu-kod/webApp-cicd/assets/48035533/e0316143-2368-4901-b279-d5b3bb914277)

# 現状
上記のCI/CDパイプラインは完成しました。
現在はLonghorn, Prometheus, Grafana, Mackarelを導入して監視を行っています。

# これから
ドメインを取得したのでLet's EncryptでSSL証明書を取得してInngressを外部にWebアプリケーションとして公開することを考えています。
