# Updating subtrees

## Add remotes
```
git remote add -f lunajson https://github.com/grafi-tt/lunajson.git
```

## Fetch and update
```
git fetch lunajson
git subtree pull --prefix lunajson lunajson master --squash
```
