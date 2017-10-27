
# Swagger UI API console theme, forked from [Jens Oleg](https://github.com/jensoleg/swagger-ui)

[Live Demo](http://swaggerui.herokuapp.com/?url=http://petstore.swagger.io/v2/swagger.json) 

# To make changes to the UI

#### Install npm & gulp

- `brew install npm`
- `npm install gulp-cli -g`
- `npm install gulp -D`

- Edit the hamlbars files in src/main/template
- Running `gulp` compiles the files to the dist directory

# To run the UI a browser

`cd dist`
`python -m SimpleHTTPServer 8000`
