# Bem vindo a mais um teste de ReactJS <img alt="Meu site" width="48px" src="https://github.com/filipeleonelbatista/filipeleonelbatista/blob/master/assets/Hi.gif" />

##### Objetivo
Criar um Crud simples, totalmente desenvolvido em `ReactJS`, onde será possível Criar/Editar/Excluir/Listar usuários e veículos. O sistema também deve possuir a possibilidade de vincular/desvincular Veiculos ao usuário.

##### Estrutura de banco de dados

O banco de dados a ser utilizado pode ser `SQLite`, `Postgres` ou pode usar o `localstorage` para salvar.<br />
Caso use o `localstorage`, crie uma função que popule alguns dados para os testes.<br />
Na etapa de avaliação será legal ter no mínimo 3 usuarios cadastrados e 2 veículos.<br />
A seguinte estrutura será utilizada para persistência dos dados, podendo ser alterada a qualquer momento para melhor funcionamento do sistema:

```sql
    tabela: users
        id      int not null auto_increment primary key
        tipo    varchar(100)
        nome    varchar(100) not null
        email   varchar(100) not null
        foto   varchar(255) not null
```
```sql
    tabela: veiculo
        id      int not null auto_increment primary key
        nome    varchar(50) not null
        placa    varchar(50) not null
        foto   varchar(255) not null
```

##### Start
Antes de iniciar Faça um Fork deste repositório.<br />
Envie o link do seu repositório 'forkado' e faça commits de cada alteração do sistema. <br />
Isso será avaliado também.<br />
Ao final envie um Pull Request para a aprovação.<br />

##### Boa Sorte
Use seu conhecimento, consulte a documentação e o google, caso ainda houver dúvidas, nos pergunte :D. Boa sorte!

##### Pontos que serão levados em conta
- Funcionalidade
- Organização
- Apresentação da interface (Poderá usar frameworks mas recomendo criar do 0 ou usar Styled Components)

🔗 [Meus links para contato](https://filipedev.ga) <br/> 

<h3 align="center" >Vamos nos conectar 😉</h3>
<p align="center">
  <a href="https://filipedev.ga">
    <img alt="Meu site" width="22px" src="https://github.com/filipeleonelbatista/filipeleonelbatista/blob/master/assets/worldwide.svg" />
  </a>&ensp;
  <a href="https://www.linkedin.com/in/filipeleonelbatista/">
    <img alt="LinkedIn" width="22px" src="https://github.com/filipeleonelbatista/filipeleonelbatista/blob/master/assets/052-linkedin.svg" />
  </a>&ensp;
  <a href="https://instagram.com/filipeleonelbatista">
    <img alt="Instagram" width="22px" src="https://github.com/filipeleonelbatista/filipeleonelbatista/blob/master/assets/044-instagram.svg" />
  </a>&ensp;
  <a href="https://desenvolvedordeaplicativos.ga/">
    <img alt="Meu site" width="22px" src="https://github.com/filipeleonelbatista/filipeleonelbatista/blob/master/assets/worldwide.svg" />
  </a>
</p>
