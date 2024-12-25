# Documentation

This repository contains several useful Nautilus scripts to enhance your file management experience. Below is the documentation for each script.

## Images to PDF

This script converts selected image files into a single PDF.

### Usage
1. Select the image files you want to convert.
2. Run the `Images to PDF` script.
3. The script will create a PDF with the current date and time as the filename.

### Requirements
- ImageMagick (`convert` command)

## OCR (Image)

This script performs Optical Character Recognition (OCR) on selected JPEG images and saves the extracted text to a file.

### Usage
1. Select the JPEG images you want to process.
2. Run the `OCR (Image)` script.
3. Enter the OCR language when prompted.
4. The script will save the extracted text to a `.txt` file with the same name as the image.

### Requirements
- Tesseract OCR

## Merge PDFs

This script merges multiple PDF files into a single PDF.

### Usage
1. Select at least two PDF files.
2. Run the `Merge PDFs` script.
3. Choose the output file name and location.
4. The script will merge the PDFs into the specified file.

### Requirements
- `pdfunite` command

## Split PDF to Images

This script splits each page of a selected PDF into separate JPEG images.

### Usage
1. Select a PDF file.
2. Run the `Split PDF to Images` script.
3. The script will create a directory with the PDF name and save each page as a JPEG image.

### Requirements
- `pdftoppm` command

## Install Fonts

This script installs selected font files to the local user's font directory.

### Usage
1. Select the font files you want to install.
2. Run the `Install fonts` script.
3. The script will copy the fonts to `~/.local/share/fonts/`.

### Requirements
- None
