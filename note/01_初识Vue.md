h# 初识

+ vue 与容器之间只能一一对应。

+ Vue双括号中为js语句，可以为data中的变量，也可以是表达式

## 模板语法

### 插值语法

### 数据绑定

#### 单向绑定（v-bind）

数据只能从data流向页面

#### 双向绑定（v-model）

数据不仅能从data流向页面，还可以从页面流向data。

1. 双向绑定一般都应用在表单元素上（如，input、select等）
2. v-model：value可以简写为v-model,因为v-model默认收集的就是value值。

+ `v-model` 只能应用在表单类元素（输入类元素）上，`<h2 v-model:x="name`></h2>`为错误代码

## el和data的两种写法

+ 由Vue管理的函数，一定不要写箭头函数，一旦写了箭头函数，this就不是Vue实例了
