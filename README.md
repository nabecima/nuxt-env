# Usage

Nuxt の docker-compose.yml をクローン

```
git clone git@github.com:nabecima/nuxt-env.git
cd nuxt-env
```

Nuxt のプロジェクトを作成

```
docker-compose run --rm front yarn create <app_name>
```

サーバーの起動

```
mv docker-compose.yml ./<app_name>/
cd <app_name>
docker-compose up
```
