# Jeanius Digital

## Project Report

### Group Members:
- Sharjeel Ahmed 20K-0288
- Shazim Ali Mughal 20K-1032
- Sameer Raza 20K-0420

### Instructor:
Miss Sumiyah Zahid

### Course:
Deep Learning For Perception

## Objective

The objective of Jeanius Digital is to revolutionize the jeans industry by developing an AI-powered platform that streamlines production processes and enhances quality control. We aim to achieve this by automating quality control procedures such as color matching and measurements.

## Problem Statement

- Manual quality control processes leading to errors and inconsistencies in jeans production.
- Lengthy design cycles and delays in responding to market trends.
- Inability to provide personalized experiences and virtual try-ons for customers.

By leveraging AI and computer vision technologies, Jeanius Digital aims to automate these processes, improve efficiency, and enhance accuracy.

## Methodology

### Data Acquisition and Preprocessing
- **Data Collection:** Gather denim images from various sources, including local inventory, manufacturer catalogs, and online databases.
- **Image Preprocessing:** Use the OpenCV library to load and resize images to a standard size. Convert images from BGR to HSV color space for color segmentation.

### Color Segmentation and Object Detection
- **Color Definition:** Define HSV color ranges for denim categories.
- **Color Segmentation:** Segment denim colors using defined ranges. Apply thresholding and contour detection for object identification.
- **Bounding Boxes and Labels:** Draw bounding boxes around segmented objects and add labels for visual identification.

### User Interaction
- Interactive user dashboard for multiple options, the user can select to run color matching model or measurement model.
- After processing the relevant results are shown to the user.

### System Integration and Testing
- **Integration:** Integrate color matching and jeans measurements models into Jeanius Digital's web app.
- **Testing and Validation:** Test system performance with sample denim images. Validate accuracy against ground truth data and from a denim manufacturer.

## Results

- **Results Evaluation:** Evaluate system performance in terms of accuracy, speed, and user experience.
- **Optimization:** Fine-tune color matching and measurements models for improved accuracy. Implement weighted thresholding for better accuracy.

## Installation

To get started, clone this repository using the `git clone` command.

## Usage

To use Jeanius Digital :

1. Install `requirements.txt` on the backend.
2. Install `requirements.txt` on the frontend.
3. Run the backend using the command: `python manage.py runserver `
4. Run the front end using: `npm start`

## Technologies Used

- React for frontend and user interface.
- Python for backend.

## Results Presentation

Results are shown to the user within the web app.
