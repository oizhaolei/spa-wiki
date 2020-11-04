---
#ダッシュボード
---
ダッシュボードは当システムにログオンしてから最初表示される画面です。
当画面でチケット進捗、ユーザーのプロジェクト、フローと操作履歴(アクティビティ)を確認できます。


##1 ダッシュボードを開く
システムに登録してから、最初に表示されるのはダッシュボード画面です。
既に他の画面に入った場合に、画面上の方の機能メニューに<u>ダッシュボード</u>をクリックするとダッシュボード画面が表示されます。
![avatar](../images-jp/userGuide/analysis/analysisMenu-jp.jpg)
ダッシュボードに下記の内容があります：
- チケット状況：最近１か月間に毎日のチケット件数を表示します
- 最近1ヶ月間チケット状況：近１か月間に進捗状態により分類して統計します
- プロジェクト：ユーザーのプロジェクトをリストアップします
- フロー：よく使うフローと最近更新フローをリストアップします
- アクティビティ：操作履歴をリストアップします

![avatar](../images-jp/userGuide/analysis/analysisPanel-jp.jpg)

##2 チケット状況
チケット状況はバーチャートで最近１か月間に毎日のチケット件数を表示します。
横軸は日付で、開始日が当日から一カ月前の日付で、終了日は昨日です。
縦軸はチケット件数、青色軸が毎日の総件数(全部)で、緑軸が毎日の未完了件数です。
![avatar](../images-jp/userGuide/analysis/ticketStatusBlock-jp.jpg)

###2.1 全部と未完了
初期はバーチャートに毎日のチケットの総件数と未完了件数の何れもが表示されます。
中の何れかだけを表示するには全部と未完了のチェックボックスをチェックオン、チェックオフすることによりできます。

(1) 全部だけ表示します
全部のチェックボックスをチェックオンし、未完了のチェックボックスをチェックオフします。
![avatar](../images-jp/userGuide/analysis/ticketStatusOnlyAll-jp.jpg)
(2) 未完了だけ表示します
未完了のチェックボックスをチェックオンし、全部のチェックボックスをチェックオフします。
![avatar](../images-jp/userGuide/analysis/ticketStatusOnlyUnfinishedl-jp.jpg)
(3) 全部と未完了の何れもを表示します
全部と未完了の両方の何れもを表示するには全部と未完了のチェックボックスの何れもをチェックオンします。
![avatar](../images-jp/userGuide/analysis/ticketStatusShowAll-jp.jpg)

###2.2 ある日付のチケット件数を確認します
確認する日付のバーにマウスを移動すると、その日のチケット件数が表示されます。
![avatar](../images-jp/userGuide/analysis/ticketStatusMouseupBar-jp.jpg)

##3 最近1ヶ月間チケット状況
最近1ヶ月間チケット状況は、最近１か月間のチケットを対応終了、対応中、一時停止、キャンセルの進捗状態で分類して統計します。
![avatar](../images-jp/userGuide/analysis/ticketStatGrp-jp.jpg)

###3.1 ドーナツチャートで一部の進捗状態のチケットを表示します
初期はドーナツチャートで各進捗状態のチケットの何れもが表示されます。
一部の進捗状態のチケットを表示するには進捗状態のチェックボックスをチェックオン、チェックオフすることによりできます。
例えば対応終了とキャンセルの両種のチケットを表示するには、対応終了とキャンセルの両チェックボックスをチェックオンし、
他のチェックボックスをチェックオフしていいです。
![avatar](../images-jp/userGuide/analysis/ticketStatGrpPartShowInPie-jp.jpg)

###3.2 ドーナツチャートである進捗状態のチケットの比率を確認します
ドーナツチャートの傍に各進捗状態のチケットの件数と比率がリストアップします。
![avatar](../images-jp/userGuide/analysis/ticketStatGrpTicketList-jp.jpg)
ドーナツチャートでもある進捗状態のチケットの比率を確認できます。例えばキャンセルのチケット比率を確認するには、
ドーナツチャートでマウスをキャンセルの部分に移動すると、キャンセルのチケット比率が表示されます。
![avatar](../images-jp/userGuide/analysis/ticketStatGrpMouseupPie-jp.jpg)

###3.3 ある進捗状態のチケット一覧を確認します
ある進捗状態のチケット一覧を確認するには最近1ヶ月受付の一覧中の一列目（進捗状態の列）をクリックすると、
その状態に相応するチケット一覧が表示されます。
![avatar](../images-jp/userGuide/analysis/ticketStatGrpListStatLink-jp.jpg)
![avatar](../images-jp/userGuide/analysis/ticketStatGrpStatTickeList-jp.jpg)

##4 プロジェクト
プロジェクトは私のプロジェクトと関連プロジェクトの両部分に分けられます。
私のプロジェクトは所有権が当ユーザーに属するプロジェクトで、
関連プロジェクトは当ユーザーがプロジェクトメンバーに含まれるプロジェクトです。
![avatar](../images-jp/userGuide/analysis/projMyProj-jp.jpg)
![avatar](../images-jp/userGuide/analysis/projParticipationProj-jp.jpg)

あるプロジェクトの詳細を確認するには、一覧にプロジェクト番号をクリックするとプロジェクト総合情報管理画面が表示されます。
![avatar](../images-jp/userGuide/analysis/projListProjNoLink-jp.jpg)
![avatar](../images-jp/userGuide/analysis/projDtlFromProjList-jp.jpg)

##5 フロー
フローは、よく使うフローと最近更新フローの両部分に分けられます。
よく使うフローは最近よく使っているフローで、最近更新フローは最近新規又は更新されたフローです。
![avatar](../images-jp/userGuide/analysis/flowFrequentlyUseList-jp.jpg)
![avatar](../images-jp/userGuide/analysis/flowRecentlyUpdatedList-jp.jpg)

あるフローの詳細を確認するには、一覧にフロー名称をクリックすると、フロー総合情報管理画面が表示されます。
![avatar](../images-jp/userGuide/analysis/flowListFlowNameLink-jp.jpg)
![avatar](../images-jp/userGuide/analysis/flowDtlFromFlowList-jp.jpg)

##6 アクティビティ
アクティビティは最近の操作履歴です。ここで操作者、操作プロジェクト、操作区分と操作日付を確認できます。
![avatar](../images-jp/userGuide/analysis/activityList-jp.jpg)

操作プロジェクトの詳細を確認するには、一覧にプロジェクトをクリックするとプロジェクトの総合情報管理画面が表示されます。
![avatar](../images-jp/userGuide/analysis/activityListProjLink-jp.jpg)
![avatar](../images-jp/userGuide/analysis/projDtlFromActivityList-jp.jpg)

操作者の詳細を確認するには、一覧に作成者をクリックすると、ユーザーの総合情報管理画面が表示されます。
![avatar](../images-jp/userGuide/analysis/activityListUserLink-jp.jpg)
![avatar](../images-jp/userGuide/analysis/userDtlFromActivityList-jp.jpg)