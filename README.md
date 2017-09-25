# DLND-TV-SCRIPT

Running Floyd:
1. Install
	```shell
		# python2
		$ pip install -U floyd-cli
		# python3
		$ pip3 install -U floyd-cli
		# anaconda python3
		$ source activate env-name && pip3 install -U floyd-cli
	```
2. LogIn
	```shell
		$ floyd login
	```
3. Setup
	```shell
		$ floyd init dlnd-tv-script-generation 
	```
4. Running
	```shell
		$ floyd run --cpu --mode jupyter --env tensorflow-1.3
		$ floyd run --gpu --mode jupyter --env tensorflow-1.3
	```
