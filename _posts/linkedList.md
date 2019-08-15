## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/BeyondSword/andy.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Leetcode链表解题思路总结
## Header 2
### Header 3

总结：（单）链表和数组的区别在于：数组在已知元素位置时，可以O(1)的效率对指定成员进行访问。而对链表而言，查找其中的一个节点往往是耗时的，时间复杂度需要O(n)。因此，对链表的考察往往围绕
如何高效地查找节点展开。另外，对单链表而言成员之间只有单向关系，进一步加大了访问的难度。
核心解法
第一类：查找链表的中点（n等分点）
	求链表的中点 =》 利用快慢指针 =》 同理可求链表的三等分、四等分点 =》 衍生出判断是否成环等题
	No.109 利用排序链表生成二叉查找树（找中点）（进阶：中序遍历，结合树的遍历思想 approach3）

第二类：链表翻转（部分元素翻转）
	考察逆向遍历 =》记录前访问节点和后访问节点，补齐单链表所缺乏的成员之间关系的信息

第三类：拆分，变换链表
	往往建立在补齐链表位置关系的基础之上 => 一般地，保留当前节点前一节点的地址总是可靠的，对单链表的任一节点而言，当保留了其前节点的信息时，他的信息就是完备的。
	例子：No.19 删除链表节点 No.21 合并链表***

第四类：链表的拷贝 哈希和链表的结合
	No.138 深拷贝链表（带随机指针） 利用哈希来实现链表的拷贝


第五类：链表排序


##弗洛伊德龟兔判圈

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/BeyondSword/andy.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.