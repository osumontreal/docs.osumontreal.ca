---
title: Pause Méthode du SÉSAME à l'UQTR
menutitle: Pause Méthode - SÉSAME
chapter: false
draft: false
---

L'atelier démontra la pertinence et le potentiel d'utiliser et de combiner des
outils tels que Git, GitHub, R et RStudio dans un contexte de collaboration avec
d’autres, mais aussi avec vous-même. Aucune expérience en programmation n'est
nécessaire afin de profiter de l'atelier. Cet atelier vise à vous montrer
diverses possibilités afin d'optimiser votre environnement de travail pour vos
projets de recherche.

Ceci étant dit, si vous voulez suivre sur votre ordinateur en même temps que la
démonstration, plusieurs étapes sont pré-requises. Ces étapes consistent à bien
installer les différents logiciels s’ils ne sont pas déjà installés.

## Instructions d'installation

La grande majorité des étapes ci-dessous sont extraites et traduites à partir de
la magnifique ressource
[Happy Git and GitHub for the useR](https://happygitwithr.com/). Vous pouvez
consulter directement la ressource à partir de la section
_[I Installation](https://happygitwithr.com/github-acct.html)_ si vous êtes à
l’aise en anglais ou si vous voulez plus de détails. Sinon, veuillez continuer
votre lecture ci-dessous.

{{% notice info %}} **NB:** Bien installer et configurer tous les logiciels
nécessaires est honnêtement la moitié de la bataille lorsque nous adoptons Git
pour la première fois. Parfois l’installation se déroule sans problème, alors
que d’autres fois c’est plus difficile en raison des particularités entre les
différents ordinateurs (par exemple les systèmes d’exploitation Windows vs Mac
vs Linux). La bonne nouvelle est qu’une fois que les logiciels sont installés,
vous n’aurez plus à le faire sur cette machine. Lorsque vous aurez passé à
travers l’installation, récompensez-vous, car vous aurez complété la partie du
boulot la plus ennuyante! {{% /notice %}}

## Voici donc les étapes préalables:

### 1. Créez un compte sur [GitHub](https://github.com/).

C'est gratuit! Vous devez vous rendre au
[https://github.com](https://github.com) et cliquer sur
_[Sign up](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)_.

- Votre _username_ (nom d’utilisateur) vous sera fort utile lorsque vous
  synchroniserez vos travaux sur GitHub et il est public. Il s’agit de votre
  identifiant avec le monde, donc prenez soin de bien le choisir.
- Pour plus de trucs et astuces sur le choix d’un nom d’utilisateur, consultez
  la section
  _[Username advice](https://happygitwithr.com/github-acct.html#username-advice)_.

### 2. Installez ou mettez à jour [R](https://cloud.r-project.org/) et [RStudio](https://rstudio.com/)

1.  Installez d’abord [R](https://cloud.r-project.org/) pour votre système
    d'exploitation (Windows, Mac, Linux) en vous rendant au
    [https://cloud.r-project.org/](https://cloud.r-project.org/).

    - Si vous installer R pour la première fois, lisez attentivement les
      instructions, car elles sont différentes selon le système d’exploitation.
    - Vous voulez installer au moins la version `4.X.X` de R, car les versions
      `3.X.X` vous causeront probablement des problèmes dans le futur.

2.  Installez ensuite [RStudio](https://rstudio.com/) pour votre système
    d’exploitation (Windows, Mac, Linux) en vous rendant au
    [https://rstudio.com/products/rstudio/download/#download](https://rstudio.com/products/rstudio/download/#download).

### 3. Installez [Git](https://git-scm.com/)

1. Consultez les instructions d'installation en fonction de votre système
   d'exploitation à partir de
   [https://git-scm.com/downloads](https://git-scm.com/downloads).
2. Il se peut que Git soit déjà installé sur votre machine, surtout si vous
   utilisez un système d’exploitation Mac ou Linux, car Git est souvent
   pré-installé. Vous pouvez vérifier s’il est déjà installé ou tentez de
   l’installer et attendre que votre machine vous dise qu’il est déjà installé.
   - Pour vérifier si vous avez installé Git ou non, ouvrez un terminal/shell et
     tapez `git --version`. Si vous obtenez quelque chose similaire à
     `git version 2.25.1`, cela veut dire que git est bien installé et vous
     pouvez ignorez cette étape!
   - Le terminal/shell est un programme sur votre ordinateur dont le travail
     consiste à exécuter d'autres programmes. Les pseudo-synonymes sont «ligne
     de commande» et «console».
   - Les [instructions](https://happygitwithr.com/shell.html#outside-of-rstudio)
     pour ouvrir un terminal varie selon votre système d’exploitation.

### 4. Dites à Git qui vous êtes

{{% notice info %}} Cette étape est facultative si vous n'est pas à l'aise avec
RStudio ou un terminal. Nous la ferons ensemble pendant l'atelier au besoin.
{{% /notice %}}

#### Option A

Si vous êtes à l’aise d’ouvrir un terminal/shell
([Appendix A](https://happygitwithr.com/shell.html#shell)), ouvrez un terminal
et vous pouvez entrer ces lignes, une à la fois, avec les informations qui
correspondent à celles que vous avez entrées sur GitHub.

```bash
git config --global user.name 'Prénom Nom'
git config --global user.email 'votre@courriel.com'
git config --global --list # Vérifier les informations que vous venez d'entrer
```

{{% notice warning %}} Pour les personnes qui utilisent **Windows**: Il se peut
que vous rencontriez des obstacles que les gens sur Mac et Linux ne rencontrent
pas. Si vous rencontrez des difficultés sous Windows, considérez qu'il existe
différents types de shell et que vous vous trompez peut-être. Vous voulez être
dans un shell «Git Bash», par opposition à Power Shell ou à la ligne de commande
cmd.exe. Pour en savoir plus, consultez
[cette annexe](https://happygitwithr.com/shell.html#windows-shell-hell) de la
ressource originale. Cela pourrait également être une raison de faire cette
configuration via l'option B. {{% /notice %}}

## Option B

Pour utiliser l’approche alternative avec le
[package usethis](https://usethis.r-lib.org/), veuillez suivre ces commandes
afin de définir votre nom d'utilisateur et votre adresse e-mail dans Git à
partir de R et RStudio:

```r
install.packages("usethis")
library(usethis)
use_git_config(user.name = "Prénom Nom", user.email = "votre@courriel.com")
```

Félicitations, vous avez survécu à l'installation!

![](https://media.giphy.com/media/dRyXC8ICV1LsUlz4dF/giphy.gif)
