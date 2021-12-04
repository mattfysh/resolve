# works

node -e "import('a')"

# doesn't work

node --experimental-specifier-resolution=node -e "import('a')"
