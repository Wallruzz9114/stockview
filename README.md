# StockView: Stock Market Prediction

This app allows the user may search or select any listed company that opens their share to the market in this app and they see what may be the possible AI driven closing price for that stock at the end of that day for that market.

![Alt text](static_in_env/static_root/admin/img/stock.png?raw=true)

# Dependencies

	urllib3==1.24
	colorama==0.3.9
	pyyaml==3.13
	Django==1.11
	django-crispy-forms==1.7.2
	numpy==1.14.3
	pandas==0.23.0
	python-dateutil==2.7.3
	pytz==2018.4
	scikit-learn==0.19.1
	scipy==1.1.0
	six==1.11.0

# How To Use

Make sure you have installed python3.6, pip and virtualenv.
	
	# Check Python Version

	open the terminal
	python3
	
	If works,then python3 and pip is insalled.If not works then you need to update python version.
	
	# Download and run the project
	
	1. Download/clone the folder.
	2. Open the terminal(Linux/OSX).For windows you can use Poweshell.You can download Poweshell from 
	https://github.com/PowerShell/PowerShell 
	
	Now we need to create a new directory.Let us our directory name is PredictionApp.
	
	mkdir PredictionApp
	cd PredictionApp
	virtualenv . 
	source bin/activate
	
	3. Then copy the src and static_in_env folder and paste it to PredictionApp.
	4. Run the following command.
	
	cd src
	pip install -r requirements.txt
	python manage.py makemigrations
	python manage.py migrate
	python manage.py runserver
	
	5. Now open your favourite browser and go to the link http://127.0.0.1:8000
	
