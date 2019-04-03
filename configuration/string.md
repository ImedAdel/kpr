## To Lower Case

```CPP
transform(all(word), word.begin(), ::tolower);
```

## Erase All Occurences of `a` in `word`

```CPP
word.erase(remove(all(word),'a'), word.end());
```
