# CalicoP(キャリコップ)
MiGTA LSPD用ツール

## ■ 概要
犯罪の一覧を手軽に閲覧したり,指名手配や報告書を必要最低限の情報を入力すると

自動で生成してくれるなど警察業務を手助けするツールです。

## ■ ダウンロード
[こちらのリンク](https://github.com/kedaryu/CalicoP/releases/tag/beta "β版v0.1.0") から下記画像にもある"CalicoP.zip"をダウンロード。

解凍して"CalicoP.exe"を起動する事で使用できます。
![CalicoP_DL](https://github.com/kedaryu/CalicoP/assets/32934931/d6801b82-766a-4f4c-aa48-b95e6aa5b295)

## ■ 使い方
### 犯罪一覧
「罪状・罰金・留置時間上限(分)・指名手配期間(分)・詳細」が記載された

犯罪一覧が表示されます。
![CalicoP_List](https://github.com/kedaryu/CalicoP/assets/32934931/79040cba-c4b9-400f-9e94-ec55bef987de) 

一番左の「？」がある場合はその罪状の詳細な情報が表示されます。
![CalicoP_List_Info](https://github.com/kedaryu/CalicoP/assets/32934931/80f2544f-9f07-448d-a0fa-bc295c8a4a29)

---


### 報告書
左側に必要な情報を入力すると報告書のフォーマットに従って右側に生成されます。

タイトルや概要をコピー&ペーストする事で報告書を書く時間を短縮できます。
![CalicoP_Report](https://github.com/kedaryu/CalicoP/assets/32934931/312f8608-51af-4168-8fac-5709b85cf7be)

罪状は[三]のボタンからチェックボックス式で簡単に選択できます。

また罰金額も自動で計算されるようになっています。
![CalicoP_Report_List](https://github.com/kedaryu/CalicoP/assets/32934931/99a6aac0-df3c-4ac4-aa97-7044be334352)

---


### 指名手配
指名手配犯の名前と罪状を選択する事でBirdyで出す文章を自動で生成してくれます。
選択した罪状の中から一番長い指名手配期間で時間も計算してくれます。
(※ 現状平日の1:00~は犯罪禁止時間となっているためそれを超える指名手配期間は1:00までで切り上げるルールですが
本ツールではそこまでは自動化できていないのでその際はBirdyに投降する前に手動で修正してください)
![CalicoP_Wanted](https://github.com/kedaryu/CalicoP/assets/32934931/e3e5d14e-8da0-49bd-966e-b0a69923bc9d)

罪状は[三]のボタンからチェックボックス式で簡単に選択できます。
![CalicoP_Wanted_List](https://github.com/kedaryu/CalicoP/assets/32934931/5afc9c67-67c3-45ba-8772-66c4fc4cbd72)
