<h1>Loan Approval Model Using ANN</h1>

<p>This project implements a loan approval prediction model using Artificial Neural Networks (ANN) to evaluate loan applications based on various applicant features. The goal is to assist financial institutions in automating the decision-making process for loan approvals.</p>

<h2>Project Overview</h2>
<ul>
    <li><strong>Dataset:</strong> The dataset consists of multiple features such as applicant demographics, loan details, and financial indicators.</li>
    <li><strong>Data Preprocessing:</strong>
        <ul>
            <li>Handling missing values through appropriate imputation techniques.</li>
            <li>Encoding categorical variables using One-Hot Encoding.</li>
            <li>Feature scaling using Standard Scaler to normalize the data.</li>
        </ul>
    </li>
    <li><strong>Model Architecture:</strong> A sequential model built using Keras with the following architecture:
        <ul>
            <li>Input layer with 128 neurons and ReLU activation function.</li>
            <li>Dropout layers to reduce overfitting.</li>
            <li>Hidden layer with 64 neurons and ReLU activation function.</li>
            <li>Output layer with a single neuron and sigmoid activation function for binary classification.</li>
        </ul>
    </li>
    <li><strong>Early Stopping:</strong> Implemented early stopping during training to prevent overfitting by monitoring the validation accuracy.</li>
    <li><strong>Evaluation:</strong> The model is evaluated on a separate test set, and the accuracy and loss metrics are reported.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>Python</strong>: Programming language used for data analysis and model implementation.</li>
    <li><strong>Pandas</strong>: Library for data manipulation and analysis.</li>
    <li><strong>Numpy</strong>: Library for numerical operations.</li>
    <li><strong>Matplotlib & Seaborn</strong>: Libraries for data visualization.</li>
    <li><strong>Scikit-learn</strong>: For preprocessing and splitting the dataset.</li>
</ul>

<h2>Installation</h2>
<p>To run this project, clone the repository and install the required libraries:</p>


<h2>Usage</h2>
<p>After setting up the environment, you can run the Jupyter Notebook file <code>Loan_Approval_Model_Using_ANN.ipynb</code> to execute the model training and evaluation process.</p>

<h2>Conclusion</h2>
<p>This project demonstrates how to build a simple yet effective ANN model for loan approval prediction. By leveraging machine learning techniques, we can enhance decision-making processes in the financial industry.</p>

