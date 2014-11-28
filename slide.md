# 出、出〜
# Mackerel課金奴〜
yokohama.pm #12 @ kayac

id:myfinder

___

# kayacさん<span style="color: red">上場</span>めでたい

___

# 自己紹介
- id:myfinder
 - まいんだー
- <span style="color: red">エム・ティー・バーン</span>株式会社
 - サーバサイド / Android

---

# 先にお知らせ

___

# MySQL Casual Talks vol.7
- <span style="color: red">12/12(金)</span>開催
- トーク/LTネタがある方はお気軽にご相談ください^^

---

# 今日話すこと
- <span style="color: red">"どオンプレ環境"</span>で作ったサービスを最近 AWS に移設しました
- 移設するにあたって、Mackerel 使い始めました
- Mackerel の Perl クライアントがなかったので書きました、育てていきたいです
- <span style="color: red">Mackerel</span> でとても捗っています

___

# 対象のサービス
## http://mtburn.jp/

___

## メディア企業の皆様
# どしどし<span style="color: red">お申込み</span>
# ください

___

## 取り急ぎ社会人としての勤めを果たした

---

# Mackerel
# 使ってますか？

---

# 実際Mackerel
# どんなもんよ
- 実際運用しているやつから

___

# グラフの<span style="color: red">連続性</span>

___

## 当初<span style="color: red">8ノード</span>で運用開始
![8nodes](images/8nodes.png)

___

## その後<span style="color: red">4ノード</span>に変更
![4nodes](images/4nodes.png)

___

## roleベースでグラフは<span style="color: red">継続</span>
![8to4nodes](images/8to4nodes.png)

___

# CloudWatch 連携

___

## 公式の手順で<span style="color: red">カジュアル</span>
![cloudwatch](images/cloudwatch.png)

___

# <span style="color: red">Norikra</span>
# to
# Mackerel

___

## <span style="color: red">fluent-plugin-(norikra|mackerel)</span>でイナフ
![norikra](images/norikra.png)

___

## <span style="color: red">分速</span>で売上/支払を見る
![growth](images/agency-media.png)

___

## ホスト登録 は
## cloud-init で
## <span style="color: red">mackerel-agent</span> を
## install すればイナフ

---

# Mackerel + Slack
![mackerel_notify](images/mackerel_notify.png)

<span style="color: red">携帯がアラートメールでうめつくされる</span>みたいなのもなくなった

___

## <span style="color: green">"デフォルトでSlack"</span>
![oranie](images/oranie.png)

___

# アラートメールに<span style="color: red">消耗</span>するのはもうやめよう

---

## WebService::Mackerel

___

- 内部のCLIツールから投稿するときとかに組み込みやすいようにCPANに上げました
 - バッチの実行時間記録とかから使ってます
- EC2の起動/停止時に自動的にMackerel側に操作を投げたり、各所でメトリクスを投げられるように継続改善したいところです


---

# まとめ

- <span style="color: red">"どオンプレ環境"</span>で作ったサービスをAWSへ移設
- 移設にあたって <span style="color: red">Mackerel</span> 使い始めました、はかどってます
- MTBurnはサーバサイド/スマートフォンのエンジニアを<span style="color: red">募集</span>してます
- <span style="color: red">MySQL Casual</span> もよろしくお願いします

---

# 質疑など?

---

# おわり
