# prisma-01: Experiência de evolução no banco

- Podemos conectar nossas aplicações aos bancos de dados utilizando drivers.
- Os drivers oferecem APIs que nos permitem escrever queries para serem executadas.
- No entanto, escrever queries “na mão” nem sempre é a melhor solução.
- Imagine que você está em uma equipe de desenvolvimento e precisa fazer a seguinte alteração na aplicação:
    - O campo `createAt` deve ser inserido na tabela `posts`. Deve ser do tipo Date.
    - A informação deve ser enviada no post no formato: `YYYY/MM/dd`. Ela não é obrigatória. Se não for informada, receber o valor `new Date()`.
    - Altere o campo `body` da tabela posts para `content`.
- ➡️ Crie os SQL correspondentes imaginando que já existem dados em produção. Faça as alterações na queries, types e o que mais for necessário.
- Não é necessário rodar o arquivo .sql, você pode só criar/alterar a tabela pelo terminal ou pgadmin usando as queries que estão no arquivo.