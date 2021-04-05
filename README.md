### S21_CSMA.213 assignment06

In this assignment you will practice using machine learning models for text generation and hand-written digit recognition, experimenting with 2 different applications of Deep Learning.

For the first part, you'll utilize the included `textgenrnn_template.ipynb` notebook together with [Google Colab](https://colab.research.google.com) to train a Recurrent Neural Network (RNN) model from a text file and then use the model to generate new titles.

**Q1.** [2 points] Create a text file that contains a list of titles on a subject of your interest such as sports teams, video games, etc.  Some good resource for finding a list of interst are the [Wikipedia List of lists of lists](https://en.wikipedia.org/wiki/List_of_lists_of_lists) or [Kaggle datasets](https://www.kaggle.com/datasets).

Your list should include at least 100 items in plain text (.txt) format, with one item per line. As a reference, see the `anime_fantasy_titles.txt` file included with this assignment.

**Q2.** [1 point] Go to [https://colab.research.google.com](https://colab.research.google.com) in a web browser and load the github link to the `textgenrnn_template.ipynb` notebook included with this assignment.

Click the 'Connect' button at the top right of the notebook in Colab and run the first two cells.  At this point you should be able to upload your text file to the files area in the left menu of Google Colab (accessible via folder icon).

Next, change `file_name` variable of the 3rd notebook cell if needed and click the play button to train the textgenrnn model for 10 epochs as specified (for example, you can upload and try the `anime_fantasy_titles.txt`).  This step will take a few minutes and after completion you should see the model file `colaboratory_weights.hdf5` generated in the Files area.

After the training is complete, run the next cell to test generating one text sample.  You can optionally un-comment the line of code to save the model file with a specified name as well (this will take a bit of time to appear in Files). If the generated title looks OK, please **download the model file** (either `collaboratory_weights.hdf5` or `textgenrnn_titles.hdf5`) to submit with your assignment.

**Q3.** [2 points] Run the final cell of the notebook to generate a list of 100 titles using the trained model. Look through this list, pick some of your favorite items and paste them into a new text file.

Repeat the process a few times, tweaking the temperature setting between the values 0.1 - 0.9. Choose a total of at least 10 titles that you find particularly interesting and add them to the text file.  When finished, commit this file to your assignment repository to submit with the assignment.
