# DevMinutes web

Czech podcast for developers. 

**Requirements (dev)**

1. Git
2. Node and npm  


### How to start development

```sh
# software preparation (bower and php server)
# software installation need do in administrator mode (sudo)
$ npm install -g bower
$ curl -s http://php-osx.liip.ch/install.sh | bash -s 5.6

$ git clone git@github.com:devminutes/devminutes-2.0.git
$ cd devminutes-2.0/
$ sudo bower install
$ php -S localhost:9090
```

Go to browser and enter url *http://localhost:9090*
