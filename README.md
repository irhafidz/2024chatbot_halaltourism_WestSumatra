# 2024chatbot_halaltourism_WestSumatra
The supplementary files, datasets and code repositories for our paper titled: Chatbot Model Development Using BERT for West Sumatra Halal Tourism Information.

## Author

 Irmasari Hafidz, Bayu Siddhi Mukti, Qudsiyah Zahra Ilham Naseela , Ahmadhian Daffa Yudistira, I Putu Adhitya Pratama Mangku Purnama, Nurul Fajrin Ariyani, Hanim Maria Astuti, Aris Tjahyanto

 ## How to cite
 Link https://journal.its.ac.id/index.php/hr/article/view/1819
 Hafidz, I., Mukti, B.S., Naseela, Q.Z.I., Yudistira, A.D., Purnama, I.P.A.P.M., Ariyani, N.F., Astuti, H.M. and Tjahyanto, A., 2024. Chatbot Model Development Using BERT for West Sumatera Halal Tourism Information. Halal Research Journal, 4(2), pp.117-131.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Google Colab (optional, for running the notebook in the cloud)

### Steps
1. **Clone the Repository**
    ```bash
    git clone https://github.com/irhafidz/2024chatbot_halaltourism_WestSumatra.git
    cd 2024chatbot_halaltourism_WestSumatra
    ```

2. **Set Up a Virtual Environment**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Download and Place the Dataset**
    - Ensure the `data` folder from the repository contains the necessary dataset files for training the chatbot model.

## Usage

### Running the Notebook
1. **Open Jupyter Notebook**
    ```bash
    jupyter notebook
    ```

2. **Navigate to the Notebook**
    - Open the `chatbot.ipynb` file in your Jupyter Notebook interface.

3. **Run the Cells**
    - Execute the cells in the notebook sequentially to train the chatbot model and test its functionality.

### Running on Google Colab
1. **Open the Notebook in Google Colab**
    - [Google Colab](https://colab.research.google.com/github/irhafidz/2024chatbot_halaltourism_WestSumatra/blob/main/chatbot.ipynb#scrollTo=ii5B-ruhqwkA)

2. **Upload the Dataset**
    - Upload the dataset from the `data` folder to the Colab environment.

3. **Run the Cells**
    - Execute the cells in the notebook sequentially to train the chatbot model and test its functionality.

- `data/`: Folder containing the dataset files for training the chatbot
  
  **chatlist.csv**: Raw datasets that consist questions and pre-defined labels (9 labels, 125 questions for each label (1125 in total))
  
  **clean.csv**: Dataset that has been cleaned and split for training and testing (80% training and 20% testing)

  **answer.json**: Dataset containing answer choices for each label

  **testing.csv**:  Raw datasets that consist questions and pre-defined labels to be tested
     
- `LICENSE: ` License to this project.
- `README.md`: Project documentation file.
- `chatbot.ipynb`: Jupyter Notebook for training and testing the chatbot model.
- `requirements.txt`: List of dependencies required for the project.

## Contributing
We welcome contributions to this project. Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

