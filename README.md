# TaskFlow – Recuperação Paralela
Aplicação didática PHP + MySQL/MariaDB, sem login.

## Instalação
1. Copie a pasta `taskflow` para `C:\xampp\htdocs`.
2. Inicie Apache e MySQL no XAMPP.
3. Importe `database/taskflow.sql` pelo phpMyAdmin.
4. Acesse `http://localhost/taskflow`.

Consulte os chamados, reproduza as falhas, investigue o código, corrija, reteste e registre causa, correção, arquivos e testes no fechamento.

TF-001: cadastre uma tarefa válida e ela deve aparecer na lista. Depois tente gravar com o responsável vazio e deve voltar o erro.
TF-002: filtre por "Em andamento" e só devem aparecer tarefas desse status.
TF-003: o Dashboard deve mostrar 2 prioritárias, que são as tarefas Alta do seed.
TF-004: edite o status de uma tarefa, grave, reabra e veja se o valor ficou.
TF-005: o Dashboard deve mostrar 2 concluídas no estado inicial. Mude outra tarefa para Concluída e confira se sobe para 3.
TF-006: clique em Excluir, cancele e confirme que a tarefa continua na lista.