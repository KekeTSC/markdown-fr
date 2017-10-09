# Titres

Lorsque l'on commence un docuement Markdown, nous devons ajouter un titre et des sous-titres.

Markdown supporte deux styles de titres, Setext et atx.

Les titres de style Setext sont "soulignés" en utilisant des signes egal (pour ceux de niveau 1) et des tirés (pour ceux de niveau 2). Par exemple:

```
Voici un H1
=============


Voici un H2
-------------
```

Quelque soit le nombre de soulignement = ou - cela fonctionnera

Les titres de style Atx utilise des un nombre en 1 et 6 de dièses au debut de la ligne, correspondants au niveau de titre compris entre 1 et 6. Par exemple: 

```
# Voici H1

## Voici un H2

###### Voici un H6
```


Optionellement, vous pouvez "fermer" les titres de style atx. C'est purement esthetique - vous pouvez les utiliser si vous pensez que cela rend mieux. Les dièses de fermage ne doivent pas necessairement correspondrent avec le nombre utilisé pour ouvrir le titre. :

```
# Voici un H1 #

## Voici un H2 ##

### Voici un H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---


