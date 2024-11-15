# Music Categorization by Competitive Neural Network Approach
#### Alex Fick, 24F, Comp Neuro Final Project

For this final project, I am implementing a competitive neural network via self-organizing maps to analyze data of over 3,000 songs from the [Million Song Dataset](http://millionsongdataset.com/). 

## Testing the Project

To run the Google Colab version of the notebook, please visit [this link](https://colab.research.google.com/drive/1Pl-D7lTKVgoO4G1Em0pixDvX8LHpUWDZ?usp=sharing). Otherwise, you can clone this repo or download `Final_Project.ipynb` and run it in your own Jupyter Notebook environment. 

## Acknowledgements
To get access to the data, I downloaded the sample provided from their website, which is in the form of a zip file that contains a series of nested folders that store data of each song in its own .h5 file. As such, I needed to unpack this data for use in the `Final_Project.ipynb` notebook. I implemented code for this in `music.py`, which is based off of the work of [Alexis Greenstreet from the University of Wisconsin-Madison](https://github.com/AGeoCoder/Million-Song-Dataset-HDF5-to-CSV/tree/master), and modified to access more features that I wanted to use in my project. This file uses some functions from `hdf5_getters.py`, which was also provided in Alexis Greenstreet's work.

All of the work in `Final_Project.ipynb` is my own, supplemented by some help for syntax from ChatGPT.  

`SongCSV.csv` is the output of the `music.py` script, which is the data that I used in `Final_Project.ipynb`.

## References
Thierry Bertin-Mahieux, Daniel P.W. Ellis, Brian Whitman, and Paul Lamere. 
The Million Song Dataset. In Proceedings of the 12th International Society
for Music Information Retrieval Conference (ISMIR 2011), 2011.