# Squirdle

## Project Summary

Squirdle is a Pokémon-themed version of the popular game Wordle. The application's frontend is designed using Vue and Sass, supported by a backend of Node/Express and MongoDB, and deployed through Heroku. Assets and data have been scraped from Serebii, PokéAPI, and Project Pokémon.

The most up-to-date version of Squirdle is currently deployed at: https://squirdle.herokuapp.com.

##  Tools Used

[![img](https://camo.githubusercontent.com/50d43af9b68ef63015963f40aac894898d7c655ed221f0bce5013787a68aba26/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5675652e6a732d3335343935453f7374796c653d666f722d7468652d6261646765266c6f676f3d767565646f746a73266c6f676f436f6c6f723d344643303844)](https://camo.githubusercontent.com/50d43af9b68ef63015963f40aac894898d7c655ed221f0bce5013787a68aba26/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5675652e6a732d3335343935453f7374796c653d666f722d7468652d6261646765266c6f676f3d767565646f746a73266c6f676f436f6c6f723d344643303844)[![img](https://camo.githubusercontent.com/a1eae878fdd3d1c1b687992ca74e5cac85f4b68e60a6efaa7bc8dc9883b71229/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e6f64652e6a732d3333393933333f7374796c653d666f722d7468652d6261646765266c6f676f3d6e6f6465646f746a73266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/a1eae878fdd3d1c1b687992ca74e5cac85f4b68e60a6efaa7bc8dc9883b71229/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e6f64652e6a732d3333393933333f7374796c653d666f722d7468652d6261646765266c6f676f3d6e6f6465646f746a73266c6f676f436f6c6f723d7768697465)[![img](https://camo.githubusercontent.com/7f73136d92799b19be179d1ed87b461120c35ed917c7d5ab59a7606209da7bd3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f457870726573732e6a732d3030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d65787072657373266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/7f73136d92799b19be179d1ed87b461120c35ed917c7d5ab59a7606209da7bd3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f457870726573732e6a732d3030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d65787072657373266c6f676f436f6c6f723d7768697465)[![img](https://camo.githubusercontent.com/72e92f69f36703548704a9eeda2a9889c2756b5e08f01a9aec6e658c148d014e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6f6e676f44422d3445413934423f7374796c653d666f722d7468652d6261646765266c6f676f3d6d6f6e676f6462266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/72e92f69f36703548704a9eeda2a9889c2756b5e08f01a9aec6e658c148d014e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6f6e676f44422d3445413934423f7374796c653d666f722d7468652d6261646765266c6f676f3d6d6f6e676f6462266c6f676f436f6c6f723d7768697465)[![img](https://camo.githubusercontent.com/8849f369ac031cc842a4ab4248c7f7db6a4b593cad1f2d1c01d3aeb6f0f8dca7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f536173732d4343363639393f7374796c653d666f722d7468652d6261646765266c6f676f3d73617373266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/8849f369ac031cc842a4ab4248c7f7db6a4b593cad1f2d1c01d3aeb6f0f8dca7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f536173732d4343363639393f7374796c653d666f722d7468652d6261646765266c6f676f3d73617373266c6f676f436f6c6f723d7768697465)[![img](https://camo.githubusercontent.com/3bcc8da5c94cefdf2d976837d1be601f4d44d36b58d9590e36debe834a6e34de/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4865726f6b752d3433303039383f7374796c653d666f722d7468652d6261646765266c6f676f3d6865726f6b75266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/3bcc8da5c94cefdf2d976837d1be601f4d44d36b58d9590e36debe834a6e34de/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4865726f6b752d3433303039383f7374796c653d666f722d7468652d6261646765266c6f676f3d6865726f6b75266c6f676f436f6c6f723d7768697465)

## Project Status

This project is still under development. The base game is functional, but features are still being planned and added and more data is still being collected.

#### To Do:

- [ ] Implement medals
- [ ] Add Gen. V - VIII to the database
- [ ] Add share mechanism
- [ ] Implement persistence on refresh
- [ ] Add hard mode setting
- [ ] Add light mode setting
- [ ] Add tooltips

## Installation and Setup

Tools Required:

- NPM
- Node

1. Clone the repository onto your local machine:

   ```
   git clone https://github.com/czhangy/squirdle.git
   ```

2. Install all required dependencies:

   ```
   npm i
   ```

3. Start the server:

   ```
   npm run server
   ```

4. Start the application:

   ```
   npm run client
   ```

5. Open the application in your browser:

   https://localhost:8080

