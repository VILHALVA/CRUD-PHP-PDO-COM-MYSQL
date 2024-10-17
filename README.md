# CRUD PHP PDO COM MYSQL
👨‍🏫ESTE PROJETO É UMA APLICAÇÃO WEB SIMPLES QUE IMPLEMENTA UM SISTEMA CRUD PARA O GERENCIAMENTO DE VAGAS DE EMPREGO.

<img src="FOTO.png" align="center" width="500"> <br> 

## DESCRIÇÃO:
Este projeto é uma aplicação web simples que implementa um sistema CRUD (Create, Read, Update, Delete) para o gerenciamento de vagas de emprego. Ele foi desenvolvido em PHP utilizando Programação Orientada a Objetos (POO) e o PDO (PHP Data Objects) para a interação com um banco de dados MySQL. A aplicação permite a criação, listagem, edição e exclusão de vagas de emprego, e foi projetada para ser executada em um ambiente local usando um servidor PHP e MySQL.

## RECURSOS:
1. **Front-end**: Interfaces construídas com Bootstrap para exibir e interagir com as vagas.
2. **Back-end**: Um conjunto de classes PHP para gerenciar a interação com o banco de dados (inserir, listar, atualizar e excluir vagas).
3. **Banco de Dados**: Usa MySQL, com uma tabela `vagas` que armazena as informações sobre as vagas.

## FUNCIONALIDADES:
- **Cadastrar vaga**: Criação de uma nova vaga com título, descrição, status (ativo/inativo) e data de publicação.
- **Listar vagas**: Listagem de todas as vagas com suas informações, exibindo detalhes como ID, título, descrição e status.
- **Editar vaga**: Edição dos dados de uma vaga existente.
- **Excluir vaga**: Excluir uma vaga específica.

## EXECUTANDO O PROJETO:
1. **Importar o `DATABASE.sql`**  
   - Antes de iniciar o site, é necessário importar o arquivo localizado em `./DATABASE/DATABASE.sql`.

2. **Instalar dependências**:
   Navegue até o diretório `./CODIGO` e execute o comando:
   ```bash
   composer install
   ```

3. **Configurar o ambiente**:
   No arquivo `./CODIGO/App/Db/Database.php`, ajuste as constantes `HOST`, `NAME`, `USER` e `PASS` de acordo com suas configurações de banco de dados.

4. **Executando o Aplicativo com Apache**  
   - Coloque os arquivos em um servidor web compatível com PHP, como XAMPP, WAMP ou LAMP.

5. **Executando o Aplicativo com `php.exe`**  
   - Como alternativa, você pode iniciar o servidor diretamente no diretório `./CODIGO` utilizando o seguinte comando:

   ```bash
   php -S localhost:8080
   ```

6. **Navegar na aplicação**:
   Abra o navegador e vá para `http://localhost:8000`. Você verá uma lista de vagas cadastradas e poderá gerenciar as vagas.

## NÃO SABE?
- Entendemos que para manipular arquivos em `HTML`, `CSS` e outras linguagens relacionadas, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PHP](https://github.com/VILHALVA/CURSO-DE-PHP)
* [CURSO DE BOOTSTRAP](https://github.com/VILHALVA/CURSO-DE-BOOTSTRAP)
* [CURSO DE JQUERY](https://github.com/VILHALVA/CURSO-DE-JQUERY)
* [CURSO DE MYSQL](https://github.com/VILHALVA/CURSO-DE-MYSQL)
* [CURSO DE PHP COM MYSQL](https://github.com/VILHALVA/CURSO-DE-PHP-COM-MYSQL)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO "william-costa"](https://github.com/william-costa/wdev-crud-php-pdo-mysql)
- [VEJA O VIDEO DESSE PROJETO](https://youtu.be/uG64BgrlX7o?si=L_DOuO9XE46AXKLt)
- [PROJETO FEITO PELO VILHALVA](https://github.com/VILHALVA)




