# Como contribuir

Obrigado por servir com a gente. Estas regras valem para todos os repositórios da organização Exsultet.

## Fluxo de trabalho

1. Crie uma branch a partir de `main`: `feat/<assunto>`, `fix/<assunto>` ou `docs/<assunto>`.
2. Faça commits pequenos no padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/):
   `feat: adiciona trilha do Credo`, `fix: corrige contagem da vela`, `docs: explica a revisão doutrinal`.
3. Abra um Pull Request preenchendo o template. A CI precisa passar.
4. `main` é protegida: nada entra sem PR revisado.

## Conteúdo doutrinal

Todo texto que ensina a fé (lições, respostas do tutor, orações, reflexões) passa por **revisão doutrinal humana** antes de chegar ao usuário. Marque o PR com a label `doutrina` e cite a fonte (número do Catecismo, documento do Magistério, passagem bíblica).

Conteúdo gerado por IA nunca é publicado como doutrina sem essa revisão.

## Dados e privacidade

Convicção religiosa é dado pessoal sensível (LGPD, art. 5º, II). Nunca registre em log dados pessoais, nunca commite segredos e trate dados de menores com o consentimento dos pais (LGPD, art. 14).

## Código

- Siga o lint e o formatador do repositório; a CI falha se não seguir.
- Escreva testes para regras de negócio.
- Interfaces acessíveis: contraste AA, alvos de toque de 44 px, rótulos em todos os controles.
