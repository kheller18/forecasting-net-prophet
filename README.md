# Forecasting Net Prophet

![license badge](https://shields.io/badge/license-mit-blue)


## Description

This project aims to analyze and predict Google Search traffic for Mercado Libre and understand how it corresponds to stock price. You can find the full notebook in the following link: [Google Colab](https://colab.research.google.com/drive/1NjAByhL7P6VcBBCj2_USxRy8g97WGCsO#scrollTo=XobvBTMTe4CC).

We start by looking at the search traffic by each week in the year of 2019.
![application screenshot](/Images/average_traffic_wk_yr.png)

We can see from above that there is a sharp increase in traffic before the new year and a sharp downturn after the new year.  Then, we can break our data down further to unerstand what days of the week and time are associated with high search traffic.
![application screenshot](/Images/search_trends_hm.png)

We can understand from the image above that the highest days for searching are Monday - Wednesday and specifically at about 10pm to 2am.  We then look at the daily sales to see if there's a correlation between the amount of Google traffic and sales.
![application screenshot](/Images/daily_sales_2019_2020.png)

Then, we look into creating a time series model with Prophet and try to understand expected profit, as well as lower and upper bounds.

## Table of Contents

- [Forecasting Net Prophet](#forecasting-net-prophet)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [1. Installation](#1-installation)
  - [2. Usage](#2-usage)
  - [3. License](#3-license)
  - [4. Contributing](#4-contributing)
  - [5. Tests](#5-tests)
  - [6. Deployment](#6-deployment)
  - [7. Contact](#7-contact)


## 1. Installation

  If you would like to clone the repository, type "git clone https://github.com/kheller18/crypto-machine-learning.git".
  In the terminal, with the conda dev environment activated, install the following packages and dependencies before running the crime analysis application. To understand how to install these, refer to the [Usage](#2-usage)

  * [csv](https://docs.python.org/3/library/csv.html) - Used to store all of our SPD data

  * [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/) - *version 3.4.4* - Used to create and share documents that contain live code, equations, visualizations and narrative text.

  * [matplotlib](https://matplotlib.org/) - For the visualization of crime data.

  * [pandas](https://pandas.pydata.org/docs/) - For the analysis of crime data.

  * [pathlib](https://docs.python.org/3/library/pathlib.html) - *version 1.0.1* - This was used to locate through the directory or file path.

  * [PyVizlot](https://pyviz.org/) -  Python visualization package that provides a single platform for accessing multiple visualization libraries. Our most heavily used library is:

    * [hvplot.pandas](https://hvplot.holoviz.org/user_guide/Introduction.html) - *version 0.7.2* - For the interactive visualization of the crime data.

  * [PyStan](https://pystan.readthedocs.io/en/latest/) - *version 2.14* - used for statistical modeling.

  * [fbProphet](https://pypi.org/project/fbprophet/) - *version 0.7.1*- used for automatic forecasting.

  * [HoloViews](https://holoviews.org/) - *version 0.8.0* - used for analysis and visualization.


## 2. Usage

  After cloning the repository locally, you'll need to have the packages listed in [Installation](#1-installation) installed on your machine. To do so, you'll need to activate your conda dev environment and running the following commands:

      ```
      pip install pandas
      pip install hvplot
      pip install jupyterlab
      conda install -c pyviz hvplot

      ```

  After all of these are installed, please refer to the [Deployment](#6-deployment) section for instructions on how to view or edit the notebook.


## 3. License

	MIT License

  Copyright (c) 2022 Keenan Heller

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in all
  copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
  SOFTWARE.



## 4. Contributing

  + [Keenan Heller](https://github.com/kheller18)


## 5. Tests

  + There are currently no tests associated with this project.


## 6. Deployment
  + There is currently no live deployment of this notebook on a common server, but the user has the ability to run this notebook locally on their machine via two different ways:
    + `Google Colab`: Navigate to Google Colab and upload the root file "forecasting_net_prophet.ipynb" into it.


## 7. Contact

  + [Keenan's LinkedIn](https://www.linkedin.com/in/keenanheller/)
