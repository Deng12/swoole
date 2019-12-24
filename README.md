# swoole
根据网络IO模型，自己用原生的代码诠释一个简易版本的swoole

目录结构如下：

  --io
  - src
       - Blocking
       - NonBlocking 
       - Multiplexing 
       - SingnalDriven 
       - Asynchronous 
  - test
      - blocking 
      - nonBlocking 
      - multiplexing
      - singnal-driven 
      - asynchronous 
  - vendor 
  - composer.json

构建项目：
$ io>composer init 
  Welcome to the Composer config generator 
  
  This command will guide you through creating your composer.json config. 
  
  Package name (<vendor>/<name>) [deng/io]: deng/io
  Description []: 
  Author [, n to skip]: deng <819763618@qq.com.com> 
  Minimum Stability []: 
  Package Type (e.g. library, project, metapackage, composer-plugin) []: library 
  License []: MIT
  
  Define your dependencies. 
  
  Would you like to define your dependencies (require) interactively [yes]? 
  
  Search for a package: 
  Would you like to define your dev dependencies (require-dev) interactively [yes]? 
  Search for a package:
  {
    "name": "deng/io", 
    "type": "library", 
    "license": "MIT",
    "authors": [ 
        { "name": "deng", 
          "email": "819763618@qq.com" 
        }
      ],
      "require": {}
   }
   
   Do you confirm generation [yes]? yes
  
  
  
  
  
