# stem
A website for the not so well covered STEM concepts

## Project structure

### src/
backend, Java classes

### web/
front end related files

### web/static/
front end pages to serve

## Server endpoints

### /api/
server api calls

### /static/
corresponding files in `web/static` directory

### / (all other requests)
serve  `web/static/index.html`. These requests should be assumed as user viewable pages, which the index.html file will handle.
