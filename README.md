# react-create-block

## Install

```bash
npm install react-create-block react prop-types
```

## Create block

```js
import { createBlock } from 'react-create-block';

export const Block = createBlock('div', 'block', ['color', 'size']);
```

## Use block

```jsx
import React from 'react';
import { Block } from '<path to created block>';

const App = () => {
    return (
        <Block block-color='red' block-size='xl'>
            Lorem Ipsum
        </Block>
    );
};
```
