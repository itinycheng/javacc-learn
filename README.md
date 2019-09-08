# javacc-learn

- javacc demo &amp; practice
- mac: use `command + d` to indicate the end of file (`<EOF>`).

# ENV

- Jdk8
- Maven 3.6.1

# Usage

- set up `<include>**/??.jj</include>` in pom.xml; 
- run `mvn clean compile` to generate java code;

 

# TOKEN

`< Id: ["a"-"z","A"-"Z"] ( ["a"-"z","A"-"Z","0"-"9"] )* >` 第一个字符匹配`英文字母`，然后匹配0～n个`字母/数字`；

# BNF 