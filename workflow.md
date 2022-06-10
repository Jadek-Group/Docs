# GIT WORKFLOW
###### Pull from the staging branch to sync your local repository with recent changes

```git pull origin staging ```

###### Checkout new branch in here
###### Your new branch should contain the intended name of the task title after the category of the task you are working

###### task category includes ft=feature, bg=bug fixes, ch=simple modification

###### eg you are to design login page feature.
###### Your branch name should be ft_design_login_page

```git checkout -b ft_design_login_page```

###### Begin Your implementation
###### once done with your implementation, 
###### Add Changed File to staged

```git add . ```

###### commit your changes 
```git commit -am "full descriptions of what you did here"```

###### push your recent changes to your newly created branch 
###### like example below
```git push origin ft_design_login_page```
