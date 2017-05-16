# Basic Django app with Zappa
Use Zappa to deploy Django apps on AWS Lambda + API Gateway
[https://github.com/Miserlou/Zappa#about](https://github.com/Miserlou/Zappa#about)

### Setup Virtual Environment in your Django app folder ###
```
virtualenv venv
```

### Activate Virtual Environment ###
```
source venv/bin/activate
```

### Install Django ###
```
pip install Django
```

### Install Zappa ###
```
pip install zappa
```

### Initialize Zappa ###
```
zappa init
```

### Deploy Zappa ###
```
zappa deploy
```

### Update Zappa ###
```
zappa update
```

### View logs from Lambda ###
```
zappa tail
```

### Undeploy Zappa ###
```
zappa undeploy
```
