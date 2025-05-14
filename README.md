# Image-filter
Image filtering program written in C as part of Harvard's CS50x course. Applies grayscale, sepia, reflect, and blur effects to BMP images.

# 🎨 Image Filter in C

This project is a simple image filtering tool written in C, developed as part of the **CS50x** course by Harvard University. It allows basic manipulation of BMP images, including:

- Grayscale
- Sepia
- Horizontal Reflection
- Blur

## 🛠️ How It Works

The program reads a 24-bit BMP image file and applies one of several filters. It processes each pixel of the image and outputs a modified version.

### Filters Implemented:

- **Grayscale**: Converts the image to shades of gray.
- **Sepia**: Applies a warm, antique-like effect.
- **Reflect**: Mirrors the image horizontally.
- **Blur**: Averages the colors of neighboring pixels to soften the image.

## 📁 Files

- `filter.c` – Main logic for applying filters.
- `helpers.c` – Implementation of the filter functions.
- `helpers.h` – Function declarations.
- `Makefile` – For compiling the project 
