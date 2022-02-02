### Linux FAQ ###

`https://github.com/tchnmf/linux-faq`

---

#### [git] How to pull remote branch?
`git pull origin BRANCH_NAME`

#### [git] How to view the change history of a file in GIT?
```
git log -p FILENAME
gitk FILENAME
```

#### [shell] How to generate random UUID string?
```
uuidgen
uuidgen --sha1 --namespace @dns --name "www.example.com"
```

#### [shell] How to generate random string using openssl?
`openssl rand -hex 6`

#### [shell] How to generate passwords using pwgen?
`pwgen -n 16|head -1`
