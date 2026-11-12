# Matrículas da rede estadual por especificidade

Quantidade mensal de matrículas da rede estadual de ensino de Minas Gerais em turmas com especificidades, por Superintendência Regional de Ensino (SRE) e município, de fevereiro a dezembro de cada ano letivo, a partir de 2023.

**Especificidades:** Educação Especial - AEE (Sala de Recursos), Educação Especial - Escola Exclusiva, Quilombola, Indígena, Socioeducativo e Prisional.

## Como os dados foram produzidos

- **Fonte:** SIMADE (Sistema Mineiro de Administração Escolar).
- **Abrangência:** escolas da rede estadual.
- **Regra de contagem:** matrículas ativas no último dia de cada mês. Matrículas encerradas em dezembro por resultado final (aprovação, reprovação, conclusão) ou por fechamento de período da EJA contam até 31/12.
- **Especificidade:** definida pela turma em que o estudante está enturmado, conforme registro no SIMADE em cada ano letivo. Uma matrícula pode ter mais de uma especificidade; por isso as categorias **não devem ser somadas entre si**.
- **Educação Especial - AEE (Sala de Recursos):** disponível a partir de 2026, quando o SIMADE passou a registrar a enturmação em Sala de Recursos.
- **Proteção de dados (LGPD):** quantidades de 1 a 4 matrículas são suprimidas (campo `qtd_matriculas` vazio e `suprimido = S`).

## Atualização

Mensal. Cada ano letivo está em um arquivo separado (`see-matriculas-especificidades-AAAA.csv`).

## Responsável

Assessoria de Inovação (ASI) - Secretaria de Estado de Educação de Minas Gerais.
