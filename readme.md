# .io game history

![History of .io games graph](io-game-history.svg)

This is a graph of the evolution of io games.

Arrows represent "inspirations". If you think I am mistaken about a relationship, please open an issue or a PR. However, since this is quite open to interpretation, I might disagree with you and not change it.

I used the [Wayback Machine](https://web.archive.org/) to determine release dates. Please open an issue or a PR if a date is wrong, with a source such as a Wayback Machine entry or a release tweet by the creator.

This graphic is by no mean complete. Please submit a PR if you want to add a game. Please do not submit smaller games for now, as I would like to keep this graph readable. I will think of a way to include more of them later.

## How to generate this graph

```sh
$ dot -Tsvg io-game-history.gv > io-game-history.svg
```

## License

[![Licence Creative Commons Attribution 4.0 International](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
