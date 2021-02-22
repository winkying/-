### 写在前面，markdown语法回顾
1. 标题等级用#
2. 字体加粗用**粗体**，斜体用一个*斜体*，加粗加斜用***粗斜***，删除用~~删除~~
3. 内容引用以及嵌套用
  >引用
  >>嵌套引用
4. 区块分割线3个短横杠，*
****
----
5. 插入图片 ![图片alt](https://avatars.githubusercontent.com/u/8393930?s=60&u=3d4cfb9b9b08627f6596dad2abbeb91778807244&v=4 "图片title")
6. 插入超链接 [winking](https://github.com/winkying/fte-QA)
7. 列表 嵌套在前面加3个空格
    ##### 无序列表
    - 无序1
       + 无序2
    * 无序3
    ##### 有序列表
    1. 有序1
       1. 有序2
    2. 有序3

8. 表格
   ####
    姓名|技能|排行
    --|:--:|--:
    刘备|哭|大哥
    关羽|打|二哥
    张飞|骂|三弟

9. 插入代码 单行代码一个反义符号，多行代码3个反义符号
##### 
`create database hero`
##### 
```javascript
function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
```

10. 流程图
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```

--------
全局loading问题分析
https://www.cnblogs.com/yangAL/p/14393124.html

https://blog.csdn.net/q411020382/article/details/91127412

路由切换取消请求和取消重复请求
https://juejin.cn/post/6844903905625653262

charles模拟超时，404，500等