Update PPT(MediaListing)


メディア掲載履歴　ppt更新フロー
=====

各URL
-----
### 文中における「スプレッドシート」
https://docs.google.com/spreadsheets/d/1RnrH7jl5RtkZ0ZHYhi6AtEO3fv0AIw8dlV3wXbZDQ6w/edit?usp=sharing

### 対象となるPPTファイルは以下のURL
https://drive.google.com/folderview?id=0B0AS-SdlYet9dzFjdkFIMFRoeDg&usp=sharing_eid&invite=CO7kp7YP&ts=560a2693&tid=0B_eOr_9ixl6VRHY0elBkME04WWM#list

登場人物
-----

1. キャプチャ役（クラウド参与orインターンを想定）
2. パワーポイント反映役（現状では波多野さん。今後クラウド参与者）
3. レビュアー（波多野さん）


フロー内容
-----
### （＊0）前提
#### 専任
本更新監視のために、以下の役割をそれぞれ専任する
- キャプチャ役を一人
- パワーポイント反映役を一人

#### Slackで通知する場合
以降の文中にて「Slackで通知」とある場合は、Basecamp上の該当URLが併記されるものとする。

### （＊1）監視
キャプチャ役はsecualのメディア掲載履歴を監視する。

#### 方法
監視方法は以下の通り。
- google アラート、もしくはgoogle検索での過去記事検索
- 前回更新日以降の
  - HP
  - Twitter
  - facebook  
の投稿を一通り確認
- Slack上でのやりとり
  （特に青柳さん・西田さん・波多野さんからの発言に含まれる可能性が高い）

#### 頻度
監視頻度は
- 週に1回
- 月曜～金曜日のいずれか作業可能な1日

とする。

#### メディア掲載がなかった場合
- 上記監視を行いメディア掲載がなかった場合、「ｘｘ日に監視を行いましたが、掲載履歴はありませんでした」という旨の内容を報告すること。
- 報告は
  - Slackにて
  - レビュアーとパワーポイント反映役へのメンションつき
で行う。

### （＊2）記述
メディア掲載履歴が見つかった場合、キャプチャ役はgoogleスプレッドシートに以下6つの内容を記述する。

1. 調査日
2. 媒体名
3. 掲載内容要約（2行程度）
4. 掲載日
5. スクリーンショット2枚、掲載メディアのロゴ画像
6. 記事URL

なお、上記「メディア掲載履歴」には、プレスリリースの転載のみの記事は含まないものとする。

#### 判断が難しいとき
掲載内容について判断が難しいものは

- その旨シートに記載
- （＊３）の段階でその旨Slackで報告
- レビュアーの判断を仰ぐ

#### 画像
このうち、
- スクリーンショット2枚
- メディアのロゴ画像

については、以下のようにする。

1. googleドライブ上に画像を展開
2. スプレッドシートにはそのURLを記述

#### 作業時間
監視作業開始からここまでの工程は、1～2時間程度と想定する。

（注：将来、掲載が多数行われるなど、週1回で足りない場合は監視頻度を増やす。
また、想定を超える掲載量・作業時間となった場合、フロー全体の見直しが必要。）

### （＊3）パワーポイント 反映役への報告
キャプチャ役は上記6つの内容を全て記述し終えた段階で、パワーポイント反映役にSlackを通じて通知・アサイン変更を行

う。

### （＊4）パワーポイント反映
- パワーポイント反映役は上記内容に基づき、パワーポイントへの反映・アップロードを行う。
- このとき、既存のバージョンに上書きせず、新しいバージョンとして保存すること。
  - ファイル名：Secual_販促活動レポート_v00.pptx
  - 00の部分がバージョン名となる。
- 終了後はレビュアーにSlackにて通知・アサイン変更を行う。


### （＊5）レビュー
レビュアーは以下の作業を行う。

1. パワーポイントを確認
2. 問題なければtodoをクローズ
3. 問題あった場合、その旨を指摘


Basecampのフローについて
-----
以下のフローをタスクが横断する。

0. INBOX(untouched)
1. Monitoring media listing
2. Spread-sheet edit
3. ppt edit
4. review

### 0. INBOX(untouched)
着手前には0.INBOX(untouched)にtodoが置かれている。

### 1. Monitoring media listing 
キャプチャ役は作業開始前に 1.Monitoring media listing に todo を移動してから作業を開始する。

### 2. Spread-sheet edit
(＊1）までの監視作業が終われば、以下の処理を行う。
- 2.Spread-sheet edit にtodoを移動
- その後、スプレッドシートを更新
- もし、(＊1）においてメディアの更新がなければ
  - その旨todoに記述
  - Slackにて報告
  - 該当todoをクローズ

### 3. ppt edit
更新作業（＊2）が終われば、以下の処理を行う。
- 3.ppt editにtodoを移動
- 報告・アサイン変更を行う（＊3）
- このとき、報告と共に、必ずアサインをパワーポイント反映役に変更すること
- 報告とアサインの変更は2つで1つの作業とする。

#### 期限
この報告は、基本的に（＝やむなく延期される理由のない限り）、キャプチャ役が監視作業を行った次の日の12:00までに行わ

れるものとする。

### 4. review
パワーポイント反映役は（＊4）のパワーポイント更新後、以下の処理を行う。
- 該当todoを4.reviewに移動
- このとき、上記同様、必ずアサインをレビュアーに変更すること

#### レビュアー
レビュアーは、
- パワーポイントを確認
- 問題があればその旨を記述して0.INBOX(untouched)にtodoを戻す
- 問題がなければ todo を完了する。（＊5）
    