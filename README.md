# tny
tny is a simple bash script that shortens a long URL using [tny.im]. It can also shorten email, Bitcoin, Dogecoin, Litecoin addresses.


### Dependencies :
- Wget - [Wget] is a free software package for retrieving files using HTTP, HTTPS and FTP, the most widely-used Internet
protocols. Most Linux distributions have Wget in their package repositories so you can easily install Wget via the package manager of your distribution in case it is not installed on your system.


### Installation :
Download [tny-master.zip], extract it, and copy the file 'tny' to '/usr/local/bin/' directory,
```sh
$ sudo cp tny /usr/local/bin/
```
Next make tny executable,
```sh
$ sudo chmod a+x /usr/local/bin/tny
```


### Usage :
You can use tny like this from your terminal,
```sh
$ tny long_url_address keyword
```
Where 'long_url_address' can be a URL, an email address or a Bitcoin-Dogecoin-Litecoin address. Second argument 'keyword' is optional. You can use it to customize the short URL.


### Credits :
[tny.im] for providing public API.


### License :
[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">tny</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/tny)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.

[tny.im]:https://tny.im/
[Wget]:https://www.gnu.org/software/wget/
[tny-master.zip]:https://github.com/hakerdefo/tny/archive/master.zip
