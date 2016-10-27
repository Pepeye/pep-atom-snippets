# pep-atom-snippets package

Atom.io snippets for ES6/7, Modules, React and BDD testing


### React ES7 snippets for atom

- Todo


### ES6/7 module imports

#### `imp⇥` import default from library
```js
import $1 from '$2'
```

#### `imb⇥` import module from library
```js
import { $1 } from '$2'
```

#### `impd⇥` import all modules as ... from library
```js
import * as $1 from '$2'
```


### BDD testing (mocha, chai, jest...)

#### `desc⇥` describe
```js
describe('${1:description}', () => {
  ${0}
})
```

#### `its⇥` synchronous "it"
```js
it('${1:description}', () => {
  ${0}
})
```

#### `ita⇥` asynchronous "it"
```js
it('${1:description}', (done) => {
  ${0}
})
```

#### `bef⇥` before
```js
before(() => {
  ${0}
})
```

#### `befe⇥` beforeEach
```js
beforeEach(() => {
  ${0}
})
```

#### `aft⇥` after
```js
after(() => {
  ${0}
})
```

#### `afte⇥` afterEach
```js
afterEach(() => {
  ${0}
})
```

#### `jta⇥` asynchronous "test"
```js
test('${1:description}', (done) => {
  ${0}
})
```

#### `its⇥` synchronous "test"
```js
test('${1:description}', () => {
  ${0}
})
```
