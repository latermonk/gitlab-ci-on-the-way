#  golang  ci demo

##  Task

https://taskfile.dev/#/installation


##  ci 

**Taskfile.yml**
```
version: '3'

tasks:
  build:
    cmds:
      - go build -v -i main.go

  assets:
    cmds:
      - minify -o public/style.css src/css
```

