# Teste de React
##### Objetivo
Criar um Crud simples, totalmente desenvolvido em ReactJS, sem a utilização de outras bibliotecas, onde será possível Criar/Editar/Excluir/Listar usuários e veículos. O sistema também deve possuir a possibilidade de vincular/desvincular Veiculos ao usuário.

##### Estrutura de banco de dados
A seguinte estrutura será utilizada para persistência dos dados, podendo ser alterada a qualquer momento para melhor funcionamento do sistema:

```sql
    tabela: users
        id      int not null auto_increment primary key
        tipo    varchar(100)
        nome    varchar(100) not null
        email   varchar(100) not null
```
```sql
    tabela: veiculo
        id      int not null auto_increment primary key
        nome    varchar(50) not null
        placa    varchar(50) not null
```

##### Start
Antes de iniciar Faça um Fork deste repositório e faça commits de cada alteração do sistema. Isso será avaliado também. Ao final envie um Pull Request para a aprovação.

##### Boa Sorte
Use seu conhecimento, consulte a documentação e o google, caso ainda houver dúvidas, nos pergunte :D. Boa sorte!

##### Pontos que serão levados em conta
- Funcionalidade
- Organização
- Apresentação da interface (Poderá usar frameworks mas recomendo criar do 0 ou usar Styled Components)
