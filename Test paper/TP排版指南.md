# TP 排版指南

使用软件：typora 

版本：不限

平台：不限

文件格式：markdown

图片：4

## 1.试卷编码

试卷编码形式是：TPxxxxx

其中 xxxxx 对应的是编码数字，比如第一份为 00001，正确的编码为 -> TP00001

编码示例：

````
正确的编码：
- TP00001
- TP00212
- TP22111
错误的编码：
- Tp22009
- tp02323
- TP1
````

## 2.试题编码

试卷编码形式是：[Txxxxxxx]

其中 xxxxxxx 对应的是编码数字，比如第一份为0000001 ，正确的编码为 -> [T0000001]

编码示例：

```
[T0000001] 史料可作为研究历史的证据。据《后汉书·章帝纪》，章帝曾在诏书中说：“前世举人贡士，或起甽亩，不系阀阅。”李贤的注称：“言前代举人，务取贤才，不拘门地。”由此可以判定当时（　　）

A．科举制度已初具雏形        B．阀阅之家享有一定选举特权

C．政治环境较为黑暗         D．世家大族垄断官员的任命
----
[T0000217] 下列有关生物体内水的叙述，正确的是(  ) 

A.晾晒失去的主要是自由水，烘干失去的主要是结合水

B.不同生物的细胞内含水量完全相同 

C.结合水是细胞内良好的溶剂 

D.冬季植物体内自由水含量相对增高，以增强抗寒能力
```

## 3.试卷摘要

标准模板（如下）：

>科目：
>
>测试形式：
>
>测试主题：
>
>RAW：
>
>试题：

需要补充的内容：```科目```、```测试形式```、```测试主题```、```RAW```、```试题```

### 3.1科目

请以简体中文的形式填上对应的题目，例如：

科目：数学

### 3.2测试形式

请扫视一遍试卷，填上正确的测试形式，例如：

测试形式：选择题、填空题、简答题

### 3.3测试主题

请将 RAW 文件上对应的标题课时补充，同时请加粗，例如：

测试主题： **隋唐制度的变化与创新**

```
错误示例：
测试主题：第二单元/第七课 **隋唐制度的变化与创新**
```

### 3.4RAW

请补充对应的 RAW 文件，不需要加上文件格式，例如：

RAW：37

### 3.5试题

请补充对应的试题范围，例如：

试题：T0000001-T0000013

### 3.6模板示例

>科目：数学
>
>测试形式：选择题、填空题、简答题
>
>测试主题：集合的运算
>
>RAW：56
>
>试题：T0000001-T0000013

## 4.图片

请将 RAW 文件中的图片保存至对应的 .md 文件同一个文件路径下的 ```img``` 文件夹中，并且根据所对应题目编号进行一定的编码

### 4.1图片编码

若该题目只有一张图片，编码示例：

T0000003-1.png

若有多张，下面的 ```x``` 代表第几张：

T0000003-1.png T0000003-x.png

> 请注意，以上的示例所涵盖的 png 格式不一定是你在实际操作中的格式，请根据你保存下来的图片格式进行一定的修改

### 4.2相对路径

请将所有保存并且排版好的图片在 .md 文件中将绝对路径改为相对路径，示例：

![T0000003-1.png](/Users/hayashiyuiyuu/microseyuyu-wiki-docs/img/T0000003-1.png)

![T0000003-1.png](./img/T0000003-1.png)

> 第一行为绝对路径，第二行为相对路径

### 4.3图片源码排版

当你都完成了以上两个要求之后，你在 .md 的源码中请保证你所插入的图片对应的上和下都有一行空格，这个操作请在源码模式中进行

正确示例：

```
[T0000003] 民俗钱币是古钱币的一种，大多由民间私制而成，是民俗文化的载体。寓意（　　）

![T0000003-1.png](./img/T0000003-1.png)

> 清代民俗钱币图案 ^ 
>
> 右图（左一图文：状元及第；右一图文：独占鳌头。）

A．学以致用的价值取向     B．仁者爱人的思想主张

C．心外无理的哲学思想     D．克己复礼的行为规范
```

错误示例1:

```
[T0000003] 民俗钱币是古钱币的一种，大多由民间私制而成，是民俗文化的载体。寓意（　　）

![T0000003-1.png](./img/T0000003-1.png)
> 清代民俗钱币图案 ^ 
>
> 右图（左一图文：状元及第；右一图文：独占鳌头。）

A．学以致用的价值取向     B．仁者爱人的思想主张

C．心外无理的哲学思想     D．克己复礼的行为规范
```

错误示例2:

```
[T0000003] 民俗钱币是古钱币的一种，大多由民间私制而成，是民俗文化的载体。寓意（　　）

![T0000003-1.png](./img/T0000003-1.png)



> 清代民俗钱币图案 ^ 
>
> 右图（左一图文：状元及第；右一图文：独占鳌头。）

A．学以致用的价值取向     B．仁者爱人的思想主张

C．心外无理的哲学思想     D．克己复礼的行为规范
```

错误示例3:

```
[T0000003] 民俗钱币是古钱币的一种，大多由民间私制而成，是民俗文化的载体。寓意（　　）
![T0000003-1.png](./img/T0000003-1.png)

> 清代民俗钱币图案 ^ 
>
> 右图（左一图文：状元及第；右一图文：独占鳌头。）

A．学以致用的价值取向     B．仁者爱人的思想主张

C．心外无理的哲学思想     D．克己复礼的行为规范
```

## 5.题目间隔排版

请将所有题目在排版时确定每个题目都有上下四行空格（对应源码模式 8 行），例如：

```
[T0000216] 下列有关细胞中的水和无机盐的叙述,正确的是(  )

A.水分子以自由水和结合水两种形式存在

B.结合水是多种离子良好的溶剂 

C.大多数无机盐以化合物的形式存在

D.无机盐含量多,具有重要的生理功能









[T0000217] 下列有关生物体内水的叙述，正确的是(  ) 

A.晾晒失去的主要是自由水，烘干失去的主要是结合水

B.不同生物的细胞内含水量完全相同 

C.结合水是细胞内良好的溶剂 

D.冬季植物体内自由水含量相对增高，以增强抗寒能力









[T0000218] 豌豆的种子有圆粒和皱粒。圆粒种子含淀粉多，成熟时能有效地保留水分。而皱粒种子含蔗糖多，在成熟时由于失水而皱缩。下列有关叙述错误的是(　　)

A．细胞内的水有自由水和结合水两种形式

B．圆粒种子保留的水分主要是结合水

C．皱粒种子失去的水分主要是自由水

D．种子储存前要晒干的主要目的是防止霉变








```

## 6.下划线替换

将所有的下划线替换成全角的 ```（        ）```

无论长度多长都替换成上面的形式

例如：

````
更改前：②将________________________分别栽培在上述两种培养液中。
更改后：②将（        ）分别栽培在上述两种培养液中。
````

## 7.测试结果

请在每一份的 TP 末尾处新增：

## 测试结果

### 要求：

### 状况：

### 补充：

可以直接复制粘贴，不用填写任何东西

## 8.多余文字删除

在每一份的 TP 中请仅保留题目，不需要其他多余的说明,例如：

**一、单选题**

![img](file:////Users/hayashiyuiyuu/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image002.jpg)课时把关练

**第****2****节 细胞器之间的分工合作**

![img](file:////Users/hayashiyuiyuu/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image002.jpg)《第一章　宇宙中的地球》素养综合训练

----

等以上的多余元素全部删除不需要出现在 .md 中，但是请保留 RAW 文件中的东西，每一次工作结束后关闭 RAW 文件时请不要保存你的所有改动，请选择不保存后再放入 ```finished-raw``` 中

## 9.答案

请不要将任何的答案放进 .md 文件中

## 10.文件命名

所有的 TP 文件命名需要是 -> TPxxxxx.md，例如：

TP00011.md

TP23244.md

TP00221.md

## 11.模板

若有任何问题，请先参考：```TP00011.md```