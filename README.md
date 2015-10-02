# style: fonts and CSS

## Markdown to HTML

```Bash
pandoc --number-sections -c https://cdn.rawgit.com/wdbm/style/master/SS/newswire.css example_1.md > example_1.html
pandoc --number-sections -c https://cdn.rawgit.com/wdbm/style/master/SS/ATLAS_Briefings.css example_1.md > example_2.html
pandoc --number-sections -c https://cdn.rawgit.com/wdbm/style/master/SS/ATLAS_Briefings_TTHbbLeptonic.css example_1.md > example_3.html
pandoc --table-of-contents --number-sections -c https://cdn.rawgit.com/wdbm/style/master/SS/newswire_TTHbbLeptonic.css example_1.md > example_4.html
pandoc --number-sections -c https://cdn.rawgit.com/wdbm/style/master/SS/darkscale.css example_2.md > example_5.html
```

```Bash
pandoc --number-sections -c SS/darkscale.css example_1.md > example_5.html
```

## examples

- <http://htmlpreview.github.io/?https://raw.githubusercontent.com/wdbm/style/master/example_1.html>
- <http://htmlpreview.github.io/?https://raw.githubusercontent.com/wdbm/style/master/example_2.html>
- <http://htmlpreview.github.io/?https://raw.githubusercontent.com/wdbm/style/master/example_3.html>
- <http://htmlpreview.github.io/?https://raw.githubusercontent.com/wdbm/style/master/example_4.html>
- <http://htmlpreview.github.io/?https://raw.githubusercontent.com/wdbm/style/master/example_5.html>
