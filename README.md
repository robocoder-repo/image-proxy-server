# Image Proxy Server

This is a simple image proxy server that allows you to fetch images from external URLs while hiding the original source.

## Setup

1. Clone this repository
2. Run `npm install` to install dependencies
3. Start the server with `npm start`

## Usage

To use this proxy server, make requests to:

```
http://your-server-url/proxy?url=IMAGE_URL
```

Replace `IMAGE_URL` with the URL-encoded address of the image you want to fetch.

## Example

```html
<img src="http://your-server-url/proxy?url=https%3A%2F%2Fexample.com%2Fimage.jpg" alt="Proxied Image">
```

## Deployment

This server can be easily deployed to platforms like Heroku or Vercel.

