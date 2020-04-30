# Arquivos de linguagem para Laravel 7.9 - Português do Brasil

Parte das traduções e este Readme.md foram baseadas no repositório [enniosousa/laravel-5.5-pt-BR-localization](https://github.com/enniosousa/laravel-5.5-pt-BR-localization). A tradução foi feita a partir dos arquivos originais do Laravel na versão 7.9

## Instalação

1. Clonar este repositório na pasta `resources/lang/pt-BR` do seu projeto
  ```
  $ cd resources/lang/
  $ git clone https://github.com/andrenunes01/laravel-7.9-pt-BR-localization.git ./pt-BR
  ```

  Você pode remover o diretório .git caso deseje incluir e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -r pt-BR/.git/
  ```

  Se você estiver usando Windows Server ou Azure
  ```
  rd /s /q pt-BR/.git/
  ```

2. Configurar o Framework para utilizar 'pt-BR' como linguagem padrão
  ```
  // Linha 83 do arquivo config/app.php
  'locale' => 'pt-BR',
  ```
  
## Localização para outras versões do Laravel
  
* [Laravel 5.4](https://github.com/Leomhl/laravel-5.4-pt-br-localization)
* [Laravel 5.5](https://github.com/enniosousa/laravel-5.5-pt-BR-localization)
* [Laravel 5.6](https://github.com/lucascudo/laravel-5.6-pt-BR-localization)
* [Laravel 5.7](https://github.com/lucascudo/laravel-5.7-pt-BR-localization)
