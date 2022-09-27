# 実践 Keycloak - OpenID Connect、OAuth 2.0を利用したモダンアプリケーションのセキュリティー保護

<a href="https://www.amazon.co.jp/dp/4814400098"><img src="https://images-na.ssl-images-amazon.com/images/I/81omwIVptSL.jpg" alt="実践 Keycloak - OpenID Connect、OAuth 2.0を利用したモダンアプリケーションのセキュリティー保護" height="512px" align="left"></a>O'Reilly Japanから出版される「[Keycloak - OpenID Connect、OAuth 2.0を利用したモダンアプリケーションのセキュリティー保護](https://www.amazon.co.jp/dp/4814400098)」のコードリポジトリーです。

## 本書について

本書は、KeycloakのコアディベロッパーであるRed Hat社のStian Thorgersen（Keycloakプロジェクトのリーダー）氏とPedro Igor Silva氏が中心となって執筆した「Keycloak - Identity and Access Management for Modern Applications」を翻訳したものです。

<a href="https://www.packtpub.com/product/keycloak-identity-and-access-management-for-modern-applications/9781800562493?utm_source=github&utm_medium=repository&utm_campaign=9781800562493"><img src="https://static.packt-cdn.com/products/9781800562493/cover/smaller" alt="Keycloak - Identity and Access Management for Modern Applications" height="256px"></a>

<br/>以下について解説しています。

* Keycloakのインストール、設定、管理の方法
* Keycloakを使用したアプリケーションのセキュリティーの保護
* OAuth2.0とOpenID Connectの基礎知識
* Keycloakを本番環境で使用できるようにする方法
* 追加機能を活用する方法と、ニーズに合わせてKeycloakをカスタマイズする方法

本書は、 [こちら](https://www.amazon.co.jp/dp/4814400098)から購入可能です。

### 対象読者と前提知識

開発者、システム管理者、セキュリティーエンジニア、またはKeycloakを活用したい人なら誰でも、本書が役立つでしょう。アプリの開発、認証、認可に関する初心者レベルの知識が求められます。

### ソフトウェア要件

次のソフトウェアとハードウェアのリストを使用すると、本にあるすべてのコードファイルを実行できます。

| 章  | ソフトウェア要件                  | OS要件                      |
| -------- | ------------------------------------| -----------------------------------|
| 1-14（＋補章）       | Keycloak 18.0.2                  | Windows, macOS, Linux (任意) |
| 1-14（＋補章）       | OpenJDK 17以上                       | Windows, macOS, Linux (任意) |
| 1-14（＋補章）       | Node.js 14以上                       | Windows, macOS, Linux (任意) |

## Code in Action

本書のCode in Actionのビデオが、[YouTube](https://www.youtube.com/playlist?list=PLeLcvrwLe187DykEKXg-9Urd1Z6MQT61d)で視聴できます。本書の内容に沿ってKeycloakの動作を確認できるビデオが章ごとに準備されています。ただし、これらのビデオの中ではWildFlyベースのKeycloak 12.0.4を使用しているため、本書が前提としているQuarkusベースのKeycloak 18.0.2とは操作方法などに大きな違いがある点に注意してください。WildFlyベースのKeycloakを使用すると、ほぼビデオの内容通りに操作ができます。

## Errata

* 現時点ではありません。

## 著者
**Stian Thorgersen**（Red Hat）

Arjuna Technologiesでキャリアをスタートし、パブリッククラウドが世に出る何年も前にクラウドフェデレーションプラットフォームの構築に携わる。その後、Red Hatに入社し、開発者の生活をより快適にする方法を模索。これがKeycloakのアイディアの発端となり、2013年にRed Hatの開発者と共同でKeycloakプロジェクトを立ち上げる。
現在、Keycloakのプロジェクトリーダーであり、プロジェクトのトップコントリビューターでもある。Red Hatに在籍し、シニアプリンシパルソフトウェアエンジニアとして、Red Hatや顧客のためのIAMに注力している。
休みの日にノルウェーの山々を自転車で駆け下りることが、何よりの楽しみ。

**Pedro Igor Silva**（Red Hat）

娘たちの自慢のパパ。2000年にISPでキャリアをスタートし、JavaやJ2EEのソフトウェアエンジニアとして、FreeBSDやLinuxなどのオープンソースプロジェクトを経験。それ以来、さまざまなIT企業で、システムエンジニア、システムアーキテクト、コンサルタントとして活躍。
現在、Red Hatのプリンシパルソフトウェアエンジニアであり、Keycloakのコアディベロッパーの1人。主な関心と研究分野は、ITセキュリティー、特にアプリケーションセキュリティーとIAM。仕事以外の時間は、水草のアクアリウムを世話している。

## 翻訳者

**和田 広之**（NRI OpenStandia所属）

OSSを利用したシステム構築の支援、OSSサポートを業務で行いつつ様々なOSSにもコントリビューションを行っている。近年では認証・認可の分野のOSSを中心に活動しており、Keycloakに対しても機能追加、バグ修正、日本語化、公式ガイドの日本語化プロジェクトの立ち上げなどを行っている。
 - GitHub: [wadahiro](https://github.com/wadahiro)
 - Twitter: [wadahiro](https://twitter.com/wadahiro)

**田村 広平**（NRI OpenStandia所属）

認証・認可の分野はSun MicrosystemsがOpenSSO 9（Keycloak同様のIAMのOSS）を開発していた頃から始め、後に後継のOpenAMのコミッターとなり、多くの改良や記事の執筆を行った。OpenAMが商用化してからは、Keycloakのサポートへメインの業務をシフトし、Keycloakのバグ修正や日本語化、公式ガイドの日本語訳、@ITの連載や書籍での執筆活動などを行っている。
 - GitHub: [k-tamura](https://github.com/k-tamura)
 - Twitter: [tamura__246](https://twitter.com/tamura__246)

**乗松 隆志**（日立製作所アーキテクチャセンタ所属）

OSSのサポートサービスの提供、機能の実装とコントリビューションを行っている。近年では、Financial-grade API (FAPI) Security Profileなどセキュリティ関係の標準仕様の実装とコントリビューションをKeycloakに対して行っている。
 - GitHub: [tnorimat](https://github.com/tnorimat)

**田畑 義之**（日立製作所アーキテクチャセンタ所属）

API管理や認証周りのOSSのコンサル/サポート/普及活動に従事。3scaleおよびkeycloakコミュニティのコントリビュータであり、多数のコードをコミットしている。
 - GitHub: [y-tabata](https://github.com/y-tabata)
