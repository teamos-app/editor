## Introduction

[Novel](https://novel.sh/) is a Notion-style WYSIWYG editor with AI-powered autocompletions.

We've edited it such that we don't need to use AI autocompletion.

<br />

## Installation

To use the editor in a project, you can run the following command to install the `editor` NPM package directly from Github

```
npm install https://github.com/teamos-app/editor/tarball/main
```

Then, you can use it in your code like this:

```jsx
import { Editor } from "novel";

export default function App() {
  return <Editor />;
}
```
