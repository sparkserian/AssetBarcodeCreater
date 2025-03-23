# Asset Barcode Creation System

A browser-based barcode design and print web application for Partners in Child Development IT department. This application allows users to generate batches of barcode labels, automatically design them in a 2" x 1" label layout, and export to PDF or print directly via Rollo or any thermal label printer.

## Features

- **Simple Authentication**: User verification system with authorized personnel access
- **Batch Barcode Generation**: Generate multiple barcodes at once with sequential numbering
- **Customizable Prefix**: Set custom prefixes for your asset tracking system
- **Multiple Barcode Types**: Support for CODE128, CODE39, EAN13, and UPC formats
- **High-Resolution Output**: Generates barcodes at 600x300 pixels for optimal printing quality
- **Multiple Preview Modes**: Grid, list, and single view options for easy review
- **Export Options**: One-click export to PDF or CSV
- **Direct Printing**: Print directly to thermal label printers
- **Responsive Design**: Works on desktop and tablet devices
- **Customizable Settings**: Adjust font size, padding, and other parameters


## Technologies Used

- **Next.js**: React framework for the frontend
- **Tailwind CSS**: For styling and responsive design
- **Framer Motion**: For smooth animations and transitions
- **JsBarcode**: For barcode generation
- **jsPDF**: For PDF export functionality
- **shadcn/ui**: For UI components


## Installation

1. Clone the repository:

```shellscript
git clone https://github.com/sparkserian/AssetBarcodeCreater.git
cd AssetBarcodeCreater
```


2. Install dependencies:

```shellscript
npm install
# or
yarn install
# or
pnpm install
```


3. Run the development server:

```shellscript
npm run dev
# or
yarn dev
# or
pnpm dev
```


4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.


## Usage Guide

### Authentication

The application features a simple authentication system. Only authorized personnel can access the application:

- Authorized users: You can hard-code whatever name you want or use a different authentication system
- Enter your name at the splash screen to gain access


### Generating Barcodes

1. **Set Prefix**: Enter a prefix ending with a number (e.g., DELL-LAW-100)
2. **Set Quantity**: Choose how many sequential barcodes to generate
3. **Adjust Settings** (optional):

1. Number padding
2. Uppercase/lowercase
3. Barcode type
4. Font size
5. Label size



4. **Click "Generate Barcodes"**


### Preview and Export

- Use the preview tabs to view generated barcodes in different layouts
- Export options:

- **Export CSV**: Save barcode data as a CSV file
- **Export PDF**: Generate a PDF with one barcode per page, sized for labels
- **Print Labels**: Send directly to your printer





## Label Specifications

The application is optimized for 2" x 1" thermal labels, commonly used for asset tracking. Each barcode is generated at 600x300 pixels for optimal print quality.

## Deployment

This application can be deployed to Vercel with a single click:

[

](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyourusername%2Fpcd-asset-labeling-system)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [JsBarcode](https://github.com/lindell/JsBarcode)
- [jsPDF](https://github.com/MrRio/jsPDF)
- [Framer Motion](https://www.framer.com/motion/)
- [shadcn/ui](https://ui.shadcn.com/)



Developed with ❤️ for Partners in Child Development
