---
title: Primeiro Post
date: "2020-07-14T21:30:00.284Z"
description: "Primeiro Post"
---

Primeiro post para teste do gatsby com github action fazendo deploy na aws s3

## Actions usadas
 - https://github.com/marketplace/actions/s3-sync
 - https://github.com/marketplace/actions/upload-a-build-artifact


## Codigo executado para gerar o blog com gatsby

```shell
mkdir dio-blog
nvm install 13.11
nvm use 13.11
npm install -g gatsby-cli 

# https://www.gatsbyjs.org/starters/gatsbyjs/gatsby-starter-blog/
gatsby new dio-blog https://github.com/gatsbyjs/gatsby-starter-blog
cd dio-blog
gatsby develop

# gerar versao final
npm run build
```

## Projetos equivalentes em outros framekworks

 - Em React: https://www.gatsbyjs.org
 - Em Angular: https://scully.io
 - Em Vue: https://gridsome.org

