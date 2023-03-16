# Pet Breed Names

Looking for comprehensive lists on dog and cat breeds in English and Dutch? Our module has got you covered, complete with extensive lists and a convenient random breed helper.

## Install

`npm install pet-breed-names --save`

## Usage

```javascript
import { dogBreeds, randomCatBreed } from 'pet-breed-names';

// Iterate through the list of all the English names of dog breeds
dogBreeds.en.map((breed) => {
  ...
});

// Get a random breed of cat in Dutch
randomCatBreed('nl')
```
