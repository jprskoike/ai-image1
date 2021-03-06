# 事前準備
---
### deeplearning4j
- Deep Learning for Java

  https://deeplearning4j.org/
---
### セットアップ
- Java SE 8

  https://www.oracle.com/technetwork/java/javase/downloads/index.html

- Eclipse

  https://www.eclipse.org/

### eclipse
---
#### プロジェクト作成
1. File → new → Project → Maven → Maven Project
1. Next
1. Check "Create simple project (skip archetype selection)"
1. Next
1. New Maven project
---

|項目|値|例|
|:--|:--|:--|
|Group Id|ドメイン名（逆順）|jp.jpdirect|
|Artifact Id|プロジェクト名|tus-image-learning|
|Name|プロジェクト名|tus-image-learning|

---
### pom.xml

---?code=pom.xml
@[4-8](プロジェクト作成時に入力した値)
@[12-13](GPU非搭載)
@[18-23](バージョン指定)

---?code=pom-g.xml
@[12-13](GPU搭載)

---
### Java
    1. package
    1. コード編集
    1. 簡単な言語解説
        - エントリーポイント
        - ファイル操作
        - 画像の取扱い（Graphics2D）
    1. 実行
        - eclipse上での実行
        - コマンドラインから実行
