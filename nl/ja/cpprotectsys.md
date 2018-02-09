---

copyright:

  years: 1994, 2018

lastupdated: "2017-12-04"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# システムの保護
{: #customerportal_protsys}

システムを保護することで、システムが不必要に中断されることなく円滑に稼働することが保証されます。

## プライベート・ネットワークを使用する
{: #cp_bpuseprivnet}

{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーのプライベート・ネットワークを使用して、最大限保護された環境でデバイスを管理することができます。可能な場合、デバイスとの対話に VPN 接続を使用し、ネットワーク・スパンを有効にして、システムがプライベート・ネットワークを介して通信するようにしてください。プライベート・ネットワークにアクセスするには、[ユーザー・リスト ![外部リンク・アイコン](../icons/launch-glyph.svg)](https://control.softlayer.com/account/user/list){:new_window} からユーザーの VPN アクセスを編集します。 [仮想プライベート・ネットワーク ![外部リンク・アイコン](../icons/launch-glyph.svg)](http://www.softlayer.com/vpn-access){:new_window} の説明に従って、さまざまな VPN オプションの 1 つに接続してください。

### RDP ポート、SSH ポート、または制御ポートをパブリック・ネットワークに置いたままにしない
{: #cp_bpnordpsshcponpubnet}

パブリック・ネットワークは多くの場合に有用ですが、開いたポートを介してパブリック・ネットワークで使用可能なままだとシステムに脆弱性を残す可能性がある側面がいくつかあります。パブリック・ネットワークで SSH を制限するか、または RDP を使用不可にすることによって、お客様自身を保護してください。これらのサービスがパブリック・ネットワーク上で使用可能でなければならない場合、RDP または SSH をカスタム・ポート番号に移動することを検討してください。

## 定期的バックアップによってデータを保護する
{: #cp_bpsafedataregback}

{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーは、ドライブ障害またはユーザー・エラーがあった場合にデータを確実に取り出すことができるように、複数のバックアップ・ソリューションを提供しています。現在、バックアップ・ソリューションには、NAS、EVault Backup、および R1Soft CDP があり、これらすべてが各種のストレージ・オプションで使用可能です。各バックアップ・ソリューションについて詳しくは、[ストレージ ![外部リンク・アイコン](../icons/launch-glyph.svg)](http://www.softlayer.com/services/storagelayer/){:new_window} ページを参照してください。

### 冗長性があると想定せず、あることを確認する
{: #cp_bpknowredundant}

{{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーは、二重パス、予備電源機構、および RAID 構成を含む、アドオンによる複数の冗長構成を提供しています。冗長環境で作業すること、および障害が発生した場合に保護されることを確実にするため、これらのフィーチャーのうちの 1 つ以上をプロビジョン済みであることを確認してください。

### OS 再ロードの前に情報がバックアップされていることを確認する
{: #cp_bpnoperfOSwobackupconf}

オペレーティング・システムを再ロードすると、デバイスのハード・ディスクからすべてのデータが削除されます。OS 再ロードを開始する前に、情報をバックアップし、そのバックアップが成功していることを検証して、情報が何も失われないようにしてください。OS 再ロードが完了した後では、失われた情報を取り戻すことはできません。

## Adaptec Storage Manager (ASM) を削除しない
{: #cp_bpsupdontremovasm}

 {{site.data.keyword.BluSoftlayer_notm}} インフラストラクチャーは、ASM を使用して RAID アレイ状況をモニターします。このソフトウェアを削除すると、サポート・チームはデバイスをモニターできなくなります。デバイスから ASM が削除されると、デバイスの RAID 障害アラートが使用可能でなくなり、自動通知システムを通して障害が通知されなくなります。