![Project Status: Active][Project Status Image]

ukupgrade
=========

<img align="right" src="https://www.kernel.org/theme/images/logos/tux.png" alt="Linux Logo" title="Tux">

**ukupgrade** stands for "*Ubuntu Kernel Upgrade*"   

**Purpose**: It provides us to upgrade linux kernel to latest version for Ubuntu/Mint and derivatives. Based on [this archive](http://kernel.ubuntu.com/~kernel-ppa/mainline/)


**Latest Stable Kernel Version on 2016-Sep:** **4.7**

-----------------------------------------


## Usage

* Download latest script
```
curl https://raw.githubusercontent.com/muhasturk/ukupgrade/master/ukupgrade > ukupgrade
```

* Give executable permission
```
chmod +x ./ukupgrade
```

* Call the script
```
./ukupgrade
```

### In order to call script as bash commannd

* Run 
```
sudo cp ./ukupgrade /usr/bin/do-kernel-upgrade
```
* Now you can call the script whereever you are
```
do-kernel-upgrade
```

### Author
[Mustafa Hasturk](https://www.linkedin.com/in/muhasturk)   

|   homepage	|   [mustafahasturk.com](http://mustafahasturk.com "Official Web Site")   	|
|:-:	|:-:	|
|   email	|  `hi [at] mustafahasturk [dot] com`	|

### Contributors
[Allan Brazute](https://www.linkedin.com/in/allan-brazute-59b378b5)   

|   email	|  `ethraza [at] gmail [dot] com`	|

[Project Status Image]: https://img.shields.io/badge/project-active-green.svg "Project Status: Active"

