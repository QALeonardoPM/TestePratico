# TestePratico

Obs: Todo conteúdo deste repositório é somente um exercício, a simulação é feita em um sistema fictício, os testes são simulações também.

# Teste Automatizado - Cadastro de Novo Usuário
Este projeto contém um script automatizado para validar o fluxo de cadastro de um novo usuário no sistema EducSimulados, utilizando Selenium IDE.

## Instalação do Selenium IDE
1. Acesse o [site oficial do Selenium IDE] (https://www.selenium.dev/selenium-ide/).
2. Baixe e instale a extensão para o seu navegador preferido (Chrome, Firefox).
3. Após a instalação, abra o Selenium IDE no seu navegador.

## Requisitos
- Selenium IDE instalado (ver seção de instalação).
- Acesso à página do EducSimulados (https://educsimulados.com).
- O usuário **admin@email.com** deve estar registrado no sistema para execução do teste e funcional.

## Fluxo de Teste
1. O script abre a página inicial do EducSimulados.
2. O login é feito com um usuário administrador.
3. O menu "Usuários" é acessado para cadastrar um novo usuário.
4. O novo usuário é criado com dados fictícios: **Nome: Teste QA**, **E-mail: testeqa@email.com**, **Senha: Senha@123**.
5. O tipo de usuário (Estudante) e a linguagem preferida (Português) são selecionados.
6. A autenticação em duas etapas é configurada via **E-mail**.
7. O cadastro é realizado com sucesso e o redirecionamento para a tela de login é validado.

## Navegadores Suportados
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari (para usuários MacOS)

## Como Rodar
1. Clone ou baixe o repositório.
2. Abra o Selenium IDE e importe o arquivo `.side` do projeto.
3. Clique em "Run all tests" para executar o teste.
4. Verifique os resultados na janela do Selenium IDE.

## Considerações
- Identificadores dos campos (ID, nome de classes, etc.) são fictícios e devem ser ajustados conforme a estrutura da página real.
- Código de verificação: Usei um código fictício e isso deve ser alterado para um fluxo real de validação 
