# ftpcp
CLI to transfer files from one FTP/SFTP server to another FTP/SFTP server

<img src='https://raw.githubusercontent.com/sunilmore690/ftp2sftp/master/demo.png' alt='ftpcp Demo'>

# Installation

Either through cloning with git or by using [npm](http://npmjs.org) (the recommended way):

```bash
npm install -g ftpcp
```

And nodemon will be installed globally to your system path.

If you don't want to install this package globally use npx to use this package

```bash
npx ftpcp <src> <dest>
```


# Usage

you need to pass 2 agument.

```bash
ftpcp <src> <dest>
```

It'll transfter all files from source server to destination server
```
src/dest >> <ftp/sftp>://<username>:<password>@<Host>:<Port><DirPath>
```
Eg.
```
ftpcp ftp://user:password@localhost:21/home/ sftp://user:password@localhost:22/home/

```







