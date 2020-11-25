# firelens-fluent-bit-newrelic

[DockerImage built on quay.io](https://quay.io/repository/palettecloud/firelens-fluent-bit-newrelic)


## Development
### リリース方法
GitHub Releases を利用しています。
以下のルールに従ってブランチ・タグ運用しています。

- PRの向き先 -> `master`ブランチ
- リリース -> `vX.Y.Z`タグ(`X`、`Y`、`Z`はそれぞれメジャー・マイナー・パッチバージョン)
- 安定版リリース -> `stable`ブランチ

リリースにはGitHub Releasesを利用しています。
リリースバージョンは、newrelic/newrelic-fluentbit-outputイメージのバージョンと同じとしています。

また、以下の形式にマッチするブランチ・タグは、quay.ioで自動ビルドが走ります。

- `master`（ビルドイメージには`latest`タグがつく）
- `stable`
- `vX.Y.Z`
