![](.pic/cover3.jpg)

# HOW TO MIGRAR REPOSITORIOS/PROJETOS GIT

para fazer isso é muito simples segue os comando abaixo, esse comandoos migram tudo, branhcs, commits, tags e etc.

baixando o repositorio/projeto

```bash
git clone --mirror <url_do_repo> repo/.git
cd repo/.git
```

subindo em novo repo:

```bash
git push --mirror <url_do_repo_destino>
```
