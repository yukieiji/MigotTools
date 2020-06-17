JA
# MigotTools
MigotをコンパイルするためのカスタムSpigotTool(このフォークはコンパイルエラーを修正したものです) 

## 使い方
ライセンスの都合上、ビルドしたMigotToolsを配布はしません
要求システム:macOS/Linux, Java, Maven

1. このリポジトリをクローンします
2. `mvn clean package`を実行してMigotTool.jarをビルドします
3. ビルドしたMigotTool.jarを別フォルダに移動後`java - jar MigotTools.jar`をMigotTool.jarに実行してMigotをビルドします



EN
# MigotTools
Modification of the Spigot's build tools for compiling Migot(This fork fix compile error)

## How to use
For license reasons, I don't distribute pre-built versions. So you need to build MigotTool.jar yourself.
Requirements:macOS/Linux, Java, Maven

1. Clone this repo
2. Run `mvn clean package` command to build MigotTool.jar
3. Move the built MigotTool.jar to a separate folder and run `java - jar MigotTools.jar` command for MigotTool.jar to build Migot.
