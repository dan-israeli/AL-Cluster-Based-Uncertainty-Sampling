# **Active Learning in the Medical Domain – an Innovative Cluster Based Uncertainty Sampling Approach** 🔬

In this project, we implement a genuine approach for sampling when performing Active Learning, named "Cluster Uncertainty Sampling". 
The approach is discussed in further detail in the paper.

## **Running Instructions**

To set up your machine, please run the following command in order to install the necessary dependencies:

```pip install torch torchvision matplotlib seaborn scipy scikit-learn numpy```

Moreover, this repository contains two Python notebooks:

- ```generate_results.ipynb``` - reproduces the results presented in the paper.

- ```display_results.ipynb``` - displays the results visually, and produces the plots shown in the paper.

Since the project code was written on a virtual machine terminal, which does not allow displaying plots, the first notebook solely generates the results discussed in the paper and writes them to TXT files, without displaying them. Displaying the results is done separately, in the second notebook, while utilizing the TXT files generated previously.

### **Generating the Results**

First, download the ```generate_results.ipynb``` file. Follow the instructions throughout the notebook, including running the required code cell by cell, and downloading
the data ZIP file from the link provided in the respective location. Once the entire notebook has been run, a total of six TXT files should be generated:

- ```combination_accuracies.txt```

- ```embedding_dim_accuracies.txt```

- ```performance_analysis - cluster uncertainty.txt```

- ```performance_analysis - random.txt```
 
- ```performance_analysis - entropy uncertainty.txt```

- ```performance_analysis - minmax uncertainty.txt```

### **Displaying the Results**

Now, download the ```display_results.ipynb``` file. Lastly, follow the instructions throughout the notebook, including running the required code cell by cell, and copying the results from the TXT files mentioned above into the respective locations in the notebook.
