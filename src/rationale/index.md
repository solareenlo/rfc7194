# 1. 根拠

プレーンテキスト（TCP/UDP ポート 194）または TLS/SSL で暗号化された（TCP/UDP ポート 994）[[IANALIST]](http://www.iana.org/assignments/service-names-port-numbers) IRC トラフィック用のシステムポート割り当てが存在しますが、IRC ネットワークの間では、ルートアクセスが許可または望まれないシステムでの利便性と汎用性の理由でそれらを使用しないことが一般的な慣習となっています。

IRC ネットワークは、かなり以前からプレーンテキスト接続のために TCP ポート 6667 をデフォルトでリッスンしています。これは IRCU の TCP/UDP ポート 6665-6669 の割り当てによってカバーされています。

IRC コミュニティでは、[TLS/SSL [RFC5246]](https://datatracker.ietf.org/doc/html/rfc5246) を介して暗号化された IRC 接続のために TCP ポート 6697 をリッスンすることについて、同様の合意が得られています。
