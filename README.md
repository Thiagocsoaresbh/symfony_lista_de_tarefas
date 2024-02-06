# Aplicativo de Lista de Tarefas (todo_list)
Este é um aplicativo de lista de tarefas desenvolvido com Symfony para o backend e Vue.js para o frontend.

## Descrição
O aplicativo de lista de tarefas permite que os usuários criem, visualizem, editem e excluam tarefas. Ele fornece uma interface amigável para gerenciar suas tarefas diárias de forma eficiente.

## Funcionalidades
- Adicionar uma nova tarefa
- Visualizar todas as tarefas existentes
- Marcar uma tarefa como concluída
- Editar o título ou a descrição de uma tarefa
- Excluir uma tarefa da lista

## Tecnologias Utilizadas
- Symfony 5.x: Framework PHP para o backend
- Vue.js 2.x: Framework JavaScript para o frontend
- Bootstrap 5.x: Framework CSS para estilização
- MySQL (ou outro banco de dados compatível com Doctrine): Banco de dados para armazenar as tarefas

## Requisitos de Instalação
- PHP >= 7.4
- Composer
- Node.js >= 14.x
- npm ou Yarn
- Um servidor web (por exemplo, Apache, Nginx) configurado para servir o aplicativo Symfony
- MySQL (ou outro banco de dados compatível com Doctrine) configurado e acessível

## Instalação

1. Clone o repositório para o seu ambiente local:
```bash
git clone https://github.com/ThiagocsoaresBH/todo_list.git
```

2. Instale as dependências PHP com o Composer:
```bash
composer install
```

3. Instale as dependências JavaScript com o npm ou Yarn:
```bash
npm install
```
ou
```bash
yarn install
```

4. Compile os assets do Vue.js com o Webpack Encore:
```bash
npm run dev
```
ou
```bash
yarn dev
```

5. Configure o banco de dados no arquivo .env e execute as migrações do Doctrine para criar as tabelas necessárias:
```bash
php bin/console doctrine:migrations:migrate
```

6. Inicie o servidor web local:
```bash
php bin/console server:run
```


**Acesse o aplicativo em seu navegador usando o URL fornecido pelo servidor web local (geralmente http://localhost:8000).**

## Autor
- Nome: Thiagocsoares
- GitHub: [GitHub](https://github.com/ThiagocsoaresBH)

### Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests, relatar problemas ou propor novos recursos.
