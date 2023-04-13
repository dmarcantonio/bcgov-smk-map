# bcgov-smk-map
Quick leaflet map using the bcgov's Simple Map Kit. 

- [Included Layers](#included-layers)
- [How to install](#how-to-install)
- [How to use](#how-to-use)

<img width="1007" alt="image" src="https://user-images.githubusercontent.com/1136023/231861548-eb3fdbfb-3cc1-474b-9693-a5a955769d7f.png">

## Included Layers

- Special Protection Areas - All - Colour Filled _(Visible by default)_
- Forest Development Units ( 1417 ) _(Visible by default)_
- Walk-in Clinics _(Visible by default)_
- Urgent and Primary Care Centres _(Visible by default)_
- Distribution of California Sealions - Coastal Resource Information Management System (CRIMS) ( 3730 )
- Distribution of Dall's Porpoises - Coastal Resource Information Management System (CRIMS) ( 3720 )
- Distribution of Gray Whales - Coastal Resource Information Management System (CRIMS) ( 3721 )
- Distribution of Harbour Porpoises - Coastal Resource Information Management System (CRIMS) ( 3722 )
- Distribution of Harbour Seals - Coastal Resource Information Management System (CRIMS) ( 3724 )
- Distribution of Humpback Whales - Coastal Resource Information Management System (CRIMS) ( 3725 )
- Distribution of Killer Whales - Coastal Resource Information Management System (CRIMS) ( 3726 )
- Distribution of Northern Fur Seals - Coastal Resource Information Management System (CRIMS) ( 3727 )
- Distribution of Pacific White Sided Dolphins - CRIMS ( 3728 )
- Distribution of Sea Otters - Coastal Resource Information Management System (CRIMS) ( 3729 )
- Distribution of Steller Sealions - Coastal Resource Information Management System (CRIMS) ( 3731 )

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
