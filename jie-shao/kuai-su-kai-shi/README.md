# 介绍

## Framer API

#### 这是一套完整的Framer Library的API说明文档，Framer这个库是专门为了实现网页端和手机端的高效的原型交互设计工作而制作的。

### 总览

Framer能帮助实现高级的基于物理现实的动效，基于触控的手势操作，同时还有通用的滚动、翻页组件以及界面化的工作流程。它被设计用来帮助初学者也能突破边界从而探索电子产品的更多可能性。它是基于以下的技术。你可以深入地了解一下以下的内容，尤其是一定要好好阅读下我们的[ES6 和React的指南](https://paper.dropbox.com/doc/Th7joG9fFSSiyZgOFYqj6)。

- [**React**](https://reactjs.org/) ****一个用于创建组件和用户界面的库。它帮助你结构化你的项目，这样你就能轻松得复用和分享它们。

```jsx
// React component
function Card({ title }) { ... }
```

- [**JSX**](https://reactjs.org/docs/introducing-jsx.html) ****一种可以直接JavaScript里使用类HTML的语法，这样你就能用熟悉的方式在JS里面搭建文档结构

```jsx
// JSX markup
<Card title="Hello">World</Card>
```

- [**TypeScript**](https://www.typescriptlang.org/)  一种可选的针对ES6语言的扩展语法，能给JS添加类型检查功能，从而让编辑器可以更好地理解你的写的代码，从而实现更好的代码自动补全和提示。

```typescript
// TypeScript string property type
type CardProps = { title: string }
```



