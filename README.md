# microwave_game
電子レンジを使ったゲームアプリです。ボタンをタップして画面遷移を行い、3つの食材から一つを選んで電子レンジで加熱を行います。
<br>
予め設定した目安の加熱時間と計測した加熱時間を比較し、3段階評価を行います。

# 機能
1.ボタンを押してゲームを始める

2.三つの食材のうち1つを選択する

3.「始める」ボタンをタップして計測開始 (ゲーム開始)

4.「止める」ボタンをタップして計測終了 (ゲーム終了)

5.設定した時間に応じて◎, 〇, ✕の3段階で評価

# 3つの食材について
1.おにぎり (加熱時間の目安：20~30秒)

2.たまご (加熱時間の目安：10秒)

3.冷凍食品 (加熱時間の目安：80~100秒)

# 作成したファイル(java)
## MainActivity.java
起動画面
## SubActivity.java
3つの食材の選択を行う
## MoreActivity.java
電子レンジの計測開始と終了を行う
## ResultActivity.java
経過時間を受け取り、◎, 〇, ✕の3段階で評価を行う
## Data.java
経過時間を受け取る

# 作成したファイル(レイアウトファイル)
## activity_main.xml
起動画面の描写
## activity_sub.xml
3つのイメージボタンを描写
## activity_more.xml
計測中の電子レンジを描写
## activity_result.xml
経過時間と3段階評価を表示

# 注意事項
string.xmlには、アプリ内で使用する文字列リソースを定義しています。文字列リソースがない場合は、アプリが動作しないためご注意ください。

# 作者
FukadaShokuto
<br>
mail to: fukafuka76790@mail.com

# Requirements
- Windows 10 home 64bit
- AndroidStudio 4.1.3

# 参考文献
- Android プログラミング 【 アニメーション ① 】 ~ 上下移動 ~ – ハコニワ デザイン
https://hakoniwadesign.com/?p=9633
