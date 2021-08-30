Whenever you want good typing, change this:

```ts
Object.keys(routingPaths).forEach(path => {});
```

To:

```ts
import { ObjectTyped } from 'object-typed';

ObjectTyped.keys(routingPaths).forEach(path => {});
```
