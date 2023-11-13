# code-style
> 代码风格, 在整个项目中保持一致的代码风格非常重要.
>
> - 使用prettier格式化代码.
> - 最好每个项目都配置一个单独的 `.prettier` 配置文件.

### .prettier文件配置

```json
{
  "tabWidth": 2, // tab缩进大小
  "printWidth": 300,  //每行最多多少个字符换行
  "semi": false, //代码末尾添加分号
  "singleQuote": true,  //使用单引号
  "trailingComma": "none", // 行尾逗号,默认none
  "bracketSpacing": true, // 对象中的空格 默认true: { foo: bar } | false: {foo: bar}
  "jsxBracketSameLine": true,// JSX标签>闭合位置 默认false换行 | true跟随
  "arrowParens": "avoid" // 箭头函数参数括号 默认avoid 可选 avoid省略括号 | always总是有括号
}
```

### .settings文件配置

使用Github账号登录Vscode, 同步设置.
