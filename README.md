# idzebra-contrib-vhosts 

idzebra-contrib-vhosts это дополнение к серверу Zebra для создания виртуальных хостов. 

# Установка программы из исходных текстов

Перед началом работы необходимо установить зависимое программное обеспечение:

```sh
$sudo pkg install yaz
$sudo pkg install zebra-server
```

Получить исходные тексты программы:

```
#!sh
$git https://github.com/komlog/idzebra-contrib-vhosts.git
```

Выполнить конфигурирование и сборку программы:

```
#!sh
$cd idzebra-contrib-vhosts
$sh build.sh
$./configure
$make
```

Перед установкой программы в систему необходимо убедиться, что используется последняя конфигурация программы:

```
#!sh
$make clean
```

От имени суперпользователя установить программу в систему:

```
#!sh
$sudo make install
```
