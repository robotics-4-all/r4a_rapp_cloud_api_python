# r4a_rapp_cloud_api_python

This is a standalone version of the [RAPP Python API](https://github.com/rapp-project/rapp-api/tree/master/python).

You can configure where the RAPP Platform instance is [here](https://github.com/robotics-4-all/r4a_RAPP_cloud_api_python/blob/master/python/RappCloud/config). If you don't know what this is, leave it as is.

The documentation of the API calls exists [here](https://github.com/robotics-4-all/r4a_RAPP_cloud_api_python/tree/master/python/RappCloud).

## Setup / installation

If you want to install RAPP API in your system do the following:
```
cd python
sudo pip install -r requirements.txt
sudo pip install pyyaml
sudo python setup.py install
```

If you want to use a virtual environment:
```
virtualenv env
source env/bin/activate
cd python
pip install -r requirements.txt
pip install pyyaml
python setup.py install
```

You can find a sample application [here](https://github.com/robotics-4-all/r4a_RAPP_cloud_api_python/blob/master/app.py).

