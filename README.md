# README
En este proyecto se muestra una aplicación creada con las funciones CRUD en relación a un dato.


![Ruby](https://img.shields.io/badge/Ruby-CC342D?logo=Ruby&logoColor=white)
![RubyOnRails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?logo=ruby-on-rails&logoColor=white)

Los pasos para instalar el lenguaje Ruby

En la siguiente pagina se descarga y se instala ruby


```Pagina web
https://www.ruby-lang.org/es/documentation/installation/

```


Confirmamos la instalación con el siguiente comando

```Pagina web
ruby -v

```


luego instalamos rails que es framework de ruby

```Pagina web
gem install rails
rails --version
```



Los pasos para crear la aplicación son:

```Pagina web
rails new ProjectDemo
cd ProjectDemo
rails generate scaffold note title description:text
rails db:migrate
bash -login
rvm use 3.0.0
```




Para ejecutar el programa creado se da el siguiente comando

```Pagina web
rails s 
```

