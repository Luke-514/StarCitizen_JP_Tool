# これは何をするためのもの？
スターシチズンを日本語化するための[日本語化ファイル](https://github.com/stdblue/StarCitizenJapaneseResources)の配置場所や、設定方法が分からないという方でも  
簡単に日本語化できるようにする日本語化支援ツールです。  
本バッチファイルはStar Citizenの操作プロファイルや設定をバックアップ、復元するものです  
本バッチファイルはStar Citizenのバージョンが変わった際に、  
CIG(SCの開発・運営)が削除することを推奨している、ユーザーフォルダとシェーダーフォルダを削除するものです  
  
# 使い方
1.&nbsp;[Releases](https://github.com/Luke-514/StarCitizen_JP_Tool/releases/latest)から支援ツールのZIPファイル(StarCitizen_JP_Tool.zip)をダウンロードします。  
  
2.&nbsp;任意の場所でZIPファイルを展開し、StarCitizen_JP_Tool.exeを起動してください。  
&emsp;(展開したフォルダ内にあるファイルはツールの動作に必要ですので、削除しないよう気を付けてください)  
<img src="image/1.png" width="80%" />  
  
3.&nbsp;日本語化したいバージョンを選択し、OKボタンを押してください。  
&emsp;(通常はLIVEでOKです)  
<img src="image/2.png" width="50%" />  
  
4.&nbsp;確認画面が出ますので、問題なければYESボタンを押してください。  
&emsp;(NOを押すと、前の画面に戻ります)  
<img src="image/3.png" width="50%" />  
  
5.&nbsp;「日本語化が完了しました。」と出力されていれば、日本語化が完了しているはずですので、  
&emsp;ゲームを起動してみてください。  
<img src="image/4.png" width="50%" />  
  
# バックアップ・復元ツールの利用上の注意
操作プロファイル・キャラクタープロファイルは手動でゲーム内からImport/Exportする必要があります  
(操作プロファイル・キャラクタープロファイル以外はImport/Exportしなくても適用されます)  
  
操作プロファイルの詳しいImport/Export方法は以下を参考にしてください  
https://support.robertsspaceindustries.com/hc/en-us/articles/360000183328-Create-export-and-import-custom-profiles  
  
# バックアップ・復元ツールの使い方
3.&nbsp;バックアップ・復元ツールボタンを押します  
4.&nbsp;LIVE、PTU、EPTUのうち、実施したいバージョンを選択します  
5.&nbsp;バックアップ、復元対象が表示されるので、YESかNOボタンを押してください  
  
# 設定コピー機能の使い方
1.&nbsp;コピーしたいバージョンの設定をBackupしておきます  
2.&nbsp;実施するモードの選択でCopyを選択します  
3.&nbsp;コピー元のバージョンを選択します  
4.&nbsp;コピー先のバージョンを選択します  
5.&nbsp;コピー対象が表示されるので、YESかNOボタンを押してください  
6.&nbsp;Restoreを実施します  

# User/Shaderフォルダ削除ツールの利用上の注意
本ツールはStar Citizenのアップデート前に使うことをお勧めします  
  
PTUがLIVEのマイナーパッチをテストしている場合は、両方のシェーダーフォルダが削除されます  
マイナーパッチの例) LIVE: 3.17.4 PTU: 3.17.5  
メジャーパッチの例) LIVE: 3.17.5 PTU: 3.18.0  
  
削除対象に表示されたフォルダは中身ごと完全削除しますので、  
表示された対象をよく確認してから削除を実施してください  
  
操作設定等は消去されますので、必要な方はバックアップ・復元ツールでバックアップしてください  

# User/Shaderフォルダ削除ツールの使い方
3.&nbsp;LIVE、PTU、EPTUのうち、消したいバージョンを選択します  
4.&nbsp;削除対象が表示されるので、YESかNOボタンを押してください  
  
# よくある質問
Q.&nbsp;自分で配置したuser.cfgがある場合はどうなりますか？  
A.&nbsp;user.cfgが配置されている場合は日本語化に必要な情報を追記します。  
&emsp;(既に必要な情報が記載されていれば何もしません)  
  
Q.&nbsp;global.ini(翻訳ファイル)を更新したい。  
A.&nbsp;通常通りに日本語化の手順を実行すると、最新版のglobal.iniを取得し、更新します。  
  
Q.&nbsp;日本語化を解除したい  
A.&nbsp;左上の日本語化解除ボタンを押して、モードを切り替えてください。  
&emsp;(その後の操作方法は日本語化の時とほぼ同じです)  
<img src="image/jp_disable.png" width="50%" />  
  
Q.&nbsp;ツールを起動するとWindows Defenderに止められる  
A.&nbsp;詳細情報を押すと出てくる実行ボタンを押してください  
<img src="image/defender.jpg" width="45%" />
<img src="image/defender_accept.jpg" width="45%" />  
  
Q.&nbsp;任意のglobal.iniを導入したい(テストバージョンなど)  
A.&nbsp;ツールのあるフォルダに任意のglobal.iniを配置してツールを実行してください  
<img src="image/withglobal.png" width="80%" />  
  
# 免責事項
本ツールの使用によって発生した、いかなる損害に対しても作者は一切の責任を負いません。  
Star Citizen®、Roberts Space Industries®、Cloud Imperium®はCloud Imperium Rights LLCの登録商標です。  
  
# 作者
Luke514  
Twitter:@rx_luke  
Star Citizen紹介コード(referral code) → 【STAR-9YPT-ZV5J】 
  
# Special Thanks
NTKestrel  
Shinnryuu  
