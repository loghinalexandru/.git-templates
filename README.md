# .git-templates
Repo used in order to centralize all my git hooks scripts

# Usage
```
cd ~/.
git clone https://github.com/loghinalexandru/.git-templates
git config --global init.templateDir ~/.git-templates/src
```

You need to reinit your old repositories via ```git init``` since only the newly cloned ones will have the template applied

**NOTE: This does not work for repositories with ```git submodule``` enabled, remove the ```fetch``` line from the config**
