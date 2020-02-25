# pixelmap

## Features

- Image processing is done server side on a remote Python microservice, so the app loads quickly and is small in size
- Multiple language support
- Users can pick images from their camera roll, take a photo with their camera, or paste in a remote link to an image

## Screenshots

![Home](https://github.com/jonathandannel/pixelmap/blob/master/doc/home_view.jpg=450x)

![Pick and crop](https://github.com/jonathandannel/pixelmap/blob/master/doc/pick_and_crop.jpg=450x)

![Process photo](https://github.com/jonathandannel/pixelmap/blob/master/doc/process_photo.jpg=450x)
![Processed text](https://github.com/jonathandannel/pixelmap/blob/master/doc/processed_text.jpg=450x)

## TODO:

This is a work in progress currently being developed.

- Create docker container for building client APKs/deploying API
- Add multiple language `tessdata` to pytesseract path in API container
- Add some interaction to text data
- Add some nice loading states
- Work on the actual OCR and preprocessing to fix common text read errors
- Upload to Google Play/App Store
