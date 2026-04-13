# DeBrown
An application for RISC OS to remove staining from scanned PDFs

## Introduction
The .zip file, debrown.zip, contains a RISC OS application !DeBrown which is intended to remove staining from scans supplied as PDF files. It is suitable for modern RISC OS machines running RISC OS 5, and supporting VFP and Neon.

You will need to have Image Magick 7 installed, You can find this on Chris Gransdden's site https://riscosports.co.uk — !DeBrown checks for the existence of this program before processing the input file.

You will also need to have PDFUtils installed — specifically the program makes use of *pdfimages* to process the PDF file and convert it into images. Ghostscript is also required, but you probably have this anyway.

## Use
Run **!DeBrown** by double-clicking on the app. This will place an icon on the icon bar. Drag a PDF file to that icon. In due course, a save box for a PDF file will appear and you simply save this in the usual way.

This program uses the *sigmoidal-contrast* feature of ImageMagick 7 to do the de-browning.
