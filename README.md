# Progress Steps
![](images/progress-step.png)
[Live Demo](https://mia-progress-steps.netlify.app/)

[50projects50days](https://github.com/bradtraversy/50projects50days)第二天的练习：Progress Steps。

## What I Learned
1. CSS: `::before`作为选中的元素前面的子元素，`::after`作为选中的元素后面的子元素。两者都经常配合`content`属性来为元素添加修饰内容。
2. CSS: 创建一个空的进度条用`.progress-container::before`画一个长方形，创建满的进度条用`<div class="progress">`画一个长方形，设置这两个长方形一样的位置和大小，只是一开始满进度条的宽度为0%，接下来的进度用JavaScript控制。

## Reference
- [MDN - ::before](https://developer.mozilla.org/zh-CN/docs/Web/CSS/::before)

