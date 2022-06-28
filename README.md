<p>
  <img width="100%" src="https://assets.solidjs.com/banner?type=solid-codemirror&background=tiles&project=%20" alt="solid-codemirror">
</p>

# solid-codemirror

A set of libraries to integrate CodeMirror to any SolidJS apps. This repository contains two packages:

- [@solid-codemirror/core](https://github.com/nimeshnayaju/solid-codemirror/tree/main/packages/core)

- [@solid-codemirror/codemirror](https://github.com/nimeshnayaju/solid-codemirror/tree/main/packages/codemirror)

## Demo

https://solid-codemirror.vercel.app/

## Installation

```bash
yarn add @solid-codemirror/codemirror
# or
npm i @solid-codemirror/codemirror
```

## Basic Usage

```tsx
import { CodeMirror } from "@solid-codemirror/codemirror";

export default function App() {
  return <CodeMirror />;
}
```

## Configure Line Numbers/Read Only

```tsx
import { CodeMirror } from "@solid-codemirror/codemirror";

export default function App() {
  return (
    <CodeMirror
      value="Hello World 🌎"
      showLineNumbers={true}
      readOnly={false}
    />
  );
}
```

## License

This project is licensed under MIT.

## Author

- [@nayajunimesh](https://twitter.com/nayajunimesh)
