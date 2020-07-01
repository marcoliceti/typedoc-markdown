# typedoc-markdown

Repo to reproduce a markdown-related issue of TypeDoc.

## The issue

Underscores immediately followed by a comma are not rendered as italic.

## How to reproduce

Type:

```
$ yarn install
$ yarn run typedoc
$ yarn run http-server
```
Then go to http://localhost:8080/docs/modules/_foo_.html and compare the output
with the content of `src/foo.ts`.
