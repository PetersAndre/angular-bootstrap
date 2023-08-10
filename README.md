# angular-bootstrap

@angular 16.2.0<br>bootstrap 5.3.1

## Steps

### 1. Create the project

    ng new angular-bootstrap --standalone --skip-tests --routing --style sass

### 2. Install bootstrap

    cd angular-bootstrap
    npm i bootstrap@5.3.1

### 3. Import bootstrap

    // styles.sass

    @import 'node_modules/bootstrap/scss/bootstrap'

### 4. Add scripts

    // angular.json

    ...
    "scripts": [ "./node_modules/bootstrap/dist/js/bootstrap.min.js" ]
    ...
