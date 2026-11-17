# Clínica Pet

Uma clínica veterinária enfrenta dificuldades em sua rotina de atendimentos devido àausência de um sistema informatizado. O controle manual dos agendamentos e dosregistros de tutores e pets tem ocasionado perda de consultas, duplicidade deinformações e falhas no armazenamento de dados. Além disso, a ausência demecanismos adequados de proteção dos dados pessoais dos tutores, como o CPF,pode comprometer a segurança dessas informações e resultar no descumprimentodas disposições da Lei Geral de Proteção de Dados (LGPD).

Com base nessa problemática, será desenvolvido um sistema que permite o cadastro e gerenciamento de tutores, pets e agendamentos, com autenticação de usuários e controle seguro de dados seguindo as seguintes regras de negócio:

- O CPF dos tutores deve ser armazenado de forma criptografada no banco de dados.
- Ao cadastrar um novo pet, o usuário deve associá-lo a um tutor.
- Na funcionalidade de login, fazer validação em caso de falha na autenticação.
- A funcionalidade principal do sistema deve exibir: nome do usuário logado e umaforma de acessar os demais recursos, assim como uma maneira de sair dosistema.
- A funcionalidade de tutor deve conter: um recurso de busca para que o usuáriopossa inserir o termo, o qual, após inserção e confirmação, deverá exibir para ousuário a atualização da listagem dos valores da tabela com os registros quecorrespondem. A funcionalidade também deve permitir editar os dados de umtutor já cadastrado, salvando a alteração no banco de dados.
- A funcionalidade de agendamento deve exibir: Listagem dos agendamentoscadastrados ordenado por dia de agendamento, trazendo todos dados do tutor edo pet. A funcionalidade também deve permitir atualizar a data de umagendamento já cadastrado, salvando a alteração no banco de dados.
