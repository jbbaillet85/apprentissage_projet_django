# Configuration de git

## Téléchargement et installation

https://git-scm.com/downloads

## Configuration de git

https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Param%C3%A9trage-%C3%A0-la-premi%C3%A8re-utilisation-de-Git

Git contient un outil appelé git config pour vous permettre de voir et modifier les variables de configuration qui contrôlent tous les aspects de l’apparence et du comportement de Git.

### Identité

La première chose à faire après l’installation de Git est de renseigner votre nom et votre adresse de courriel. C’est une information importante car toutes les validations dans Git utilisent cette information et elle est indélébile dans toutes les validations que vous pourrez réaliser :
```
git config --global user.name "jbbaillet"
git config --global user.email jbbaillet.dev@gmail.com
```

### Editeur de texte

À présent que votre identité est renseignée, vous pouvez configurer l’éditeur de texte qui sera utilisé quand Git vous demande de saisir un message. Par défaut, Git utilise l’éditeur configuré au niveau système, qui est généralement Vi ou Vim.

Si vous souhaitez utiliser un éditeur de texte différent, comme Nano, vous pouvez entrer ce qui suit :
```
git config --global core.editor nano
```

### Vérifier la configuration
```
git config --list
```

### Initialiser git

```
touch .gitignore
git init
```

