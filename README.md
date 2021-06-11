<h1 align="center">
  mediafire-dl
</h1>

## Description

**mediafire-dl** is a script written in Python to automate the download of files from [mediafire.com](https://mediafire.com) with a simple command-line interface.

> Much of the code comes from [gdown](https://github.com/wkentaro/gdown)

## Prerequisites

It is necessary to have **python3** and **pip3**


## Installation

```bash
pip3 install git+https://github.com/Juvenal-Yescas/mediafire-dl
```

## Usage

### From Command Line

```bash
$ # mediafire-dl mediafire_link_1 

$ # mediafire-dl mediafire_link_1 mediafire_link_2 mediafire_link_3
```

### From Python

```python
import mediafire_dl

url = 'https://mediafire.com/xx/xx/file.zip'
output = 'file.zip'
mediafire_dl.download(url, output, quiet=False)
```
## Build with

* [Python3](https://www.python.org/download/releases/3.0/) - Python is an interpreted, high-level, general-purpose programming language. 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* Inspired by :
* [gdown](https://github.com/wkentaro/gdown)
* [openload-dl](https://github.com/gius-italy/openload-dl)
* [mediafire-dl](https://github.com/pythonoma/mediafire-dl)
