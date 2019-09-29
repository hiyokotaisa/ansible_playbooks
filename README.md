# Ansible構築・運用ガイドブック プレイブック集
## 概要
このリポジトリでは、『Ansible構築・運用ガイドブック』内で提示したサンプルプレイブックおよびvagrantfileを公開しています。
各プレイブックの詳しい説明については、書籍を参照してください。

## 使用方法
以下のコマンドを実行し、ファイルをクローンしてください。
```
$ git clone https://github.com/hiyokotaisa/ansible_playbooks.git
```
Vagrantで生成する各VM上には、このリポジトリが自動的にクローンされます。

## コンテンツ
- [README.md](https://github.com/hiyokotaisa/ansible_playbooks/blob/master/README.md): このドキュメント
- [bootstrap](https://github.com/hiyokotaisa/ansible_playbooks/tree/master/bootstrap): Vagrantで作成する仮想マシンのSSH設定を変更するプレイブック
- chapterX: 各章で提示したプレイブックおよび検証に使用するVagrantfile
  - vagrant: Vagrantfile
  - playbooks: プレイブックおよびロール

本リポジトリに関するお問い合わせは、[@hiyoko_taisa](https://twitter.com/hiyoko_taisa) までお願いします。
