# Memory Underground

Convert a list of memories into a subway map http://memoryunderground.brianfoo.com/

## Running locally

1. Install [Node.js](https://nodejs.org/)
2. Clone this repository:

   ```
   git clone https://github.com/apjmason/memory-underground.git
   cd memory-underground
   ```
   
3. Install and run the server

   ```
   npm install connect serve-static
   node server.js 8888
   ```
   
4. Then go to [localhost:8888/](http://localhost:8888/)

## Creating and saving new maps

1. Create a new map using the GUI interface and tweak until you're satisfied
2. Save the png and svg outputs from the Finish & View tab
3. To save the data, you must find it in [browser localStorage]([url](https://developer.chrome.com/docs/devtools/storage/localstorage)) and paste into a json file
