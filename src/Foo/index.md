---
nav:
  title: Components
  path: /components
---

## Foo

Demo:

```
import React from 'react';
import { Foo } from 'points';

export default () => <Foo title="First Demo" />;
```

### 点表示法

我们可以使用点表示法（dot notation）来访问对象的属性和方法。这种表示方法与Java相同。示例如下：

```js
person.age
person.interests[1]
person.bio()
```

### 括号表示法

括号表示法（bracket notation）是另一种访问属性的方式。

我们用点表示法访问对象的属性如下：

```js
person.age
person.name.first
```

而使用括号表示法访问如下：

```js
person['age']
person['name']['first']
```

![image-20200908165751576](./assets/index/image-20200908165751576.png)
