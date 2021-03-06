# HTML文本.md

## 标题与段落
```html
<h1>HTML简介</h1>

<h2>什么是 HTML？</h2>
<p>超文本标记语言(Hypertext Markup Language, HTML)是一个可以用来结构化 Web 内容并给予其含义和目标的编码语言。<p>

<h3>嵌套元素</h3>
<p>你可以将一个元素置于其他元素之中——这被称作嵌套。<p>

<h3>空元素</h3>
<p>有一些元素并不包含内容，它们被称为空元素。</p>

<h2>HTML文本</h2>

<h3>标题</h3>
<p>标题元素允许你指定内容的标题和子标题。</p>

<h3>段落</h3>
...
```

## 列表
### 无序列表
`<ul>` **U**nordered **L**ist 

### 有序列表
`<ol>` **O**rdered **L**ist

### 嵌套列表
```html
<p>金州勇士队的全明星球员包括：<p>
<ul>
  <li>
    斯蒂芬·库里
    <ul>
      <li>微博：<a href="http://weibo.com/u/3432945104">@StephenCurry</a></li>
      <li>Twitter: <a href="https://twitter.com/stephencurry30">@StephenCurry30</a></li>
    </ul>
  </li>
  <li>凯文·杜兰特</li>
  <li>克莱·汤普森</li>
  <li>德雷蒙德·格林</li>
</ul>
```

## `<em>` 与 `<strong>`
### `<em>`
```html
<p>我<em>祝福</em>大家找到好工作。</p>
<p>我祝福<em>大家<em>找到好工作。</p>
```

### `<strong>`
```html
<p>靠你了，明天<strong>不要</strong>迟到!</p>
```

## 描述列表 `<dl> <dt> <dd>`
```html
<dl>
  <dt>吃藕</dt>
  <dd>chi ou = 吃藕 = 丑 例句：被老板忽悠剪了个吃藕的发型。<dd>
  <dt>扩列<dt>
  <dd>扩充好友列表的简写，意为交朋友。<dd>
  <dt>狗带</dt>
  <dd>狗带 = go die, 表示去死。 例句：这节课太无聊了，我选择狗带。<dd>
</dl>
```

## 缩写
```html
<p>最近大家都在学 <abbr title="Hypertext Markup Language">HTML</abbr>。</p>
```

## 时间
```html
<time datetime="2016-01-20">2016年1月20日</time>
```


## 参考链接
* https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals
* https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting