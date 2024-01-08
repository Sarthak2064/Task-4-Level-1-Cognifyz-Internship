# Task-4-Level-1-Cognifyz-Internship

1. **Install Git:**
   If you haven't installed Git on your system, you can download and install it from [Git's official website](https://git-scm.com/).

2. **Clone the GitHub Repository:**
   Open a terminal or command prompt on your computer and use the `git clone` command to clone the GitHub repository where the Jupyter Notebook project is hosted. Replace `<repository URL>` with the URL of the GitHub repository.
   ```bash
   git clone <repository URL>
   ```

3. **Install Anaconda (Optional but recommended):**
   If you haven't installed Anaconda, it's a good idea to do so. Anaconda comes with Jupyter Notebook and many useful Python packages pre-installed. You can download it from the [Anaconda website](https://www.anaconda.com/products/distribution).

4. **Create a Virtual Environment (Optional but recommended):**
   If you're using Anaconda, you might want to create a virtual environment for the project to manage dependencies cleanly.
   ```bash
   conda create --name myenv python=3.8   # Replace myenv with your preferred environment name
   conda activate myenv  # Activate the created environment
   ```

5. **Install Required Packages:**
   Navigate to the project directory in the terminal and install the required packages using `pip` or `conda` (if you're using Anaconda) by reading the `requirements.txt` or `environment.yml` file in the project. Use the following commands:
   ```bash
   cd <project_directory>
   pip install -r requirements.txt  # For pip users
   # OR
   conda env update --file environment.yml  # For conda users
   ```

6. **Launch Jupyter Notebook:**
   Start Jupyter Notebook by running the following command in the terminal. It will open a browser window with the Jupyter file navigator.
   ```bash
   jupyter notebook
   ```

7. **Access the Notebook:**
   In the Jupyter file navigator, navigate to the directory where the Jupyter Notebook file (`.ipynb` file) is located. Click on the notebook's filename to open and interact with the project.

8. **Execute the Notebook Cells:**
   Once the notebook is open, you can run individual cells by selecting them and pressing `Shift + Enter` or by clicking on "Run" in the Jupyter Notebook menu.
