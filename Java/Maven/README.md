# このディレクトリは

Javaの例です。

# 必要なもの

- Eclipse環境(「既存のプロジェクト」の形でインポートできます)
- Apache [Maven](https://maven.apache.org/)

# 実行方法

- Eclipseでインポートした場合は、`App.java` を開いて実行
- Maven使っている人は

```
$ mvn compile
$ mvn exec:java # pom.xmlにて実行クラス名記述を入れてます
```