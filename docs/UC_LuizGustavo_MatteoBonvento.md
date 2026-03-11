## UC01 — Realizar Login (UC EXEMPLO - FAZER DESSA FORMA PARA TODOS OS CASOS DE USO, NESSE MESMO DOCUMENTO)

### Ator Principal
Usuário

### Objetivo
Permitir que o usuário acesse o sistema.

### Pré-condições
- Usuário deve possuir cadastro ativo.

### Pós-condições
- Sessão iniciada com sucesso.

### Fluxo Principal
1. O usuário informa e-mail e senha.
2. O sistema valida as credenciais.
3. O sistema autentica o usuário e redireciona para a tela inicial.

### Fluxos Alternativos
- **A1 — Senha incorreta:**  
  O sistema exibe mensagem de erro.

- **A2 — Conta bloqueada:**  
  O sistema impede o login e instrui o usuário a recuperar o acesso.

### RF Relacionados
- (inserir RF aqui)

### RNF Relacionados
- (inserir RNF aqui)

### RN Relacionadas
- (inserir RN aqui)


Alunos
- fazer matricula
- escolher tipo de plano
- realizar pagamento
- Cadastrar facial na catraca
- Agendar aula
- presença em aulas
(talvez)
- Passar pela avaliação física

Recepcionistas
- Gerenciar matrículas
- Indicar planos
- Gerenciar pagamentos
- Gerenciar Agendamento de aulas

Instrutores
- Disponibilizar horário para aulas
- Avaliações fisicas
- Cadastrar catraca

Gerentes
- Gerenciar planos
- Relatórios Gerenciais
- Pagamentos de funcionários

Sistema de catraca:
- Acatar matriculas
- Boquear alunos com pagamentos atrasados
- Gerenciar controles de acesso/presença