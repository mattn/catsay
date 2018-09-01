# catsay [![CircleCI](https://circleci.com/gh/muhammadmuzzammil1998/catsay.svg?style=svg)](https://circleci.com/gh/muhammadmuzzammil1998/catsay) [![CodeFactor](https://www.codefactor.io/repository/github/muhammadmuzzammil1998/catsay/badge)](https://www.codefactor.io/repository/github/muhammadmuzzammil1998/catsay) [![GitHub license](https://img.shields.io/github/license/muhammadmuzzammil1998/catsay.svg)](https://github.com/muhammadmuzzammil1998/catsay/blob/master/LICENSE) [![Twitter](https://img.shields.io/twitter/url/https/github.com/muhammadmuzzammil1998/catsay.svg?style=social)](https://twitter.com/intent/tweet?hashtags=catsay&text=Take%20a%20look%20at%20this!%20CatSay%20by%20@mmuzzammil1998&url=https://github.com/muhammadmuzzammil1998/catsay/)

**catsay** is a program that generates pictures of a cat holding a sign with a message. 
![image](https://user-images.githubusercontent.com/12321712/44936312-c7474500-ad91-11e8-87a5-e341f5f55170.png)

## Build
Requires [git](https://git-scm.com/download/win) to clone and [Go](https://golang.org/dl/) to build.
```bash
$ git clone https://github.com/muhammadmuzzammil1998/catsay.git
$ cd catsay
$ go build
```

## Installation
### Linux
Download `.deb` file for catsay from [releases](https://github.com/muhammadmuzzammil1998/catsay/releases) page.
```bash
$ wget https://github.com/muhammadmuzzammil1998/catsay/releases/download/v{version}/catsay.deb
$ sudo dpkg -i catsay.deb
```

### Windows
Start PowerShell as an admin
```ps
$ Invoke-WebRequest https://github.com/muhammadmuzzammil1998/catsay/releases/download/v{version}/catsay.exe -OutFile catsay.exe
$ mv .\catsay.exe C:\Windows\catsay.exe
```

### NOTE: This should be obvious but still, adapt version number. Check from [here](https://github.com/muhammadmuzzammil1998/catsay/releases).

## Usage
Pipe the data you want your cat to say.
### Examples
![image](https://user-images.githubusercontent.com/12321712/44936315-c7dfdb80-ad91-11e8-9277-1377706b6da5.png)

## Seeing blocks instead of eyes, nose, or hand?
This is probably because your terminal doesn't support those characters. lulz.

Try `catsay -ascii` to use ASCII-only characters. 
![image](https://user-images.githubusercontent.com/12321712/44936316-c9110880-ad91-11e8-8e0f-05c07666e436.png)

## Help
![image](https://user-images.githubusercontent.com/12321712/44936317-cadacc00-ad91-11e8-85f7-14f1206a6c4d.png)

## Uninstall
### Linux
```bash
$ sudo dpkg --remove catsay
```
### Windows
Start PowerShell as an admin
```ps
$ del C:\Windows\catsay.exe
```
