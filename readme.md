# node resolve + symlink issue

This works:

```
node -e "import('a')"
```

However, this stopped working from v7.1.0:

```
node --experimental-specifier-resolution=node -e "import('a')"
```
