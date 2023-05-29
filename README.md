# Hip-Hop Popularity

This project aims to analyze the popularity of hip-hop music using data fetched from the Spotify API. It includes a thorough exploratory data analysis (EDA) of the retrieved data.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Libraries Used](#libraries-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Hip-hop music has been a significant cultural and artistic movement, influencing various aspects of society. With the advent of streaming platforms like Spotify, it has become easier to access and analyze music data. This project leverages the Spotify API to fetch hip-hop music data and performs an EDA to gain insights into its popularity.

The project repository contains the code and data necessary to replicate the analysis and explore the findings.

## Installation

To use this project locally, follow the steps below:

1. Clone the repository:

   ```shell
   git clone https://github.com/deepakjangir15/Hip-Hop-Popularity.git
   ```

2. Navigate to the project directory:

   ```shell
   cd Hip-Hop-Popularity
   ```

3. Install the required dependencies. It is recommended to set up a virtual environment before installing the dependencies:

   ```shell
   pip install spotipy pydub librosa IPython
   ```

## Usage

1. Obtain API credentials from Spotify by creating a new application on the Spotify Developer Dashboard. You will need the client ID and client secret for authentication.

2. Update the `config.py` file with your Spotify API credentials:

   ```python
   CLIENT_ID = 'your-client-id'
   CLIENT_SECRET = 'your-client-secret'
   ```

3. Run the Jupyter notebook `Hip_Hop_Popularity.ipynb` to perform the EDA on the hip-hop music data fetched from the Spotify API.

4. Follow the instructions within the notebook to explore the data and analyze the popularity of hip-hop music.

## Libraries Used

The following libraries were used in this project:

- [spotipy](https://pypi.org/project/spotipy/): A lightweight Python library for the Spotify Web API.
- [pydub](https://pypi.org/project/pydub/): Manipulate audio with a simple and easy-to-use interface.
- [librosa](https://librosa.org/doc/main/index.html): A Python library for music and audio analysis.
- [IPython](https://ipython.org/): An interactive command-line interface for Python.

Make sure to install these libraries before running the code.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.
