

# PyIpResolver



<center>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</center>

This is a simple IP Resolver written in Python


### Prerequisite

```diff
- Python3
- host command (if not installed)
```

### Clone this repo

```
git clone "https://github.com/valentinmne/pyipresolver.git"
cd pyipresolver
```

### Add new samples
```diff
- You can add URLs or IP in url.txt
```
## Execute Python script :

```
python3 pyipresolver.ip
```

### With Makefile
```
make <OPTION>
```
### Options:  

Options | Description | In Terminal
:-|:-|:-|
run | Run the program with args | ```python3 pyipresolver.py```
rm | Remove the binary file | ```rm -rf host_list info```
re | Combination of ```rm``` and ```run``` commands | ```rm -rf host_list info && python3 pyipresolver.py ```

### Currently implemented

- Generating a file with the IPs of the URL
- Generating a host file
- Printing the Network Status of the given IP or URL



## Contributors

- valentinmne : valentin.moine@protonmail.com