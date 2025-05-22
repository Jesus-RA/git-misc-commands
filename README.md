# Coding with <code>@jra_dev</code> 👨🏻‍💻

## git misc commands

> From jr to ? 🚀
> 
> Follow for more coding content 🤓 👨🏻‍💻


### Delete changes accidentally pushed to remote repository

```shell
git push --delete origin <branch_name>
```

### Reset to previous commit and delete changes
```shell
git reset --hard HEAD~N
```

### Reset to previous commit but keeping last commit changes
```shell
git  reset --soft HEAD~N
```