# Photo Crop Resize & Print

**Photo Crop Resize & Print** is a simple browser-based tool for preparing photographs for digital use and printing.

It allows you to either:

* **Crop and resize a photo to exact pixel dimensions**, or
* **Prepare a photo for printing at an exact physical size**, specified in centimetres or inches and at a selected PPI.

The application can also create an **A4 PDF containing 1, 4, or 9 copies** of the photograph.

## Features

<img width="1280" height="1024" alt="WhatsApp Image 2026-09-27 at 12 29 40 PM" src="https://github.com/user-attachments/assets/1b0b9652-b511-4fbb-92f7-8087d307d90f" />


### 1. Pixel Size

Select a photograph and enter the required:

* Width in pixels
* Height in pixels

The app automatically crops the photograph to the required aspect ratio and then resizes it to the exact pixel dimensions.

For example:

**400 × 514 pixels**

This is useful for applications such as passport, visa and other online photo requirements where an exact pixel size is specified.

The resulting photograph is saved as a JPEG file.

### 2. Print Size

Instead of specifying pixels, you can specify the physical size at which you want the photograph prepared for printing.

You can enter:

* Width in **cm or inches**
* Height in **cm or inches**
* **PPI (pixels per inch)**

The application calculates the required pixel dimensions from the physical size and PPI, then automatically crops and resizes the photograph accordingly.

For example:

**4 × 5 cm at 300 PPI**

produces an image of approximately:

**472 × 591 pixels**

### 3. A4 PDF

The Print Size option can create an A4 PDF containing multiple copies of the photograph.

Available layouts are:

* **1 × 1** — 1 photograph
* **2 × 2** — 4 photographs
* **3 × 3** — 9 photographs

The photographs are placed on an A4 page with equal spacing while maintaining the exact physical dimensions specified.

This can be useful when several copies of the same photograph are required for printing.

## Automatic Cropping

The application does not simply stretch a photograph to fit the requested dimensions.

Instead, it:

1. Determines the aspect ratio of the original photograph.
2. Determines the aspect ratio required by the user.
3. Crops the excess portion from the photograph.
4. Resizes the cropped image to the required pixel dimensions.

This helps preserve the proportions of the subject in the photograph.

## Privacy

The photograph is processed **in the browser on your own device**.

The application does not require the photograph to be uploaded to a server for processing.

## Where It Works

The application is designed to work in modern web browsers on:

* iPhone and iPad
* Android devices
* Windows computers
* Mac computers

The application is hosted using GitHub Pages and can be accessed directly through the web.

## Example

Suppose you have a photograph from a mobile phone and need a **4 × 5 cm photograph at 300 PPI**.

Simply:

1. Select the photograph.
2. Choose **Print Size**.
3. Enter **4 cm** for width.
4. Enter **5 cm** for height.
5. Enter **300 PPI**.
6. Select the required number of photographs per A4 page.
7. Select **Create PDF**.

The application automatically performs the required cropping and resizing and creates an A4 PDF ready for printing.

## Why This Tool Was Created

Many photo requirements specify either an exact **pixel size** or an exact **physical print size**. Converting between pixels, physical dimensions and PPI can otherwise require separate software or manual calculations.

This tool brings these operations together in one simple interface.

## Technology

The application is built using standard web technologies:

* HTML
* CSS
* JavaScript
* HTML Canvas for image processing
* jsPDF for creating PDF files

No installation is required. Simply open the web application in a browser and select a photograph.

## Application

**Photo Crop Resize & Print**

[Open the application](https://natsy1944.github.io/Photo-Crop-Resize/)
