一份前端面试问题清单.

# 目录

  1. [常规问题/破冰](#general)
  1. [管理相关](#management)
  1. [JavaScript 相关](#javascript)
  1. [HTML 相关](#html)
  1. [CSS 相关](#css)
  1. [HTTP 相关](#http)
  1. [处理问题能力相关](#problem-solving)
  1. [算法/数据结构/计算机基础相关](#algorithms)
  1. [快速评估](#general-evaluation-questions)
  1. [React 相关](#react)

----

## <a name='general'>常规问题/破冰</a>

> 你正在寻找一个当他们讨论他们以往的项目或者兼职项目是充满激情和热情的候选人, 他们表现出对软件开发的热情, 这是他们是否有能力满足您的要求的一个很好的指标. 一旦你平息了候选人的紧张情绪或兴奋状态，那么继续下一组问题吧, 这一组问题上最多花费5分钟.

* 谈一谈你最近做的项目.
* 你是否在你的工作时间外写代码(做别的项目)?
* 你在 Github 上有账号吗?
  * 如果有的话, 你都关注一些什么项目?
* 谈一下你最近的一个项目遇到的棘手的问题, 如何处理的?
* 谈一下创建应用程序或网站的过程.
* 你为什么想进入程序员这一行的?
* 过去这一年你读过多少技术相关的书籍?
* 过去这一年你最喜欢的技术书籍是什么? 你从中学到了什么?
* 你会经常访问哪些与开发相关的技术网站?
* 你有没有维护过什么开源项目?
* 你在业余时间写代码吗?
* 你喜欢编程吗, 还是仅仅因为它很赚钱?
* 在你的职业生涯中你完成过什么重要的事情吗, 或者说想完成什么重要的事?
* 你做过什么对你来说很重要的事情?
* 你最喜欢的编程语言是什么, 为什么?
* 如果你想给你最喜欢的编程语言增加一个功能, 你想添加什么? 为什么?
* 如果你想让你最喜欢的编程语言移除一个功能, 你想去掉哪个? 为什么?
* 假设周一你可以开始一份梦想的工作, 有着理想的职位和不错的薪水, 你所要做的就是告诉你的员工你要什么，你完全可以做到. 对于你而言这份工作意味着什么? (非常感谢! [原文链接](https://www.nczonline.net/blog/2015/09/my-favorite-interview-question/))

## <a name='management'>管理相关</a>

> 基本来讲, 需要候选人营造一个良好的工作氛围, 让团队成员们愉快的工作, 并且有一个良好的发展方向和机会. 如果这些事都发生了, 可以向更高级别的经理和 HR 寻求解决方案.

* 如何处理难以估计和高风险故事/任务？?
    - 及早调查
    - 指派有经验的员工处理问题
    - 及时更新, 及时反馈沟通
    - 向上级主管报备, 及时反馈情况

* 如何处理频繁的需求变更, 从概念阶段到生产环境阶段.
    - 对于概念阶段:
      - 及时和团队成员沟通, 让他们知道哪些地方做了更改.
      - 提供解决方案比完美的设计/实现更重要. 对于需求变更, 力求找到原因. 如果是商业原因, 大多情况下应该直接搞定. 如果是处于技术原因, 首先应该讨论然后做出决定.
    - 对于生产阶段(线上环境):
      - 首先应该确定一个计划. 重新重新评估需求变更, 从以下几个方面处理:
         - 如果不是那么紧急, 那继续工作, 改变未来的计划
         - 如果是很紧急的, 要么要求更多的人力财力资源, 要么就砍掉一些功能
         - 如果完全搞不定, 建议推迟发布日期

* 在岗位有限的情况下, 如何保持团队稳定. (比如竞争对手能给更多的报酬, 在不增加预算的情况下怎么处理)

## <a name='javascript'>JavaScript</a>

* 什么是 ECMAScript, JScript?
* 什么是文档对象模型(DOM)?
* undefined 和 null 的区别是什么? 如果有 null 的情况下, 最好说一些为什么我们需要 undefined.
* 什么是 JavaScript 严格模式? 它有什么作用? 为什么要使用它?
* 什么是 AJAX? AJAX 的工作流程是什么样的? 如何实现一个跨域 (CORS)? 在 JavaScript 中同步和异步有什么区别?
* 谈一下 JavaScript 封装.
* 谈一下 JavaScript 的继承(传统继承方式和现代继承方式).
* 什么是闭包?
* 什么时候我们需要使用 `this` 关键词? 为什么?
* 如何使用 JavaScript 处理 cookie?
* DOM 操作 – 如何添加/删除/移动/拷贝/创建/查找一个节点.
* 对于 JavaScript 正则表达式而言, 什么是贪婪匹配/惰性匹配和字符名匹配? 如何用正则匹配出 `<script>greediness</script>`?
* 事件(Events) - 如何使用它们? IE 和 DOM 事件模型之间的主要区别是?
* 什么是 XMLHttpRequest, 如何使用它完成一个 GET 请求, 如何处理异常?
* 什么是 JSON, 为什么你要使用它, 如何实际去使用它, 实现细节是?
* 什么是 Promise, 为什么要用它? 它是解决什么问题的?
* 在父元素上使用一个事件处理方法, 检测左滑动和右滑动, 并用 Alert() 打印出滑动的方向.
* 写一个 JavaScript 闭包的例子. 代码实现什么功能不重要, 只需要展示出闭包何处创建的.
* `document.write` 和 `innerHTML`的区别是什么.
* JavaScript 中 `delete` 操作符用在什么地方? 什么是可以删除的, 什么是不可以删除的, 为什么?
* 原型继承(prototypal inheritance)是如何工作的?
* 是什么定义了闭包?
* 如何改变 `this` 关键词?
* 如何使用 apply/bind/map/filter/call?
* 请你说下这段程序的流程控制是怎样的?
  ~~~JavaScript
  makeAjaxRequest( url, function(response){ alert( "Response: " + response ); } );
  ~~~

* 写一个阶乘函数.
* 写一个函数它接收一个字符串并反转它. 使用递归最好.
  ~~~JavaScript
  function reverseString(str) {
    return str.split("").reverse().join("");
  }

  // 使用递归
  function reverseString(str) {
    return (str === '') ? '' : reverseString(str.substr(1)) + str.charAt(0);
  }

  // 在 ES6 中, 你还可以这样
  [...str].reverse().join('')
  ~~~

* 写一个 map 递归函数.
  ~~~JavaScript
  function map(arr, fn) {
    if (arr.length === 0) {
      return [];
    }

    return [fn(arr[0])].concat(map(arr.slice(1), fn));
  }
  ~~~

* 下面四种 Promise 有什么不同?
  ~~~JavaScript
  doSomething().then(function () {
    return doSomethingElse();
  }).then(finalHandler);

  doSomething()
    .then(function () {
      doSomethingElse();
    })
    .then(finalHandler);

  doSomething()
    .then(doSomethingElse())
    .then(finalHandler);

  doSomething()
    .then(doSomethingElse)
    .then(finalHandler);
  ~~~

* 下面这些原生 JavaScript 代码片段实现, 结果是?
  ~~~JavaScript
  setTimeout(function(){console.log("three");}, 0);

  Promise.resolve().then(function(){ console.log( "two" ); });

  console.log("one");
  ~~~

* 解释一下 `bind` `apply` `call` 的使用场景, 以及他们的区别?
* 解释一下事件代理, 为什么它很有用?
* 什么是事件循环(event loop)?
* JavaScript 变量提升是如何发生的?
* 在新版的 JavaScript 中让你最兴奋的是哪个功能, 为什么?
* 在 JavaScript 中原型继承是非常酷的特别是当需要保持代码简洁和可维护性时, 那么说下下面代码的输出结果吧?
  ~~~JavaScript
  var parent = {
    get: function fn() {
      return this.val;
    },
    val: 42
  };

  var child = Object.create(parent);
  child.val = 3.14159;
  var grandchild = Object.create(child);

  console.log(parent.get());
  console.log(child.get());
  console.log(grandchild.get());
  ~~~
* 什么是纯函数(Pure Function)?

  纯函数有以下特点:
    * 给一个相同的参数, 总是输出一样的结果
    * 没有副作用
    * 没有依赖

* 如何判断一个值是否是数字? (注意: `typeof value === 'number'` 这个表达式输入数字和 `NaN` 都会成立)
* 如何获取下面这些值的类型:

```
 NaN, 0, 1, Infinity,                // numbers
 null, undefined, false, 'str',      // other primitives
 new String('a'), new Boolean(true), // wrapped primitives
 {}, [], new Map, new WeakSet(),     // containers
 /regex/, new Date(),                // other custom objects
 window, navigator,                  // native objects
 function () {}, (() => {}), atob,   // functions
 Symbol(),                           // symbol
 {[Symbol.toStringTag]: 'Custom'}    // @@ToStringTag
```

* 下面这些日志的输出顺序是这样的?

```javascript
console.log('script start')
setTimeout(function() {
  console.log('setTimeout')
}, 0)
Promise.resolve()
  .then(function() {
    console.log('promise1')
  })
  .then(function() {
    console.log('promise2')
  })
console.log('script end')

```

## <a name='html'>HTML</a>

* 什么是 `<!DOCTYPE>` 标签? 如何使用它?
* childNodes[] 和 children[] 有什么区别?
* DOM 结构 – 节点之间如何关联, 如何遍历一个节点到下一个节点.
* 操作 DOM – 如何添加/移除/移动/复制/创建/查找节点?
* 标准盒子模型和怪异盒子模型(Quirks Modes) – 如何在它们之间切换, 为什么这很重要?
* 块级元素和行内元素 – 如何使用 CSS 改变它们的状态, 它是如何影响周边元素的, 你如何用样式控制它们?
* 浮动元素 – 如何使用它们, 它带来了一些糟糕影响那么如何解决它们.
* HTML 和 XHTML(1.x&2) – 它们有什么不同, 你会使用它们中的哪一个, 为什么?
* 尽可能多的列出一些 HTML5 的标签, 以及为什么你需要使用它们.
* 写一个 'Hello, Word!' 页面. (是否了解一个页面所必须的标签,比如定义 DOCTYPE 等等..).
* XHTML 1.x 和 HTML4 有什么不同?
* h1~h6 标签有什么不同? ul 和 ol 标签有什么区别?
* 你有没有用过 dl, dt, dd? 它们的具体语义是什么?
* `form` 常用的属性有哪些?
* `input` 元素如果不设置 `type` 会怎样? 
* 哪些场景使用 `input` 会给它的 的 `type` 设置成 `image`?

## <a name='css'>CSS</a>

* 什么是 CSS?
* 尽可能多得列出你知道的 CSS hacks 技巧.
* `display` 这个属性它的值可能有哪些? 什么是块级元素和行内元素, 它们之间的区别是什么? 尽可能多得列出你知道的行内元素和块级元素.
* 盒子模型 - margin, padding, and border 在 border-box (standards mode) 和 content-box (old Internet Explorer)之间的区别是什么.
* 列出一些 CSS 的布局方式.
* 什么是 CSS stack, 你谈谈对他的理解?
* 列出一些浏览器的兼容性问题, 你曾遇到过的或者你知道的.
* 列出 `position` 的值有哪些, 以及每种值对应的效果是什么.
* 列出 `display` 的值有哪些, 以及每种值对应的效果是什么.
* `display: inline-block` 有什么作用?
* 谈一谈 CSS3, 比如 transition, animation, transform, 等等..
* 什么是 box-sizing , 什么时候会用到它?
* 什么是 CSS transform?
* 谈一谈 Flexbox, 为什么我们要用它? 它是如何工作的, 如何使用它?
* 为什么说 Table 布局是一种糟糕的布局方式?
* 什么情况下需要用到浮动属性, 如何清除浮动?
* 你用过哪些 CSS 选择器?
* `cssRules` 和 `rules` 的区别是什么?

## <a name='http'>HTTP</a>

* 尽可能多的列出你知道的 HTTP 状态码.
* 这些状态码有什么含义? 200, 302, 304, 404, 500, 503.
* 谈一谈 Web 缓存或者 HTTP 缓存, 例如什么是条件 GET 请求? Etags/Expires/Cache-Control 这些具体有什么含义?
* `Get` 和 `Post` 请求有什么区别?
* 无状态 HTTP (HTTP stateless) 和 `Connection:keep-alive`的区别是什么 ?
* HTTP Request/Response 的消息结构式怎样的?
* HTTP 状态码 301 和 302 的区别是什么? 搜索引擎是如何处理它们的?
* 什么是 HTTP 响应头缓存? 它们的用法是什么?
* 当您发送Ajax请求时, 如何判断已收到完整的服务器响应以便进行进一步处理?
* 为什么我们要用 <kbd>Ctrl</kbd> + <kbd>F5</kbd>或刷新按钮来避免一些本地缓存?
* 为什么要把样式表文件放在页面顶部, JS 文件放在页面底部?
* HTTP request/response 消息包含哪些内容?

## <a name='problem-solving'>处理问题能力相关</a>

* 经典初学者编程问题: 猜谜游戏. 下面是它的工作原理: 我们的程序会随机生成一个1到100之间的整数. 它会要我们输入一个数来猜, 程序会告诉我们输入的数字太大了或者太小了, 一旦猜对了, 它会恭喜我们.
* 给数组添加一个 `unique` 方法，以便生成一个无重复版本的数组使用 [Vanilla JS](https://jsfiddle.net/starandtina/87TSF/) 或者 [with ES5 compatible JS](https://jsfiddle.net/starandtina/b6hbtbhz/).
* 使用 Vanilla JS 从对象复制属性来实现深度克隆继承.
* 使用 JavaScript 来控制一个 input 的最大长度, 如果超出了最大长度, 那么就把输入框标红.
* 使用 JavaScript 或者 jQuery 改变所有类名是 `test` 的元素, 背景改成黄色.
* 使用 JavaScript 写一个跑马灯效果.
* 使用 JavaScript 吧 16进制颜色代码转成 RGB 颜色代码.
* 生成一个连续唯一的随机数.
* 查找 JavaScript 数组中最小数的索引.
* 使用 JavaScript 检查一个数是否是整数.
* [实现下面代码的功能:](https://jsfiddle.net/starandtina/et7dnge8/)

  ~~~JavaScript
  [1, 2, 3].duplicate(); // [1, 2, 3] => [1, 2, 3, 1, 2, 3]
  ~~~
* 在 JavaScript 中如何检查一个值是否是 `NaN` ?
* 如何异步载入 CSS/JavaScript 文件? 如果你知道怎么实现, 那么写一个 `loadCSS` 和 `loadJS` 函数.
* 写一个简单的模板引擎, 使下面的代码按照预期工作:

  ~~~JavaScript
  var tpl = template('<p>hey there {{ name }}</p>');
  var div = document.createElement('div');
  div.innerHTML = tpl({ name: 'Neo' });
  document.body.appendChild(div);
  ~~~
* 定义一个 `spacify` 函数, 它使用字符串作为参数并且原样返回相同的结果, 只是每个字符之间多了一个空格, 举个栗子:

  ~~~JavaScript
  spacify('hello world') // => 'h e l l o w o r l d'
  ~~~~
  如果答上了, 那么继续实现以下这个函数, 把 `spacify` 函数直接放在字符串对象上, 举个栗子:

  ~~~JavaScript
  'hello world'.spacify();
  ~~~~
* [实现一个 Pivot 函数](https://jsfiddle.net/starandtina/e6n5h/): Pivot 意思就是总是把位于中间元素右边的值放到左边, 反之亦然

  ~~~JavaScript
  Eg: Pivot {A, B, C} should give {C, B, A}
        Pivot { 1, 2, 3, 4 } should give { 3, 4, 1, 2 }
        Pivot { 1, 2, 3, 4, 5, 6, 7 } should give { 5, 6, 7, 4, 1, 2, 3 }
        Pivot { 11, 8, 45 } should give { 45, 8, 11 }
     提示: 应该输入输出什么类型? 为什么?
  ~~~
* 提供一个函数版的 `each` 或者 `forEach`, 用于迭代元素列表, 每个元素依次产生一个迭代函数.
* 提供一个函数版的 `function.apply`.
* 通过填充任意数量的参数来使用函数, 而不改变其动态的这个值.
* 实现 _currying_, 可以在函数执行之前预先填充参数.
* 编写一个合并函数，返回一个合并列表的函数, 其中每个函数返回里面函数的返回值, 用数学术语来说, 合并三个函数 `f()`, `g()`, 和 `h()`最后结果为 `f(g(h()))`.
* 使用 [Fisher-Yates shuffle](http://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle) 实现一个数字数组洗牌算法.
* 提供一个字符串 trim 增强函数.
* 获取一个数字数组中的最大值和最小值.
* 写一个过滤 HTML 危险字符(`<`, `>` 等..)的函数.
* [按数组中的属性查找元素](https://gist.github.com/starandtina/267f2935c2f3f1553ee5).

## <a name='algorithms'>Algos, Data Structures, & Computer Science Fundamentals</a>

> Algorithm is at the heart of every nontrivial computer application, and algorithmic is a modern and active area of computer science. Every computer scientist and every professional programmer should know about the basic algorithmic toolbox: structures that allow efficient organization and retrieval of data, frequently used algorithms, and basic techniques for modeling, understanding and solving algorithmic problems and our expectation of
event candidates is that they are very strong in this area.

* Merge sort has a complexity of O(n*log n), making it one of the more efficient sorting algorithms available, also it's a stable sort. That's why Firefox and Safari use merge sort for their implementation of `Array.prototype.sort()`. Please implement `Array.prototype.sort()` using merge sort.
* Binary search implementation in JavaScript.
* Define a function that returns n lines of [Pascal’s Triangle](https://en.wikipedia.org/wiki/Pascal%27s_triangle).
* Use recursion to log a Fibonacci sequence of n length. (Notice: only need to log instead of calculating the result)

  ~~~JavaScript
  function fib(depth, n1, n2) {
    if (!depth) { return; }
    console.log(n1);
    fib(depth-1, n2, n1 + n2);
  }
  ~~~
* How to find the longest word in a string with JavaScript?

  ~~~JavaScript
  "The quick brown fox jumped over the lazy dog".split(' ').sort(function (a, b) {
    return b.length - a.length;
  })[0].length;
  ~~~

## <a name='react'>React</a>

> React is a library that’s designed to be one piece of the puzzle. React provides a thin view layer and leaves it to the developer to choose the remaining pieces of the architecture. Nothing comes in the box, so your team has full control over everything that you use. Choose-your-adventure works well if you have a team of experienced JavaScript developers who are comfortable with functional programming and immutable data structures. The React community is on the cutting edge of innovation in the use of web technologies. If your organization needs to target many platforms with the same codebase, knowing React will allow you to write for the web, for native with React Native, and for VR devices with ReactVR.

- When does **React** will trigger re-render?
- What happens when you call setState?
- What’s the difference between an Element and a Component in **React**?
- When would you use a Class Component over a Functional Component?
- What are refs in **React** and why are they important? Can we use the refs in functional components?
- What are keys in **React** and why are they important?
- If you created a **React** element like Twitter below, what would the component definition of Twitter look like?

~~~JavaScript
<Twitter username='starandtina'>
 {(user) => user === null ? <Loading /> : <Badge info={user} />}
</Twitter>
~~~

- What is the difference between a controlled component and an uncontrolled component
- In which lifecycle event do you make AJAX requests and why?
- What does shouldComponentUpdate do and why is it important?
- How do you tell **React** to build in Production mode and what will that do?
- Why would you use `React.Children.map(props.children, () =>)` instead of `props.children.map(() =>)`
- Describe how events are handled in **React**.
- What is the difference between createElement and cloneElement?
- What is the second argument that can optionally be passed to setState and what is its purpose?
- What’s wrong with this code?

~~~JavaScript
this.setState((prevState, props) => {
  return {
    streak: prevState.streak + props.count
  }
})
~~~

- What's the result of `state.count` and why? If it's not what you want and how to fix it?

~~~JavaScript
// assuming state.count === 0
this.setState({count: state.count + 1})
this.setState({count: state.count + 1})
this.setState({count: state.count + 1})
// state.count === 1 or 3
~~~

- setState is async or sync in React? 

>[setState() does not immediately mutate this.state but creates a pending state transition. Accessing this.state after calling this method can potentially return the existing value. There is no guarantee of synchronous operation of calls to setState and calls may be batched for performance gains.](https://reactjs.org/docs/react-component.html#setstate)

- If it's async, why would they make setState async as JS is single threaded language and this setState is not a WebAPI or server call?

It is because setState alters the state and causes rerendering. This can be an expensive operation and making it synchronous might leave the browser unresponsive. Thus the setState calls are asynchronous as well as batched for better UI experience and performance.
 
[React batches state updates that occur in event handlers and lifecycle methods. Thus, if you update state multiple times in a `<div onClick />` handler, **React will wait for event handling to finish before re-rendering. To be clear, this only works in React-controlled synthetic event handlers and lifecycle methods.** State updates are not batched in AJAX and setTimeout event handlers, for example.](https://stackoverflow.com/questions/33613728/what-happens-when-using-this-setstate-multiple-times-in-react-component)

- What’s **context** why we need it?
- [What's the **Presentational** and **Container** components and why it's so important?](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.ky4oqu4f2)
- Why should I use an immutable-focused library such as immutable.js or seamless-immutable? ImmutableData
- Why this kind of error occurs? [**Parse Error: Adjacent JSX elements must be wrapped in an enclosing tag.**](https://stackoverflow.com/questions/31284169/parse-error-adjacent-jsx-elements-must-be-wrapped-in-an-enclosing-tag)
- How would you make the choice between **Redux** and **React's setState**?
- [12 Essential React.js Interview Questions](https://www.toptal.com/react/interview-questions)
- How should we structure the data in our Redux store?
- How would you categorize and normalize your data?
- [Should I use React with jQuery? ](https://www.quora.com/Should-I-use-React-with-jQuery)

> If you find yourself needing jQuery when using React, you are probably using React in the wrong way. jQuery is a DOM manipulation library and the main point of using React is to abstract DOM manipulation away from you.

- What's new in **React 16**?

## <a name='general-evaluation-questions'>快速评估</a>

> 以下是技术面试中一些常见的评估问题, 以便快速检查应聘者的背景

~~~
function foo(a, b, c) {
  return a + b + c;
}
console.log(foo(1, 2));

// --------------------------------------

function DB() {
  this.read = function () {
    // ...
    console.log('Call read method')
  }
}
var db = new DB();
var aRead = db.read;

db.read();
aRead();

// --------------------------------------

var parent = {
  get: function fn() {
    return this.val;
  },
  val: 1
};

var child = Object.create(parent);
child.val = 3.14159;
var grandchild = Object.create(child);

console.log(parent.get());
console.log(child.get());
console.log(grandchild.get());

// --------------------------------------

for (var i = 1; i <= 5; i++) {
  setTimeout(function timer() {
    console.log(i);
  }, i * 1000);
}

// --------------------------------------

function foo() {
  console.log(a);
}

function bar() {
  var a = 3;

  foo();
}

var a = 2;

bar();
~~~

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
