## 試合データ

※ユーザーデータと同名及び同じ内容のものは対象外とする※

| キー                      | 型                     | 概要                                                         |
| ------------------------- | ---------------------- | ------------------------------------------------------------ |
| charaqcterNum             | int                    | キャラクターID                                               |
| skinCode                  | int                    | スキンID                                                     |
| characterLevel            | int                    | 実験終了時のキャラクターレベル                               |
| gameRank                  | int                    | 順位                                                         |
| playerKill                | int                    | キル数                                                       |
| playerAssistant           | int                    | アシスト数                                                   |
| monsterKill               | int                    | 野生動物討伐数                                               |
| bestWeapon                | int                    | 最高熟練度に到達した武器ID                                   |
| bestWeaponLevel           | int                    | 討伐/生存時の最高熟練度                                      |
| masteryLevel              | <int,int>              | 各武器IDと対応した熟練度辞書                                 |
| equipment                 | <int,int>              | 討伐/生存時の装備部位IDと対応した装備ID辞書                  |
| versionMajor              | int                    | パッチのメジャーバージョン                                   |
| versionMinor              | int                    | パッチのマイナーバージョン                                   |
| language                  | string                 | （おそらく）利用ユーザーの設定言語                           |
| skillLevelInfo            | <int,int>              | 各スキルのレベルアップ履歴辞書                               |
| skillOrderInfo            | <int,int>              | スキルオーダーの詳細辞書                                     |
| serverName                | string                 | サーバー名                                                   |
| maxHp                     | int                    | 最大HP                                                       |
| maxSp                     | int                    | 最大スタミナ                                                 |
| attackPower               | int                    | 攻撃力（AD）                                                 |
| moveSpeed                 | float                  | 移動速度                                                     |
| defence                   | int                    | 防御力                                                       |
| hpRegen                   | float                  | HP自動回復量                                                 |
| spRegen                   | float                  | スタミナ自動回復量                                           |
| attackSpeed               | float                  | 基本攻撃速度                                                 |
| criticalStrikeChance      | float                  | 致命打確率                                                   |
| criticalStrikeDamage      | float                  | 致命打ダメージ増加割合                                       |
| coolDownReduction         | float                  | スキルCD                                                     |
| lifeSteal                 | float                  | 吸血割合                                                     |
| normalLifeSteal           | float                  | **※現在未提供※**基本攻撃の吸血割合                           |
| skillLifeSteal            | float                  | **※現在未提供※**スキルダメージの吸血割合                     |
| amplifierToMonster        | float                  | 野生動物への与ダメージ                                       |
| trapDamage                | float                  | トラップによる与ダメージ                                     |
| gainExp                   | int                    | ユーザーレベルへの付与経験値                                 |
| startDtm                  | DateTime<br>(日付情報) | 実験の開始時刻（サーバー時間）                               |
| duration                  | int                    | 試合終了時のサーバー時間（フレーム単位）                     |
| mmrBefore                 | int                    | 試合開始前のMMR                                              |
| mmrGain                   | int                    | MMRの増減値                                                  |
| mmrAfter                  | int                    | 試合終了時点のMMR                                            |
| playTime                  | int                    | ユーザーの生存秒数                                           |
| watchTime                 | int                    | ユーザーの観戦秒数                                           |
| totalTime                 | int                    | 生存秒数と観戦秒数の合計時間                                 |
| bptAdded                  | int                    | 試合に追加したBot（AI）の数                                  |
| botRemain                 | int                    | ユーザーの試合終了時に生存していたBot（AI）の数              |
| restrictedAreaAccelerated | int                    | 禁止区域加速回数                                             |
| safeArea                  | int                    | 実験終了時のセーフエリア数                                   |
| teamNumber                | int                    | ユーザーのチーム番号                                         |
| preMade                   | int                    | プリメイドの人数。マッチ後に入ったチームメイトは含まない     |
| eventMissionResult        | <int,int>              | イベントミッションIDと目標数の辞書                           |
| victory                   | int                    | 勝利か否か（bool）                                           |
| craftUncommon             | int                    | 高級アイテムの作成数                                         |
| craftRare                 | int                    | 貴重アイテムの作成数                                         |
| craftEpic                 | int                    | 英雄アイテムの作成数                                         |
| craftLegend               | int                    | 伝説アイテムの作成数                                         |
| damageToPlayer            | int                    | 対実験体へのダメージ                                         |
| damageToPlayer_trap       | int                    | 対実験体へのトラップダメージ                                 |
| damageToPlayer_skill      | int                    | 対実験体へのスキルダメージ                                   |
| damageToPlayer_itemSkill  | int                    | 対実験体へのアイテムスキルダメージ                           |
| damageToPlayer_direct     | int                    | 対実験体への基本攻撃ダメージ                                 |
| damageToMonster           | int                    | 野生動物へのダメージ                                         |
| damageToMonster_trap      | int                    | 野生動物へのトラップダメージ                                 |
| damegeToMonster_normal    | int                    | 野生動物へのノーマルダメージ？**（詳細不明。要確認）**       |
| damageToMonster_skill     | int                    | 野生動物へのスキルダメージ                                   |
| damageToMonster_itemSkill | int                    | 野生動物へのアイテムスキルダメージ                           |
| damageToMonster_direct    | int                    | 野生動物への基本攻撃ダメージ                                 |
| killMonsters              | <int, int>             | 野生動物IDと倒した対数の辞書                                 |
| healAmount                | int                    | 自分の回復量                                                 |
| teamRecover               | int                    | 自分以外の味方の回復量                                       |
| protectAbsorb             | int                    | シールドによるダメージ軽減量                                 |
| addSurveillanceCamera     | int                    | 設置した監視カメラの数                                       |
| addTelephotoCamera        | int                    | 設置した望遠カメラの数（ナタポンの偽装カメラを含む）         |
| removeSurveillanceCamera  | int                    | 破壊した監視カメラの数                                       |
| removeTelephotoCamera     | int                    | 破壊した望遠カメラの数（ナタポンの偽装カメラを含む）         |
| useHyperLoop              | int                    | 利用したハイパーループの回数                                 |
| useSecurityConsole        | int                    | 利用した保安コンソールの回数                                 |
| giveUp                    | int                    | ギブアップしたか（bool）                                     |
| teamSpector               | int                    | チーム内の観戦者数                                           |
| routedOfStart             | int                    | 実験開始時のルートID                                         |
| routeSlotId               | int                    | 選択されているルートID                                       |
| placeOfStart              | int                    | 試合開始時の選択したエリアID                                 |
| mmrAvg                    | int                    | チームのMMR平均                                              |
| teamKill                  | int                    | チームでのキル数                                             |
| accountLevel              | int                    | ユーザーレベル                                               |
| killerUserNum             | int                    | 自分を処置したユーザーID                                     |
| killer                    | string                 | 処置された対象（その他、キラー欄参照）                       |
| killDetail                | string                 | 処置原因。時間による処置の場合はエリア名                     |
| killerCharacter           | string                 | 処置をされたキャラクター。チームモードの場合は代表が入る。   |
| killerWeapon              | string                 | 処置をされた武器。チームモードの場合は代表が入る。           |
| causeOfDeath              | string                 | 処置原因のスキルやオブジェクト名                             |
| placeOfDeath              | string                 | 処置をされたエリアID(もしかしたらintかもしれない)            |
| fishingCount              | int                    | 釣りをした回数                                               |
| useEmotionCount           | int                    | エモートを行った回数                                         |
| traitFirstCore            | int                    | 特性のメイン                                                 |
| traitFurstSub             | int[2]                 | メイン特性の選択要素2つ                                      |
| traitSecoundSub           | int[2]                 | サブ特性の選択要素2つ                                        |
| TotalVFCredit             | int[20]                | 獲得したクレジット数。配列内で1分ごとの獲得量                |
| CreditSource              | <string, int>          | クレジットの取得要因と回数？クレジット数？**（詳細不明。要確認）** |
| UsedVFCredit              | int[20]                | 利用したクレジット数。配列内で1分ごとの利用量                |
| CraftMythic               | int                    | 作成された神話アイテム数                                     |
| PlayerDeaths              | int                    | プレイヤーの脂肪回数                                         |
| KillGamma                 | bool                   | ガンマのキル数                                               |
| KillDetails               | <int, int>             | 自分が処置した実験体と回数の辞書？                           |
| DeathDetails              | <int, int>             | 自分を処置した実験体と回数の辞書？                           |
| CCTimeToPlayer            | float                  | 相手に与えたCCの時間                                         |
| foodCraftCount            | <int, int>             | 作成した食事の等級と回数の辞書                               |
| bevarageCraftCount        | <int, int>             | 作成した飲物の等級と回数の辞書                               |
| airSupplyOpenCount        | <int, int>             | 開封した航空支援物資の等級と回数の辞書                       |
| escapeState               | int                    | 脱出場に行った際の結果Z<br>1: 2以外の理由で脱出失敗<br>2: 脱出所で敵にキルされて脱出失敗<br>3:  脱出成功 |
| collectItemForLog         | int[]                  | 配列[採取素材ポイント[ID] を利用した回数                     |
| collectFirstItemForLog    | <int, int[]>           | 装備位置IDと装備しているアイテムコードの辞書<br>アイテムコードは最高レアリティで更新されていく |
| totalDoubleKill           | int                    | 合計ダブルキルの回数                                         |
| totalTriplKill            | itn                    | 合計トリプルキルの回数                                       |
| totalQuadraKill           | int                    | 合計クアドラキルの回数                                       |
| totalExtraKill            | int                    | 合計5キル以上の連続キルを行った回数                          |



## 

### ルミア島限定

| キー                   | 型    | 概要                                           |
| ---------------------- | ----- | ---------------------------------------------- |
| ItemTransferredConsole | int[] | コンソールを利用して取り寄せたアイテムのコード |
| ItemTransferredDrone   | int[] | ドローンを利用して取り寄せたアイテムのコード   |



### コバルトモード限定

| キー                     | 型        | 概要                                                         |
| ------------------------ | --------- | ------------------------------------------------------------ |
| TotalTurbineTakeover     | int       | 増幅装置を占領した回数                                       |
| StartingItems            | int[7]    | プレイヤーが最初に取得したアイテムセット（アイテムのIDが入る）<br/>一部例外で7アイテム入ることが発生する。 |
| UsedNormalHealPack       | int       | 通常のヒールパックを取得した回数                             |
| UsedReinforcedHealPack   | int       | 強化されたヒールパックを取得した回数                         |
| UsedNormalShieldPack     | int       | 通常のシールドパックを取得した回数                           |
| UsedReinforcedShieldPack | int       | 強化されたシールドパックを取得した回数                       |
| BoughtInfusion           | <int,int> | インフュージョンのIDと購入したクレジットの辞書<br/ >**<InfusionProductCode , amount>** |
| FinalInfusion            | int[3]    | 最終インフュージョンの配列                                   |
| ScoredPoint              | int[20]   | 自分が獲得したスコア。1分ごとのスコア数で配列とて格納されている |
| KillsPhaseOne            | int       | フェーズ1で処置をした回数                                    |
| KillsPhaseTwo            | int       | フェーズ2で処置をした回数                                    |
| KillsPhaseThree          | int       | フェーズ3で処置をした回数                                    |
| DeathsPhaseOne           | int       | フェーズ1で処置された回数                                    |
| DeathsPhaseTwo           | int       | フェーズ2で処置された回数                                    |
| DeathsPhaseThree         | int       | フェーズ3で処置された回数                                    |
| afk                      | bool      | コバルトプロトコルでのAFK（Away From KEyboard）の判定        |

