# Python 代码规范

- 缩进
  - 使用 tab 键缩进，一个 tab 为 4 个空格
  - 同一级函数、同一语法框架（例如 if--elif--else）或者同一数据排列需要有相同的缩进格式
- 变量命名
  - 关键变量或者常量，不允许以中文拼音或者随意的字母组合来命名
  - 所有单词之间的分隔通过大小写不同来区分
  - 常量全字母大写，通过下划线连接各个单词，如：`HOME_PAGE_URL`
  - 普通变量采用驼峰命名法，如：`keyList`
  - 类名采用首字母大写法， 如：`GithubData`
  - 函数名采用驼峰命名法，如：`matchElse()`
- 每行最多字符数
  - 每行最多100个字符
- 函数最大行数
  - 函数最多不超过100行
- 空行规则
  - 引入包与常量空三行
  - 常量与函数间空三行
  - 函数之间空两行
- 注释规则
  - 函数的定义，其上方一行，最多不超过两行进行注释说明
  - 精简明了，减少不必要的废话
  - 采用英文进行注释
- 操作符前后空格
  - 操作符前后必须添加空格，如：`a = 1 + 1`，`b = x * y`
- 其他规则
  - 函数传参、数据罗列等，在逗号之后必须空一格
  - 超出每行最多字符数时尽可能换行，右括号换行，左括号可选（若换行，左右括号尽量处于同一列）逻辑运算符放在新一行左侧。
  - 必要时，需要指定输入参数和返回参数的类型