# DataProcessing

This Python file uses Pandas-Data Manipulation Library, and Joblib-Parallel processing library to convert a large data file which contains lexical information about users and their lexical knowledge in English while their native speaking language is Arabic into a desired shape. In the final file, the columns represent the words, and rows indicate the number of users who have accurately answered the words presented with no less than three errors.

The required information of the users is distributed in three files namely profiles.csv,sessions.csv, and lexical-decision.csv.
The column common to any two files is used to combine the user information to create a final entry in the output file.

### View on GitHub
You can view the notebook directly on GitHub by navigating to the `.ipynb` file.

### Download the Notebook
1. Navigate to the `.ipynb` file.
2. Click the `Raw` button.
3. Right-click and select `Save as...` to download the notebook file.

### Clone the Repository
1. Open a terminal.
2. Run the following command:
   ```sh
   git clone https://github.com/gouthamipriyanka/DataProcessing.git

### Google Colab
1. Open Google Colab.
2. Click on File > Open notebook.
3. Navigate to the GitHub tab.
4. Enter the repository URL and find the notebook file.
5. Click Open to open and run the notebook in Google Colab.
