# REBASE --onto

## Transplant

To transplant a topic branch based on one branch (subsystem) to another (main)

```fs
o---o---o---o---o  master
     \
      o---o---o---o---o  next
                       \
                        o---o---o  topic
```

```fs
o---o---o---o---o  master
    |            \
    |             o'--o'--o'  topic
     \
      o---o---o---o---o  next
```

## Replace part of a branch

Another example of --onto option is to rebase part of a branch. If we have the following situation:


## Reference

https://git-scm.com/docs/git-rebase
