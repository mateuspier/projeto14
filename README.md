# Projeto Experiencein 💻

Objetivo: A origem do projeto, desenvolvido por estudantes do curso de Tecnologia em Sistemas para Internet do Instituto Federal de Brasília - Campus Brasília, proposta pela disciplina de Programação para Internet II, lecionada pelo Mestre Fábio Henrique teve por objetivo a criação de um projeto de API (Application Programming Interface), isto é, um conjunto de regras e protocolos que permite a comunicação entre diferentes aplicativos ou sistemas que podem ser acessados por meio de solicitações HTTP (como GET, POST, PUT, PATCH e DELETE)  para receber requisições do servidor e retornar dados no formato JSON ou XML. Um exemplo, utilizado na trilha de conhecimento disponibilizada pelo professor na plataforma de estudos Canva, é a possibilidade de acessar dados de redes sociais e integrá-los em outros aplicativos.


-----------------------------------------------------------------------------------

## Funcionalidades 🚀

• Criação de uma requisição GET 
• Retornar um JSON

Descrição: Um projeto de requisição GET que retorna um JSON é um projeto de desenvolvimento de software que faz uma solicitação HTTP GET para uma URL específica e retorna a resposta em formato JSON. 

A requisição GET é usada para solicitar dados de um servidor sem fazer alterações nos dados existentes. A resposta é geralmente retornada no corpo da resposta HTTP.

JSON (JavaScript Object Notation) é um formato de dados leve e fácil de ler que é usado para transmitir dados entre aplicativos. Ele é uma estrutura de dados composta por pares de chave-valor e é facilmente convertido para e de objetos JavaScript.

Esse tipo de projeto pode ser utilizado para criar aplicações que precisam acessar e exibir dados de fontes externas, como APIs de terceiros, sem necessidade de acesso direto aos bancos de dados dessas fontes.

-----------------------------------------------------------------------------------

## Tecnologias 🚀

• Python 3.7.9
• Django 2.2
• PIP3
• Visual Studio Code 1.69

-----------------------------------------------------------------------------------

## Como configurar o back-end do projeto 🔨

1. Abra o terminal gitbash e clone o repositório para sua máquina local:

		git clone https://github.com/Prof-Fabio-Henrique/projeto-final-2022-2-g4-rm.git

2. Navegue até a raiz do diretório do projeto:

		cd experiencein/

3. Crie um ambiente virtual e ative-o:

		python -m venv venv
		source venv/bin/activate


4. Instale os pacotes necessários:

		pip3 install -r requirements.txt


5. Configure as variáveis de ambiente, se necessário.

6. Faça as migrações no banco de dados:

		python manage.py makemigrations
		python manage.py migrate

-----------------------------------------------------------------------------------

## Licença 🔑

Este projeto possui limita sua licença a uso pessoal, somente, e é proibida a comercialização ou uso indiscriminado do mesmo para fins de lucro ou infração de qualquer natureza nestes termos. 

-----------------------------------------------------------------------------------

## Autores 👨 

O projeto contou com a produção e realização do estudante Mateus Santos, aluno do 5º semestre do curso de tecnologia em Sistemas para Internet do Instituto Federal de Brasília (IFB) – Campus Brasília. O desenvolvimento ocorreu durante o semestre letivo em curso da disciplina de Programação para Internet II, ministrada pelo professor Fábio Henrique.

-----------------------------------------------------------------------------------

## Problemas conhecidos 🚩

• Problemas de compatibilidade entre as versões do Django e do Python, especialmente se o projeto usa bibliotecas ou pacotes que não são compatíveis com essas versões específicas.

• Problemas de performance ao lidar com grandes volumes de dados ou de usuários simultâneos.

-----------------------------------------------------------------------------------

## Colabore ✋

• Abra Pull Requests com atualizações
• Discuta ideias em Issues
• Compartilhe o repositório com a sua comunidade
• Envie feedbacks por e-mail para mateus.santos5@estudante.ifb.edu.br ou richard.ornelas@estudante.ifb.edu.br 

-----------------------------------------------------------------------------------

## Futuras atualizações e contribuições 🔮

  Para aprimorar o desenvolvimento do projeto, pretende-se em breve, evoluir o produto de software de tal maneira que possa hospedar o back-end em um ambiente de hospedagem na nuvem, o PythonAnywhere, conforme sugere os futuros módulos desta disciplina, que permite aos desenvolvedores executar código Python em um servidor remoto. Ele fornece uma plataforma fácil de usar para desenvolvimento e implantação de aplicativos Python, incluindo projetos Django. Com o PythonAnywhere, é possível implantar seu aplicativo em um ambiente de produção seguro e escalável, gerenciar de banco de dados, gerenciar arquivos e fornecer suporte para vários frameworks e bibliotecas Python populares. Em seguida, nos passos consecutivos, será necessário configurar o front-end e hospedar a versão no deploy para explorar versões incrementais das seguintes funcionalidades, oferecendo um app com uma experiência completa:

• Acessibilidade: Tornar a aplicação reconhecida em ferramentas de tradução para pessoas portadoras de necessidades visuais e/ou auditivas.

• Busca e filtragem: Adicionar recursos de busca e filtragem ao seu projeto, permitindo que os usuários pesquisem e filtrem os dados disponíveis.

• Paginação: Adicionar recursos de paginação ao seu projeto, permitindo que os usuários naveguem facilmente por grandes conjuntos de dados.

• Notificações: Adicionar recursos de notificação ao seu projeto, permitindo que os usuários recebam notificações sobre atualizações ou eventos importantes.

• Carrinho de compras: Adicionar recursos de carrinho de compras ao projeto, permitindo que os usuários adicionem itens ao carrinho e efetuem pagamentos.

• Integração com redes sociais: Adicionar recursos de integração com redes sociais ao seu projeto, permitindo que os usuários se conectem com suas contas de redes sociais e compartilhem conteúdo.

• Integração com outros serviços: Adicionar recursos de integração com outros serviços, como por exemplo envio de email, pagamentos online, entre outros.

• Geração de relatórios: Adicionar recursos de geração de relatórios, permitindo que os usuários visualizem e exportem dados do projeto.

• Multi-idiomas: Adicionar recursos de suporte a múltiplos idiomas, permitindo que os usuários naveguem e interajam com o projeto em sua própria língua.

• Suporte a dispositivos móveis: Adicionar recursos de suporte a dispositivos móveis, permitindo que os usuários acessem o projeto a partir de dispositivos móveis.

• Dashboard: Adicionar um dashboard para o administrador, para que ele possa gerenciar o projeto, visualizar estatísticas e dados.

• Backup automático: Adicionar recursos de backup automático, para garantir que os dados do projeto estejam sempre seguros.

• Integração com inteligência artificial: Adicionar recursos de inteligência artificial, para melhorar a experiência do usuário e tornar o projeto mais inteligente e personalizado.

• Integração com Chatbot: Adicionar recursos de chatbot, permitindo que os usuários interajam com o projeto através de conversas naturais, e ajudando-os a encontrar informações ou realizar tarefas de forma rápida e eficiente.
