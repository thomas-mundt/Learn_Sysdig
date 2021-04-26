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

```
sysdig -cl
sysdig -c topprocs_cpu
sysdig -c spectrogram
sysdig -c spy_users
```


## Filters for containers

When cat is executed inside a container
```
proc.name=cat and container.id!=host
```



## CSysdig (GUI)


