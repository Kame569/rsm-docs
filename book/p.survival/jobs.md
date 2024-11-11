---
description: 仕事に就職したり、その職業ごとのクエストを行ったりすることができます。
---

# Jobs

### Jobsの利用目的

経済システムの活性化。ショップ等を用いた経済を回すための前提プラグインです。\
是非職業に就いてたくさんMoneyをゲットしよう！

{% hint style="danger" %}
2024/11/16 22:00\~のメンテナンスでJobsの取得可能なお金が制限されます。\
今のうちに取得しましょう！
{% endhint %}



### コマンド一覧



#### グローバルトップ、トップ

| 名前                 | 説明                                |
| ------------------ | --------------------------------- |
| /jobs gtop/top     | グローバルトップリストをスコアボードまたはチャットに表示します。  |
| /jobs gtop/top {2} | 指定されたページ({2})からグローバルトップリストを表示します。 |

#### 情報

| 名前                         | 説明                                 |
| -------------------------- | ---------------------------------- |
| /jobs info `jobName`       | 指定された仕事に関する情報を表示します。               |
| /jobs info `jobName` 2     | 2ページ目から指定された仕事に関する情報を表示します。        |
| /jobs info `jobName` place | 指定されたアクションタイプで指定された仕事に関する情報を表示します。 |

#### 参加

| 名前                                       | 説明                 |
| ---------------------------------------- | ------------------ |
| /jobs join `jobName`                     | 指定された仕事に参加します。     |
| /jobs join `jobName` `-needConfirmation` | 確認して指定された仕事に参加します。 |

#### クエスト

| 名前                        | 説明                             |
| ------------------------- | ------------------------------ |
| /jobs quests              | プレイヤーが利用できるクエストを表示します。         |
| /jobs quests `playerName` | 指定されたプレイヤーに関する利用可能なクエストを表示します。 |
| /jobs quests next         | リセットして新しいクエストリストを取得します。        |

#### その他のコマンド

| 名前                                                     | 説明                                      |
| ------------------------------------------------------ | --------------------------------------- |
| /jobs archive                                          | プレイヤーのアーカイブされた仕事リストを表示します。              |
| /jobs blockinfo                                        | プレイヤーが見ているブロックの情報を表示します。                |
| /jobs bonus `jobName`                                  | 指定された仕事で現在利用可能なボーナスを表示します。              |
| /jobs bp `-a`                                          | プレイヤーの周囲10半径以内のすべてのブロック保護を表示します。        |
| /jobs browse                                           | 利用可能なすべての仕事をGUIまたはチャットに表示します。           |
| /jobs browse `-p:3`                                    | 3ページ目から利用可能な仕事をチャットに表示します。              |
| /jobs browse `-j:jobName`                              | 指定された仕事をチャットに表示します。                     |
| /jobs clearownership                                   | プレイヤーのすべての登録済み所有権 (かまど、醸造台など) をクリアします。  |
| /jobs clearownership `playerName`                      | 指定されたプレイヤーの登録済み所有権 (かまど、醸造台など) をクリアします。 |
| /jobs convert                                          | 現在のデータベースを新しいデータベースに変換します。              |
| /jobs demote `playerName` `jobName` `level`            | 指定されたプレイヤーの仕事のレベルを新しいレベルに降格させます。        |
| /jobs employ `playerName` `jobName`                    | 指定された仕事に指定されたプレイヤーを雇用します。               |
| /jobs entitylist                                       | 既知の生きているスポーン可能なエンティティをすべて一覧表示します。       |
| /jobs explored                                         | 特定のチャンクで探索されたすべてのチャンクプレイヤーを表示します。       |
| /jobs fire `jobName` `playerName`                      | 指定された仕事から指定されたプレイヤーを解雇します。              |
| /jobs fireall all                                      | すべてのプレイヤーをすべての仕事から解雇します。                |
| /jobs fireall `playerName`                             | 指定されたプレイヤーをすべての仕事から解雇します。               |
| /jobs give `playerName` `jobName` `items/limiteditems` | 指定されたプレイヤーに制限付きアイテムを与えます。               |
| /jobs glog                                             | すべての仕事のログをグローバルに表示します。                  |
| /jobs grantxp `playerName` `jobName` 3.4               | 指定されたプレイヤーに指定された仕事に対して3.4の経験値を与えます。     |
| /jobs itembonus                                        | プレイヤーが現在持っているアイテムボーナスを、防具の内容を含めて表示します。  |
| /jobs iteminfo                                         | プレイヤーが現在持っているアイテムの情報を表示します。             |
| /jobs leave `jobName`                                  | 指定された仕事を辞めます。                           |
| /jobs leaveall                                         |                                         |