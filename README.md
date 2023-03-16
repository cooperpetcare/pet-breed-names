# Pet Breed Names

Looking for comprehensive lists on dog and cat breeds in English and Dutch? Our module has got you covered, complete with extensive lists and a convenient random breed helper. The source code for this library has been extracted from [Cooper Pet Care](https://cooperpetcare.com/)’s code base.

## Install

`npm install pet-breed-names --save`

## Usage

```javascript
import { dogBreeds, randomCatBreed } from 'pet-breed-names';

// Iterate through the list of English dog breed names
dogBreeds.en.map((breed) => {
  ...
});

// Generate a random cat breed in Dutch
randomCatBreed('nl')
```
