# docker-nux-typescript-base

## Description
DockerでNuxt.js+TypeScript開発環境を構築した  

## Usage

```sh
> git clone git@github.com:KETAKOM/docker-nuxt-typescript-base.git
> cd docker-nux-typescript-base
> docker-compose up -d --build
> docker exec -it nuxt-app bash
> cd app
> yarn
> yarn dev
```

## 参考サイト
https://cloudpack.media/44788

https://github.com/kai-kou/nuxtjs-typescript-with-docker

→ほぼほぼ内容一緒、DockerFile, docker-compose.yml多少変更