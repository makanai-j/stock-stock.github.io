# 操作説明

## 取引データ追加

一番右のアイコン

![inputicon](./inputicon.png)

追加方法は、キーボード入力と CSV ファイルの 2 つあります。

#### 入力で

##### 入力項目

- 日付
- 銘柄コード
- 取引区分
- 株数
- 値段
- 手数料
- 税金
- 口座

##### 新規追加

- 一番下の新規追加ボタン押下

##### コピーして追加

同じ取引情報を何度も入力することをさけるため、同一情報でレコードを追加するためのものです。

- レコード一番左のプラスアイコン押下

  ![コピー追加](./copyplusicon.png)

##### グループ追加

SOR 取引などで一度の取引が異なる値段で約定された際に、一つの取引として保存したい場に使用してください。

- レコード左から 2 番目の G アイコンを押下

  ![グループに追加](./groupplusicon.png)

> ##### 補足
>
> 平均約定単価で追加されます
> {: .block-tip }

#### CSV ファイルで

- 保存ボタン右の CSV ボタンを押下

  ![csv追加](./csvbutton.png)

> ##### 注意
>
> SBI 証券の CSV ファイルのみ読み込みできます。
> また、SBI 証券の CSV ファイルは日付情報のみで、時間情報がないので、正確な日時で追加したい場合は、csv ファイルを編集するか、キーボード入力していただく必要があります。
> {: .block-warning }

> ##### 補足
>
> SBI 証券 CSV ファイル出力
> [ホームページ](https://www.sbisec.co.jp/ETGate/WPLETmgR001Control?OutSide=on&getFlg=on&burl=search_home&cat1=home&cat2=service&dir=service&file=home_kakutei_rei.html) > [HYPER SBI 2](https://search.sbisec.co.jp/v2/popwin/guide/tool/hyper_sbi_2/05_trading/ck_orderstatus.html#a14)
> {: .block-tip }

## 履歴確認

右から 2 番目のアイコン

![historyicon](./historyicon.png)

日付選択は年月のみになります。

> ##### 注意
>
> インターネット接続されていない場合はチャート情報が表示されません。
> {: .block-warning }

## 損益確認

右から 3 番目のアイコン

![profitandlossicon](./pnlicon.png)

### 間隔種別とその表示期間

| 間隔 | 表示期間 |
| ---- | -------- |
| 日   | 1 か月   |
| 週   | 3 か月   |
| 月   | 1 年     |
| 年   | 全期間   |

### グラフについて

#### 円グラフ

- 33 業種で分けた取引回数
- ロング(利益と損失)とショート(利益と損失)の割合

#### 散布図

- 時間(x)と損益(y)の関係

#### 折れ線グラフ

- 選択された日付以前の取引も含めた損益

#### 棒グラフ

- 選択された間隔内での損益
