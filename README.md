# Diário Oficial

**Diário Oficial** is the Brazilian government gazette, one of the best places to know the latest actions of the public administration, with distinct publications in the federal, state and municipal levels.

Even with recurrent efforts of enforcing the [Freedom of Information legislation](http://www.acessoainformacao.gov.br/assuntos/conheca-seu-direito/principais-aspectos/principais-aspectos) across the country, official communication remains - in most of the municipalities - in PDFs.

The goal of this same project is to upgrade **Diário Oficial** to the year when it gets published, making accessible information that is currently only available.

**At the current state, there isn't much to see or download. Come back in a few weeks. :)**

*Unless you are a software developer and want to contribute even in this chaotic starting moment. In this case, make yourself at home and start downloading [Docker](https://www.docker.com) and [Docker Compose](https://docs.docker.com/compose/overview/).*

## Setup

```console
$ make setup
```

To extract data from Porto Alegre, do the following:

```console
$ docker-compose run --rm processing sh

# cd data_collection
# scrapy crawl rs_porto_alegre
```

## Running the test suite

```
$ make test
```
