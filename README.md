# Ilokano-Tagalog Translator

The Ilokano-Tagalog Translator is a web application machine translation tool that translates Ilokano to Tagalog and vice versa using a combination of example-based, rule-based, and statistical machine translation models.

## 🗒️ Table of Contents
- [Background](#background)
- [Project Structure](#project-structure)
- [Tools and Languages](#tools-and-languages)
- [Usage](#usage)

## 📖 Background

The Ilokano and Tagalog language are two of the most spoken languages in the Philippines. However, based on reasearch, there are very limited studies related to these languages in the field of computing, specifically, in Natural Language Processing. 

This project aims to lay a foundation for the future studies regarding local languages in the Philippines, wherein most of the languages are low-resource.

The translator utilizes a hybrid approach in converting langauges. The example-based, rule-based, and statistical machine translation models are used in translating Ilokano and Tagalog text.

## 📁 Project Structure
    ILOKANO-TAGALOG TRANSLATOR
      
      ├── data/                    <- Data used and collected for this project
      │   ├── csv data/
      │   ├── excel data/
      │   ├── json data/
      │   ├── scores/
      │   └── text data/
      ├── module/                  <- Backend implementation for the web application
      │   ├── il_tl/
      │   ├── scoring/
      │   ├── smt/
      │   └── tl_il/
      ├── notebooks/               <- Data used and collected for this project
      │   ├── evaluation/
      │   ├── functions/
      │   ├── Ilokano to Tagalog/
      │   └── Tagalog to Ilokano/
      ├── website/                 <- Front end implementation for the web application
      ├── .gitignore               <- Avoids uploading data, credentials, outputs, system files etc
      ├── LICENSE                  <- License for this project
      ├── main.py                  <- Launches the application
      ├── README.md                <- The top-level README for developers/collaborators using this project.
      └── requirements.txt         <- The requirements file for reproducing the analysis environment

## 🤖 Tools and Languages

<div style = "display: inline-block">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"></img>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"></img>
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white"></img>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"></img>
  <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"></img>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"></img>
</div>

## 📓 Usage

Clone the project

```bash
  git clone https://github.com/sheyn018/Ilokano-to-Tagalog-Machince-Translation.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Once all requirements are installed, follow these steps to run the app:

1. Run '**main.py**'.
2. Click on the development server in the terminal to access the web app.