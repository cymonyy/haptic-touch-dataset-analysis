# Welcome to haptic-touch-dataset-analysis! 

This open source project is a notebook series for data collection, data pre-processing, exploratory data analysis, and machine learning processes on the haptic touch dataset collected from [GetEmotion](https://github.com/cymonyy/GetEmotion) application. The content of these notebook series are based on the studies and concepts discussed in an undergraduate thesis entitled **Integrating Haptic Touch on Android Devices for Emotion Recognition in an Emotionally Stimulated Environment**. 

The names of the notebook are as follows:

1. Data Collection from Firebase.ipynb
2. Data Preprocessing.ipynb
3. Exploratory Data Analysis.ipynb
4. Machine Learning and Hyperparamater Tuning.ipynb

Each file contains a guide on how to perform the said stages using the haptic touch dataset as well as their actual code blocks. 

You are also allowed to modify the code on your own preference or standards in data analysis, but ***please make sure to read the guide as you modify***. 

# Important Notes: 
- Some contents in the notebooks are highly based on the methodology of the thesis. 
- Files `Data Preprocessing.ipynb`, `Exploratory Data Analysis.ipynb`, and `Machine Learning and Hyperparamater Tuning.ipynb` are **dependent of one another and should be run in sequential**. 
- Developers of this project have also included a sample file `haptic-touch-data-sample.csv` which includes the haptic touch dataset primarily used for the methodologies and results of the thesis.


# File Format, Languages, and IDEs 

All notebooks in this series are in [Jupyter Notebook](https://jupyter.org/) format, which mainly consists of [Markdowns](https://www.markdownguide.org/) and programming codes using [Python](https://www.python.org/).

It is recommended to run this project on the [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) IDE, which can be opened through either the [command line](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) or the [Anaconda Navigator](https://www.anaconda.com/download).

# Running the Project
To run the project without errors, run these notebooks in sequential manner: 

1. Data Preprocessing.ipynb
2. Exploratory Data Analysis.ipynb
3. Machine Learning and Hyperparamater Tuning.ipynb

This is because there are files from the notebooks that are exported and imported again to the next one. For example, the sub-datasets generated by `Data Preprocessing.ipynb` are crucial to import for both `Exploratory Data Analysis.ipynb` and `Machine Learning and Hyperparamater Tuning.ipynb`. 

Also, **you do not have to worry if there are multiple files created by these notebooks**. 

For clarification, these are the files that should be generated once the project is ran in sequential manner:

### **Datasets**
|**Type of Dataset**| **Filename** |
|--|--|
| Whole Dataset *without* Extrapolation| `whole.csv` |
| Quadrant 1 (HV-HA) *without* Extrapolation| `q1.csv` |
| Quadrant 2 (LV-HA) *without* Extrapolation| `q2.csv` |
| Quadrant 3 (LV-LA) *without* Extrapolation| `q3.csv` |
| Quadrant 4 (LV-HA) *without* Extrapolation| `q4.csv` |
| Whole Dataset *with* Extrapolation| `whole-extrapolated.csv` |
| Quadrant 1 (HV-HA) *with* Extrapolation| `q1-extrapolated.csv` |
| Quadrant 2 (LV-HA) *with* Extrapolation| `q2-extrapolated.csv` |
| Quadrant 3 (LV-LA) *with* Extrapolation| `q3-extrapolated.csv` |
| Quadrant 4 (LV-HA) *with* Extrapolation| `q4-extrapolated.csv` |

### Significant Features per Type of Dataset (Target: Valence Values)

|**Type of Dataset**| **Filename** |
|--|--|
| Whole Dataset *without* Extrapolation| `whole_df_val_sig.txt` |
| Quadrant 1 (HV-HA) *without* Extrapolation| `q1_df_val_sig.txt` |
| Quadrant 2 (LV-HA) *without* Extrapolation| `q2_df_val_sig.txt` |
| Quadrant 3 (LV-LA) *without* Extrapolation| `q3_df_val_sig.txt` |
| Quadrant 4 (LV-HA) *without* Extrapolation| `q4_df_val_sig.txt` |
| Whole Dataset *with* Extrapolation| `whole_ex_val_sig.txt` |
| Quadrant 1 (HV-HA) *with* Extrapolation| `q1_ex_val_sig.txt` |
| Quadrant 2 (LV-HA) *with* Extrapolation| `q2_ex_val_sig.txt` |
| Quadrant 3 (LV-LA) *with* Extrapolation| `q3_ex_val_sig.txt` |
| Quadrant 4 (LV-HA) *with* Extrapolation| `q4_ex_val_sig.txt` |

### Significant Features per Type of Dataset (Target: Arousal Values)

|**Type of Dataset**| **Filename** |
|--|--|
| Whole Dataset *without* Extrapolation| `whole_df_ars_sig.txt` |
| Quadrant 1 (HV-HA) *without* Extrapolation| `q1_df_ard_sig.txt` |
| Quadrant 2 (LV-HA) *without* Extrapolation| `q2_df_ars_sig.txt` |
| Quadrant 3 (LV-LA) *without* Extrapolation| `q3_df_ars_sig.txt` |
| Quadrant 4 (LV-HA) *without* Extrapolation| `q4_df_ars_sig.txt` |
| Whole Dataset *with* Extrapolation| `whole_ex_ars_sig.txt` |
| Quadrant 1 (HV-HA) *with* Extrapolation| `q1_ex_ars_sig.txt` |
| Quadrant 2 (LV-HA) *with* Extrapolation| `q2_ex_ars_sig.txt` |
| Quadrant 3 (LV-LA) *with* Extrapolation| `q3_ex_ars_sig.txt` |
| Quadrant 4 (LV-HA) *with* Extrapolation| `q4_ex_ars_sig.txt` |

Meanwhile, developers of this project have also included a sample file `haptic-touch-data-sample.csv` which includes the haptic touch dataset primarily used for the methodologies and results of the thesis. 

This makes `Data Collection from Firebase.ipynb` file optional and usable only when [GetEmotion](https://github.com/cymonyy/GetEmotion) application is executed for a separate experiment procedure. A file called `collected-haptic-dataset.csv` is generated if this notebook is run. 

By this, you can choose which dataset to be used at the start of the `Data Preprocessing.ipynb` notebook.
