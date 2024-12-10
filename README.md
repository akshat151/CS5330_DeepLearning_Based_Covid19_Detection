# CS5330_DeepLearning_Based_Covid19_Detection

## Project Links
- **Models**: [Google Drive Link](https://drive.google.com/drive/folders/1sqLyBZl5FHT4OAoKN1_Doi1BJ0ZWMb1m?usp=drive_link)
- **Dataset**: [Kaggle Link](https://www.kaggle.com/code/drorchen/diagnosis-of-covid19-pneumonia-and-tuberculosis#Goal)
- **OneDrive Dataset**: [OneDrive Link](https://northeastern-my.sharepoint.com/:u:/r/personal/devarasetty_h_northeastern_edu/Documents/CV%20PROJECT/combined_1.zip?e=4%3ac3b04a81af50446fabac0af985410985&web=1&openShare=true&fromShare=true&at=9&xsdata=MDV8MDJ8a2hhcmUuYWtzQG5vcnRoZWFzdGVybi5lZHV8M2VmZmM5NzI4NzdjNGFiZDA4OTEwOGRkMTRiN2M2Mjl8YThlZWMyODFhYWEzNGRhZWFjOWI5YTM5OGI5MjE1ZTd8MHwwfDYzODY4OTUwMTc0MTQ0MDIxMXxVbmtub3dufFRXRnBiR1pzYjNkOGV5SkZiWEIwZVUxaGNHa2lPblJ5ZFdVc0lsWWlPaUl3TGpBdU1EQXdNQ0lzSWxBaU9pSlhhVzR6TWlJc0lrRk9Jam9pVFdGcGJDSXNJbGRVSWpveWZRPT18MHx8fA%3d%3d&sdata=OUh1SngyUThkQ2RxUWN3Y2ozU3p3eXNUTVlrUHQ5QnZFcTZqMDVMYm52QT0%3d)

We will create a new environment for the project setup using the following instructions.


# Setup
1. Install [Miniconda](https://conda.io/miniconda.html). It doesn't matter whether you use Python 2 or 3 because we will create our own environment that uses python3 anyways.
2. Create a conda environment using the appropriate command. On Windows, open the installed "Conda prompt" to run the command. On MacOS and Linux, you can just use a terminal window to run the command, Run: `conda env create -f cs5330_project_env.yml`
3. This will create an environment named 'cs5330_pa4'. Activate it using the Windows command, `activate cs5330_project` in the Windows default Command Prompt or the MacOS / Linux command, `conda activate cs5330_project` or `source activate cs5330_project`
4. Run the notebook using `jupyter notebook ./evaluation.ipynb` to evaluate the existing pre-trained models present in the drive link above.
