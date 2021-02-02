# Impulso FullStack Developer :diamonds:

Anotações das atividades do Bootcamp. :pencil2::books:

- Boas-vindas ao Impulso FullStack Developer
- Fundamentos de Lógica de Programação
- Aprenda o que são Estrutura de Dados e Algoritmos
- [Aprendendo o que é Ruby](#aprendendo-o-que-é-ruby)
- Ruby: Introdução a orientação a objetos
- Solucionando problemas básicos em Ruby
- Da arquitetura ao deploy com Ruby
- Programação para internet com HTML5 e CSS3
- Solução de problemas básicos em JavaScript
- Desenvolvimento de aplicações para internet com ReactJS
- Crie um gerenciador de esferas do Dragon BallZ usando ReactJS, Jest, React Testing Library e Cypress
- MindApp - Desenvolvendo uma Cloud Tags com Ruby
- Praticando com desafios intermediários em Ruby
- Criando um sistema de classificados com Ruby on Rails
- Ruby on rails: Montando uma rede social
- Solucionando desafios matemáticos em Ruby

<br><br><br><br><br>

------

## Aprendendo o que é Ruby

*Este curso é para quem teve pouco, ou nunca teve, contato com a linguagem orientada a objetos e de tipagem forte: o Ruby. Aprenda o que é e o porquê você deve trabalhar com ela.*

:hourglass: 3 horas	[⤴](#impulso-fullstack-developer-diamonds)

<br>

*Notas da aula*

- **Introdução e Ambiente de desenvolvimento**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>Introdução ao curso</u>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>O que são Ruby, Rails e Gems?</u>

Criada em 1995 por Matz, é uma LP interpretada, multi paradigma. Popularidade em 2001 após o livro "Programming Ruby". Foco em Simplicidade.

```Ruby
class Hello
    def initialize(nome)
        @nome = nome.capitalize
    end
    
    def falar
        puts "Olá #{@nome}"
    end
end

# Criar um objeto
h = Hello.new("mundo")

# Saída: "Olá mundo"
g.falar
```

[Documentação do Ruby](https://www.ruby-lang.org/pt/documentation/) 

Tipagem Dinâmica e Forte

Orientada a Objetos

<u>*Rails*</u>

> Framework Web escrito em Ruby
>
> Criada em 2004 por David Heinemeier Hansson (DHH)
>
> Extraído do Basecamp
>
> Otimizado para a facilidade da pessoa programando
>
> Convenção sobre configuração
>
> Padrão MVC

<u>Gems</u>

São Bibliotecas em Ruby. o Rails é uma gem.

https://rubygems.org

```shell
gem intall nome_da_gem
```

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>O ambiente de desenvolvimento</u>

O Ruby pe uma linguagem interpretada.

**Instalando o asdf**

https://asdf-vm.com/#/core-manage-asdf

```bash
asdf version
```

```shell
asdf plugin-add ruby
```

```shell
asdf install ruby 2.7.2
```

```shell
ruby -v
```

Listando as versões do Ruby

```shell
asdf list ruby
```

Trocando a versão local por outra

```shell
asdf local ruby 2.7.1
```

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>Brincando no shell do Ruby</u>



<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>Executando um código fonte</u>



<br>

- **Tipos de variáveis**



- **Símbolos, arrays, hases, inputs, condicionais e laços**



- **Exercício final**







