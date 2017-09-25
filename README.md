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

Running Docker:
1. Building it image:
```shell
    $ sudo docker build -t dlnd_tv_script_generation .
```
2. Running it __jupyter notebook__ into a container
```shell
    $ docker run -p 8888:80 dlnd_tv_script_generation
```
3. Running it __tensor board__ into a container
```shell
    $ docker run -p 6006:80 dlnd_tv_script_generation
```