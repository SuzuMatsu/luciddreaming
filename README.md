# luciddreamingは夢の世界で鍵を集め、脱出するというコンセプトのゲームです。
#操作は以下の順番の通りです。

#タイトル画面で制限時間が３つ設定されているので、自分に合った難易度を選択肢ゲームをスタートします。
#夢の中の世界だと、蝶(画面中央)がアバターとなります。マウスドラッグによって操作します。
#上にドラッグで前進、下にドラッグで前進、左で左に方向転換、右で右に方向転換します。
#移動中のスピードについては、sキー押打で減速、fキー押打で加速します。
#移動中は１~８の数字のキーでカメラ視点を操作します。

#敵
#ゲームスタート後、一定時間経過すると敵が出現します。敵にあたるとゲームオーバーです。敵はそれぞれ所定の位置をランダムに徘徊します。

#鍵
#フィールド内にランダムに４つ出現します。獲得すると右上に獲得状況が表示され、全て獲得すると扉から脱出できます。

#OpenFrameWorksを用いてコーディングしています。(言語はC++です)
#コーディングしているファイルを記載します。
#ofApp.hにはプログラム内で使われている関数の設定、#main.cppに画面の大きさの設定、ofApp.cppにメインのゲームのプログラムを記載しています。
