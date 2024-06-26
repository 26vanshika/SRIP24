# Develop SpiroMask end-to-end.





## Authors

- [Vanshika Jain](https://www.github.com/26vanshika)
  Sophomore in Electrical Engineering at NIT Rourkela.

## Navigation and Installation
You can do the below installations or just view the files from the repository directly. Both the python file(SRIPTask-2.ipynb) and the quarto file(SRIPTask-2-2.pdf) are present.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/26vanshika/SRIP24.git
   cd SRIP24

2. **Set up a Virtual Environment**
   ```bash
    python -m venv venv
    # For mac
    source venv/bin/activate
    # For Windows
    use ".\venv\Scripts\activate"

4. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

6. **Run Jupyter Notebook**
   ```bash
   jupyter notebook

7. **Run my file**
   In your web browser, go to the URL displayed in the terminal http://localhost:8888/ . Open main Jupyter Notebook file SRIPTask-2.ipynb.
   
9. **Quarto file**
    ```bash
   quarto render SRIPTask-2.ipynb --to pdf

## Roadmap
The steps that I followed for this mini-project were as follows:

I first gathered and learnt about the resources I would be needing by searching them through the internet.

It was not a one day work though the project seems small. I ran into multiple challenges which I will be mentioning below.

I first recorded the audio of breathing in mask.

Then using IPython I imported it in my jupyter notebook.

To do the analysis of the audio I used Librosa package mainly used for Sound analysis.

I learnt about the low-pass filter to filter high frequencies and coded one(I faced a lot of issues here :) ).

Then using Matplotlib and Librosa's display feature I plotted the waveform and spectogram of Original and Filtered audio.


## What I learned
So basically I had pre-requisite knowledge in Machine learning, but I learnt a lot of things 

Like I was aware of Matplotlib but wasnt aware of Librosa's waveform feature.

I also learnt how to make filters in python(I only learnt about them in theory thanks to an Electrical Engineering course)

Also Quarto is just something I didnt know and glad through this project I learnt about it, because it really does wonders. Definetly going to use in my future projects.

## Challenges I ran into

There were a lot of challenges I ran into:

Firstly my packages were installed but were showing "module not found", fixed that with a lot of frustration.

I also faced issues with Quarto since I was completely new to it.

And a lot of errors in making the low-pass filter.

My github was also not committing changes smoothly, it was continously showing errors.

## References

https://www.comet.com/site/blog/working-with-audio-data-for-machine-learning-in-python/

https://quarto.org/docs/tools/jupyter-lab.html

https://medium.com/analytics-vidhya/how-to-filter-noise-with-a-low-pass-filter-python-885223e5e9b7

https://stackoverflow.com/questions/25191620/creating-lowpass-filter-in-scipy-understanding-methods-and-units
