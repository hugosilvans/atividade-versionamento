# Guia de leitura do código

Este guia descreve a organização para estudar e explicar o repositório. Os comentários do código destacam regras, contratos, validações e responsabilidade pela memória ou pelos dados.

## Por onde começar

| Caminho | Responsabilidade |
| --- | --- |
| [index.txt](index.txt) | Exemplo HTML com o conflito resolvido. |
| [exemplos/conflito-nao-resolvido.txt](exemplos/conflito-nao-resolvido.txt) | Registro do conflito original para comparação. |

## Como estudar uma alteração

1. Identifique a entrada: argumento, formulário ou requisição HTTP.
2. Localize a validação e a função que transforma os dados.
3. Observe a saída e o comportamento quando algo falha.
4. Execute um exemplo pequeno antes de mudar a regra.
5. Consulte o diff do Git para distinguir formatação de mudanças de comportamento.

## Convenções

- `.editorconfig` define codificação, indentação e final de linha.
- Comentários explicam motivos e restrições; não repetem cada comando.
- Arquivos gerados, dependências e credenciais locais ficam fora do versionamento.
- Um `main` pertence ao seu exercício; projetos de aula independentes não formam um único executável.
- Créditos, autoria anterior e licenças são preservados.
- `.prettierrc.json` registra a formatação dos arquivos web.

## Limite desta organização

A formatação e os comentários não comprovam que todos os exercícios estejam completos. Os testes adicionados cobrem os fluxos descritos no README; validar sintaxe não equivale a testar todos os resultados. Veja também as instruções e limitações específicas do projeto.
