
The experiments from this GitHub repository https://github.com/hharcolezi/ldp-protocols-mobility-cdrs/tree/main were conducted during the course 188.992 Experiment Design for Data Science at TU Wien. Great work by Héber H. Arcolezi, Jean-François Couchot, Bechara Al Bouna, Xiaokui Xiao.

Maryna Gutruf and Adnan Rafique Butt successfully reran the experiments. Excellent implementation!

Our suggestions for improvement are as follows:

Implement virtual environments (e.g., venv or conda) for creating isolated Python environments. This ensures consistent dependencies across different machines and developers.

Maintain a requirements.txt or environment.yml file to specify exact versions of libraries and dependencies needed to run the code.

Refactor code from Jupyter notebooks (.ipynb) into Python scripts (.py) when complex debugging or unit testing is required. This facilitates easier tracking of changes and more robust error handling.

Update the README file comprehensively. Provide detailed instructions for setting up the environment, running the notebooks, and the order of operations. Make it a clear starting point for new users.

Consider containerizing the application with Docker for enhanced reproducibility. Containers package code with dependencies, providing a consistent environment across different systems.

Ensure proper data management in notebooks. Make sure data is well-managed, easily accessible, and provide clear instructions on retrieval and preprocessing.

Establish a .gitignore file to specify which files or directories should be excluded from version control. This helps maintain a clean and organized repository by preventing irrelevant files from being tracked. It enhances collaboration and ensures only essential code and configuration files are shared among collaborators.

Highly recommend implementing Git as your version control system for effective project management and change tracking. Git provides a robust framework for collaborative development, enabling multiple contributors to work simultaneously on the same project.


## How to run the project 
1. create a virtual environment python3 -m venv venv
2. activate virtual environment source venv/bin/activate
3. install necessary libraries and their versions: pip install -r requirements.txt

## Update
We have released a package named [Multi-Freq-LDPy](https://github.com/hharcolezi/multi-freq-ldpy) for Multiple Frequency Estimation Under Local Differential Privacy in Python.

## Content
This repository is organized per paper (experiments and protocols) and is regularly updated. Please refer to the [papers](https://github.com/hharcolezi/ldp-protocols-mobility-cdrs/tree/main/papers) folder.

## Keywords
differential privacy, local differential privacy, longitudinal studies, multidimensional data, big data privacy, human mobility, privacy-preserving machine learning.

## Environment
I mainly used Python3 with numpy, pandas, and numba libaries. Although not tested, the codes should run with any recent versions. The versions I use are listed below:

- Python 3.8.8
- Numpy 1.19.5
- Pandas 1.2.4
- Numba 0.53.1

## Contact
For any questions about the experiments, please contact [Héber H. Arcolezi](https://hharcolezi.github.io/): heber.hwang-arcolezi [at] inria.fr
