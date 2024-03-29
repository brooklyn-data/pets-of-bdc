# Pets of Velir including BDC (a Velir Company)

This is a place where the BDC and Velir teams post pictures of their pets.

Want to meet our friends? Head to [petsofbdc.netlify.app](https://petsofbdc.netlify.app/)

## A little note about this website

Forked from the OG: [petsofnetlify](https://github.com/netlify/petsofnetlify). We're grateful to them for the inspiration. 🐱🫶🐶

## You are a BDCer or Velirian but your pet is missing?

Well that won't do. If your little friend is missing from this site please submit a pull request. But this site is just for the pets of people working at BDC or Velir (and our beloved alumni) I'm afraid. To get your pet on here, you first have to _[join us](https://www.brooklyndata.co/careers)_

## Contributing code or pets (!)

Please submit a pull request! To add your pet, you need to give us a photo of your lovely pet, and their name. Add the details to the [pets.json](src/_data/pets.json) data file like this:

```json
  {
    "name": "Your pet's name",
    "photo": "your-pets-photo.jpg",
    "owner": "your name"
  }
```

Then add a nice photo to the [images folder](src/images). It's best not to use a very large image file (no larger than 1600x1200) - holler if you need help resizing your image!

## Running locally

Want to tinker with the code?

```sh
# if you don't have node 
brew install node

# clone the repo
git clone git@github.com:brooklyn-data/pets-of-bdc.git

# move into the project and install dependencies
cd pets-of-bdc
npm install

# generate the site and watch for changes
npm start
```
