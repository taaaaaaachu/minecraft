---
title: "使用できるコマンド"
date: 2023-05-14T20:50:48+09:00
draft: false
description: "コマンド一覧"
summary: "コマンド一覧"
---

# 使用できるコマンド

## 木こりMOD(TreeAssist)

<table>
    <table border="1">
    <tr>
        <th>コマンド</th>
        <th>説明</th>
    </tr>
    <tr>
        <td>/treeassist toggle</td>
        <td>原木の一括破壊のON/OFFを切り替える</td>
    </tr>
</table>

## 統合版ユーザー向け(Geyser-Spigot)

<table>
    <table border="1">
    <tr>
        <th>コマンド</th>
        <th>説明</th>
    </tr>
    <tr>
        <td>/geyser offhand</td>
        <td>左手にアイテムを持つ</td>
    </tr>
    <tr>
        <td>/geyser advancements</td>
        <td>Java の進歩メニューを開く</td>
    </tr>
</table>

## チェスト保護プラグイン(LWCX)

下表のコマンドを入力したあとチェスト等をクリックすることで保護を操作できます
<table>
    <table border="1">
    <tr>
        <th>コマンド</th>
        <th>説明</th>
    </tr>
    <tr>
        <td>/cremove</td>
        <td>保護解除</td>
    </tr>
    <tr>
        <td>/cpublic</td>
        <td>誰でも開けれるようにする（追加で保護をかけることはできない）</td>
    </tr>
    <tr>
        <td>/cprivate</td>
        <td>自分だけが開けれるようにする（他のユーザーを追加することもできます）</td>
    </tr>
    <tr>
        <td>/cpassword</td>
        <td>パスワードで保護をする</td>
    </tr>
    <tr>
        <td>/cdonation</td>
        <td>入れられるが出せなくする（自分以外）</td>
    </tr>
    <tr>
        <td>/cdisplay</td>
        <td>見れるが取り出せないし入れられなくする</td>
    </tr>
    <tr>
        <td>/cinfo</td>
        <td>保護に関する情報を表示する</td>
    </tr>
    <tr>
        <td>/cmodify　<ユーザー1> <ユーザー2>...</td>
        <td>既存の保護にユーザーを追加する</td>
    </tr>
    <tr>
        <td>/cmodify　-<ユーザー1> -<ユーザー2>...</td>
        <td>既存の保護からユーザーを削除</td>
    </tr>
</table>

その他詳しい情報は[公式wiki](https://github.com/pop4959/LWCX/wiki)を参照してください

## 経済系プラグイン(Jecon)
<table>
    <table border="1">
    <tr>
        <th>コマンド</th>
        <th>説明</th>
    </tr>
    <tr>
        <td>/money</td>
        <td>自分の所持金を表示します</td>
    </tr>
    <tr>
        <td>/money pay <プレイヤー> <金額></td>
        <td>プレイヤーに指定した金額を送金します</td>
    </tr>
</table>

## チェストショッププラグイン(QuickShop)
### 使い方

売りたいものを手に持った状態で左クリックをすると売りたい金額を聞かれます
![001](https://github.com/taaaaaaachu/taaaaaaachu.github.io/blob/main/static/images/chestshop01.png?raw=true)
チャット欄に金額を入力します（　/　は不要です）
![002](https://github.com/taaaaaaachu/taaaaaaachu.github.io/blob/main/static/images/chestshop02.png?raw=true)
ショップが作成されます  
売りたいアイテムをチェストの中に入れておくと売買できます  
右クリックでショップのオプションを変更できます。  
売り、買いの変更もここです  
チャット欄をクリックして変更できます。
![003](https://github.com/taaaaaaachu/taaaaaaachu.github.io/blob/main/static/images/chestshop03.png?raw=true)

### コマンド

<table>
    <table border="1">
    <tr>
        <th>コマンド</th>
        <th>説明</th>
    </tr>
    <tr>
        <td>/qs buy</td>
        <td>アイテムを購入するショップに変更します。</td>
    </tr>
    <tr>
        <td>/qs sell</td>
        <td>アイテムを販売するショップに変更します。</td>
    </tr>
    <tr>
        <td>/qsprice <price></td>
        <td>アイテムの買値/売値を変更します。</td>
    </tr>
    <tr>
        <td>/qs create <price> [item]</td>
        <td>手持ちのアイテムまたは指定したアイテムを使用してショップを作成するコマンド</td>
    </tr>
</table>

その他詳しい情報は[公式サイト](https://www.spigotmc.org/resources/quickshop-reremake-1-19-ready-multi-currency.62575/)を参照してください

## home系コマンド  

<table>
    <table border="1">
    <tr>
        <th>コマンド</th>
        <th>説明</th>
    </tr>
    <tr>
        <td>/sethome</td>
        <td>ホームを指定します</td>
    </tr>
    <tr>
        <td>/home</td>
        <td>指定したホームにテレポートします</td>
    </tr>
    <tr>
        <td>/delhome</td>
        <td>ホームを削除します</td>
    </tr>
    <tr>
        <td>/home bed</td>
        <td>最後に寝たベッドにテレポートします</td>
    </tr>
</table>

## jobコマンド(jobs reborn)  

<table>
    <table border="1">
    <tr>
        <th>コマンド</th>
        <th>説明</th>
    </tr>
    <tr>
        <td>/jobs join</td>
        <td>ジョブに就くためのGUIを表示します</td>
    </tr>
    <tr>
        <td>/jobs join [jobName]</td>
        <td>jobに就きます</td>
    </tr>
    <tr>
        <td>/jobs leave [jobName]</td>
        <td>jobを辞めます</td>
    </tr>
    <tr>
        <td>/jobs shop</td>
        <td>ジョブショップを表示します</td>
    </tr>
</table>
<table>
    <table border="1">
    <tr>
        <th>ジョブ一覧</th>
    </tr>
    <tr>
        <td>brewer</td>
    </tr>
    <tr>
        <td>builder</td>
    </tr>
    <tr>
        <td>crafter</td>
    </tr>
    <tr>
        <td>digger</td>
    </tr>
    <tr>
        <td>enchanter</td>
    </tr>
    <tr>
        <td>explorer</td>
    </tr>
    <tr>
        <td>farmer</td>
    </tr>
    <tr>
        <td>fisherman</td>
    </tr>
    <tr>
        <td>hunter</td>
    </tr>
    <tr>
        <td>miner</td>
    </tr>
    <tr>
        <td>weaponsmith</td>
    </tr>
    <tr>
        <td>woodcutter</td>
    </tr>
    <tr>
</table>