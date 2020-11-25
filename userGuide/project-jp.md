---
#プロジェクト管理
---

##1 プロジェクト管理画面を開きます

画面上の方の機能メニューに <u>プロジェクト</u>をクリックし、プロジェクト管理画面が表示されます。
![avatar](../images-jp/userGuide/project/projectMenu-jp.jpg)

プロジェクトは、私のプロジェクト、関連のプロジェクトと公開プロジェクトの3種に分けられます。
- 私のプロジェクト：ユーザー個人専用プロジェクト。
- 関連のプロジェクト：プロジェクトメンバーに当ユーザーが含まれるプロジェクト。
- 公開プロジェクト：ユーザー全員に公開されるプロジェクト。

一覧の一列目(プロジェクト)は、プロジェクト所有者とプロジェクトIDを繋げた文字列です。
![avatar](../images-jp/userGuide/project/projectListPrivate-jp.jpg)
![avatar](../images-jp/userGuide/project/projectListRelated-jp.jpg)
![avatar](../images-jp/userGuide/project/projectListPublic-jp.jpg)

###1.1 プロジェクト検索
プロジェクト件数が多い場合、一覧上の検索ボックスを利用して表示件数を縮められます。
マッチパターンは部分一致で、それに大文字小文字を区別しません。

下図通りに検索ボックスに検索文字を入力します。
![avatar](../images-jp/userGuide/project/projSelWord-jp.jpg)
検索ボタン（拡大鏡アイコン）又はEnterキーをクリックします。
![avatar](../images-jp/userGuide/project/projSelIcon-jp.jpg)
該当プロジェクトが検索されます。
![avatar](../images-jp/userGuide/project/projSelected-jp.jpg)

「備考」プロジェクト全件を表示するには、検索ボックスに入力した文字列を全て消してから、
検索ボタン（拡大鏡アイコン）又はEnterキーをクリックします。

###1.2 プロジェクト新規
プロジェクト一覧右上の<u>+新規</u>ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projNewBtn-jp.jpg)
プロジェクト新規画面が表示されます。
![avatar](../images-jp/userGuide/project/projNewInit-jp.jpg)
プロジェクトの各項目を入力し、<u>保存</u>ボタンをクリックします。
「公開」の項目の説明：公開をオンにしたらが公開プロジェクトとなり、オフにしたら個人専用プロジェクトとなります。
![avatar](../images-jp/userGuide/project/projNew-jp.jpg)
プロジェクト総合情報画面が表示されます。
![avatar](../images-jp/userGuide/project/projCreated-jp.jpg)
画面の上の方の機能メニューに<u>プロジェクト</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewToProjMenu-jp.jpg)
プロジェクト一覧画面に戻り、一覧に新規したプロジェクトが表示されます。
![avatar](../images-jp/userGuide/project/projList-jp.jpg)

###1.3 プロジェクト削除
プロジェクト一覧に消すプロジェクト前のチェックボックスをチェックオンします。
![avatar](../images-jp/userGuide/project/projListChkbox-jp.jpg)
プロジェクト一覧の上に選択した件数と<u>削除</u>が表示されます。
![avatar](../images-jp/userGuide/project/projListChkOn-jp.jpg)
削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projDelBtn-jp.jpg)
削除確認ダイアログボックスが表示され、OKボタンをクリックします(プロジェクト新規を取り消したい場合にキャンセルをクリックします)。
![avatar](../images-jp/userGuide/project/projListDelProjConfirm-jp.jpg)
プロジェクト一覧が再表示され、消したプロジェクトが一覧に無くなりました。
![avatar](../images-jp/userGuide/project/projListDeledProj-jp.jpg)

###1.4 プロジェクト総合情報管理
プロジェクト総合情報管理画面を開くには、両方法があります。
一つはプロジェクトを新規したら、プロジェクト総合情報管理画面に遷移されます(1.2プロジェクト新規を参照)。
もう一つはプロジェクト一覧にプロジェクト番号のリンクをクリックします。
![avatar](../images-jp/userGuide/project/projListProjNo-jp.jpg)
プロジェクト総合情報管理画面に概要、フロー、チケット、アクティビティ、メモ、設定と台帳の七つの子画面があります。
![avatar](../images-jp/userGuide/project/projView-jp.jpg)

####1.4.1 概要
当画面でプロジェクト基本情報編集とチケット情報確認が出来ます。

#####1.4.1.1 プロジェクト基本情報編集

画面の左下の<u>編集...</u>ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewEditBtn-jp.jpg)
プロジェクト編集画面が表示されます(画面項目説明は下記のプロジェクト編集画面各項目説明を参照)。
![avatar](../images-jp/userGuide/project/projViewEditInit-jp.jpg),
プロジェクト情報を直してから、<u>保存</u>ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewEdit-jp.jpg)
概要画面に戻り、プロジェクト情報が再表示されます。
![avatar](../images-jp/userGuide/project/projViewEdited-jp.jpg)

<u>プロジェクト編集画面各項目説明</u>
(1) 無効にする
&ensp;当項目をオンにすると，プロジェクトがプロジェクト一覧に無効状態となります。
![avatar](../images-jp/userGuide/project/projViewEditDisable-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewListDisable-jp.jpg)

#####1.4.1.2 チケット情報確認
概要画面の右側に日付セルで組み立てられたテーブルがあります。灰色セルはチケットはない日付で、
緑セルはチケットがある日付です。

(1) 日付セルのチケット情報を確認します
&ensp;マウスを確認する日付セルに移動します。
![avatar](../images-jp/userGuide/project/projViewOverViewDateMouseup-jp.jpg)
&ensp;当セルの日付とチケット件数が表示されます。
![avatar](../images-jp/userGuide/project/projViewOverViewDateTip-jp.jpg)

(2) 日付セルのチケット作成情報を確認します
&ensp;確認するセルをクリックします。
![avatar](../images-jp/userGuide/project/projViewOverViewDateClick-jp.jpg)
日付セルテーブルの下にチケット作成情報が表示されます。
![avatar](../images-jp/userGuide/project/projViewOverViewDateClicked-jp.jpg)

####1.4.2 フロー
プロジェクト総合情報管理画面、<u>フロー</u>タグをクリックし、フロー一覧画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowTag-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowList-jp.jpg)

#####1.4.2.1 フロー新規
フロー一覧画面で、一覧右上の<u>+新規</u>ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewNewFlowBtn-jp.jpg)
フロー新規画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewNewFlowInit-jp.jpg)
各項目を入力してから、保存ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewNewFlow-jp.jpg)
フロー総合情報管理画面に遷移します。画面の左側にフローの基本情報表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowDtlFromNew-jp.jpg)
画面の左上のプロジェクトのリンクをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowDtlProjLink-jp.jpg)
プロジェクト総合管理画面に戻り、<u>フロー</u>タグをクリックします。
![avatar](../images-jp/userGuide/project/projViewFromFlowDtl-jp.jpg)
フロー一覧画面が再表示され、新規したフローが一覧に表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowListFromFlowDtl-jp.jpg)

#####1.4.2.2 フロー編集
フローを編集するにはまずフロー総合情報管理画面を開きます。この画面を開くには、両方法があります
一つはフローを新規したら、自動的にこの画面に遷移されます(1.4.2.1フロー新規を参照)。
もう一つはフロー一覧で編集するフローをクリックすると、この画面に遷移されます。
![avatar](../images-jp/userGuide/project/projViewFlowListFlowNameLink-jp.jpg)
フロー総合情報管理画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowDtlFromFlowList-jp.jpg)
画面左側にフロー基本情報があります。基本情報の直下に編集ボタンがあり、このボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowDtlEditBtn-jp.jpg)
フロー編集画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditInit-jp.jpg)
各項目を直してから、保存ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEdit-jp.jpg)
フロー総合情報管理画面に戻り、画面の左側にフロー基本情報が再表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEdited-jp.jpg)

#####1.4.2.3 フローを無効にします
フロー編集画面に無効にするという項目があり、当項目を無効にしたら、フローの状態が無効となります。
![avatar](../images-jp/userGuide/project/projViewFlowDisable-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowDisableInFlowList-jp.jpg)

#####1.4.2.4 フローエディター
フローを作成されたら、このフローに暗黙的なテンプレートが付けられますが、具体的な要望によりフローテンプレートを直していいです。
フロー総合情報管理画面の左側に、フローエディターというボタンがあり、このボタンをクリックすると、フロー編集画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorLink-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorInit-jp.jpg)
フローエディターは四部分に分けられます。上の方が編集ツールバーで、左側がフロー基本チャート欄で、真ん中がフローチャート描画区域です。
左側が隠される設定区域で、チャートをダブルクリックしたら、或いはクリックしてから、設定ボタン(歯車)をクリックしたら、設定区域が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDtlSetArea-jp.jpg)

######1.4.2.4.1 フロー基本チャート
フローエディターの左側にフロー基本チャート欄があります。基本チャートに六種があります。
- 開始：作業の開始ノード。
- 処理：作業処理内容ノード。
- メーラー：メール送信ノード。
- 入力：作業に要る引数を入力するノード。
- 判断：条件判断してから、分岐処理をするノード。
- 終了：作業終了ノード。

![avatar](../images-jp/userGuide/project/projViewFlowEditorBasicChart-jp.jpg)

######1.4.2.4.2 フローエディターツールバー
フローエディターの上の方に、編集ツールバーがあります。下記は各ツールを説明します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorEditToolBar-jp.jpg)

(1)クラウドへ保存
マウスを一番目のツールに移動したら、クラウドへ保存というツールチップが表示されます。
このツールはフローチャートの編集を保存する機能です。フローチャートを直してから、このボタンをクリックすることにより保存できます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloud-jp.jpg)

(2)クラウドから取得
マウスを二番目のツールに移動したら、クラウドから取得というツールチップが表示されます。
このツールは、最近保存されたフローチャートに今エディターで表示されるフローチャートを切替えます。
このツールを利用したら、前回保存した時から今までの編集が無くなるので注意要です。
![avatar](../images-jp/userGuide/project/projViewFlowEditorRetrieveFromCloud-jp.jpg)

(3)UndoとRedo
UndoとRedoは、元に戻すとやり直しです。元に戻すは、編集を取消し、元に戻します。やり直しは取り消した編集を再度やり直します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarUndo-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarRedo-jp.jpg)

(4)CopyとPaste
CopyとPasteはコピーと貼り付けです。チャートを選択し、Copyをクリックしてから、Pasteをクリックすることにより、チャートを複製できます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarCopy-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarPaste-jp.jpg)

例えば、あるチャートをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelChart-jp.jpg)
このチャートが選択され、背景色が深くなり、それに枠線に接続丸が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelectedChart-jp.jpg)
Copyをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelChartCopy-jp.jpg)
Pasteをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelChartPaste-jp.jpg)
選択されたチャートが複製されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelChartPasted-jp.jpg)

(4) Delete
Deleteは削除です。あるチャートを選択してからDeleteをクリックしたら、チャートが削除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarDelete-jp.jpg)
下図の通りで、あるチャートをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelChartDelete-jp.jpg)
チャートが選択されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelectedDelChart-jp.jpg)
Deleteをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelChartDel-jp.jpg)
チャートが削除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelChartDeleted-jp.jpg)

(5)ズームインとズームアウト
ズームインはフローチャートを大きく表示できます。ズームアウトはフローチャートを小さく表示出来ます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarZoomIn-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarZoomOut-jp.jpg)
下図通りにズームインをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowZoomInBtn-jp.jpg)
フローチャートが大きくなります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorZoomedIn-jp.jpg)
フローチャートを小さくするには、ズームアウトをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowZoomOutBtn-jp.jpg)
フローチャートが小さくなります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorZoomedOut-jp.jpg)

(6)フィットマップ
フィットマップはページのサイズに合わせてフローチャートのサイズを調整します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarFitMap-jp.jpg)
下図通りに、フィットマップをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFitMapBtn-jp.jpg)
フローチャートのサイズがページのサイズに合わせて調整します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFitedMap-jp.jpg)

(7)ズームをリセット
ズームリセットはフローチャートのサイズを元のサイズに戻します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarActualSize-jp.jpg)
下図通りに、フローチャートがズームアウトされた状態で、ズームをリセットをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorActualSizeBtn-jp.jpg)
フローチャートのサイズが元の大きさに戻ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorActualSized-jp.jpg)

(8)全画面表示
全画面はフローチャートを全画面で表示します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarFullscreen-jp.jpg)
下図通りに、全画面をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFullscreenBtn-jp.jpg)
フローチャートが全画面で表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFulledscreen-jp.jpg)
全画面表示を終了するには、キーボードでEscキーをクリックし、或いは再度全画面ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorExitFullscreenBtn-jp.jpg)
全画面表示が解除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorExitedFullscreen-jp.jpg)

(9)試験実行
試験実行は仮のチケットを一時作成し、フローが正しく進められるかをテストします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorToolBarFlowTest-jp.jpg)
試験実行をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowTestBtn-jp.jpg)
仮のチケットが表示されます。一歩ずつチケットを進め、正しく進められるかを確認できます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorTestFlow-jp.jpg)
試験実行を終了するには、戻るボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowTestBack-jp.jpg)
フローエディターに戻ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowTestBacked-jp.jpg)

######1.4.2.4.3　フローチャート描画
フローチャート描画で、チャートの追加とチャートを線で繋げることを説明します。
注意するのは、描画が終わったら、クラウドへ保存をクリックすること。

(1)チャート追加
基本チャート欄で、追加するチャートにマウスを移動し、マウスが手の形となります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelDragChart-jp.jpg)
マウスの左ボタンを押したまま、フローチャート描画区域にドラッグしてから、マウスの左ボタンを離します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDragedChart-jp.jpg)
最後はクラウドへ保存をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloundDragChart-jp.jpg)

(2)チャートを線で繋げます
繋げ元のチャートをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelJoinBegin-jp.jpg)
繋げ元のチャートが選択され、背景色が深くなり、枠線に接続丸が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelectedJoinBegin-jp.jpg)
マウスを繋げ元の丸に移動し、繋げ元の丸の背景色が深くなり、マウスの形がクロスに成ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelectedJoinSrcPoint-jp.jpg)
マウスの左ボタンを押したまま、ドラッグします。ドラッグしているうちに全チャートの枠線の接続丸が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorJoinDragging-jp.jpg)
マウスを繋げ先の丸にドラッグしてから、マウスの左ボタンを離します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelectedJoinDestPoint-jp.jpg)
これで両チャートが線で繋がります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorChartJoined-jp.jpg)
最後はクラウドへ保存をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloundJoinChart-jp.jpg)

(3)両チャート間の接続線を削除します
接続線を消すには、マウスを消す線に移動し、線が青色と成ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelDelLine-jp.jpg)
線をクリックし、線が灰色に戻りますが、色が少し深くなり、線も少し太くなります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorClickDelLine-jp.jpg)
編集ツールバーの削除ボタンをクリックします。或いはキーボードで削除(Delete)キーをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorLineDelBtn-jp.jpg)
線が削除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorLineDeleted-jp.jpg)
最後はクラウドへ保存をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloundDelJoinLine-jp.jpg)

(4)接続線を直します
接続線の始終点を直すには、まずマウスを直す始終点に移動します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorMovePoint-jp.jpg)
マウスの形がクロスに成ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorMovePointJoinCross-jp.jpg)
マウスの左ボタンを押したままドラッグします。ドラッグしているうちに、全チャートの枠線の接続丸が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorMovePointDrag-jp.jpg)
新繋げ先の接続丸にドラッグしてから、マウスの左ボタンを離します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorMovePointDest-jp.jpg)
これで接続線が直されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorMovedJoinPoint-jp.jpg)
最後はクラウドへ保存をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloundModifyJoinLine-jp.jpg)

######1.4.2.4.4フローチャートの設定
フローチャートと接続線が描画出来てから、フロー全体と各ノードチャートを設定出来ます。
設定内容はラベル、作業内容、アクション、目標時間等です。

(1)フローチャート全体の設定
フローチャート描画区域で任意の空白の箇所をダブルクリックし、或いは空白の箇所をクリックしてから設定ボタン(歯車)をクリックしたら
設定画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowSetBtn-jp.jpg)
フローチャート全体設定画面は一般、変数とバージョンの三部分に分けられます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowSet-jp.jpg)

(1.1)一般設定
この設定で、フロー名前の編集、フローのエクスポートとインポートが出来ます。

·フローチャート名称編集
ここのフローチャート名称は論理名で、フロー編集画面とフロー一覧画面にあるフロー名が物理名(番号に当たる)です。
テキストボックスにフローチャート名称を入力します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowNameOld-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowNameNew-jp.jpg)
設定終了ボタン(×ボタン)をクリックし、或いはフローチャート描画区域で任意の空白の箇所をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowSetCloseBtn-jp.jpg)
設定画面が隠れます。クラウドへ保存をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveFlowNameToClound-jp.jpg)
設定が保存されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSavedFlowNameToClound-jp.jpg)

·フローチャートをエクスポートします
エクスポートで、フローチャートをZIPファイルでローカルにダウンロードできます。ですが、エクスポートするのは、
現在表示されるものではなく、クラウドに保存されるフローチャートです。

エクスポートボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorExportFlowBtn-jp.jpg)
Zipファイルがダウンロードされます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorExportedFlow-jp.jpg)
Zipファイルが自動的に開かれます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorExportedFlowOpenZip-jp.jpg)

·フローチャートをインポートします
フローチャートインポートで、ローカルに保存されたフローチャートをインポートできます。
ですが、インポートはクラウドにインポートしておきますので、インポートしても画面に表示されません。
画面に表示するには、インポートしてから、再度クラウドから取得をクリックします。

インポートボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorImportFlowBtn-jp.jpg)
ファイル選択ダイアログボックスが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelImportFlowFileDlg-jp.jpg)
ローカルに保存されたフローチャートファイルを選択してから、開くボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelectedImportFlowBySelFileDlg-jp.jpg)
クラウドから取得ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorRetrieveFromCloundImPortedFlow-jp.jpg)
インポートされたフローチャートがフローチャート描画区域に表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorShowImPortedFlow-jp.jpg)

(1.2)変数設定
変数設定は、フローに要るパラメータを入力します。設定後に入力のノードでユーザーの入力を受取ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmTag-jp.jpg)

·変数追加
追加ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmAddBtn-jp.jpg)
変数一覧の一行目に空白行が追加されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmAddInit-jp.jpg)
変数名と暗黙値を入力してから、OKボタンをクリックします(変数追加を放棄する場合に取消ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmAdd-jp.jpg)
変数追加が終わり、追加された変数が変数一覧に表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmAdded-jp.jpg)
クラウドへ保存ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloundAddParm-jp.jpg)

·変数削除
変数一覧で、消す変数行の操作欄にある削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmDelBtn-jp.jpg)
変数が削除され、一覧に無くなりました。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmDeleted-jp.jpg)
クラウドへ保存ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloundDelParm-jp.jpg)

·変数編集
直す変数行の操作欄にある編集ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmEditBtn-jp.jpg)
変数が編集可の状態となり、操作欄のボタンもOKと取消と成ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmEditable-jp.jpg)
変数名と値を直してから、OKボタンをクリックします(編集を放棄する場合に取消ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmEdit-jp.jpg)
編集が終わり、変数が編集不可の状態となり、操作欄のボタンも編集と削除と成ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParmEdited-jp.jpg)
クラウドへ保存ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloundEditParm-jp.jpg)

(1.3)バージョン
バージョン画面で、フローの編集履歴を表示されます。
·バージョン編集履歴
![avatar](../images-jp/userGuide/project/projViewFlowEditorFlowVersions-jp.jpg)

·改名と削除
?？ Bug

(2)開始ノードの設定
開始ノードは、フローの一番目のノードで、作業の開始とします。
開始ノードをダブルクリックします。或いは開始ノードをクリックしてから、設定(歯車)ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorStartNode-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorStartNodeSelected-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorStartNodeSetBtn-jp.jpg)
設定画面が表示され、設定が一般、作業内容、アクションと権限の四部分に分けられます。
- 一般：ノードのラベルと目標時間を設定します。
- 作業内容：ノードの作業内容を記述します。
- アクション：特定機能を実現するソースコードです。
- 権限：ノードの作業を他のユーザーまたはグループを渡します。

![avatar](../images-jp/userGuide/project/projViewFlowEditorStartNodeSetTag-jp.jpg)

(2.1)一般設定
一般設定は、ノードのラベル、目標時間とメモを設定します。
ノードが追加されたら、ラベルと目標時間に暗黙値がありますが、暗黙値を直していいです。
各項目を入力します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorStartNodeSetGeneral-jp.jpg)
設定閉めるボタンをクリックします。あるいはフローチャート描画区域の空白箇所をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorStartNodeSetGeneralCloseBtn-jp.jpg)
設定画面が隠れてから、クラウドへ保存ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSaveToCloundStartNodeSetGeneral-jp.jpg)
設定が保存されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSavedToCloundStartNodeSetGeneral-jp.jpg)

(2.2)作業内容
作業内容は、作業の内容を記述します。
作業内容エディターはリッチテキストエディターで、文字列を記述できる上に、文字列のフォーマットの設定、画像設定、テーブル設定とメディア設定も出来ます。
エディターの上部は文字列形式設定ツールバーです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentToolBarWordsFormat-jp.jpg)
ツール欄の右の方にあるもっと多く表示(Show more)ボタンをクリックしたら、画像挿入、ブロック引用、テーブル挿入、メディア挿入、元に戻すとやり直しの六ツールが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentToolBarShowMoreBtn-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentToolMore-jp.jpg)

(2.2.1)文字列の入力とフォーマット設定
まずテキストエディターに作業内容を記述します。あと設定ツールで文字列フォーマットを設定できます。
文字列フォーマット設定ツールバーに左から段落、太字、斜体、リンク、箇条書き、段落番号、インデントを増やす、インデントを減らす六ツールがあります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentFormatBar-jp.jpg)
·段落の設定
段落を設定する文字列を選択します。一行文字列の場合に、カーソルをその行に置くだけでいいです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelWordParagraph-jp.jpg)
設定ツールバーで段落をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParagraph-jp.jpg)
段落設定リストが表示され、中で設定するフォーマットをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorParagraphList-jp.jpg)
段落設定が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSetedWordParagraph-jp.jpg)

段落設定を解除するには、解除する文字列を選択します。一行文字列の場合に、カーソルをその行に置くだけでいいです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelWordDelParagraph-jp.jpg)
段落設定ツールをクリックし、段落設定リストが表示され、中から一番目のParagraphをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDelParagraph-jp.jpg)
文字列の段落設定が解除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDeletedWordParagraph-jp.jpg)

·太字の設定
太字を設定する文字列を選択します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelWordBold-jp.jpg)
設定ツールバーで太字ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorBold-jp.jpg)
設定が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSetedWordBold-jp.jpg)

太字設定を解除するには、解除する文字列を選択します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelWordDelBold-jp.jpg)
設定ツールバーで太字ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDelBold-jp.jpg)
太字設定が解除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDeletedWordBold-jp.jpg)

·斜体の設定
?? Bug32
斜体を設定する文字列を選択します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelWordItalic-jp.jpg)
設定ツールバーで斜体ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorItalic-jp.jpg)
設定が終わりです。
？？BUG 斜体になれない
![avatar](../images-jp/userGuide/project/projViewFlowEditorSetedWordItalic-jp.jpg)

斜体設定を解除するには、解除する文字列を選択します。
??bug32 日语时完全无效果
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelWordDelItalic-jp.jpg)
設定ツールバーで斜体ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDelItalic-jp.jpg)
斜体設定が解除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDeletedWordItalic-jp.jpg)

·リンク設定
文字列をリンクを挿入するには、まずリンクを挿入する文字列を選択します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorSelWordLink-jp.jpg)
設定ツールバーでリンクボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLink-jp.jpg)
リンクアドレス入力ダイアログボックスが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkDlg-jp.jpg)
リンクアドレスを入力します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkUrl-jp.jpg)
保存ボタンをクリックします(リンクアドレス入力を放棄する場合に取消×ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkDlgOkBtn-jp.jpg)
リンク挿入が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkNewed-jp.jpg)

文字列のリンクを直すには、リンクが追加された文字列をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkClick-jp.jpg)
リンクアドレスを編集するダイアログが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkEditDlg-jp.jpg)
編集ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkEditDlgEditBtn-jp.jpg)
リンクアドレスが編集可能状態となります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkEditDlgEditable-jp.jpg)
リンクアドレスを直します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkEdit-jp.jpg)
保存ボタンをクリックします(リンクアドレス編集を放棄する場合に取消×ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkEditDlgOkBtn-jp.jpg)
リンク編集が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkEdited-jp.jpg)

文字列のリンクを消すには、リンクが追加された文字列をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkDelClick-jp.jpg)
リンクアドレスを編集するダイアログが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkDelDlg-jp.jpg)
リンク削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkEditDlgDelBtn-jp.jpg)
文字列のリンクが削除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorWordsLinkDeleted-jp.jpg)

·箇条書き
？？bug33 无序列表和数字列表使用效果无差别
·段落番号
？？bug33 无序列表和数字列表使用效果无差别

·增加缩进
·减少缩进
？？bug34 无法使用

(2.2.2)画像の設定
·插入图片　画像挿入
画像を挿入する箇所にカーソルを置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentInsertImgCursor-jp.jpg)
ツールバーで画面挿入をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentInsertImgBtn-jp.jpg)
画像選択ダイアログが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSelImgDlg-jp.jpg)
画像を選択します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSelImg-jp.jpg)
画像選択ダイアログの開くボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSelImgDlgOpenBtn-jp.jpg)
画像が挿入されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentInsertedImg-jp.jpg)

·画像削除
画像を消すには、画像をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentClickDelImg-jp.jpg)
画像の周りに青い枠が表示されてから、キーボードで削除(Delete)キーをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSelectedDelImg-jp.jpg)
画像が削除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentDeletedImg-jp.jpg)

·画像の表示パターン
画面を挿入してから、表示パターンを設定できます。
表示パターンを設定する画像をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentClickImg-jp.jpg)
画像設定ツールバーが画像の上に表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgSetBar-jp.jpg)
画像設定ツールバーに、左から、全サイズ画像(これは暗黙表示パターン)、片側画像、(画像表示失敗時に)代わる文字列の三ツールがあります。
画像の直下に画像説明を設定するテキストボックスがあります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgFullSize-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgSide-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgAlternativeText-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgCaption-jp.jpg)

全サイズ画像を設定するには、画像をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgClickFullSize-jp.jpg)
画像設定ツールバーが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgSetBarFullSize-jp.jpg)
全サイズ画像をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgFullSizeBtn-jp.jpg)
画像が全サイズ画像で表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSetedImgFullSize-jp.jpg)

片側画像を設定するには、画像をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgClickSide-jp.jpg)
画像設定ツールバーが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgSetBarSide-jp.jpg)
片側画像をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgSideBtn-jp.jpg)
画像が片側画像で表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSetedImgSide-jp.jpg)

(画像表示失敗時に)代わる文字列を設定するには、画像をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgClickAlternativeText-jp.jpg)
画像設定ツールバーが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgSetBarAlternativeText-jp.jpg)
代わる文字列のボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgAlternativeTextBtn-jp.jpg)
代わる文字列入力ダイアログボックスが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgAlternativeTextDlg-jp.jpg)
代わる文字列を入力します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentInputImgAlternativeText-jp.jpg)
ダイアログボックスの保存ボタンをクリックします(入力を放棄する場合に×ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgAlternativeTextDlgOkBtn-jp.jpg)
(画像表示失敗時に)代わる文字列が設定されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgSetedAlternativeText-jp.jpg)

画像説明を設定するには、画像をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgClickCaption-jp.jpg)
画像の直下に説明を入力するテキストボックスが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgCaptionTextBox-jp.jpg)
画像説明を入力します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgEnterCaption-jp.jpg)
カーソルを画像説明入力テキストボックスから離し、画像説明の設定が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentImgEnteredCaption-jp.jpg)


(2.2.3)ブロック引用の設定
文字列行にブロック引用を設定するには、文字列行を選択します。一行文字列の場合に、カーソルをその行に置くだけでいいです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSelQuoteWords-jp.jpg)
ブロック引用ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentQuoteBtn-jp.jpg)
ブロック引用の設定が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSetedQuote-jp.jpg)

ブロック引用の設定を解除するには、解除する文字列を選択します。一行文字列の場合に、カーソルをその行に置くだけでいいです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSelDelQuoteWords-jp.jpg)
ブロック引用ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentDelQuoteBtn-jp.jpg)
ブロック引用が解除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentDeletedQuote-jp.jpg)

(2.2.4)テーブル設定
·テーブル挿入
テーブル挿入する箇所にカーソルを置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentInsTableCursor-jp.jpg)
テーブル挿入のボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentInsTableBtn-jp.jpg)
行列数セッターが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableRowColSetter-jp.jpg)
行列数セッターにマウスを右下のほうに移動することで行列数を選び、移動しているうちにセッターの直下に選択する行列数が表示されます。
期待の行列数に達した時にマウスの左ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSetRowCol-jp.jpg)
テーブルが挿入されます。挿入してからテーブルの編集と設定ができ、下記は説明します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentInsertedTable-jp.jpg)

·テーブル削除
マウスを消すテーブルに移動し、テーブルの周りに黄色枠が表示され、枠の左上に小さい四角があり、この小さい四角をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelBlock-jp.jpg)
テーブルの周りの枠が青くとなり、テーブルが選択された状態となります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSelectedDelTable-jp.jpg)
キーボードで削除キー(Delete)をクリックし、テーブルが削除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDeleted-jp.jpg)

·文字列編集
テーブル中で文字列編集につき、普通使うオフィスソフトと同じです。キーボードのTabキーと方向キー(↑↓→←)でカーソルを移動できます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableWordEdit-jp.jpg)

·列ヘッダー設定
任意一行で、列ヘッダーにする列の最後の一列にカーソルを置きます。下図のように、先頭の両列を列ヘッダーにすると、カーソルを二列目に置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableColHeaderCell-jp.jpg)
テーブルの上にテーブル設定ツールバーが表示され、列設定ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableColMenu-jp.jpg)
列設定メニューが表示され、中で列ヘッダー(Header column)のスイッチボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableHeaderColMenu-jp.jpg)
列ヘッダー設定が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSetedHeaderCol-jp.jpg)
カーソルをテーブルから離し、テーブル設定ツールバーが消え、列ヘッダー設定結果を確認します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSetedHeaderColNoMenu-jp.jpg)

·列ヘッダー解除
列ヘッダーを解除するには、解除する列の一列目にカーソルを置きます。
下図のように、先頭の三列が列ヘッダーで、二列目と三列目の列ヘッダーを解除するには、カーソルを二列目に置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelHeaderColCell-jp.jpg)
テーブル設定ツールバーで、列設定ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableColMenuDelColHeader-jp.jpg)
列設定メニューが表示され、中で列ヘッダー(Header column)のスイッチボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelHeaderColMenu-jp.jpg)
列ヘッダー解除が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDeletedHeaderCol-jp.jpg)
カーソルをテーブルから離し、テーブル設定ツールバーが消え、列ヘッダー解除結果を確認します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDeletedHeaderColNoMenu-jp.jpg)

·左側に列を挿入します
ある列の左側に一列を挿入するには、カーソルをその列に置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsLeftColCell-jp.jpg)
テーブル設定ツールバーで列設定ボタンをクリックし、左側に列挿入(Insert column left)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsLeftColMenu-jp.jpg)
列挿入が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsertedLeftCol-jp.jpg)

·右側に列を挿入します。
ある列の右側に一列を挿入するには、カーソルをその列に置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsRightColCell-jp.jpg)
テーブル設定ツールバーで列設定ボタンをクリックし、右側に列挿入(Insert column right)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsRightColMenu-jp.jpg)
列挿入が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsertedRightCol-jp.jpg)

·列削除
一列を消す場合に、カーソルを消す列に置くだけでいいです。連続な複数列を消すには、消す列の一列目をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelColBegin-jp.jpg)
キーボードでシフト(Shift)キーを押したまま、消す最後の列をクリックしてからシフト(Shift)キーを放します。
この時、消す列の背景色が青色と成ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelColEnd-jp.jpg)
列設定メニューで列削除(Delete column)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelColMenu-jp.jpg)
列が削除されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDeletedCol-jp.jpg)

·列選択
一列を選ぶ場合に、その列にカーソルを置くだけでいいです。連続な複数列を選ぶには、選ぶ列の一列目をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelColBegin-jp.jpg)
キーボードでシフト(Shift)キーを押したまま、選ぶ列の最後の列をクリックしてからシフト(Shift)キーを放します。
選ぶ列の背景色が青くなり、これらの列が選択済み状態となります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelColEnd-jp.jpg)
列設定メニューで列選択(Select column)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelColMenu-jp.jpg)
列が選択済み状態となり、後で列削除、列挿入等を続いて出来ます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelectedCol-jp.jpg)

·行ヘッダー設定
任意一列で、行ヘッダーにする行の最後の行にカーソルを置きます。
下図のように、先頭の両行を行ヘッダーにすると、カーソルを二行目に置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableRowHeaderCell-jp.jpg)
テーブルの直上にテーブル設定ツールバーが表示され、行設定ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableRowMenu-jp.jpg)
行設定メニューが表示され、中で行ヘッダー(Header row)のスイッチボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableHeaderRowMenu-jp.jpg)
行ヘッダー設定が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSetedHeaderRow-jp.jpg)
カーソルをテーブルから離し、テーブル設定ツールバーが消え、設定結果を確認できます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSetedHeaderRowNoMenu-jp.jpg)

·行ヘッダー解除
行ヘッダーを解除するには、任意の一列で、行ヘッダーを解除する行の一行目にカーソルを置きます。
下図のように、先頭の三行が行ヘッダーで、二行目と三行目の行ヘッダーを解除するには、二行目にカーソルを置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelHeaderRowCell-jp.jpg)
テーブル設定ツールバーで、行設定ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableRowMenuDelRowHeader-jp.jpg)
行設定メニューが表示され、中で行ヘッダー(Header row)のスイッチボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelHeaderRowMenu-jp.jpg)
行ヘッダー解除が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDeletedHeaderRow-jp.jpg)
カーソルをテーブルから離し、テーブル設定ツールバーが消え、ヘッダー解除結果を確認できます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDeletedHeaderRowNoMenu-jp.jpg)

·直上に行挿入
ある行の直上に一行を挿入するには、その行にカーソルを置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsAboveRowCell-jp.jpg)
行設定メニューで、直上に行挿入Insert row above)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsAboveRowMenu-jp.jpg)
行挿入が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsertedAboveRow-jp.jpg)

·直下に行挿入
ある行の直下に一行を挿入するには、その行にカーソルを置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsBelowRowCell-jp.jpg)
行設定メニューで、直下に行挿入をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsBelowRowMenu-jp.jpg)
行挿入が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableInsertedBelowRow-jp.jpg)

·行削除
一行を消す場合に、消す行にカーソルを置くだけでいいです。連続な複数列を消す場合に、消す行の一行列目にカーソルを置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelRowBegin-jp.jpg)
キーボードでシフト(Shift)キーを押したまま、消す行の最後の行をクリックしてから、シフト(Shift)キーを放します。
消す行の背景色が青色となり、これらの行が選択済み状態となります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelRowEnd-jp.jpg)
行設定メニューで、行削除(Delete row)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDelRowMenu-jp.jpg)
行削除が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableDeletedRow-jp.jpg)

·行選択
一行を選ぶ場合に、その行にカーソルを置くだけでいいです。連続な複数行を選ぶ場合に、選ぶ行の一行目にカーソルを置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelRowBegin-jp.jpg)
キーボードでシフト(Shift)キーを押したまま、選ぶ行の最後の行をクリックしてから、シフト(Shift)キーを放します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelRowEnd-jp.jpg)
行設定メニューで、行選択(Select row)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelRowMenu-jp.jpg)
行が選択済み状態となり、後で行の削除、挿入等を続いて出来ます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentTableSelectedRow-jp.jpg)

·選択範囲のセルを結合します
結合範囲の開始セルにカーソルを置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellBegin-jp.jpg)
キーボードでシフト(Shift)キーを押したまま、結合範囲の終了セルをクリックしてからシフト(Shift)キーを放します。選択済みのセルの背景色が青色と成ります。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellEnd-jp.jpg)
テーブル設定ツールでセル結合のボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellMenu-jp.jpg)
選択済みのセルが結合されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergedCell-jp.jpg)

·上のセルを結合します
あるセルを直上のセルと結合する場合に、カーソルを結合元のセルに置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeUpCellSrc-jp.jpg)
セル結合ツールの右側にあるドロップダウン矢印をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellUpDropdown-jp.jpg)
セル結合分割メニューリストが表示され、上のセル結合(Merge cell up)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellUpMenu-jp.jpg)
上のセルが結合されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergedCellUp-jp.jpg)

·右のセルを結合します
あるセルを右側のセルと結合する場合に、カーソルを結合元のセルに置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeRightCellSrc-jp.jpg)
セル結合ツールの右側にあるドロップダウン矢印をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellRightDropdown-jp.jpg)
セル結合分割メニューリストが表示され、右のセル結合(Merge cell right)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellRightMenu-jp.jpg)
右側のセルが結合されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergedCellRight-jp.jpg)

·下のセルを結合します
あるセルを直下のセルと結合する場合に、カーソルを結合元のセルに置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeDownCellSrc-jp.jpg)
セル結合ツールの右側にあるドロップダウン矢印をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellDownDropdown-jp.jpg)
セル結合分割メニューリストが表示され、下のセル結合(Merge cell down)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellDownMenu-jp.jpg)
下のセルが結合されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergedCellDown-jp.jpg)

·左のセルを結合します
あるセルを右側のセルを結合する場合に、カーソルを結合元のセルに置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeLeftCellSrc-jp.jpg)
セル結合ツールの右側にあるドロップダウン矢印をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellLeftDropdown-jp.jpg)
セル結合分割メニューリストが表示され、左のセル結合(Merge cell left)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergeCellLeftMenu-jp.jpg)
左のセルが結合されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentMergedCellLeft-jp.jpg)

·セルを縦に分割します
あるセルを縦に分割する場合に、カーソルを分割元のセルに置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSplitCellVerSrc-jp.jpg)
セル結合ツールの右側にあるドロップダウン矢印をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSplitCellVerDropdown-jp.jpg)
セル結合分割メニューリストが表示され、セル縦分割(Split cell vertically)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSplitCellVerMenu-jp.jpg)
セルが左右の両セルに分割されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSplitedCellVer-jp.jpg)

·セルを横に分割します
あるセルを横に分割する場合に、カーソルを分割元のセルに置きます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSplitCellHorSrc-jp.jpg)
セル結合ツールの右側にあるドロップダウン矢印をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSplitCellHorDropdown-jp.jpg)
セル結合分割メニューリストが表示され、セル横分割(Split cell horizontally)をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSplitCellHorMenu-jp.jpg)
セルが上下の両セルに分割されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentSplitedCellHor-jp.jpg)

(2.2.5)マルチメディア
?? bug40 URL路径：this media URL is not supported.

(2.2.6)元に戻す(Undo)とやり直し(Redo)
UndoとRedoは、元に戻すとやり直しです。元に戻すは、編集を取消して、元に戻します。やり直しは取り消した編集を再度やり直します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentUndoBtn-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorContentRedoBtn-jp.jpg)

(2.3)アクションの設定
アクションは、幾つかの機能を実現できるコードをここに書き、後でチケットでアクションのボタンをクリックすることでアクションの機能を実行できます。
例えば、指定アドレスのウェブサイトを開き、指定データベースからデータを読み込んで、指定パスのファイルを読み込む等です。
これで、複雑な作業を、人間に代わり、ソースコードで自動的に実行でき、効率を明らかに向上できます。

ラベルとコードの設定
ラベルは、チケットにアクションを実行するボタン名です。アクションは機能を実現するソースコードです。
下図通りにラベルとコードを設定します。コードの機能はページに簡単な文字列(Hello World)を出力します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorActionSet-jp.jpg)
これで、チケットにアクションボタンが表示され、ボタン名がアクション設定で設定されたラベルです。
![avatar](../images-jp/userGuide/project/projViewFlowTicketActionBtn-jp.jpg)
このボタンをクリックしたら、コードの機能を実行できます。
![avatar](../images-jp/userGuide/project/projViewFlowTicketActionRunning-jp.jpg)

(2.4)権限
?? bug28 某节点权限加入其它用户后，工作流到达其节点后，其它用户操作出错

(3)入力ノードの設定
入力ノードは、ユーザーから入力したパラメータを受取るノードです。入力パラメータはフロー全体設定で設定した変数です。
入力ノードの設定は、一般、作業内容、入力項目と権限の四部分に分けられます。
一般、作業内容と権限は開始ノードと同じで、開始ノード設定の説明を参照していいです。下記は入力項目だけを説明します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorInputNode-jp.jpg)

(3.1)入力項目
入力項目タグ画面にドロップダウンリストボックスがあり、これをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorInputDropDown-jp.jpg)
リストが表示され、リストの要素ががフロー全体設定で設定した変数で、中にこのノードで受取る変数を選択します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorInputDropDownList-jp.jpg)
入力項目が選択されました。
![avatar](../images-jp/userGuide/project/projViewFlowEditorInputSelectedItemInDropdown-jp.jpg)
設定が終わった後にクラウドに保存をクリックします。後チケットでこのノードに達した時に、入力テキストボックスが表示され、
ユーザーがパラメータを入力してから、直下にある保存ボタンをクリックすると入力パラメータが保存されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorInputNodeInput-jp.jpg)

(4)処理ノードの設定
処理ノードは作業の処理内容を記述するノードで、設定は開始ノードと同じで、開始ノード設定の説明を参照していいです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorProcessNode-jp.jpg)

(5)メーラーノードの設定
メーラーノードでは、作業進捗をチケット関係者にメールで知らせます。
メーラーノードの設定は、一般、作業内容、メーラーと権限の四部分に分けられます。一般、作業内容と権限が開始ノードと同じで、
開始ノード設定の説明を参照していいです。下記はメーラーの部分だけを説明します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorMailNode-jp.jpg)

(5.1)メーラー
メーラー設定は、普通で使う電子メールと同じで、宛先、CCBCCによく使う連絡先を設定しておいていいです。
件名と本文にもテンプレート内容を設定しておいていいです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorMailTag-jp.jpg)
ここで予め設定した内容は、チケットで暗黙値として表示されますが、作業実況により直していい、メーラー各項目内容を確認してから、
ノードの左下の送信をクリックしたら、メールが送信されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorMailInTicket-jp.jpg)

(6)判断ノードの設定
判断ノードでは、ある条件を判断してから、分岐処理をします。
判断ノードの設定は、一般、作業内容、アクション、判断と権限の五部分に分けられます。中で一般、作業内容、アクションと権限は
開始ノードと同じで、開始ノードの説明を参照していいです。下記は判断の部分だけを説明します。
![avatar](../images-jp/userGuide/project/projViewFlowEditorDecisionNode-jp.jpg)

(6.1)判断
?? 判断里的下拉列表项目是工作流参数，有何用？怎么用？

(6)終了ノードの設定
終了ノードは、作業の終了して、作業の最後のノードです。
終了ノードの設定は、一般、作業内容、アクションと権限の四部分に分けられます。開始ノードと同じで、開始ノードの設定を参照していいです。
![avatar](../images-jp/userGuide/project/projViewFlowEditorEndNode-jp.jpg)

(7)接続線の設定
ノードを繋げる線につき、接続線のラベルと形を設定できます。
設定する接続線をダブルクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowEditorLine-jp.jpg)
接続線の設定画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorLineSet-jp.jpg)

ラベルは、線の真ん中に表示するラベルを設定します。形は接続線の形を設定します。形に三種があります：
- Smooth：曲線
- Polyline：折れ線
- Polyline Round：角丸折れ線

![avatar](../images-jp/userGuide/project/projViewFlowEditorLineShapes-jp.jpg)

(7.1)ラベル
ラベルテキストボックスにラベル入力してから、キーボードでリタ—ン(Enter)キーをクリックすると、線の真ん中に表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowEditorLineSetedLabel-jp.jpg)

(7.2)線の形
下の三図は、曲線、折れ線と角丸折れ線の表示結果です。
![avatar](../images-jp/userGuide/project/projViewFlowEditorLineSmooth-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorLinePolyline-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewFlowEditorLinePolylineRound-jp.jpg)

#####1.4.2.5 フロー削除
フロー一覧画面で、フロー一覧から消すフロー前のチェックボックスをチェックオンします。
![avatar](../images-jp/userGuide/project/projViewFlowListChkbox-jp.jpg)
一覧の上に選択した件数と削除ボタンが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowListChkOn-jp.jpg)
削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowDelBtn-jp.jpg)
削除確認ダイアログボックスが表示され、OKボタンをクリックします(削除を放棄する場合にキャンセルボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowDelConfirm-jp.jpg)
消されたフローが一覧に無くなります。
![avatar](../images-jp/userGuide/project/projViewFlowListDeled-jp.jpg)

#####1.4.2.6 チケット新規
1.4.3.1のチケット新規を参照となります。

#####1.4.2.7 転送
転送はフローをほかのプロジェクトに転送します。転送に両種類があり、一つは移動で、もう一つは複製です。
&ensp;移動：フローとフローのチケットをほかのプロジェクトに移します。
&ensp;複製：フローコピーし、ほかのプロジェクトに複製します(チケットは複製しません)。

######1.4.2.7.1 移動
フロー総合情報管理画面で、左側の一番下にある転送ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowTransferBtn-jp.jpg)
転送先のプロジェクトダイアログボックスが表示され、移動先の暗黙値が現在所属先のプロジェクトです。
![avatar](../images-jp/userGuide/project/projViewFlowTransferDlg-jp.jpg)
移動ラジオをチェックオンします。
![avatar](../images-jp/userGuide/project/projViewFlowTransferDlgMoveChkBox-jp.jpg)
移動先のプロジェクトを入力します。入力しているうちに入力文字列とプロジェクト番号が部分一致したプロジェクトがリストアップし、
中に選択していいです。
![avatar](../images-jp/userGuide/project/projViewFlowTransferDlgMoveDest-jp.jpg)
OKボタンをクリックします(移動を放棄する場合に、キャンセルボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowTransferDlgOkBtn-jp.jpg)
移動が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowTransferMoved-jp.jpg)
移動元のプロジェクトのフロー一覧に、移動されたフローが無くなります。
![avatar](../images-jp/userGuide/project/projViewFlowTransferMovedNotInSrcProj-jp.jpg)
移動先のプロジェクトのフロー一覧に、移動されたフローが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowTransferMovedInDestProj-jp.jpg)
このフローのチケットも一緒に移動されます。
![avatar](../images-jp/userGuide/project/projViewFlowTransferMovedTicketInDestProj-jp.jpg)

######1.4.2.7.2 複製
複製はフローだけをコピーします。チケットは複製しません。

フロー総合情報管理画面で、左側の一番下にある転送ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowTransferCopyBtn-jp.jpg)
転送先のプロジェクトダイアログボックスが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowTransferCopyDlg-jp.jpg)
複製ラジオをチェックオンします。
移動先のプロジェクトを入力します。入力しているうちに入力文字列とプロジェクト番号が部分一致したプロジェクトがリストアップし、
中に選択していいです。
![avatar](../images-jp/userGuide/project/projViewFlowTransferDlgCopyDest-jp.jpg)
OKボタンをクリックします(移動を放棄する場合に、キャンセルボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowTransferCopyDlgOkBtn-jp.jpg)
複製が終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowTransferCopyed-jp.jpg)
移動元のプロジェクトのフロー一覧に複製フローが存在するままです。
![avatar](../images-jp/userGuide/project/projViewFlowTransferCopyedExistInSrcProj-jp.jpg)
移動元のプロジェクトのチケット一覧に複製フローのチケットが存在するままです。
![avatar](../images-jp/userGuide/project/projViewFlowTransferCopyedTicketInSrcProj-jp.jpg)
遷移先のプロジェクトのフロー一覧に複製フローが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowTransferCopyedInDestProj-jp.jpg)
ただしチケットが複製されません。
![avatar](../images-jp/userGuide/project/projViewFlowTransferCopyedTicketInDestProj-jp.jpg)

#####1.4.2.8 フロー総合情報管理
フロー総合情報管理画面は、下記のタグ子画面があります：
- 概要：チケット概要情報を確認します。
- 分析：各ノードの期待時間と実にかかった時間を表示します。
- チケット：このフローのチケット一覧です。
- トリガ-：？？

######1.4.2.8.1 概要
概要タグ画面に日付セルで組まれたテーブルがあり、灰色セルはチケットがない日付で、緑セルはチケットがある日付です。

(1)ある日のチケット件数を確認します
チケット件数を確認する日付セルにマウスを移動します。
![avatar](../images-jp/userGuide/project/projViewFlowOverViewDateMouseup-jp.jpg)
当セルの日付とチケット件数が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowOverViewDateTip-jp.jpg)

(2)ある日のチケット作成情報を確認します
![avatar](../images-jp/userGuide/project/projViewFlowOverViewDateClick-jp.jpg)
日付セルテーブルの下に当日付のチケットの作成情報が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowOverViewDateClicked-jp.jpg)

######1.4.2.8.2 分析
フロー総合情報管理画面で、分析のタグをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowAnalysisTag-jp.jpg)
分析タグ画面が表示され、この画面は横柱で各ノードの期待時間と実にかかった時間(単位が秒)を表示します。
縦軸はフローの各ノードで、横軸は各ノードの期待時間と実にかかった時間(単位が秒)です。
![avatar](../images-jp/userGuide/project/projViewFlowAnalysisTagWind-jp.jpg)
マウスをあるノードの横柱に移動し、このノードの期待時間と実にかかった時間が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowAnalysisMouseUp-jp.jpg)

######1.4.2.8.3 チケット
フロー総合情報管理画面で、チケットタグをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowTicketTag-jp.jpg)
このフローのチケット一覧画面が表示されます。この画面で、各チケット経過時間を確認でき、或いはチケットIDをクリックすることで
チケット詳細画面を表示します
![avatar](../images-jp/userGuide/project/projViewFlowTicketList-jp.jpg)

(1)チケットIDをクリックすることでチケット詳細画面を表示します
チケット一覧で、確認するチケットIDをクリックし、チケット詳細画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowTicketIdInList-jp.jpg)
チケット詳細画面で、チケット詳細情報を確認でき、或いはチケットを進められます。
![avatar](../images-jp/userGuide/project/projViewTicketDtlFromFlowView-jp.jpg)

(2)チケット経過時間
チケット一覧に目標時間/経過時間という列があり、時間が横柱で表示されます。マウスを横柱に移動すると、
このチケットの経過時間が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowTicketTakeupTime-jp.jpg)

(3)チケット削除
チケット一覧に、消すチケット前のチェックボックスをチェックオンします。
![avatar](../images-jp/userGuide/project/projViewFlowTicketListChkbox-jp.jpg)
チケット一覧の上に選択した件数を削除ボタンが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowTicketListChkOn-jp.jpg)
削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowTicketDelBtn-jp.jpg)
削除確認ダイアログが表示され、OKボタンをクリックします(削除を放棄する場合にキャンセルボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewFlowTicketDelConfirm-jp.jpg)
消されたチケットがチケット一覧に無くなります。
![avatar](../images-jp/userGuide/project/projViewFlowTicketListDeled-jp.jpg)

####1.4.3 チケット
プロジェクト総合情報管理画面で、<u>チケット</u>をクリックし、チケット一覧画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewTicketTag-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketList-jp.jpg)

#####1.4.3.1 チケット新規
チケットを新規するにはまずフロー一覧画面に入り、フロー一覧から使うフローのフロー名称をクリックします。
![avatar](../images-jp/userGuide/project/projViewSelNewTicketFlwTmpl-jp.jpg)
フロー総合情報管理画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowDtlForNewTicket-jp.jpg)
画面の左下の<u>チケット作成</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewNewTicketBtn-jp.jpg)
使うフローに入力パラメータがある場合にパラメータ入力ダイアログボックスが表示され、それにパラメータに暗黙値があります。
使うフローに入力パラメータがない場合にパラメータ入力ダイアログボックスが表示されません。
![avatar](../images-jp/userGuide/project/projViewNewTicketParmDlg-jp.jpg)
パラメータの暗黙値を直すには編集ボタンをクリックします（暗黙値を直さない場合に直にOKボタンをクリックします）。
![avatar](../images-jp/userGuide/project/projViewNewTicketParmDlgEditBtn-jp.jpg)
パラメータが編集可能となり、操作欄のボタンもOKと取消の両ボタンとなります。
![avatar](../images-jp/userGuide/project/projViewNewTicketParmEditStat-jp.jpg)
パラメータを直してから、操作欄のOKボタンをクリックします（編集を放棄したい場合に取消をクリックします）。
![avatar](../images-jp/userGuide/project/projViewNewTicketParmEdit-jp.jpg)
パラメータが保存され、編集不可となり、操作欄のボタンも編集ボタンと成ります。
![avatar](../images-jp/userGuide/project/projViewNewTicketParmEditSaved-jp.jpg)
ダイアログボックスのOKボタンをクリックします（チケット新規を放棄したい場合にキャンセルをクリックします）。
![avatar](../images-jp/userGuide/project/projViewNewTicketParmDlgOk-jp.jpg)
チケットが作成され、チケット記入画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewTicketNewed-jp.jpg)

#####1.4.3.2 チケット記入
チケットが作成されてから、使うフローを参照し、実際の作業進捗によりをチケットに一歩一歩と記入していいです。
チケット画面は作業詳細とフロー図の両部分に分けられます。
![avatar](../images-jp/userGuide/project/projViewTicketWorkDtl-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketDiagram-jp.jpg)

(1)チケット名称
チケットが作成されたら、チケット名称に暗黙値がありますが、編集していいです。
![avatar](../images-jp/userGuide/project/projViewTicketNo-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewEditTicketNo-jp.jpg)
(2)チケット経過時間
画面の右上にある経過時間は、チケットが作成されてから今までの経過時間です。
これでチケットの経過時間がフローの全体処理時間を超えたかどうかを評価できます。
![avatar](../images-jp/userGuide/project/projViewTicketElapsedTime-jp.jpg)
(3)ある段階の経過時間
ある段階の経過時間は段階名称の直下に表示され、両部分に分けられます。左は文字列で経過時間を表示され、
右は横柱で時間を表示されます。マウスを横柱に移動すると目標時間と実際の経過時間が表示されます。
もし目標時間を超えると横柱は赤色となり、逆は青色となります。
![avatar](../images-jp/userGuide/project/projViewTicketStepTime-jp.jpg)
(4)チケット記入
ある段階が完了したら、<u>次へ</u>をクリックすると次の段階に入ります。
下図のチケットを例としてチケットの記入を説明します。
一段階目は開始です。ここで入力パラメータが表示されるだけです。<u>次へ</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketStart-jp.jpg)
二段階目(処理日付入力)に入ります。ここでパラメータを編集してもいいです。編集してから保存ボタンをクリックします。
後<u>次へ</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketInput-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketEditInput-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketInputNextBtn-jp.jpg)
三段階目(作業対応)に入ります。作業が終わり次第に<u>次へ</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketProcess-jp.jpg)
四段階目目(責任者への報告)に入ります。宛先からメール内容まで全部編集していいです。メールの各項目を決めったら送信をクリックします。
送信が終わったら、<u>次へ</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketReport-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketReportEMail-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketReportNextBtn-jp.jpg)
五段階目目(正しく終わったか)。正しく終わったと評価したら、Yesラジオをクリックします。<u>次へ</u>ボタンが活性となり、
当ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketIsEnd-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketIsEndNextBtn-jp.jpg)
最後段階(完了)に入ります。閉じるボタンをクリックします。これで当チケットが終わります。
![avatar](../images-jp/userGuide/project/projViewTicketEnd-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketEndCloseBtn-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketClosed-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewTicketClosedOkStatus-jp.jpg)

#####1.4.3.3 チケットの取消
対応中のチケットを取り消していいです。チケット記入画面で、右上の取消ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketCancelBtn-jp.jpg)
取消理由ドロップダウンリストが表示され、中に取消理由をクリックして選択します。
![avatar](../images-jp/userGuide/project/projViewTicketCancelReason-jp.jpg)
チケットが取消され、状態がキャンセルとなります。当チケットが廃棄されました。
![avatar](../images-jp/userGuide/project/projViewTicketCanceled-jp.jpg)
チケット一覧に当チケットもキャンセル状態と成りました。
![avatar](../images-jp/userGuide/project/projViewTicketCanceledInList-jp.jpg)

#####1.4.3.4 チケットの一時停止と再開
対応中のチケットを、一時停止していいです。画面の右上の一時停止ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketPauseBtn-jp.jpg)
チケットが一時停止の状態となり、一時停止ボタンが再開ボタンとなり、チケットの下の方に一時停止のログが表示されます。
![avatar](../images-jp/userGuide/project/projViewTicketPaused-jp.jpg)
チケット一覧に一時停止のチケットが一時停止の状態と成りました。
![avatar](../images-jp/userGuide/project/projViewTicketPausedInList-jp.jpg)
一時停止したチケットを再開するにはチケット一覧に再開するチケットのIDをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketListTicketNo-jp.jpg)
チケット記入画面が表示され、画面右上の再開ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketReopenBtn-jp.jpg)
チケットが再開され、再開ボタンが一時停止ボタンとなり、画面の下の方に再開のログが表示されます。
![avatar](../images-jp/userGuide/project/projViewTicketReopened-jp.jpg)

#####1.4.3.5 チケット記入又はチケット詳細確認
チケット記入又はチケット確認するにはチケット一覧にチケットIDをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketListTicketID-jp.jpg)
チケット記入画面が表示されます。チケットを記入していいです。
![avatar](../images-jp/userGuide/project/projViewTicketFillIn-jp.jpg)

#####1.4.3.6 チケットでノードにコメントを追加します
対応中又は終了のチケットで、各ノードにコメントを追加出来ます。
注意するのは一ノードに複数のコメントを追加でき、完了ノードにもコメントを追加できます。

ノードにコメントを追加するには、まずノードの右上の<u>...</u>メニューをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketNodeMenuAddComment-jp.jpg)
メニューリストが表示され、中からコメントをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketNodeCommentMenu-jp.jpg)
ノードの下の方にテキストボックスとコメント追加ボタンが表示されます。
![avatar](../images-jp/userGuide/project/projViewTicketNodeAddCommentInputBox-jp.jpg)
コメントを入力してから、コメント追加ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketNodeInputComment-jp.jpg)
追加したコメントがノードの下の方に表示されます。
![avatar](../images-jp/userGuide/project/projViewTicketNodeSavedComment-jp.jpg)

#####1.4.3.7 指定ノードからチケットを再開します
一時停止のチケットを再開することと異なり、ここの再開は対応中と終了のチケットを再開します。
対応中のチケットの再開と終了のチケットの再開とで、操作的に少し違いがありますので、下記で別別に説明します。

######1.4.3.7.1 対応中のチケットを再開します
下図の通りで、対応中のチケットの進捗は、四ノード目の関係者に送信までに達します。
![avatar](../images-jp/userGuide/project/projViewTicketReOpenDoing-jp.jpg)
もし二ノード目の処理日入力から再開とすれば、このノードの右上の<u>...</u>メニューをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketReOpenNodeMenu-jp.jpg)
メニューリストが表示され、中にここから再開をクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketReOpenNodeMenuReStart-jp.jpg)
チケットの一番下に、再開の開始ノードが追加され、この新ノードから、チケットが再開されます。
![avatar](../images-jp/userGuide/project/projViewTicketAddedReOpenNode-jp.jpg)

######1.4.3.7.2 終了のチケットを再開します
終了のチケットは、各ノードの<u>...</u>のメニューリストに、ここから再開が表示されません。
![avatar](../images-jp/userGuide/project/projViewTicketReOpenDoneStatus-jp.jpg)
終了のチケット場合に、まず画面の右上の復活ボタンをクリックします
![avatar](../images-jp/userGuide/project/projViewTicketResurrectBtn-jp.jpg)
チケット状態は対応中となり、各ノードの<u>...</u>のメニューリストにここから再開が再表示されます。
![avatar](../images-jp/userGuide/project/projViewTicketReOpenDoneResurrectMenu-jp.jpg)
後の操作は1.4.3.7.1-対応中のチケットの再開と同じで、再開の開始ノードで<u>...</u>のメニューリストから再開をクリックすると再開されます。

#####1.4.3.8 フロー図で進捗を確認します
チケット画面中のフロー図で、これまでの作業進捗を表示できます。
灰色の段階は未着手で、以外は終わり又は着手です。
![avatar](../images-jp/userGuide/project/projViewTicketDiagramStatus-jp.jpg)

#####1.4.3.9 進捗リスト
作業詳細とフロー図の右の方に、これまで終わった又は開始した段階のリストがあります。これで進捗が確認出来ます。
![avatar](../images-jp/userGuide/project/projViewTicketDoneStepList-jp.jpg)

#####1.4.3.10 チケット削除
消すチケット前のチェックボックスをチェックオンします。
![avatar](../images-jp/userGuide/project/projViewTicketListChkbox-jp.jpg)
チケット一覧の上に選択した件数を削除ボタンが表示されます。
![avatar](../images-jp/userGuide/project/projViewTicketListChkOn-jp.jpg)
削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewTicketDelBtn-jp.jpg)
削除確認ダイアログボックスが表示され、OKボタンをクリックします（削除を放棄したい場合にキャンセルをクリックします）。
![avatar](../images-jp/userGuide/project/projViewTicketDelConfirm-jp.jpg)
消されたチケットは一覧に無くなりました。
![avatar](../images-jp/userGuide/project/projViewTicketListDeled-jp.jpg)

####1.4.4 アクティビティ
プロジェクト総合情報画面で<u>アクティビティ</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewActivityTag-jp.jpg)
アクティビティ一覧画面が表示されます。この一覧で当プロジェクトの操作履歴が確認できます。
![avatar](../images-jp/userGuide/project/projViewActivityList-jp.jpg)

####1.4.5 メモ
プロジェクト総合情報画面で<u>メモ</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewMemoTag-jp.jpg)
メモ一覧画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewMemoList-jp.jpg)

#####1.4.5.1 メモ新規
メモ一覧上の<u>+新規</u> ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewMemoNewBtn-jp.jpg)
メモ新規画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewMemoNewInit-jp.jpg)
画面で各項目を入力してから、<u>保存</u> ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewMemoNew-jp.jpg)
メモ詳細情報画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewMemoNewed-jp.jpg)

メモ一覧画面に戻すにはプロジェクトのリンクをクリックします。
![avatar](../images-jp/userGuide/project/projViewMemoDtlProjLink-jp.jpg)
プロジェクト総合情報管理画面に戻ります。
![avatar](../images-jp/userGuide/project/projViewMemoDtlToProjDtl-jp.jpg)
メモタグをクリックします。
![avatar](../images-jp/userGuide/project/projViewMemoTagEdited-jp.jpg)
メモ一覧画面が表示され、新規したメモが一覧に表示されます。
![avatar](../images-jp/userGuide/project/projViewMemoNewedBackList-jp.jpg)

#####1.4.5.2 メモ編集
メモを編集するにはまずメモ詳細情報画面を開きます。
メモ詳細情報画面を開くには両方法があります。
一つがメモを新規してから、メモ詳細情報画面が表示されます(1.4.5.1メモ新規)。
もう一つはメモ一覧に直すメモのタイトルのリンクをクリックします。

![avatar](../images-jp/userGuide/project/projViewMemoListTitleLink-jp.jpg)
メモ詳細情報画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewMemoDetail-jp.jpg)
<u>編集...</u>ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewMemoDetailEditBtn-jp.jpg)
メモ編集画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewMemoEditInit-jp.jpg)
メモ情報を直してから、<u>保存</u>ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewMemoEdit-jp.jpg)
メモ詳細情報画面に戻り、メモ情報が再表示されます。
![avatar](../images-jp/userGuide/project/projViewMemoEdited-jp.jpg)

#####1.4.5.3 メモ削除
メモ一覧に消すメモ前のチェックボックスをチェックオンします。
![avatar](../images-jp/userGuide/project/projViewMemoListChkbox-jp.jpg)
メモ一覧の上に選択した件数と削除ボタンが表示されます。
![avatar](../images-jp/userGuide/project/projViewMemoListChkOn-jp.jpg)
削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewMemoDelBtn-jp.jpg)
削除確認ダイアログボックスが表示され、OKボタンをクリックします(削除を取り消したい場合にキャンセルをクリックします)。
![avatar](../images-jp/userGuide/project/projViewMemoDelConfirm-jp.jpg)
メモ一覧が再表示され、消したメモが一覧に無くなりました。
![avatar](../images-jp/userGuide/project/projViewMemoListDeled-jp.jpg)

####1.4.6 設定
プロジェクト総合情報管理画面で、<u>設定</u>タグをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetTag-jp.jpg)
設定画面が表示されます。
当画面で、プロジェクトのID、所有権、公開/非公開、メンバー、グループ、フローラベル、チケットラベルを設定できます。
![avatar](../images-jp/userGuide/project/projViewSetWind-jp.jpg)

#####1.4.6.1 一般設定
一般設定で、プロジェクトID、所有権、公開/非公開、メンバー、グループを設定でき、プロジェクト削除も出来ます。
![avatar](../images-jp/userGuide/project/projViewSetCommon-jp.jpg)

######1.4.6.1.1 プロジェクトID変更
初期に改名ボタンが非活性です。
![avatar](../images-jp/userGuide/project/projViewSetRenameInit-jp.jpg)
プロジェクトIDを直してから、改名ボタンが活性となり、当ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetRename-jp.jpg)

######1.4.6.1.2 プロジェクト所有権を他人に譲る
<u>プロジェクト所有権を他人に譲る</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewSetTransferOwnerMenu-jp.jpg)
所有権譲渡設定区域が表示されます。初期に転送ボタンが非活性です。
![avatar](../images-jp/userGuide/project/projViewSetTransferOwnerInit-jp.jpg)
譲渡先のユーザーを入力します。入力している時に、入力した文字とマッチしたユーザーがリストアップしますので、
リストから選択していいです。
![avatar](../images-jp/userGuide/project/projViewSetTransferOwnerEdit-jp.jpg)
譲渡先のユーザーを入力したら、転送ボタンが活性となり、当ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetTransferOwnerNewUser-jp.jpg)
譲渡が完了です。
![avatar](../images-jp/userGuide/project/projViewSetTransferredOwner-jp.jpg)

######1.4.6.1.3 公開・非公開の切替
<u>公開・非公開の切替</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewSetTransferPublicMenu-jp.jpg)
公開・非公開の設定区域が表示されます。初期に切替ボタンが非活性です。
![avatar](../images-jp/userGuide/project/projViewSetTransferPublicInit-jp.jpg)
スイッチボタンをクリックすることで公開・非公開を切り替えます。
![avatar](../images-jp/userGuide/project/projViewSetTransferPublicBtn-jp.jpg)
切替ボタンが活性となり、当ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetTransferPublicEdit-jp.jpg)
公開・非公開の切替が完了です。
![avatar](../images-jp/userGuide/project/projViewSetTransferredPublic-jp.jpg)

######1.4.6.1.4 プロジェクト削除
<u>プロジェクトを削除</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewSetDelProjMenu-jp.jpg)
プロジェクト削除区域が表示されます。
![avatar](../images-jp/userGuide/project/projViewSetDelProjInit-jp.jpg)
削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetDelProjBtn-jp.jpg)
削除確認ダイアログボックスが表示され、OKボタンをクリックします(削除を取り消したい場合に取消ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewSetDelProjConfirm-jp.jpg)
プロジェクトが削除され、プロジェクト一覧画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewSetDeledProj-jp.jpg)
検索により削除プロジェクトが無くなることを確認できます。
![avatar](../images-jp/userGuide/project/projViewSetDeledProjNotInPrjList-jp.jpg)

#####1.4.6.2 メンバー
設定画面の左側の<u>メンバー</u>をクリックします。
![avatar](../images-jp/userGuide/project/projViewSetMemberTag-jp.jpg)
メンバー管理画面が表示されます。当画面はメンバー招待とグループ招待の両部分に分けられます。
画面の下の方に既存メンバーとグループリストがあります。
![avatar](../images-jp/userGuide/project/projViewSetMemberInit-jp.jpg)

######1.4.6.2.1 メンバー招待
メンバーIDまたはメールアドレスを入力します。入力しているうちに入力した文字列とマッチしたユーザーがリストアップしますので、
リストから選択していいです。
![avatar](../images-jp/userGuide/project/projViewSetMemInviteUser-jp.jpg)
権限を設定するには権限のドロップダウンリストボックスをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUserPermitBox-jp.jpg)
権限リストが表示されます。
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUserPermitSelList-jp.jpg)
権限リストから追加する権限をクリックします。追加された権限の右側に✓が表示されます。複数追加でいいです。
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUserPermitSeled-jp.jpg)
追加した権限を消すには、消す権限の傍にある<u>×</u>をクリックしていいです。
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUserPermitDelX-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUserPermitDeledX-jp.jpg)
或いはドロップダウンリストに追加した権限を再クリックし、右の✓が消え、当権限が外されます。
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUserPermitDelClick-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUserPermitDeledClick-jp.jpg)
ユーザーIDと権限を入力したら招待ボタンが活性となり、当ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUserPermitBtn-jp.jpg)
既存メンバーとグループ一覧に招待したユーザーが表示されます。
当プロジェクトが追加したユーザーの関連プロジェクトとなります。
![avatar](../images-jp/userGuide/project/projViewSetMemInvitedUser-jp.jpg)

######1.4.6.2.2 メンバー削除
既存メンバーとグループリストで消すメンバーの後ろにあるRemoveボタンをクリックしたら当メンバーが削除されます。
![avatar](../images-jp/userGuide/project/projViewSetMemUserRemoveBtn-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewSetMemUserRemoved-jp.jpg)

######1.4.6.2.3 グループ招待
<u>グループ招待</u>招待をクリックします。
![avatar](../images-jp/userGuide/project/projViewSetMemGrpTag-jp.jpg)
グループ招待の区域が表示されます。
![avatar](../images-jp/userGuide/project/projViewSetMemGrpWind-jp.jpg)
招待するグループIDを入力します。入力しているうちに入力した文字列とマッチしたグループがリストアップしますので、
リストから選択していいです。
![avatar](../images-jp/userGuide/project/projViewSetMemGrpInput-jp.jpg)
招待するグループに権限を設定します(1.4.6.2.1メンバー招待の権限設定を参照)。
![avatar](../images-jp/userGuide/project/projViewSetMemGrpPermitSel-jp.jpg)
グループIDと権限を入力したら、招待ボタンが活性となり、当ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetMemGrpInviteBtn-jp.jpg)
既存メンバーとグループ一覧に招待したグループが表示されます。
当プロジェクトが追加したグループの関連プロジェクトとなります。
![avatar](../images-jp/userGuide/project/projViewSetMemGrpInvited-jp.jpg)

######1.4.6.2.4 グループ削除
既存メンバーとグループリストで消すグループの後ろにあるRemoveボタンをクリックしたら当グループが削除されます。
![avatar](../images-jp/userGuide/project/projViewSetMemGrpRemoveBtn-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewSetMemGrpRemoved-jp.jpg)

#####1.4.6.3 ラベル
ラベルの使い道は、ユーザーがカスタマイズしたラベルでデータを分類します。これでデータ検索を柔軟的に行われます。
設定画面の左側の<u>ラベル</u>タグをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetLabelTag-jp.jpg)
ラベル画面が表示されます。ラベルはフローラベルとチケットラベルの両部分に分かられます。
![avatar](../images-jp/userGuide/project/projViewSetLabelInit-jp.jpg)

######1.4.6.3.1 フローラベル
(1) ラベル追加
追加ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetLabAddBtn-jp.jpg)
ラベル一覧に新レコードが1件追加され、各項目に暗黙値があります。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabAddedRec-jp.jpg)
新レコードのラベル色をクリックします。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabColorColumn-jp.jpg)
色の設定ダイアログボックスが表示され、色を選択します。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabColorSelDlg-jp.jpg)
ラベルとメモを入力します。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabInput-jp.jpg)
保存ボタンをクリックします(ラベル追加を取り消したい場合に取消ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabSave-jp.jpg)
ラベルが保存され、編集不可となり、操作欄のボタンは編集と削除となります。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabNewed-jp.jpg)

(2) ラベル編集
直すラベルの後ろにある編集ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabEditBtn-jp.jpg)
ラベルが編集可能と成ります。操作欄のボタンが保存と取消と成ります。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabEditStatus-jp.jpg)
各列を直してから、保存ボタンをクリックします(ラベル編集を取り消したい場合に取消ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabReEdit-jp.jpg)
編集が完了で、ラベルが編集不可となり、操作欄のボタンは編集と削除となります。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabEdited-jp.jpg)

(3) ラベル削除
消すラベルの後ろにある削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabDelBtn-jp.jpg)
消したラベルがラベル一覧に無くなりました。
![avatar](../images-jp/userGuide/project/projViewSetFlowLabDeled-jp.jpg)

(4) フローにラベルを付けます
まずフロータグをクリックし、フロー一覧画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowTagFromFlowLab-jp.jpg)
フロー一覧から、ラベルを付けるフローを選びます。
![avatar](../images-jp/userGuide/project/projViewSelecteLabFlowInList-jp.jpg)
フローを幾つか選択したら、一覧の上に青い枠が表示され、中に選択件数、ラベルボタンと削除ボタンがあります。
![avatar](../images-jp/userGuide/project/projViewSelectedLabFlowInList-jp.jpg)
ラベルボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowListLabSetBtn-jp.jpg)
ラベルリストが表示されます(ラベルリスト中の項目は、設定→一般→ラベル→フローラベルで作成されたものです)。
![avatar](../images-jp/userGuide/project/projViewFlowListLabSetList-jp.jpg)
ラベルリストからフローに付けるラベルをクリックします(複数でもいい)。
![avatar](../images-jp/userGuide/project/projViewFlowListSelectLab-jp.jpg)
クリックしたラベルの前にチェックマーク(✔)が表示され、このラベルが選択済状態となります。
選択済みのラベルを外すには、そのラベルを再クリックします。
![avatar](../images-jp/userGuide/project/projViewFlowListSelectedLab-jp.jpg)
カーソルをラベルリストから離し、画面の空白の箇所でマウスをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowSelectedLabMoveCursor-jp.jpg)
フローへのラベル付けが終わりです。
![avatar](../images-jp/userGuide/project/projViewFlowSetedLab-jp.jpg)

(5) フローラベルの編集
フローラベルの編集は、フローにラベルを付ける操作と同じで、まず編集するフローを選択します。
![avatar](../images-jp/userGuide/project/projViewSelectedEditLabFlowInList-jp.jpg)
一覧上のラベルボタンをクリックし、ラベルリストが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowListLabEditList-jp.jpg)
ラベルリストから新たにラベルを選択します。
![avatar](../images-jp/userGuide/project/projViewFlowListReSelectedLab-jp.jpg)
カーソルをラベルリストから離し、画面の空白の箇所でマウスをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowReSelectedLabMoveCursor-jp.jpg)
フローのラベルが直されます。
![avatar](../images-jp/userGuide/project/projViewFlowReSetedLab-jp.jpg)

(6) フローのラベルを消します
フローのラベルを消すには、ラベルの後ろにある×をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowSelectDelFlowLab-jp.jpg)
消すラベルが無くなります。
![avatar](../images-jp/userGuide/project/projViewFlowDeletedLab-jp.jpg)

(7) ラベルフィルターを設定します
ラベルフィルターで指定ラベルを持つフローを洗い出せます。

(新規ボタンの左側にある)ラベルボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowListLabSelectBtn-jp.jpg)
ラベルリストが表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowListLabSelectList-jp.jpg)
ラベルリストからフィルターを構成するラベルをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowListSelectFilterLab-jp.jpg)
クリックしたラベルの前にチェックマーク(✔)が表示され、このラベルが選択済状態となります。
選択済みのラベルを外すには、そのラベルを再クリックします。
![avatar](../images-jp/userGuide/project/projViewFlowListSelectedFilterLab-jp.jpg)
カーソルをラベルリストから離し、画面の空白の箇所でマウスをクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowSelectedFilterLabMoveCursor-jp.jpg)
一覧の上にフィルターのラベルが表示され、一覧にフィルターのラベルを持つフローだけが表示されます。
ラベルが複数の場合に、各ラベルの間に又は(OR)のロジックです。
![avatar](../images-jp/userGuide/project/projViewFlowSelectedByLab-jp.jpg)

(8) ラベルフィルターを直します
ラベルフィルターを直すには、まずラベルボタンを再クリックします。
![avatar](../images-jp/userGuide/project/projViewFlowListLabReSelectBtn-jp.jpg)
ラベルリストが表示され、初期はフィルターを構成したラベルが選択済み状態となります。
![avatar](../images-jp/userGuide/project/projViewFlowListLabReSelectList-jp.jpg)
フィルターのラベルを新たに選択します。
![avatar](../images-jp/userGuide/project/projViewFlowListReSelectFilterLab-jp.jpg)
カーソルをラベルリストから離し、画面の空白の箇所でマウスをクリックします。
ラベルフィルターが直され、新フィルターに該当するデータが一覧に再表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowReSelectedByLab-jp.jpg)

(9) フィルターのラベルを消します
フィルターのラベルを一部消す(全部削除も可能)には、ラベルの後ろにある×をクリックします。
![avatar](../images-jp/userGuide/project/projViewFlowLabFilterDelLabBtn-jp.jpg)
消すラベルが無くなり、残りのラベルに該当するデータが一覧に再表示されます。
![avatar](../images-jp/userGuide/project/projViewFlowLabFilterDeletedLab-jp.jpg)

######1.4.6.3.2 チケットラベル
ラベル設定画面で、<u>チケット</u>タグをクリックします。チケットラベル設定画面が表示されます。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabTag-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewSetTicketLabWind-jp.jpg)

(1) ラベル追加
追加ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetLabTicketAddBtn-jp.jpg)
ラベル一覧に新レコードが1件追加され、各項目に暗黙値があります。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabAddedRec-jp.jpg)
新レコードのラベル色をクリックします。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabColorColumn-jp.jpg)
色の設定ダイアログボックスが表示され、色を選択します。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabColorSelDlg-jp.jpg)
ラベルとメモを入力します。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabInput-jp.jpg)
保存ボタンをクリックします(ラベル追加を取り消したい場合に取消ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabSave-jp.jpg)
ラベルが保存され、編集不可となり、操作欄のボタンは編集と削除となります。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabNewed-jp.jpg)

(2) ラベル編集
直すラベルの後ろにある編集ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabEditBtn-jp.jpg)
ラベルが編集可能と成ります。操作欄のボタンが保存と取消と成ります。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabEditStatus-jp.jpg)
各列を直してから、保存ボタンをクリックします(ラベル編集を取り消したい場合に取消ボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabReEdit-jp.jpg)
編集が完了で、ラベルが編集不可となり、操作欄のボタンは編集と削除となります。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabEdited-jp.jpg)

(3) ラベル削除
消すラベルの後ろにある削除ボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabDelBtn-jp.jpg)
消したラベルがラベル一覧に無くなりました。
![avatar](../images-jp/userGuide/project/projViewSetTicketLabDeled-jp.jpg)

(4) チケットラベルの使い道
チケットラベルの使い道は、フローラベルと同じで、フローラベルの使い道の説明を参照となります。

####1.4.7 台帳
台帳は、ローカルにあるCSVファイルのデータをインポートできます。

####1.4.7.1 台帳新規
画面右上の台帳追加ボタンをクリックします。注意するのは台帳が複数でいいです。
![avatar](../images-jp/userGuide/project/projViewAddLedgerBtn-jp.jpg)
台帳名前入力ダイアログボックスが表示されます。
![avatar](../images-jp/userGuide/project/projViewNewLedgerTitle-jp.jpg)
台帳名前を入力してからOKボタンをクリックします(台帳新規を放棄する場合にキャンセルボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewInputLedgerTitle-jp.jpg)
新しい台帳タグ画面が表示され、この台帳タグをクリックします。
![avatar](../images-jp/userGuide/project/projViewAddedEmptyLedger-jp.jpg)
新規台帳にまだデータが無し、csvファイルをアップロードすることでデータをインポートします。
![avatar](../images-jp/userGuide/project/projViewEmptyLedger-jp.jpg)

####1.4.7.2 Csvファイルデータをインポートします
アップロードボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewLedgerUpLoadBtn-jp.jpg)
ファイル選択ダイアログボックスが表示されます。
![avatar](../images-jp/userGuide/project/projViewLedgerSelFileDlg-jp.jpg)
インポートするcsvファイルを選択してから、開くボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewLedgerSelectedCsvFile-jp.jpg)
![avatar](../images-jp/userGuide/project/projViewLedgerUploadCsvContent-jp.jpg)
csvファイルのデータが台帳にインポートされます。
![avatar](../images-jp/userGuide/project/projViewLedgerUploadedCsv-jp.jpg)

####1.4.7.2 台帳データをダウンロードします
台帳のデータは、ローカルにダウンロードできます。

ダウンロードボタンをクリックします。
![avatar](../images-jp/userGuide/project/projViewLedgerDownLoadBtn-jp.jpg)
ダウンロードが完了してから、ファイルダウンロード状態欄でファイルの傍にある矢印をクリックします。
![avatar](../images-jp/userGuide/project/projViewLedgerDownLoadedCsv-jp.jpg)
メニューリストが表示され、フォルダを開くをクリックします。
![avatar](../images-jp/userGuide/project/projViewLedgerShowDownloadFileInFld-jp.jpg)
ファイルを格納したフォルダが開かれます。
![avatar](../images-jp/userGuide/project/projViewLedgerDownloadFileInFld-jp.jpg)
ファイルを開いてから内容を確認します。
![avatar](../images-jp/userGuide/project/projViewLedgerDownloadFileContent-jp.jpg)

####1.4.7.3 台帳削除
台帳を消すには台帳画面の削除ボタンをクリックします。注意するのは台帳削除が、データだけではなく、台帳タグ画面も消されます。
![avatar](../images-jp/userGuide/project/projViewLedgerDelBtn-jp.jpg)
台帳削除確認ダイアログボックスが表示され、OKボタンをクリックします(削除を放棄する場合にキャンセルボタンをクリックします)。
![avatar](../images-jp/userGuide/project/projViewLedgerDelConfirmDlg-jp.jpg)
台帳が消されます。
![avatar](../images-jp/userGuide/project/projViewLedgerDeleted-jp.jpg)




