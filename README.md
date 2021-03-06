# React DDD boilerplate

## Development
### Requirements
1. Yarn
2. NVM
3. Docker (Optional)

### Steps
* `nvm use`
* `yarn install` to install the dependencies
* `yarn start` to run the server on port 8080
* Open your browser on [http://localhost:8080](http://localhost:8080)

### Architecture
To separate web related concerns from core application logic, this boilerplate adopts a convention where code required to perfrom business requirements is situated in the `modules` directory, while code required to present the feature to the user stays in the `pages` directory.

## Production (or to try it out)
* `yarn run build` to compile code to ./static directory
