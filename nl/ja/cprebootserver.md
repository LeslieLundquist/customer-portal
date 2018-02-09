---

copyright:

  years: 1994, 2018

lastupdated: "2017-12-05"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}

# サーバーのリブート
{: #customerportal_rebootserver}

サーバーのリブートが必要なイベントが {{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーで発生することがあります。
{:shortdesc}

サーバーをリブートするには、以下の手順を使用します。
1. カスタマー・ポータルで**「サポート」**タブをクリックします。
2. **「リブート (Reboot)」**をクリックします。
3. リブートするサーバーを選択し、**「リブート (Reboot)」**をクリックします。
4. サーバーをリブートするため、以下のいずれかの方式を選択します。
  * デフォルト (IPMI でリブートを試行し、次に電源ストリップでリブートを試行します)
  * IPMI
  * 電源ストリップ
5. 「リブート」をクリックします。

このページではレスキュー・カーネルへのブートを行う機能も提供されています。この機能は、構成の問題のためにサーバーが OS にブートできないという問題が発生したときに役立ちます。レスキュー・カーネルへのブートの後、サーバーのドライブをマウントし、構成の問題を修正できます。問題が修正された後、コマンド・ラインからサーバーをリブートできます。そうすると、サーバーはサーバーのデフォルトのカーネルにリブートされます。reboot コマンドを実行すると、完了までの見積もり時間が表示されます。