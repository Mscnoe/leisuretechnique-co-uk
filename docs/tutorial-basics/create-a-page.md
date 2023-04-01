---
sidebar_position: 1
---

# Create a Page

Who are we? Our core team of three, Carl, Richard and Steve have over 100 years of experience in Bingo between us. Manufacturing new and replacement equipment, maintaining existing rigs, supplying spare parts and repairing faulty items (in some cases long after they have been discontinued). Even a "new" instalation in Bingo can be 15 years old now - much of the kit in the field is over 20 years old and is expected to last even longer! We can help you keep running reliably by supplying spare parts, assemblies, support and advice. By drawing on our resources and connections with other experienced personnel we can offer installation, on site service, repairs and support. Many parts can be supplied from out extensive stocks and shipped for next day delivery. If we don't have it on the shelf we will be able to source it - Email us or call with your requirements - we are sure to be able to help. 

Add **Markdown or React** files to `src/pages` to create a **standalone page**:

- `src/pages/index.js` → `localhost:3000/`
- `src/pages/foo.md` → `localhost:3000/foo`
- `src/pages/foo/bar.js` → `localhost:3000/foo/bar`

## Create your first React Page

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

A new page is now available at [http://localhost:3000/my-react-page](http://localhost:3000/my-react-page).

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at [http://localhost:3000/my-markdown-page](http://localhost:3000/my-markdown-page).
