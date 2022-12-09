Build image

```bash
build -t mkdocs .
```

Start development server

```bash
docker run -it --rm --name MkDocs -p 8001:8000 -v ${PWD}:/docs mkdocs
```