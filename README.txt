The data used in this project was obtained by:


*   [Berkley Deep Drive ](https://bdd-data.berkeley.edu/)
  * Click on download

The dataset contains over 100,000 images and 100,000 videos. For this project, we used the images only. The dataset possesses geographic, environmental and weather diversity which is useful for training models. 

>**Citations:**
@InProceedings{bdd100k,
    author = {Yu, Fisher and Chen, Haofeng and Wang, Xin and Xian, Wenqi and Chen,
              Yingying and Liu, Fangchen and Madhavan, Vashisht and Darrell, Trevor},
    title = {BDD100K: A Diverse Driving Dataset for Heterogeneous Multitask Learning},
    booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    month = {June},
    year = {2020}
}


Prerequisites
Python 3.8 or higher
Jupyter Notebook
Virtual environment management tool (e.g., venv, virtualenv, or conda)
Git (optional, for cloning the repository)

Setup and Installation
1. Clone the Repository
If you have git installed, you can clone the repository. Alternatively, you can download the zip file from the project repository.
git clone https:https://github.com/KhanRayyan3622/Image-Classification-for-Self-Driving-Cars.git
cd image-classification-self-driving-cars

2. Create and Activate a Virtual Environment
It’s important to create a virtual environment to manage project dependencies and avoid conflicts with other projects.

Using venv or virtualenv:
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate

# On Unix or MacOS
source venv/bin/activate
Using conda:

Copy code
# Create a conda environment
conda create --name image_classification python=3.8

# Activate the environment
conda activate image_classification
3. Install Dependencies
All necessary dependencies are listed in the requirements.txt file.

# Install dependencies
pip install -r requirements.txt
Running the Code
1. Launch Jupyter Notebook
Start the Jupyter Notebook to access the project code and execute cells interactively.

jupyter notebook
2. Open the Project Notebook
Navigate to the Image Classification for Self Driving Cars.ipynb file in the Jupyter interface and open it.

3. Execute Cells
Execute the notebook cells sequentially to preprocess data, train the model, and evaluate its performance. Make sure you have the dataset available as specified in the notebook.