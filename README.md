# petjournal.qa
Repositório criado para armazenar cenário de testes desenvolvido pela equipe de QA

enário: Visualizar a página inicial (Home)
Dado que o usuário está logado no aplicativo
Quando o usuário abrir o aplicativo
Então o usuário deve ser redirecionado para a página inicial (Home)
E o usuário deve ver as opções de serviços disponíveis, como "Agenda", "Localizar Serviços", "Registro de Vacinas" e "Registro de Vermífugos"

Cenário: Visualizar lista de pets
Dado que o usuário está logado no aplicativo
Quando o usuário selecionar a aba "Pets"
Então o usuário deve ver uma lista de todos os seus pets cadastrados
E o usuário deve ver os detalhes de cada pet, como nome, foto e informações básicas de saúde

Cenário: Visualizar perfil do tutor
Dado que o usuário está logado no aplicativo
Quando o usuário selecionar a aba "Tutor"
Então o usuário deve ver seu perfil como tutor de pets
E o usuário deve ver suas informações pessoais, como nome, e-mail e telefone de contato
E o usuário deve ver a opção de editar seu perfil

Cenário: Agendar uma consulta para o pet
Dado que o usuário está logado no aplicativo
E o usuário selecionou um pet da lista de pets
Quando o usuário selecionar a opção de "Agenda"
E preencher as informações necessárias para a consulta (data, hora, tipo de serviço)
Então a consulta deve ser agendada com sucesso para o pet selecionado
E o usuário deve receber uma confirmação da consulta

Cenário: Localizar serviços próximos
Dado que o usuário está logado no aplicativo
E o usuário possui permissão para acessar sua localização
Quando o usuário selecionar a opção "Localizar Serviços"
Então o aplicativo deve exibir uma lista de serviços próximos, como veterinários, pet shops e banho e tosa, baseados na localização do usuário

Cenário: Registrar vacina para o pet
Dado que o usuário está logado no aplicativo
E o usuário selecionou um pet da lista de pets
Quando o usuário selecionar a opção de "Registro de Vacinas"
E preencher as informações necessárias da vacina (nome da vacina, data de aplicação)
Então a vacina deve ser registrada com sucesso para o pet selecionado
E o usuário deve receber uma confirmação do registro da vacina

Cenário: Registrar vermífugo para o pet
Dado que o usuário está logado no aplicativo
E o usuário selecionou um pet da lista de pets
Quando o usuário selecionar a opção de "Registro de Vermífugos"
E preencher as informações necessárias do vermífugo (nome do vermífugo, data de administração)
Então o vermífugo deve ser registrado com sucesso para o pet selecionado
E o usuário deve receber uma confirmação do registro do vermífugo
