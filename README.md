# this-commit

A repository of self-referential Git commits: commits whose subject line states
the very prefix that their own SHA-1 begins with.

```
This commit has hash 7a91c
```

...where the commit's real object id is `7a91c...`. The text and the hash agree,
even though the text was written before the hash existed :o

## Branches

Each mined result lives on its own ref (for example `self-hash`) so the main
branch stays clean.
