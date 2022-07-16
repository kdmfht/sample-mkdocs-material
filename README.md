# Sample web site made with Mkdocs Material

### Document
https://squidfunk.github.io/mkdocs-material/getting-started/

### Installation with pipenv
```
pipenv install mkdocs-material
```
```
pipenv install fontawesome_markdown 
```
### Creating web site with pipenv
```
pipenv run mkdocs new .
```
This will create the following structure.
```
.
├─ docs/
│  └─ index.md
└─ mkdocs.yml

```
### Previewing with pipenv
```
pipenv run mkdocs serve
```
### Build with pipenv
```
pipenv run mkdocs build --clean
```