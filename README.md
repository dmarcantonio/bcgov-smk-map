# bcgov-smk-map
Quick leaflet map using the bcgov's Simple Map Kit

## How to install

1. Install [NodeJS](https://nodejs.dev/en/learn/how-to-install-nodejs/)

1. Clone this repository:

    ```sh
    git clone git@github.com:dmarcantonio/bcgov-smk-map.git
    ```

1. Install the dependencies:

    ```sh
    cd bcgov-smk-map
    npm install
    ```

## How to use

1. Add your ESRI API Key to `./smk-config.json`

  ``` json
        "esriApiKey": "{{YOUR API KEY HERE}}",
        "baseMap": "Imagery"
  ```

2. Run the application:

    ```sh
    npm run view
    ```

## License

This project is licensed under the [Apache 2.0 License](LICENSE).
