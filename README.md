# Rails API Starter

Getting projects up and running can be time consuming. This is a simple starter rails 6 app for quickly creating JSON APIs. Preconfigured with devise auth token authentication.

## Usage
To get the app set up git clone and run `bundle install` to install all required dependencies. This app is configured to be paired with it's sister front-end react, angular or vusjs app

### Server
You can start the server with a standard `rails s`

### Testing
This app uses rspec for testing and guard to monitor changes and auto-run any changed specs. `bundle exec guard` will start guard and monitor files for changes. `bundle exec rspec` will run the entire test suite. Simplecov is also included for code coverage metrics and will automatically be run with the test suite.
