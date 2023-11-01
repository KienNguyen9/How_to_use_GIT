# LESSION 5 - Config Repository
- user 
- history 
- 
# 1. Create a new repository 
```shell
git init L05_config_repository # create a repository 
cd L05_config_repository # change directory to L_05...
```
# 2. Read the config of new repo
- Who work in this repo
- 
```shell
git config -l # show the config of this repo
```
# 3. Read Global config 
```shell
git config -l --global
```

# 4. Read local config
```shell
git init -l -- local
```
# 5. Config global: 'user.name'
```shell
git config --global user.name "Kien Nguyen" 
```
# 6. Config global: 'user.email'
```shell
git config --global user.email "kierannguyen98@gmail.com" # email sign in github
```
# 7. Repeat the same steps above (5,6) for local
```shell
git config --local user.name "Kien Nguyen" 
git config --local user.email "kierannguyen98@gmail.com"
```