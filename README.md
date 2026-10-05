# Sistema de Estoque - Oficina Mecânica

## Integrantes do grupo
| Nome | Prontuário |
|------|------------|
| Gabriel Luis de Lima Capodeferro | BP3053628 |
| Sanmara Gomes de Lima | BP306106X |

## Propósito
Simular o planejamento e a execução de releases de uma miniaplicação web
(login com perfis de administrador e operador), praticando controle de
versão com Git: branches, commits, pull requests, tags e releases.
Tema: base de um futuro sistema de estoque para oficina mecânica, em que o
administrador cadastrará os itens e cuidará do financeiro, e o operador
apenas informará a quantidade em estoque. Nesta atividade só existem as
páginas de login e de perfil, sem as funcionalidades de estoque.
Disciplina: Gestão de Projetos de Software - 4º ADS - IFSP Bragança Paulista.

## Plano de releases
| Release | Tag  | Conteúdo |
|---------|------|----------|
| 1 | v0.1 | index.html (login) e working.html (em construção) |
| 2 | v0.2 | index.html sem consistência chamando pg001.html (administrador) |
| 3 | v1.0 | Funcionamento completo: index, pg001, pg002 e msg |

## Estratégia de branches
- main: somente código de release (marcado com tags)
- develop: integração das funcionalidades
- release1, release2, release3: branches de funcionalidade
- correcoes: branch de correção de bug
