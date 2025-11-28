# Product Search Web App

A responsive web application that allows users to search for products and get links to products in a WhatsApp channel.

## Features

- Responsive design that works on mobile, tablet, and desktop
- External JSON file for product data management
- Search functionality with keyword matching
- Quick search buttons for common categories
- Loading indicator while fetching data
- Clean, modern UI with Tailwind CSS
- WhatsApp integration for product links

## Setup

1. Place all files in the same directory:
   - `index.html`
   - `products.json`

2. Open `index.html` in a web browser

## Customization

### Adding Products

Edit the `products.json` file to add your products:

```json
{
  "id": 9,
  "name": "Product Name",
  "description": "Product description",
  "price": "$XX.XX",
  "image": "https://example.com/image.jpg",
  "keywords": ["keyword1", "keyword2"],
  "whatsappLink": "https://wa.me/channel/your-channel-id?text=Product%20Name"
}