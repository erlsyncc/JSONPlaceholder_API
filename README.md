# SVG Converter Web App

A simple web application that converts uploaded images into SVG (Scalable Vector Graphics) using the SVG.new API.

## Project Description

This project is a browser-based SVG converter application built using HTML, CSS, and JavaScript. Users can upload an image file and send it to the SVG.new API for vector conversion. The generated SVG output is displayed directly on the webpage.

## Features

- Upload PNG, JPG, JPEG, or WEBP images
- Convert images into SVG format using SVG.new API
- Display generated SVG output directly in the browser
- Preview converted vector artwork
- API response handling
- Error messages for failed requests
- Simple and responsive user interface

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Fetch API
- SVG.new API

## Project Structure

```
project/
│
├── public/
│   ├── css/
│   ├── js/
│   └── uploads/
│
├── views/
│   ├── index.html
│
├── routes/
│   └── api.js
│
├── app.js
├── package.json
├── .env
└── README.md
```

## Installation

1. Clone the repository.

```bash
git clone https://github.com/yourusername/svg.git
```

2. Navigate to the project folder.

```bash
cd svg
```

3. Open the application.
You can run the project by opening:

```bash
index.html
```

## How It Works

1. The user uploads an image.
2. The server sends the image to the SVG.new API.
3. The API processes the image and generates an SVG.
4. The application displays the SVG.
5. The user can download the generated SVG.

## API Used

SVG.new API

Documentation:
https://svg.new/

## Error Handling

The application handles:

- Invalid file uploads
- Missing image files
- API request failures
- Network connection errors
- Server errors

## Future Improvements

- Drag and drop image upload
- Image preview before conversion
- Conversion history
- User authentication
- Dark mode

## Author/s

- Combenido, Earlsin Mae G.
- Consigo, Rica Mae G.
- Tariao, Bernadette B.

## License

This project is created for educational purposes.
