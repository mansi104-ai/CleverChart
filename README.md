<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/mansi104-ai/CleverChart">
    <img src="/logo_2.png" alt="Logo" height="80">
  </a>

  <h3 align="center">BrevityAI</h3>

  <p align="center">
    AI-powered Document Summarization
    <br />
    <br />
    <a href="https://your-demo-link.com">View Demo</a>
    ·
    <a href="https://github.com/mansi104-ai/CleverChart/issues/new">Report Bug</a>
    ·
    <a href="https://github.com/mansi104-ai/CleverChart/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
  <h2>Table of Contents</h2>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <!-- <li><a href="#license">License</a></li> -->
  </ol>

<!-- ABOUT THE PROJECT -->
## About The Project

BrevityAI is an AI-powered document summarization tool that helps you quickly understand and summarize long documents. With the integration of the T5 model and a user-friendly interface, it generates concise, accurate, and context-aware summaries in multiple languages.

Key Features:

- **Multilingual Summarization**: Automatically generates summaries in multiple languages.
- **Document Upload & Management**: Securely upload and manage documents for summarization.
- **Detailed Summaries**: View and download summaries in a clean and readable format.
- **Export Results**: Export your document summaries and logs as PDFs for easy sharing.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* ![T5](https://img.shields.io/badge/T5-2D3A3A?style=for-the-badge&logo=TensorFlow&logoColor=white)
*  ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
* ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
* ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=GoogleCloud&logoColor=white)
* ![Vertex AI](https://img.shields.io/badge/Vertex%20AI-1288E5?style=for-the-badge&logo=Google&logoColor=white)
* ![Python](https://img.shields.io/badge/Python-306998?style=for-the-badge&logo=python&logoColor=white)
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This section explains how to set up the project locally.

### Keywords
1. Maximum summary length : Adjust the number of words you want in your summary. (Range 50 - 500)
2. Minimum summary length : Adjust the minimum number of words that should be present in your summary (Range 10 - 100)
3. Length penalty : It refers to the tradeoff between the quality of the summary and the length of the summary.
>If you want more precise summary in shorter sequences , keep the penalty < 1.0.If you wish to obtain longer sequences of the summary , kepp the penalty > 1.0. Setting it to 1.0 has neutral effect.

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/mansi104-ai/BrevityAI.git

   cd BrevityAI
   ```

2. Install the dependencies :
  ```sh
  pip install -r requirements.txt
  ```

3. Run the application : 
  ```sh
  streamlit run main.py
  ```
4. Access the App: Open your browser and navigate to http://localhost:8501.



