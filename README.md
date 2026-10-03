# agentic-team

Um conjunto de perfis de agentes e skills reutilizáveis para colaborar em tarefas de desenvolvimento de software. Os arquivos descrevem responsabilidades e fluxos de trabalho; podem ser adaptados para a plataforma de agentes utilizada pelo projeto.

## Agentes

| Agente | Responsabilidade | Skills |
| --- | --- | --- |
| [Coordenador](agents/coordinator.md) | Entender a solicitação, dividir o trabalho e integrar os resultados. | Descoberta do repositório, validação |
| [Pesquisador](agents/researcher.md) | Investigar o código e identificar requisitos, convenções e riscos. | Descoberta do repositório |
| [Implementador](agents/implementer.md) | Fazer mudanças pequenas e direcionadas e cobrir o comportamento com testes. | Implementação, validação |
| [Revisor](agents/reviewer.md) | Revisar mudanças em busca de regressões, falhas e riscos. | Validação |

## Skills

- [Descoberta do repositório](skills/repository-discovery.md): mapear estrutura, comportamento existente e comandos de validação.
- [Implementação](skills/implementation.md): planejar e realizar uma alteração focada, com cobertura adequada.
- [Validação](skills/validation.md): executar verificações relevantes e revisar o diff.

## Fluxo sugerido

1. O coordenador registra o objetivo e os critérios de conclusão.
2. O pesquisador mapeia o código e as verificações existentes.
3. O implementador realiza a menor alteração completa e executa testes direcionados.
4. O revisor verifica o diff e os resultados; o coordenador integra e comunica a conclusão.

Para tarefas pequenas, uma única pessoa ou agente pode acumular papéis. Preserve a separação de responsabilidades como orientação, não como requisito de ferramenta.
