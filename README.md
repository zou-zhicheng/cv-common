# 1. cv-mkdocs
This is a template project that write and publish your CV in github pages using mkdocs

# 2. Installation
## 2.1 install python
## 2.2 install mkdocs
```bash
pip install mkdocs
pip install mkdocs-material
```

## 2.3 create a project using mkdocs
```bash
mkdocs new you-project
cd you-project
mkdocs build 
mkdocs serve
```

## 2.4 create a github repository
![github create repository](./images/github01.png)

## 2.5 attach project with repository
```bash
cd you-project

# attach
echo "# you-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/zou-zhicheng/you-project.git
git push -u origin main
```

## 2.6 deploy
```bash
mkdocs gh-deploy
```

# 3. Origin
Fork from [https://github.com/sachint2202/mkdocs-resume](https://github.com/sachint2202/mkdocs-resume) and make some changes

# 4. codecv
`CodeCV.pdf` 由 `CodeCV.md` 在平台 https://codecv.top/ 上生成