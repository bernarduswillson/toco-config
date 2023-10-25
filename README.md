# toco-config

### Cloning
bash
git clone --recurse-submodules https://gitlab.informatika.org/toco-2/toco-config.git

### Pushing changes
1. go to the submodule directory first and checkout to main branch
```bash
cd toco-config
git checkout main
```
2. then work in it like usual. After done, commit and push the submodule
```bash
git add .
git commit -m "message"
git push
```
3. then go back to the main directory (__config__)
```bash
cd ..
```
4. then push the main directory (__config__)
```bash
git add .
git commit -m "message"
git push
```

### Update Config / Pulling latest changes in submodule

git submodule update --recursive --remote
