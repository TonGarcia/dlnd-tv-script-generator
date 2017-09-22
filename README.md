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
2. Setup
	```shell
		$ floyd init dlnd-tv-script-generation 
	```
3. Running
	```shell
		$ floyd run --mode jupyter --env tensorflow:py3
	```
