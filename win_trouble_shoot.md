# windowsが調子悪いときに確認すること
<!-- 2022/07/19(TUE) -->

## SysMainの確認
C:¥Windows¥Prefetch¥フォルダを確認
(SuperFetch SysMainの可能性もある)

「コンピュータの管理」を起動

[コンピュータの管理(ローカル)]-[サービスとアプリケーション]-[サービス]を選択
SysMainを停止

## ユーザプロファイルの確認
[システムのプロパティ]で、[詳細設定]タブを選択
[ユーザプロファイル]-[設定(E)...]ボタンを押下
サイズが200MBを越えるユーザがいないか確認する

## LocalGlobalPolicy
gpdeit.mscを起動

## LocalSecurityPolicy
secpol.mscを起動
