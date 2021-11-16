# confslist
Conferences list for https://t.me/getconf


To convert:

 docker run --rm --volume "`pwd`:/data" --user `id -u`:`id -g` pandoc/latex:2.6 -f gfm %filename.md% -o %output.html%
