# Install
```
git clone https://github.com/patrickpierson/ipcampy
sudo python setup.py install
```

# Setup config
```
cp cam.conf.example cam.conf
```

# Configure cam.conf
```
{"address":"###.###.###.###", "user":"USERNAME", "pswd":"PASSWORD", "port":"##", "type":"foscam", "name":"CamName"}
```

# Run it
```
campatrol -d cam.conf -p password --debug
```

# Login
Go to http://localhost:6001 
Login with 'watcher' and 'password' above.
