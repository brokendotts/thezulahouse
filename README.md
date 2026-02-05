# The Zula House - PDF Viewer

A simple, elegant HTML-based PDF viewer for displaying documents.

## Features

- 📄 Full-screen PDF display using iframe
- 🎨 Modern gradient design
- 📱 Responsive layout
- 🚀 Ready for Vercel deployment

## Project Structure

```
zulahouse/
├── index.html          # Main HTML page
├── style.css           # Styling
├── public/             # PDF files directory
│   └── TZH SINGLE SWINGS.pdf
├── vercel.json         # Vercel configuration
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## Local Development

Simply open `index.html` in your web browser to view the PDF.

## Deployment

### Deploy to Vercel

1. Install Vercel CLI (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

3. Follow the prompts to complete deployment.

### Or use Vercel Dashboard

1. Push your code to GitHub
2. Import the repository in [Vercel Dashboard](https://vercel.com)
3. Deploy with one click

## Configuration

To change the PDF being displayed, update the `src` attribute in `index.html`:

```html
<iframe src="/public/YOUR_PDF_FILE.pdf" class="pdf-iframe" title="THE ZULA HOUSE" frameborder="0">
</iframe>
```

## License

MIT
