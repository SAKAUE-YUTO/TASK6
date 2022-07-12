# TASK6

# CloudTrailのログ
- PutMetricAlarm　（アラームの更新・作成など）
主な情報　リソースタイプはもちろんのこと、ユーザーからAZ・IAMのUSERなど。アクセスキーやarnまであった。何を監視しているかなどもあり、ログとしては最大限の情報が含まれていると感じた。

- LookupEvents （イベント閲覧）
誰が何時何分にどのCloudTrailのログ操作（true切り替えなど）をやっているかわかるのはすごい。自分が管理者だからここまで見れるのかと思う。

- DescribeDBInstances (RDS関連)
だれが終了させたなどはわかるようになっている。そもそも停止できる権限を持っているUSERしかできないので、どのUSERかさえわかればそれほど情報はいらないと思う。
最低限の時間とうはあるので、これだけあれば十分かなとは思った。

# CloudWatch アラーム

- メトリクス
![bandicam 2022-07-12 15-19-33-001](https://user-images.githubusercontent.com/105532255/178441651-832812ef-d0cc-47cd-8cf1-ea0ea91d8f10.jpg)

- メール
![bandicam 2022-07-12 15-20-06-273](https://user-images.githubusercontent.com/105532255/178441733-66a69116-1aaf-4182-bf4c-c8a4dc982b32.jpg)


# 見積
[AWS Pricing Calculator.pdf](https://github.com/SAKAUE-YUTO/TASK6/files/9090905/AWS.Pricing.Calculator.pdf)
