# RegexBuilder New!

在原开源项目 https://github.com/ScottLouvau/RegexBuilder 的基础上。增加：
1. 生成的代码前一行增加注释，如果需要调整正则表达式可以从注释复制出来修改。
2. C#代码增加生成静态字段的形式：“static private Regex expression = new Regex("R(?[eg]+)x", RegexOptions.Compiled);”。
3. 增加软件图标。

# RegexBuilder

RegexBuilder helps you write, debug, and test regular expressions using the .NET syntax.
 - Use the menus to help construct expressions.
 - Run all or part of the expression on your source text quickly.
 - See matches, groups, and captures in a tree to see how it matches.
 - Supports an Xml file format so you can have other tools output files for quick diagnosis in RegexBuilder.
 
 I used RegexBuilder to help me build and debug expressions used in Visual Studio editor automated tests. Test failures due to a regex failing to match would automatically write an Xml file which RegexBuilder could import for diagnosis.
