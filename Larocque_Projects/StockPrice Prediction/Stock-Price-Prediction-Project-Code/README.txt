******************************************************************
*
* Title:  ReadMe file for Stock Prediction 
* Author: Brandon M. Larocque
* Date:   April 21, 2021
*
* Description
*      This program is used to predict Stock prices using an LSTM model.
*      1 half of the project is given in the stock_pred file. It details an algorithm used to predict 
*	   stock prices by reading in a data set (csv), and incorpating it into dataframe. It then
*	   filters the dataset and trains the dataset using the LSTM Model. After the data has been trained
*	   it is saved and then the we begin using our model to predict prices. Lastly our results are plotted.
*
* How to get the code running
* 
* This application uses Python 3.6
* Install the following packages prior to running
*   1) Dash (1.1.2)
*   2) TensorFlow (2.2 or greater)
*   3) Keras (2.4.3)
*
*
* Describe how you ran the program (PyCharm?, Python Notebook?, ..)
*		Google Colab: (Not recommended)
* 		0) Assuming you have received the zip file from gmail...
*		1) Google Google Colab in your Browser
*		2) Create a new notebook(.ipynb)
*		3) Copy and paste the code into run.txt into the cell
*		4) Ctrl + M +L to show line numbers
*		5) When ready, click the play button on the left 
*          hand side of the screen
*		6) scroll to the bottom to the output window
*		   you should see a "choose file button"
*			click it, and select "NSE-Tata.csv"
*		7) shortly after it will prompt you do to the 
*			choose a file again but this time choose
*			"stock_data.csv"
*		8) It will prompt a third time, simply choose
*			"NSE-Tata.csv"
*		9)After a few seconds the program should display it's results.
*
*		Jupyter Notebook
*		1) connect to jupyter notebook and create two
*		python files 1 named stock_app.py the other 
*		stock_pred.py (you would of course have to install
*		from anaconda if you don't already have it)
*		2) From the respectively named files copy the code
*		into respective notebooks and run the file.
*		3) It should bring to your localhost where you can 
*		interact with the dashboard and observe the comaparisons.
*
*
*
*
*
*
*
*
*
******************************************************************