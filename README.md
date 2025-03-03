## Acknowledgment
I would like to acknowledge the invaluable assistance of ChatGPT-4 and Grammarly in the preparation of this project. The tools played a significant role in:

- Debugging and resolving coding challenges encountered during the development of the Python package.
- Providing insights and suggestions for improving the structure and functionality of the code.
- Generating concise and accurate summaries of complex texts to enhance understanding and clarity.

While ChatGPT-4 contributed significantly to streamlining the development process and improving the quality of outputs, all results were rigorously reviewed, tested, and refined to ensure their accuracy, relevance, and alignment with project objectives.

## Introduction
This report aims to present the study on the MNIST dataset, (this contains 70000 images  handwritten digits of dimension $28\times28$). In particular, training Neural Network models and others (SVM and Random Forests), to read images from a new dataset obtained from randomly allocating images from the original MNIST (new dataset $56\times28$ images of size 80000), the new labels for each image is the sum of the collection images. Additionally, we are going to analyse the performance of a weak linear classifier, on the $56\times28$ dataset compared to two sequential images from the original MNIST. 

## Getting started 
1. Create a Virtual Environment

   Run the following command to create your virtual environment

   ``` bash
    python -m venv <your_env>

- If the above command fails, please try:
   ```bash
   python3 -m venv <your_env>

Replace `<your_env>` with your preferred environment name, e.g. `dual_venv`.

2. Activate your virtual environment

  Activate your virtual environment with:
   ```bash
    source <your_env>/bin/activate
   ```
  Deactivate your environment with:
   ```bash
    deactivate
   ```
3. To install all the required libraries please run the command:
   ```bash
   pip install -r requirements.txt
   ```