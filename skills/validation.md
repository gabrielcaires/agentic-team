# Skill: validação

## Objetivo

Obter evidências de que a mudança funciona e não causa regressões conhecidas.

## Processo

1. Execute primeiro os testes focados nos caminhos alterados.
2. Execute lint, compilação ou outras verificações existentes relevantes ao escopo.
3. Inspecione o diff e confirme que não há alterações não relacionadas, arquivos gerados ou segredos.
4. Revise casos de erro, entradas de borda e implicações de segurança introduzidas pela mudança.
5. Registre os comandos executados e os resultados; diferencie falhas preexistentes das causadas pela mudança quando houver evidência.

## Resultado

Um relatório conciso com verificações aprovadas, falhas e itens não executados. Nunca trate uma verificação não executada como aprovada.
