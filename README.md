# Introduction

A Database containing data from the various pokemon games.

# Questions

  1. Highest base attack stat
  2. Highest speed pokemon that was introduced in version 1
  3. Some pokemons have unique ability.  Output pokemon name and
     it's associated unique ability name, sort by pokemon name ascending
  4. Pokemon that belong to both 'flying' and 'fighting' types.
  5. Generation 1 pokemon with more than 1 evolution triggers
  6. Find out all generation 1 pokemon that were evolved from later generations.
     For example, Pikachu is from generation 1, but is evolved from pichu,
     a generation 2 pokemon.
  7. Some pokemons can evolve into mulitple species, find out the name of these
     pokemons and how many species they are evolve into.


# Notes

Data generated via https://github.com/veekun/pokedex.  I needed to
download and install the code, then run the `pokedex load` command
and extract the pokedex.sqlite file.
# Hand-in

Test your solution by executing the following command on the bash terminal:

```shell
$ pytest
```

When you are satisified, execute the following commands to submit:

```shell
$ git add -A
$ git commit -m 'submit'
$ git push
```
