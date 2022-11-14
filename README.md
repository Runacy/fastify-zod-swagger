# fastify-zod-swagger

This is sample API that outputs OpenAPI specifications based on the validation schema defined by [Zod]().

Check the example of Swagger-UI from here.  
https://joe-king-sh.github.io/fastify-zod-swagger/


## Getting Started

### Prerequisites

```bash
$ node --version
node v18.2.1
```

### Installing

```bash
$ npm i
```

### Run

```bash
$ npm run dev
```

## Link

This repository stores sample codes for the below article.
- [Fastifyで作るAPIにZodでスキーマバリデーションをかけながら型定義と実用レベルのOpenAPI仕様を自動生成する](https://dev.classmethod.jp/articles/fastify-zod-openapi/)


## memo

- nodeのバージョンを変更して動くかどうか( -> v16.16.0) => ⭕️
- pnpmではなくyarnにしても動くかどうか => ⭕️
- tsndからesbuildにしても動くかどうか => ⭕️
- docsは生成できるはず
 - 完全な生成はできない
 - swagger-ui.*.jsみたいなやつはなくてよし
 - openapi.yamlさえあれば最悪動くっぽい
  - swagger-codegenで生成したものでもないなあ
  - jsonは次のようなコードでも問題ないっぽい
