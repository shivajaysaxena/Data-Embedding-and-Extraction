# Data Embedding and Extraction

Location data can be embedded within objects using Geotagging. However, traditional geotagging methods come at a cost, compromising privacy and exposing sensitive location information. This project contains a design and development for secure geotagging, seamlessly weaving cryptography and steganography into a protective cover for digital footprints. We leverage robust encryption algorithms to scramble geospatial data, rendering it unreadable to prying eyes. This encrypted payload then is invisibly embedded and meticulously concealed within the chosen digital object using steganographic techniques. Our approach ensures secure embedding, high robustness against noise, and faithful extraction of geospatial information, guaranteeing data integrity and minimizing perceptual alterations.

## Technologies Used

### Programming Language
Python served as the foundation for the project, offering a versatile and efficient environment for both backend development and image processing tasks.

### Backend Framework
Flask, a lightweight and flexible web framework built on top of Python's Werkzeug WSGI utility toolkit, was chosen to power the application's backend API.

### Frontend Technologies
The user interface (UI) was constructed using the fundamental web development building blocks: HTML, CSS, and JavaScript. HTML provided the structure for the UI, CSS defined the visual presentation, and JavaScript enabled interactive elements for user input and dynamic content manipulation.

## Installation

To install the required libraries to execute the program, run the following commands:

1. Install `hashlib`:
    ```bash
    pip install hashlib
    ```

2. Install `PIL`:
    ```bash
    pip install pillow
    ```

3. Install `flask`:
    ```bash
    pip install flask
    ```

## Running the Program

To run the program, execute the `app.py` file after installing the above-mentioned libraries:

```bash
python app.py
