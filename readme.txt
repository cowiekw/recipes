## Tips

View the [official documentation](https://cooklang.org/docs/getting-started/)

Import recipes by adding cook.md/ before the full URL in your browser's address bar (e.g., https://cook.md/https://bbcgoodfood.com/recipes/easy-pancakes/).

* In a code editor open a new directory where the project should live. 
** If you have VSCode, Vim, or Sublime install the [CookLang exension](https://cooklang.org/docs/getting-started/)
* Install GitHub's [command line interface](https://github.com/cli/cli#installation) via ``brew install gh``
** On a mac you'll need homebrew.
* Authenticate to Github
* Clone the repository using SSH or the CLI
** You may need your GitHub SSH key downloaded to your device, e.g. /Users/yourame/.ssh/id_ed12445.pub

```
# Clone with SSH
run ssh -T git@gitlab.com`
git clone git@github.com:cowiekw/recipes.git

# Or clone with Github's CLI
gh auth login
gh repo clone cowiekw/recipes
```

