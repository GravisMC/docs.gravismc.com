---
title: Towny
icon: /static/mine.webp
date: 2023-08-12
description: GravisMCのドキュメント
order: 100
---
# Towny (/towny)コマンド

コマンド | 説明
---    | ---
/towny | 基本的なタウンコマンドを表示します。
/towny ？| さらに詳しいタウンコマンドを表示します。
/towny allowedblocks | どのブロックの設置/破壊が許可されているかを確認できるメニューを表示する。
/towny map| 周辺のマップを表示する。
/towny prices | 町の運営にかかる税金や費用を表示します。
/towny time | 税金の徴収や街の維持費の支払いまでの時間を表示します。
/towny top residents all | 国や町の住民数ランキングを表示します。
/towny top top residents town | 全ての町の住民数ランキングを表示する。
/towny top residents nation | 全ての国の住民数ランキングを表示する。
/towny top land all | 自分がオーナーとなっている町や国の土地数ランキングを表示する。
/towny top land town | 自分がオーナーとなっている町の土地数ランキングを表示する。
/towny top land resident | 自分がオーナーとなっている住民の土地数ランキングを表示する。

# Town (/town)コマンド

コマンド | 説明
---    | ---
/town| 自分の町の情報を表示します。
/town ? | 使用可能な /town コマンドを表示します。
/town 街の名前 | 指定した町の情報を表示します。
/town here | 自分が立っている町の情報を表示します。
/town new 町の名前 | 新しい町を作ります。
/town claim | 今立っている土地を町の土地にします。(16×16)
/town claim auto | 自動で周囲の土地を購入します。(町の銀行にお金がある場合のみ)
/town claim outpost | 今立っている土地をアウトポストに設定します。
/town unclaim | 土地を手放します。
/town deposit 金額 | 町の銀行にお金を追加します。
/town deposit all | 所持金を全て銀行に追加する。
/town deposit 金額 町の名前 | 指定した町の銀行にお金を追加します。
/town withdraw 金額 | 町の銀行からお金を引き出します。
/town withdraw all | 町の銀行からお金を全額引き出します。
/town bankhistory | 町の銀行の履歴を表示します。
/town leave | 町から抜けます。
 add ユーザーネーム | 町へプレイヤーを招待します(市長のみ)/accept (承諾) /deny (拒否)
/town kick ユーザーネーム | 町からプレイヤーをキックします(市長のみ)
/town invite | あなたの街への招待状を受け取ったプレイヤーのリストを表示します。
/town spawn | 町のスポーン地点にテレポートします。
/town outpost 数字 | 指定したアウトポストにテレポートします(アウトポストに設定した順番で数字が割り当てられる)
/town set spawn | 自分がいる場所を町のスポーン地点に設定する。(ホームブロックの中のみ)
/town spawn 町の名前 | 指定した町のスポーン地点にテレポートする。(パブリックのみ)
/town list | 町の一覧を表示します。
/town online | 自分の町のオンラインプレイヤーを表示します。
/town plots 町の名前 | 町が所有する土地とその種類/収益の役立つリストを表示します。
/town baltop | 指定した町の最も裕福なプレイヤーを表示します。
/town allylist 町の名前 | タウンの同盟者のリストを表示します。
/town enemylist | 町の敵のリストを表示します。
/town merge 町の名前 | 指定した町と自分の町を合併します。
/town outlawlist 町の名前 | 町の無法者のリストを表示します。
/town outlaw add/remove ユーザーネーム | 町の無法者リストに無法者を追加または削除します
/town plotgrouplist 町の名前 page 数字 | 販売と価格が示された町の区画グループをリストします。
/town purge 日数 | 指定された日数活動しなかった住民を町から追い出し、npc と市長を免除します。
/town ranklist 町の名前 | 住民とその階級を表示します。別の町の階級リストを表示するためのオプションの町名も表示します。
/town rank add/remove ユーザーネーム ランク名 | 町の住人にランクを付与または削除します。
/town reclaim | 居住者が荒廃した町を取り戻すことができます。
/town reslist 町の名前 | 町の全住民の完全なリストを表示します。
/town say メッセージ | オンライの住人にメッセージを送信します。
/town set board メッセージ | ログイン時に住民に表示されるメッセージを設定します。
/town set none | ログイン時や /town ステータス画面には表示されない空のボードを設定します。
/town set mayor 住民の名前 | 別の住民に市長の地位を与える。(市長のみ)
/town set homeblock | あなたの町のホームブロックとスポーンを設定します。
/town set mapcolor 色 |  dynmap に表示される町のマップカラーを設定します。
/town set neme | 町の名前を変更します。
/town set outpost | アウトポストのスポーンポイントをプレイヤーの位置にリセットします。（アウトポストで使用する必要があります。）
/town set taxes 金額 | 各居住者から毎日徴収される税金を設定します。（Taxpercent がオンになっている場合は、パーセンテージも設定します。）
/town set taxpercentcap 金額 | Taxpercent が有効な場合に取得できる最大金額。
/town set plottax 金額 | 各居住者が所有する区画ごとに、毎日徴収される税金を設定します。
/town set plotprice 金額 |  町のデフォルトの土地のコストを設定します。
/town set shopprice 金額 | 町のショッププロットのデフォルトのコストを設定します
/town set shoptax 金額 | 各居住者が所有する店舗敷地ごとに、毎日各居住者から徴収する税金を設定します。
/town set embassyprice 金額 | 町の大使館敷地のデフォルトのコストを設定します。
/town set embassytax 金額 | 各居住者が所有する大使館敷地ごとに、毎日各居住者から徴収する税金を設定します。
/town set title ユーザーネーム タイトル | 町のメンバーに称号を追加します。(市長のみ)
/town set primaryjail |  あなたの町の主要な刑務所を設定します。
/town toggle explosion | 街中の爆発をオン/オフを切り替えます。
/town toggle fire | 街中の延焼のオン/オフを切り替えます。
/town toggle mobs | 街中の敵対的なMobのスポーンをオン/オフを切り替えます。
/town toggle public | スポーンと街のホームブロックの位置を公開のオン/オフを切り替えます。
/town toggle pvp | 街中でのPVPのオン/オフを切り替えます。(使用不可)

