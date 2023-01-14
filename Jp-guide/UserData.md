## ユーザーデータの説明

**備考**

- すべてのレスポンスはJson形式で返却される。今回Jsonの説明は行わない
- ユーザー＝検索を行ったプレイヤーを指す



### ユーザーデータ

- ユーザーの情報のため、概要にはユーザーの。等という表記は行わない

| キー              | 型             | 概要                                                         |
| ----------------- | -------------- | ------------------------------------------------------------ |
| seasonId          | int            | シーズンID（プレシーズンがどう格納されるか不明）             |
| userNum           | int            | 固有ID（ゲームで管理しているユーザーID）                     |
| nickname          | string         | ニックネーム                                                 |
| gameid            | int            | 実験（試合）ID                                               |
| matchingMode      | int            | 試合モード<br/>(2:一般)<br/>(3:ランク)                       |
| matchingTeamMode  | int            | 試合モード<br/>(1:ソロ)<br/>(2:デュオ)<br/>(3:スクアッド)    |
| mmr               | int            | MMR                                                          |
| nickname          | string         | ニックネーム                                                 |
| rank              | int            | ランク                                                       |
| rankSize          | int            | 全プレイヤー内のランクの順位<br>（Total Poolがディビジョンを指しているのか全プレイヤーを指しているのかがあいまい。**今回は全プレイヤーと判断**） |
| totalGames        | long           | 合計試合数                                                   |
| totalWins         | long           | 1位で実験が終了した試合数                                    |
| totalTeamKills    | int            | 合計チームキル数（すべてのチームモード）                     |
| rankPercent       | float          | 全プレイヤー内の順位の割合**（詳細不明。要確認）**           |
| averageRank       | float          | シーズンの平均順位                                           |
| averageKills      | float          | シーズンの平均キル                                           |
| averageAssistants | float          | 試合の平均アシスト数**（変数が間違っている？との注釈あり）** |
| averageHunt       | float          | シーズンの野生動物平均討伐数                                 |
| top1              | float          | 1位で実験が終了した割合                                      |
| top2              | float          | 2位以上で実験が終了した割合                                  |
| top3              | float          | 3位以上で実験が終了した割合                                  |
| top5              | float          | 5位以上で実験が終了した割合                                  |
| top7              | float          | 7位以上で実験が終了した割合                                  |
| characterStats    | characterStats | シーズンに利用した各キャラクターの詳細スタッツ（複数存在する） |