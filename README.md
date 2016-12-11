# Trabalho final da disciplina de Tópicos Avançados em Programação
Este foi um tutorial feito para a disciplina de Tópicos Avançados em Programação, para este trabalho foi utilizado o seguinte tu
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## HOW TO?

Para iniciar, deve-se clonar o repositório, isso pode ser feito utilizando:

```
$ git clone https://github.com/vitorfgd/TwitterCloneRails
```

Em seguida é necessário acessar a pasta onde se encontra o arquivo Gemfile e executar o seguinte comando:

```
$ bundle install --without production
```

É necessário executar o seguinte comando para a migração da base:

```
$ rails db:migrate
```

Como este trabalho foi feito utilizando técnicas de TDD, portanto é uma boa pratica executar também os testes:

```
$ rails test
```

Se todos os testes derem positivos, basta executar o servidor utilizando:

```
$ rails server
```

## Qualquer dúvida:

vitorfgd@gmail.com