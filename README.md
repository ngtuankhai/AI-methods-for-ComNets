# AI-methods-for-ComNets

### Prerequisites
Python 3.6 or newer
pip (Python package installer)

### Installation
- Open a terminal or command prompt and change to the directory where the files are located.
- Use pip to install the required Python packages listed in the requirements.txt file. Run the following command in your terminal or command prompt: pip install -r requirements.txt

### Running the Notebooks
- After installing the dependencies, you can open the Jupyter notebooks using Jupyter Lab or Jupyter Notebook. If you haven't installed Jupyter yet, you can do so by running: pip install jupyterlab
- Then, to start Jupyter Lab, use: jupyter lab
- Navigate to the notebook you wish to open in the Jupyter interface that opens in your web browser.

For a cloud-based option, Google Colab offers a free and easy way to run Jupyter notebooks in the cloud without any local setup. 

### Troubleshooting
If you encounter any issues with package versions or conflicts, consider creating a virtual environment. You can do this using venv (included in the standard Python library) or with conda if you're using Anaconda.
For venv, you can create a virtual environment by running: python -m venv myenv
Then, activate it with:
- Windows: myenv\Scripts\activate
- macOS and Linux: source myenv/bin/activate
After activation, run the pip install command mentioned above to install the dependencies within your virtual environment.

### Required CSV Files

For the `Hands-on Exercise 1 - Pandas.ipynb` notebook, you will need two specific Excel files:

- `Universities.csv`
- `african_econ_crises.csv`

Check that they exist in the directory of the 'Hands-on Exercise 1 - Pandas.ipynb' notebook.

### Exercise Format

Each exercise notebook starts with a theoretical introduction to the concepts being taught, followed by practical examples. At the end of each notebook, except for the NetworkX exercise, there is a detailed exercise for the student to complete. To assist in the learning process, we have included empty cells for students to write their code, as well as additional cells that contain only the visualization of the expected results. This setup allows students to verify their answers independently.

