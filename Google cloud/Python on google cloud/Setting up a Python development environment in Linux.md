# Google Cloud

## Setting up a Python development environment in Linux


### Installing Python
```
sudo apt update
sudo apt install python3 python3-dev python3-venv
```

```
sudo apt-get install wget
wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py
```

```
pip --version
```

### Using venv to isolate dependencies

```
cd your-project
python3 -m venv env
```

```
source env/bin/activate
```

```
pip install google-cloud-storage
```

```
deactivate
```


### Installing an editor

```
pip install --upgrade google-cloud-storage
```


#### Documentation
```
https://cloud.google.com/python/docs/setup#linux
```



