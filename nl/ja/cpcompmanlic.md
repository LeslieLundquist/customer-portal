---

copyright:

  years: 1994, 2018

lastupdated: "2017-12-06"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}

# デバイスの管理
{: #cp_compacclisc}

cPanel や Parallels などのアクティブなコントロール・パネル・ソフトウェアのライセンスを、カスタマー・ポータルの「コントロール・パネル・ライセンス (Control Panel Licenses)」ウィンドウで管理できます。 ライセンスおよびそれに関連付けられた IP の表示、ライセンス・ファイルのダウンロード、個々のライセンスの取り消しを行うことができます。 また、カスタマー・ポータルから、各デバイス上のソフトウェア用のパスワードを管理することもできます。
{:shortdesc}


## デバイスへのライセンスのダウンロード
{: #cp_compdllisc}

ライセンス・ファイルは、デバイス上のソフトウェアおよび使用可能にされたすべてのソフトウェア・フィーチャーに対してライセンスが有効かどうかを検証するために使用されます。 カスタマー・ポータルからライセンス・ファイルをダウンロードできますが、対応するコントロール・パネル・ソフトウェアが実行されているデバイスでのみ行うことができます。 ライセンス・ファイルをダウンロードするには、以下の手順を使用します。

1. 固有の資格情報を使用してカスタマー・ポータルにログインします。
2. メニューから**「デバイス (Devices)」** > **「管理 (Manage)」** > **「コントロール・パネル・ライセンス (Control Panel Licenses)」**を選択して、「コントロール・パネル・ライセンス (Control Panel Licenses)」ウィンドウにアクセスします。
3. ライセンスに対して**「アクション (Actions)」 > 「ライセンス・ファイルのダウンロード (Download License File)」**を選択します。
4. デバイスのオペレーティング・システムによって提供されるプロンプトを使用して、デバイス上のコントロール・パネル・ソフトウェアにファイルを保存またはダウンロードします。

ライセンス・ファイルをデバイスにダウンロードした後、ライセンスに関するコントロール・パネル・ソフトウェアの詳細が更新されます。 問題が発生するか、ダウンロードが正常に終了しなかった場合は、上の手順を繰り返してダウンロード処理を再試行してください。

## コントロール・パネル・ライセンスの取り消し
{: #cp_compcanlisc}

コントロール・パネル・ライセンスは、ライセンス購入時に合意したご利用条件に基づいて月次で請求されます。 ライセンスはいつでも取り消すことができ、取り消しは次回の請求応当日に行われます。 現行の請求サイクルに取り消しが適切に適用されることを確実にするには、請求応当日の 24 時間以上前に取り消しを行う必要があります。 取り消し処理中に、アカウントの請求応当日についての具体的な情報が表示されます。 コントロール・パネル・ライセンスを取り消すには、以下の手順を使用します。

1. コントロール・パネル・ライセンスに関連付けられたすべてのデータをバックアップまたは転送します。
2. 固有の資格情報を使用してカスタマー・ポータルにログインします。
3. メニューから**「デバイス (Devices)」** > **「管理 (Manage)」** > **「コントロール・パネル・ライセンス (Control Panel Licenses)」**を選択して、「コントロール・パネル・ライセンス (Control Panel Licenses)」ウィンドウにアクセスします。
4. 取り消すコントロール・パネル・ライセンスに対して**「アクション (Actions)」** > **「取り消し (Cancel)」**を選択します。
5. **「メモ (Notes)」**テキスト・ボックスに、この取り消しに関するメモを入力します。
6. **「続行 (Continue)」**をクリックして確認画面に進みます。
7. **「データ損失確認応答 (Data Loss Acknowledgement)」**チェック・ボックスを選択します。

  重要なデータをバックアップしなかった場合、ライセンスを取り消す前に、最初のステップに戻ってすべてのデータをバックアップしてください。
  {: tip}

8. **「ライセンスの取り消し (Cancel License)」**をクリックします。

取り消し処理を開始すると、コントロール・パネル・ライセンスの取り消しが次回の請求応当日に行われるようにスケジュールされます。 取り消しが誤って行われた場合、カスタマー・ポータルの「取り消し (Cancellations)」画面でその取り消しを無効にすることができます。

## デバイス上のソフトウェア・パスワードの管理
{: #cp_bpmanacctresp}

デバイス上でプロビジョンされた各ソフトウェアには、{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャー・システムによって自動生成されるパスワードが割り当てられます。 各デバイスのソフトウェア・パスワードは、カスタマー・ポータルの「デバイス詳細 (Device Details)」画面の**「パスワード (Passwords)」**タブに保管されています。  初めてソフトウェアにアクセスした後、パスワードを変更してください。 オプションで、デバイスごとに**「パスワード (Passwords)」**タブにソフトウェア資格情報を保管できます。 ただし、カスタマー・ポータルにパスワードを保管する場合、アカウントへのアクセス権限および適切な許可を持つ人であれば誰でもそれらのパスワードを見ることができます。
