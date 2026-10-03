<h1 align="center">Mansi Memes</h1>

<p align="center">
  <b>Read in:</b>
  <a href="https://github.com/avysmorfias/mansi-memes/blob/main/README.ru.md">Русский</a> |
  <a href="https://github.com/avysmorfias/mansi-memes/blob/main/README.eo.md">Esperanto</a>
</p>

**Mansi Memes** is a collection of memes in the Mansi language.

The idea is simple: I take words and expressions from Mansi dictionaries, books, and other learning materials and put them into familiar internet formats — from simple jokes to Minecraft screenshots.

The project is a small attempt to show Mansi in a context where you might not expect to see it: not only in dictionaries, archives, and linguistic publications, but also in a meme sent to a friend.

## Why?
Mansi is usually encountered through dictionaries, linguistic publications, archives, and educational materials. I wanted to do something much less serious with it: take words and expressions from those materials and put them into the kind of internet culture I encounter every day.

A Minecraft screenshot with a Mansi caption may seem like a very small thing. That is exactly what I like about it. It shows that Mansi can be used not only in materials about the language, but also to make a joke, share something with a friend, and simply exist on the internet.

I also hope that the project can make other people curious about Mansi — or inspire them to make something similar with their own language.

> Somewhere in Siberia, there is a language in which someone can make a Minecraft meme.

## Why Esperanto?
English is here because it is the easiest way to reach an international audience. Russian is natural for the project because much of the Mansi material I work with is in Russian.

Esperanto has a different purpose. It gives the project a way to reach people who are already interested in languages and linguistic diversity, but who may never have encountered Mansi before.

So Esperanto is not here simply as another translation language. It is a small bridge between an international language community and a small Indigenous language of Siberia.

**Mansi → Esperanto → a wider world.**

## What is here?
The repository contains Mansi memes, the expressions used in them, translations, information about their sources, and structured data.

The memes currently represent several Mansi varieties, including Sosva and Upper Lozva. More varieties can be added as new material becomes available.

The collection is intentionally small. It is not meant to be a complete dictionary, corpus, or academic database. It is a growing collection of things I find interesting, funny, and worth sharing.

## How it works
I look through Mansi dictionaries, phraseological dictionaries, textbooks, and other learning materials, find words and expressions that can work in a meme, and create the meme around them.

The original Mansi expression is kept together with translations into English, Russian, and Esperanto. The source of the expression is recorded as well, so that the material can be traced back to the dictionary, book, lesson, or other resource where I found it.

Some of the material comes from older printed books that are difficult to find outside specialized collections. I also use newer digital materials, including online Mansi lessons and other resources.

The complete source information is kept in [`data/sources.json`](./data/sources.json).

## Data
The collection is also stored as structured JSON in [`data/memes.json`](./data/memes.json).

Each entry connects the Mansi expression, its variety, translations, source, and the corresponding meme image.

For example:
```json
{
  "id": 1,
  "expression": {
    "text": "Ам тувыл хотьют?",
    "language": "mns",
    "variety": "sosva"
  },
  "translations": {
    "en": "Me and who?",
    "ru": "Я и кто?",
    "eo": "Mi kaj kiu?"
  },
  "sources": [
    "valdazs-untuy-erzyanin-lesson-1"
  ],
  "meme": {
    "image": "memes/sosva/me-and-who.png"
  }
}
```

The JSON is not the main purpose of the project, but it makes the collection easier to maintain and reuse. The data can also be used for small linguistic experiments, scripts, or other projects built around the collection.

## Gallery
<div align="center">

![Mansi meme: Me and who?](./memes/sosva/me-and-who.png)

<p align="center"><i>“Ам тувыл хотьют?” — “Me and who?”</i></p>

<br>

![Mansi meme: Why](./memes/sosva/why.png)

<p align="center"><i>“Манрыг” — “Why?”</i></p>

</div>

The gallery is the heart of the project. The point is not only to collect Mansi expressions, but to actually put them into modern visual and humorous contexts.

## Have something I don't have?
A large part of the fun of this project is finding Mansi material that is difficult to discover.

If you have a Mansi dictionary, textbook, recording, translation, or another rare resource that could help find new words and expressions, I would be very happy to hear about it.

You can also help by:
* pointing out mistakes in the expressions or translations;
* suggesting a meme idea or template;
* contributing your own Mansi meme;
* sharing the project with someone interested in Mansi or other lesser-known languages.

For corrections, suggestions, and contributions, you can use [GitHub Issues](https://github.com/avysmorfias/mansi-memes/issues) or contact me directly at **[beeressence@gmail.com](mailto:beeressence@gmail.com)**.

## License and Copyright
Original material created for this repository, including original translations, descriptions, and other original text and data, is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Mansi expressions and other linguistic material come from dictionaries, books, lessons, recordings, and other sources listed in [`data/sources.json`](./data/sources.json). Third-party images used in the memes are not covered by this license.

Images created by the repository author, such as original photographs or screenshots, are also not covered by this license unless explicitly stated otherwise.

See [`LICENSE`](./LICENSE) for the full licensing and copyright information.
