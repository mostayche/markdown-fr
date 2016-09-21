# Links
# Liens

Markdown supports two styles of links: inline and reference.
Le Markdown supporte deux styles de liens : "inline" et "reference".

In both styles, the link text is delimited by [square brackets].
Le texte du lien est délimité par des [crochets] dans les deux cas.

To create an inline link, use a set of regular parentheses immediately after the link text’s closing square bracket. Inside the parentheses, put the URL where you want the link to point, along with an optional title for the link, surrounded in quotes. For example:
```markdown
Pour créer un lien "inline", utiliser un jeu de parentheses immédiatement après les crochets enfermant le texte du lien. A l'intérieur des parenthèses, mettez l'URL que vous désirez.

[I'm an inline-style link](https://www.google.com)
[Je suis un lien de type inline](https:/www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")
[Je suis un line de type inline avec un titre](https://www.google.com "Page d'accueil de Google")

[I'm a reference-style link][Arbitrary case-insensitive reference text]
[Je suis un lien de type reference][Texte de reference de case insensible de manière arbitraire]

[I'm a relative reference to a repository file](../blob/master/LICENSE)
```
[Je suis une reference relative à un dossier de fichiers](../blob/master/lICENSE)


Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:
```markdown
Les liens de tyoe reference utlise un second jeu de crochets, à l'interieur duquel vous placez un label de votre choix pour identifier votre lien:


This is [an example][id] reference-style link.
```
Exemple de lien de type reference [exemple][id].


You can optionally use a space to separate the sets of brackets:
```markdown
Vous pouvez accessoirement choisir d'utiliser un espace pour séparer les crochets:


This is [an example] [id] reference-style link.
```
Exemple de lien de type reference [exemple] [id].


Then, anywhere in the document, you define your link label like this, on a line by itself:
```markdown
Puis, n'importe où dans le document, vous definissez le label du lien comme ceci, sur une ligne:

[id]: http://example.com/  "Optional Title Here"
```
[id]:http://exemple.com/ "Titre Optionnel Ici"


**GitHub** and **GitBook** supports URL autolinking. They will autolink standard URLs, so if you want to link to a URL (instead of setting link text), you can simply enter the URL and it will be turned into a link to that URL.
**GitHub** et **GitBook* supportent l'autolinking URL :P... Blalblabla

---

Here's a quiz about markdown links.

Select the valid links:
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> The link text is delimited by [square brackets].

What are the correct informations from this link: ```[a link](http://google.fr "google")```
- [ ] the link is https://google.fr
- [x] the title of the link is "google"
- [ ] it'll show the text "google"
- [x] it'll show the text "a link"

> Links can have 3 parts: the text, the url and a title.

---

