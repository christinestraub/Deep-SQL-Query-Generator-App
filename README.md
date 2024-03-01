DeepSQL Query Generator App using Gemini AI Model
===============================================

This repository contains the code for a query generator app that uses the Gemini AI model to generate SQL queries. The app allows users to input natural language descriptions of the data they are looking for, and the model generates the corresponding SQL query to retrieve that data.

Getting Started
---------------

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

-   Python 3.9
-   pip (Python package manager)
-   virtualenv (Python virtual environment manager)

### Installing

A step by step series of examples that tell you how to get a development environment running

1. Clone the repository to your local machine

```
git clone https://github.com/christinestraub/Deep-SQL-Query-Generator-App.git
```

2. Create a virtual environment and activate it

```
virtualenv venv
source venv/bin/activate
```

3. Install the required packages

```
pip install -r requirements.txt
```

4. Get Gemini AI API KEY from the Google AI Studio.

5. Run the app

```
python app.py
```

Using the App
-------------

The app will prompt you to enter a natural language description of the data you are looking for. For example, you might enter "Show me the names and salaries of all employees in the sales department." The model will then generate the corresponding SQL query and display it.

You can then copy and paste the query into your database management system to retrieve the data.

Built With
----------

-   [Python](https://www.python.org/) - Programming language
-   [Streamlit](https://streamlit/) - Web framework
-   [Gemini AI Model](https://huggingface.co/babelscape/gemini) - AI model for generating SQL queries

Contributing
------------

Please read [CONTRIBUTING.md](https://gist.github.com/your-username/new-file.md) for details on our code of conduct, and the process for submitting pull requests to us.

Versioning
----------

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your-username/deepsql-query-generator-app/tags).

Authors and Acknowledgment
--------------------------

-   **Christine Straub** - 

License
-------

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
