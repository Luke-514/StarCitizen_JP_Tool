# これは何をするためのもの？
Star Citizenを日本語化するための設定を自動で行ったり、  
設定のバックアップ、ユーザーフォルダの削除などを行うツールです。  
  
手動で日本語化したい場合は、以下の記事をご覧ください  
https://lukesplaygrounds.com/2025/08/17/star-citizen-how-to-configure-japanese-localization/  
  
<img src="image/tool.jpg" width="50%" />  
  
# 主な機能
・Star Citizenの日本語化、日本語化解除  
&emsp;(最新の[日本語化ファイル](https://github.com/stdblue/StarCitizenJapaneseResources)を自動で取得します)  
・設定のバックアップ、復元、コピー  
・ユーザー、シェーダーフォルダの削除  
・ゲームフォルダ名の変更  
・日本語化ファイル、ツールの更新確認  
<!--・作者独自の推奨スペック確認  -->
  
# ツールの入手と起動
1.&nbsp;[Releases](https://github.com/Luke-514/StarCitizen_JP_Tool/releases/latest)からツールのZIPファイル(StarCitizen_JP_Tool.zip)をダウンロードします  
  
2.&nbsp;任意の場所でZIPファイルを展開し、StarCitizen_JP_Tool.exeを起動してください  
&emsp;(展開したフォルダ内にあるファイルはツールの動作に必要ですので、削除しないよう気を付けてください)  
&emsp;<img src="image/start.png" width="70%" />  
  
# 利用上の注意(共通)
> [!CAUTION]  
>・一度もStar Citizenを起動したことが無い場合は、ツールの利用前にStar Citizenを起動してください  
>&emsp;(Star Citizenを起動しないとインストール先の情報がログに書き込まれないため)
>  
>・ツールを利用される際はStar Citizenを落としてからご利用ください  
>&emsp;(Star Citizenを起動したままだと設定などが反映されません)  
>  
>・自動で生成されるToolDataフォルダは削除しないでください  
>&emsp;(削除するとツールが正しく動作しなくなる可能性があります)  
>  
>・日本語化ファイルは翻訳途中のため、英語/機械翻訳/手動翻訳が混ざっています  
>&emsp;ローカライゼーション自体にバグが点在しています  
  
# バックアップツール利用上の注意
・バージョンによってはキーバインドや各種設定の内容が大幅に変わり、  
&emsp;復元しても正しく動作しない可能性があります  
  
・キャラクターファイルをバックアップ・復元する場合は、  
&emsp;手動でキャラクターカスタマイズ画面からImport/Exportする必要があります  
&emsp;<img src="image/char menu.jpg" width="60%" />  
&emsp;<img src="image/char save.png" width="60%" />  
  
・操作プロファイルをバックアップ・復元する場合は、手動でゲーム内からImport/Exportする必要があります  
&emsp;詳しい手順は[公式ナレッジ](https://support.robertsspaceindustries.com/hc/en-us/articles/360000183328-Create-export-and-import-custom-profiles)を参考にしてください  
  
・グラフィックレンダラーの設定はバックアップできません  
  
・コピー機能はバックアップされた設定などを別のバージョンのバックアップフォルダへコピーする機能です  
  
・バックアップしたファイルなどは、ツールのあるフォルダに生成されるBackupDataフォルダ内にあります  
  
# 設定・シェーダー削除ツール利用上の注意
> [!WARNING]
> ・バージョン関係なく全てのシェーダーフォルダを削除します  
> &emsp;(ユーザーフォルダは選択したバージョンのものを削除します)
>  
> ・削除対象に表示されたフォルダは中身ごと完全削除しますので、  
> &emsp;表示された対象をよく確認してから削除を実施してください  
>  
> ・操作設定等は消去されますので、必要な方はバックアップツールでバックアップしてください  
  
> [!NOTE]  
> ユーザー・シェーダーフォルダは公式ランチャーから削除できるようになったため、  
> 基本的にはそちらを利用されることをおすすめします
  
# ゲームフォルダ名変更ツール利用上の注意
> [!CAUTION]  
>・複数のバージョンがインストールされていると正しく動作しません  
>&emsp;インストールされているバージョンが１つのときのみお使いください
  
<!-- # スペック確認ツール利用上の注意
> [!CAUTION]  
>・あくまでも作者が考えた推奨スペックに適合するかのチェックツールです  
>&emsp;一部がNGでも、遊ぶことのできるPCは沢山ありますので、参考程度にご利用ください  
>
> ・SCプレイヤーが利用しているPCスペックは[公式テレメトリー](https://robertsspaceindustries.com/telemetry)をご覧ください  
>
> ・サーバー向けと一部特殊な製品は登録していないため、結果がNGとして表示されます  
>
> ・Star Citizenがインストールされていなくても使用可能な[スタンドアロン版](https://github.com/Luke-514/StarCitizen_Spec_Check_Tool)もあります
> 
> ・判定基準などは以下の記事をご覧ください  
>&emsp;https://lukesplaygrounds.com/2024/11/05/recommended-pc-specs-for-star-citizen/  -->
  
# 日本語化ツールの使い方
1.&nbsp;日本語化ボタンを押します  
&nbsp;&emsp;(ツール起動時は日本語化ツールが選択されています)  
&nbsp;&emsp;<img src="image/jp.png" width="50%" />  
  
2.&nbsp;日本語化したいバージョンを選択し、OKボタンを押してください  
&nbsp;&emsp;(通常はLIVEでOKです)  
  
3.&nbsp;確認画面が出ますので、問題なければYESボタンを押してください  
&nbsp;&emsp;(NOを押すと、前の画面に戻ります)  
  
4.&nbsp;「日本語化が完了しました。」と出力されていれば、日本語化が完了しているはずですので、  
&nbsp;&emsp;ゲームを起動してみてください  
  
# バックアップツールの使い方
1.&nbsp;バックアップボタンを押します  
&emsp;<img src="image/br.png" width="50%" />  
  
2.&nbsp;バックアップ・復元・コピーのうち、実施したいモードを選択してOKボタンを押してください  
  
3.&nbsp;LIVE、PTU、EPTUのうち、実施したいバージョンを選択します  
&nbsp;&emsp;(コピーを実施する場合はコピー元とコピー先のバージョンを選択してください)  
  
4.&nbsp;対象のファイル等が表示されるので、問題なければYESボタンを押してください  
  
# 設定・シェーダー削除ツールの使い方
1.&nbsp;設定・シェーダーフォルダ削除ボタンを押します  
&nbsp;&emsp;<img src="image/us.png" width="50%" />  
  
2.&nbsp;設定・シェーダーフォルダを消したいバージョンを選択してOKボタンを押してください  
  
3.&nbsp;削除対象が表示されるので、問題なければYESボタンを押してください  
  
# ゲームフォルダ名変更ツールの使い方  
1.&nbsp;フォルダ名変更ボタンを押します  
&nbsp;&emsp;<img src="image/cfn.png" width="50%" />  
  
2.&nbsp;変更前と変更後のバージョンを選択して、OKボタンを押してください  
  
3.&nbsp;確認画面が出ますので、問題なければYESボタンを押してください  
  
<!--# スペック確認ツールの使い方  
1.&nbsp;スペック確認ボタンを押します  
&nbsp;&emsp;<img src="image/spec.png" width="50%" />  
  
2.&nbsp;スペック確認を実行してもよければ、OKボタンを押してください  -->
  
# よくある質問
Q.&nbsp;自分で配置したuser.cfgがある場合はどうなりますか？  
A.&nbsp;user.cfgが配置されている場合は日本語化に必要な情報を追記します。  
&nbsp;&emsp;(既に必要な情報が記載されていれば何もしません)  
  
Q.&nbsp;global.ini(翻訳ファイル)を更新したい。  
A.&nbsp;通常通りに日本語化の手順を実行すると、最新版のglobal.iniを取得し、更新します。  
  
Q.&nbsp;日本語化を解除したい  
A.&nbsp;左上の日本語化解除ボタンを押して、日本語化解除モードへ切り替えてください。  
&nbsp;&emsp;(その後の操作方法は日本語化の時とほぼ同じです)  
&nbsp;&emsp;<img src="image/djp.png" width="50%" />  
  
Q.&nbsp;ツールを起動するとWindows Defenderに止められる  
A.&nbsp;詳細情報を押すと出てくる実行ボタンを押してください  
&emsp;<img src="image/defender.jpg" width="45%" />
<img src="image/defender_accept.png" width="45%" />  
  
Q.&nbsp;任意の日本語化ファイルを導入したい(PTU用のテストバージョンなど)  
A.&nbsp;日本語化ファイル選択ボタンを押して、global.iniを選択した後に日本語化を実施してください  
&nbsp;&emsp;(ツールのあるフォルダにglobal.iniを配置して日本語化を実施してもよいです)  
&nbsp;&emsp;<img src="image/se.png" width="50%" />  
  
Q.&nbsp;LIVE以外の日本語化ファイルが最新かどうか確認したい  
A.&nbsp;日本語化モードの状態で確認したいバージョンを選択すると、最新の日本語化ファイルかどうかが表示されます  
  
Q.&nbsp;Star Citizenがクラッシュした後に、ツールを利用しようとしたら起動しなくなった  
A.&nbsp;Star Citizenをもう一度起動しなおし、正常に終了させてから、ツールを起動してみてください  
  
Q.&nbsp;ツールをしばらく使っていたら、ツールの動作がおかしくなった or 更新を検知しなくなった  
A.&nbsp;GitHubのAPI制限に引っかかったことが原因と考えられますので、１時間後に再度お試しください  
  
Q.&nbsp;上記いずれでも解決しない問題がある  
A.&nbsp;アンチウイルスソフトの例外リスト等への登録と、管理者権限での起動を試してみてください  
  
# 利用規約
許可  
・個人利用  
・SNSや動画、ブログでの紹介  
&emsp;(掲載連絡は不要ですが、当ページのリンクを貼ってください)  
  
禁止  
・商用利用  
・二次配布  
・逆コンパイル、コードの抽出  
  
# 免責事項
本ツールの使用によって発生した、いかなる損害に対しても作者は一切の責任を負いません。  
Star Citizen®、Roberts Space Industries®、Cloud Imperium®はCloud Imperium Rights LLCの登録商標です。  
  
# 作者
Luke514  
  
Twitter  
@rx_luke  
  
Star Citizen紹介コード(referral code)  
STAR-9YPT-ZV5J  
  
# Special Thanks
SEAGANG  
Someone  
Ugachain  
aritu  
ぽえな  
NTKestrel  
Shinnryuu  
MoMoShrine  
クレクレ柴犬  
Popolilo  
あしま  
[Star Citizen Japan Community](http://discord.gg/Wa99tKE48e)  
  
# 寄付
<a href="https://www.buymeacoffee.com/Luke514" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
