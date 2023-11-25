# Introduction to GenerativeAI Workshop - iii 2023

This repository contains resources and notebooks for the Introduction to Generative AI workshop for iii, conducted by artificialnouveau.

## Quick Start

To get started with voice and face cloning, you can use the following Google Colab notebooks:

Notebook for Generative AI:
[![Open Generative AI Notebook In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/artificialnouveau/a7bf8132042845210fce69ff0df7e960/iii_generative_ai_2023.ipynb)

Notebook for Voice Cloning:
[![Open Voice Cloning Notebook In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/artificialnouveau/ed4f01cbbb665887cf41d1e672d73430/impakt2023-voice-cloning-with-advanced-rvc-inference.ipynb?authuser=1)

OR GO TO HUGGING FACE FOR THE VOICE CLONING:
https://huggingface.co/spaces/jarvislk/Advanced-RVC-Inference-voice-chaner

# Import necessary modules
from IPython.display import Audio, FileLink

# Assuming you have an audio file named 'example_audio.mp3' in your Colab environment
# Display the audio file
display(Audio('example_audio.mp3'))

# Create a download link
download_link = FileLink('example_audio.mp3', result_html_prefix="Click here to download: ")
display(download_link)



## Usage

Follow the steps in the provided Colab notebooks to learn about and experiment with Stable Diffusion, InterfaceGAN, and MusicGen.

## Contributing

Participants are welcome to provide feedback and suggestions by creating issues or pull requests in this repository.

## License

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

## Author

- artificialnouveau

## Acknowledgments

Acknowledgements for any third-party libraries, datasets, or other resources used will be provided in the notebooks.
