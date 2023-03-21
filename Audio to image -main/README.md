# Audio to Image Web Application

## Problem Statements

The problem is to develop a machine learning model that can generate room interior designs based on audio signals, and to deploy this model using Streamlit to create a user-friendly web interface. The main challenge is to train the model to accurately recognize patterns in audio signals and generate corresponding designs, while ensuring stability and reliability.

This repository contains a web application that allows users to record a 10-second audio clip and outputs a detailed image based on the 
speech in the audio. The web application is written in Python and uses the Streamlit library.

## Features

- Record a 10-second audio clip and get a detailed image based on the speech
- The generated image is unique to the user's audio input

## Requirements

- Python 3.6 or higher
- Streamlit
- Other dependencies can be found in requirements.txt

## Usage

1. Clone the repository
```
git clone https://github.com/YOUR_USERNAME/audio-to-image.git
```

2. Install the dependencies

```
pip install -r requirements.txt
```

3. Run the web application

```
streamlit run app.py
```

4. Record a 10-second audio clip and see the generated image


5. To install PyAudio i have provided default dependency for PyAudio 

```
pip install <filename>
```


## Contributing

If you want to contribute to this project, please fork the repository and make your changes in a separate branch. Once you are ready to submit your changes, open a pull request and we will review your changes.


## License
This project is licensed under the terms of the MIT license. See the LICENSE file for more information.
