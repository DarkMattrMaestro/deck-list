# DarkMattrMaestro's Decks

Decks for each card game are stored in `<Card Game Name>/decks.txt`.

## Why use a Git repository?

Storing the version history of decks I build will allow me to revert back if new modifications don't work.

## Format

Version numbers are formatted similarly to [Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html).

### Digimon TCG:
```
# Name: <Name>
# Based on: <Deck Name/Description> (<Link/Source>)
# Description {
  <Description>
}
# Version: <SemVer Version>
<Number of Copies> <Card Name>   <Card-ID>
...
<Number of Copies> <Card Name>   <Card-ID>
```
