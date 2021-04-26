# Learn Sysdig

## Install Sysdig
```
apt install sysdig
brew install sysdig
```


## Documentation

```
https://github.com/draios/sysdig
```



## Usage

List all system calls
```
sysdig
```

Filter for program nano
```
sysdig proc.name=nano
sysdig proc.name=nano or proc.name=cat
```


List possible filters
```
sysdig -l
```


## CSysdig (GUI)


