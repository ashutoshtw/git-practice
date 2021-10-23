# Key Concepts  

- Key idea is **version snapshots** and not specific file related versioning  
- Commit saves changes to repository, its SHA1 hash is being used to identify a commit and it has direct impact on history of the repository  
- **HEAD** a pointer to last commit on a branch  
- **Remote** a pointer to remote repository and not local  

### Getting help

> `git help`  

- This will show help on all avaiable commands with git command line tool  


## Configurations

- Done at different levels such as global, system, working-tree, file etc..  
- global level configuration settings are tracked is in user's home directory i.e. ~, in .gitconfig file  

> `git config --global user.name "Ashutosh Singh"`

- Adds a new configuration key user.name with value "Ashutosh Singh"  
- Similarly any key can be added in the configuration files  
- Git internally or by convention uses some of the keys such user.name, user.email, user.password etc... for its own purpose  
- to fetch all the available config at a level use following command  

> `git config --global --list`  
>
> `git config --global -l`  

## Initializing a repository  

> `git init folder_name` #A fresh repository  
> `git init` #From inside an existing folder
