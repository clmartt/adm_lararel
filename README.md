![kvm](./doc/img/user2-160x160.jpg)

# Powerservice

#### Desenvolvido por:

<li>Claudio Martinele: claudio.martt@kvminformatica.com.br</li>


### Guia para deploy

#### Dependências
<li>PHP ^7.4</li>
<li>Composer</li>

<p>Após a intação com PHP e Composer acesse a raiz do projeto e execute
os seguintes comandos:</p>

~~~ composer
composer install 
~~~
Copie o arquivo .env.exemple para a raiz do projeto com o nome .env
e adicione/troque os valores das variaveis de ambiente.

![dotenv](./doc/img/dot_env.png)



- Gere a chave da aplicação

~~~
php artisan key:generate --ansi
~~~


- NPMs da Vida

~~~
npm install
npm run dev
~~~


- Subir aplicação

~~~
php artisan serve
~~~
