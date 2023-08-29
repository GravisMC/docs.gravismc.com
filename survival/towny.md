Towny（/towny）コマンド
​コマンド

​説明

/towny

各コマンドのヘルプ一覧を表示

/towny ?

/towny系のコマンドヘルプ

/towny map

周辺のマップを表示

/towny prices

​町の運営にかかわる機能の値段を表示

/towny time

時間を表示する。次の税収の時間などの参考になります。

/towny top residents all

住民数ランキングを表示（すべての町や国）

/towny top residents town

住民数ランキングを表示（すべての町）

/towny top residents nation

​住民数ランキングを表示（すべての国）

/towny top land all

オーナーとなっている土地のランキングを表示（すべての町や国）

/towny top land town

オーナーとなっている土地の数ランキングを表示（町ごと）

/towny top land resident

オーナーとなっている土地の数ランキングを表示（住民ごと）

町（/town）コマンド
​コマンド

​説明

/town

自分の町の情報を見る

/town ?

/town系のコマンドヘルプ

/town list

町一覧を表示

/town 町名

​指定した町の情報を見る

/town here

今いる場所の町の情報を見る

/town new 町名

新しい町を作成。自身が町長になる（町名は半角英数で入力すること）。費用は1,000mine

/town new 町名 プレイヤー名

新しい町を作成。指定したプレイヤーを町長にする。（町名は半角英数で入力すること） 。費用は1,000mine

/town add プレイヤー名

​指定したプレイヤーを町に招待する

/town kick プレイヤー名

​指定したプレイヤーを町から追い出す

/town join 町名

​町に参加する（その町がopen設定になっていなければこのコマンドでは参加できません。）

/town leave

​所属している町から離脱する（町長はこのコマンドを実行できません。）

/town spawn

町のスポーン地点へワープする

/town spawn 町名

指定した町のスポーン地点へワープする

/town claim

今いる土地を町にする（5チャンク以内に他の町の土地がある場合は実行できません。）。費用は100mine

/town claim outpost

​町に隣接していない土地を町の土地にする（5チャンク以内に他の町の土地がある場合は実行できません。）

​費用は300mine

/town claim 値

​指定した値の分だけ自身の周辺の土地を町の土地にする（5チャンク以内に他の町の土地がある場合は実行できません。）

/town claim auto

町の銀行にあるだけのお金を使って、自身の周辺の土地をできる限り町の土地にする（5チャンク以内に他の町の土地がある場合は実行できません。）

/town unclaim

​今いる土地を手放す

/town unclaim all

​町のすべての土地を手放す

/town unclaim 値

​指定した値分だけ自身の周辺の土地を手放す

/town withdraw 値

​指定した値の分のお金を町の銀行から引き出す

/town deposit 値

指定した値の分のお金を町の銀行に預け入れる【注意！】お金を入れたままにすると不具合でお金が消失することがあります

/town buy bonus 値

町が取得可能な土地の上限を引き上げる（できない）

/town delete 町名

​【注意！】町を削除する

/town outpost

アウトポストへワープする

/town outpost 値

​指定したアウトポストへワープする（作成した順に１，２，３と数が割り振られる）

/town ranklist

住民一覧と住民のランクを表示する

/town rank add プレイヤー名 ランク名

指定したプレイヤーにランクを付与する（assistantを付与可能）

/town remove プレイヤー名 ランク名

指定したプレイヤーからランクをはく奪する（assistantをはく奪可能）

/town reslist

住民の一覧を時表示する

/town set board メッセージ

​参加した時に指定したメッセージを表示する（半角英数のみ可能）

/town set mayor プレイヤー名

​指定したプレイヤーに町長を譲渡する

/town set homeblock

​今いる町の土地を町のホームブロックにする

/town set spawn

​今立っている場所をスポーンポイントに設定する（ホームブロックの中でのみ可能）

/town set name 新しい名前

​町の名前を変更する（半角英数で入力すること）

/town set outpost

​今いる町の土地をアウトポストにする

/town set perm on/off

build/destroy/switch/itemuse すべての許可/拒否を設定する

/town set perm build on/off

/town set perm destroy on/off

/town set perm switch on/off

/town set perm itemuse on/off

住民の権限権限のオンオフを設定する

buildは設置、destroyは破壊、switchはボタンやスイッチの使用、itemuseはアイテムの使用

/town set tag タグ

​町のタグ（略称のようなもの）を設定する（最大４文字）

/town set tag clear

町のタグ（略称のようなもの）を削除する

/town set taxes 値

​税金を設定する【注意！】銀行に不具合があるためおすすめしません

/town set plottax 値

​プロットの税金を設定する【注意！】銀行に不具合があるためおすすめしません

/town set plotprice 値

​プロットの値段を設定する

/town set shopprice 値

​商店区画の値を設定する

/town set shoptax 値

商店区画の税金を設定する【注意！】銀行に不具合があるためおすすめしません

/town set embassyprice 値

​大使館の値段を設定する

/town set embassytax 値

​大使館の税金を設定する【注意！】銀行に不具合があるためおすすめしません

/town toggle explosion

​爆発による破壊のオンオフを切り替える（切り替え関係なく爆発しても壊れない）

/town toggle fire

火の延焼のオンオフを切り替える（切り替え関係なく火が付かない）

/town toggle mobs

敵対mobの出現のオンオフを切り替える（切り替え関係なく敵が沸かない）

/town toggle public

​町のホームブロックの場所を公開するかどうかのオンオフを切り替える

/town toggle pvp

PvPのオンオフを切り替える

/town toggle taxpercent

​税金を値で設定するか割合で設定するか切り替える

/town toggle open

町の参加モードを切り替える。Enableの場合誰でも/town joinコマンドで参加できるようになる

​小区画（/plot）コマンド
​コマンド

​説明

/plot

/plot ?

/plot系のコマンドヘルプ

/plot claim

販売中の小区画（plot）を購入する

/plot claim auto

周辺の販売中の小区画（plot）を自動で購入する

/plot fs 値

​今いる町の土地を小区画として指定した値で売りに出す（値を設定しなかった場合タダで売りに出す）

/plot fs 値 circle 半径

​小区画を指定した値で円形の範囲で売りに出す（/plot fs 値と同じ挙動する）

/plot fs 値 rect 半径

小区画を指定した値で正方形の範囲で売りに出す（/plot fs 値と同じ挙動する）

/plot nfs

今いる小区画の販売を中止する

/plot nfs circle 半径

​円形の範囲で小区画の販売を中止する

/plot nfs rect 半径

正方形の範囲で小区画の販売を中止する

/plot perm

今いる小区画の情報を表示する

/plot set reset

​小区画の設定をリセットする

/plot set shop

​今いる小区画を商店区画に設定する

/plot set embassy

​今いる小区画を大使館に設定する

/plot set arena

​今いる小区画をアリーナ区画に設定する

/plot set wilds

小区画を荒野に設定する

/plot set name 名前

​通常の小区画は「~称号　所有者の名前」が表示されるがこのコマンドで表示される名前を変更する

/plot set perm on/off

​小区画でのすべての権限のオンオフを設定する（resident/ally/outsiderの全員が対象）（build/destroy/switch/itemuseのすべてを切り替え）

/plot set perm resident on/off

/plot set perm ally on/off

/plot set perm outsider on/off

​小区画での権限のオンオフを設定する

residentは住民、allyは同盟国者、outsiderは部外者

（build/destroy/switch/itemuseのすべてを切り替え）

/plot set perm build on/off

/plot set perm destroy on/off

/plot set perm switch on/off

/plot set perm itemuse on/off

​小区画での権限のオンオフを設定する

buildは設置、destroyは破壊、switchはスイッチ操作、itemuseはアイテムの使用

（resident/ally/outsiderの全員が対象）

/plot set perm resident build on/off

/plot set perm resident destroy on/off

/plot set perm resident switch on/ off

/plot set perm resident itemuse on/off

小区画での住民の権限のオンオフを設定する

buildは設置、destroyは破壊、switchはスイッチ操作、itemuseはアイテムの使用
​（residentが対象）

/plot set perm ally build on/off

/plot set perm ally destroy on/off

/plot set perm ally switch on/off

/plot set perm ally itemuse on/off

​小区画での同盟国者の権限のオンオフを設定する

buildは設置、destroyは破壊、switchはスイッチ操作、itemuseはアイテムの使用​

（allyが対象）

/plot set perm outsider build on/off

/plot set perm outsider destroy on/off

/plot set perm outsider switch on/off

/plot set perm outsider itemuse on/off

小区画での部外者の権限のオンオフを設定する

buildは設置、destroyは破壊、switchはスイッチ操作、itemuseはアイテムの使用​

（outsiderが対象）

/plot set perm reset

小区画での権限の設定をリセットする

/plot toggle fire

​小区画での火の延焼のオンオフを切り替える

/plot toggle pvp

小区画でのPvPのオンオフを切り替える

/plot toggle explosion

小区画での爆発による破壊のオンオフを切り替える（切り替え関係なく爆発しても壊れない）

/plot toggle mobs

​小区画での敵の出現のオンオフを切り替える（切り替え関係なく敵が沸かない）

/plot clear

​今いる小区画の看板を撤去する（町長又はそのプロットの所有者が実行可能）（多分意味あってる）

​住民（/resident）コマンド・・（/resでも可）
​コマンド

​説明

/resident

​自分の情報を見る

/resident ?

/resident系のコマンドヘルプ

/resident プレイヤー名

指定したプレイヤー名の情報を見る

/resident friend add/remove プレイヤー名

指定したプレイヤーを”自分の”友達リストに追加/削除する（相手の友達リストに入るわけではない）

スペースで区切り複数人指定することも可能

/resident friend clearlist

友達リストからすべての友達を削除する

/resident friend list

自分の友達リストを表示する

/resident spawn

/town spawn と同じ挙動する（違いがよくわからない）

/resident toggle map

地図表示モードのオンオフを切り替える（オンだとチャンクをまたぐたびに地図が表示される）

/resident toggle townclaim

​土地購入モードのオンオフを切り替える（オンだとチャンクをまたぐたびに（可能なら）土地を取得する）

/resident toggle plotborder

小区域の境界表示モードのオンオフを切り替える（オンだとチャンクをまたぐたびにチャンクの境界にエフェクトが出る）

/resident toggle reset

/resident toggle で設定したモードをすべてオフにする

/resident set perm on/off

​自身が所有する土地でのすべての権限のオンオフを切り替える（friend/town/ally/outsiderの全員が対象）

​（build/destroy/switch/itemuseのすべてを切り替え）

/resident set perm friend on/off

/resident set perm town on/off

/resident set perm ally on/off

/resident set perm outsider on/off

​自身が所有する土地での権限のオンオフを設定する

friendは友達、townは町民、allyは同盟国者、outsiderは部外者

(build/destroy/switch/itemuseのすべてを切り替え）

/resident set perm build on/off

/resident set perm destroy on/off

/resident set perm switch on/off

/resident set perm itemuse on/off

​自身が所有する土地での権限のオンオフを設定する

buildは設置、destroyは破壊、switchはスイッチ操作、itemuseはアイテムの使用

​（friend/town/ally/outsiderの全員が対象）

/resident set perm reset

​所有している小区画の権限をresidentに設定している権限の設定に変更する

国（/nation）コマンド
​コマンド

​説明

/nation

加盟している国の情報を表示する

/nation ?

/nation系のコマンドヘルプ

/nation list

​国の一覧を表示

/nation online

オンラインの国民

/nation 国名

​指定した国の国民一覧を表示

/nation leave

​所属している国から離脱する

/nation withdraw 値

指定した値を国の銀行から引き出す

/nation deposit 値

​指定した値を国の銀行に預け入れる【注意！】お金を入れたままにすると不具合でお金が消滅することがあります

/nation new 国名

自分の町を首都に立国する

/nation new 国名 首都名

​首都名を指定して立国する

/nation rank

Command to set assistant/custom ranks in the nation.

/nation add 町名

自国に町を追加する

/nation kick 町名

自国に加盟している国を外す

/nation delete 国名

【注意！】国を削除する

/nation ally add 国名

指定した国と同盟関係になる

/nation ally remove 国名

指定した国との同盟関係を解除する

/nation enemy add 国名

指定した国と敵対関係になる

/nation enemy remove 国名

指定した国との敵対関係を解除する

/nation rank add プレイヤー名 ランク名

​指定した国民にランクを追加する

/nation rank remove プレイヤー名 ランク名

​指定した国民からランクを外す

/nation set king プレイヤー名

指定したプレイヤーを王にする

/nation set capital 町名

首都を変更する

/nation set taxes 値

​税金を設定する【注意！】銀行に不具合があるためお勧めしません

/nation set name 名前

国の名前を変更する

/nation set surname プレイヤー名 称号

​指定した国民に称号を与える

/nation set tag タグ

国のタグ（略称のようなもの）を設定する（最大４文字）

/nation set tag clear

国のタグを削除する

/nation toggle neutral

国を中立国にする