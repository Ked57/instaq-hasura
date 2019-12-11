<h1 align="center">Welcome to instaq-hasura 👋</h1>
<p>
  <a href="https://twitter.com/ClementFassot" target="_blank">
    <img alt="Twitter: ClementFassot" src="https://img.shields.io/twitter/follow/ClementFassot.svg?style=social" />
  </a>
</p>

> Migrations and metadatas for instaq's hasura instance

## Get started

First, you need to use docker-compose on your computer

```sh
docker-compose up -d
```

Then install the hasura cli: https://docs.hasura.io/1.0/graphql/manual/hasura-cli/install-hasura-cli.html

And then apply the migrations and metadatas

```sh
cd hasura
hasura metadata apply
hasura migrate apply
```

You can also open the console and the migrations will be auto generated into your migrations folder

```sh
hasura console
```

## Author

👤 **Clément Fassot**

* Twitter: [@ClementFassot](https://twitter.com/ClementFassot)
* Github: [@Ked57](https://github.com/Ked57)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Ked57/instaq-hasura/issues). 

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_