# cloudfront-nuxt-spa-sample

![cloudfront-nuxt-spa-sample](https://main.d2elhmbkojzkli.amplifyapp.com/amplify-nuxt-spa-sample.png "cloudfront-nuxt-spa-sample")

<https://cloudfront-nuxt-spa-sample.desr.blue/>

* Nuxtアプリケーション（SPAモード）をAWSの`Cloudfront`+`S3`でデプロイするためのサンプルです

* Github ActionsでCDを定義し、mainブランチが更新されるとS3に最新リソースが反映されます
  * `Cloudfront`のディストリビューションと`S3`の配信先バケットは事前に作成しておく必要があります

* その他のファイルは`create-nuxt-app`コマンドのデフォルト生成ファイルから大きな変更はしていません

```Shell
? Project name: cloudfront-nuxt-spa-sample
? Programming language: TypeScript
? Package manager: Yarn
? UI framework: None
? Nuxt.js modules: 利用しない
? Linting tools: ESLint, Prettier, StyleLint
? Testing framework: Jest
? Rendering mode: Single Page App
? Deployment target: Static (Static/Jamstack hosting)
? Development tools: 利用しない
? Continuous integration: GitHub Actions (GitHub only)
? What is your GitHub username? waicode
? Version control system: Git
```
