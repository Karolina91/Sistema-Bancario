# Sistema-Bancario
<h1>Desenvolvimento de um sistema de autoatendimento bancário.</h1>
<p1> No âmbito deste projeto que desenvolvi como parte da disciplina de Programação Orientada a Objetos, elaborei um sistema bancário em Python. Essa modelagem de caixa de autoatendimento proporciona a execução de diversas operações financeiras, como saques, depósitos, pagamentos programados, solicitações de crédito e consultas de histórico. A estrutura do sistema é construída com base em classes, onde foram criadas as classes "Pessoa", "Cliente", "Gerente", "BancoDados" e "CaixaEletronico". Essa abordagem orientada a objetos contribui para uma organização eficiente e modular do código.</p1>
<h1>Classes utilizadas:</h1>

  <h2>Pessoa</h2>
  <p>Classe base para "Cliente" e "Gerente", armazenando informações comuns:</p>
  <ul>
    <li>Nome</li>
    <li>CPF/CNPJ</li>
    <li>Endereço</li>
    <li>Telefone</li>
    <li>Senha</li>
  </ul>

  <h2>Cliente</h2>
  <p>Subclasse de "Pessoa" com recursos específicos:</p>
  <ul>
    <li>Saldo</li>
    <li>Histórico de Transações</li>
  </ul>
  <p>Operações disponíveis para clientes:</p>
  <ul>
    <li>Saques</li>
    <li>Depósitos</li>
    <li>Pagamentos Programados</li>
    <li>Verificação de Histórico</li>
    <li>Solicitação de Crédito</li>
  </ul>

  <h2>Gerente</h2>
  <p>Outra subclasse de "Pessoa" com métodos específicos:</p>
  <ul>
    <li>Cadastrar Cliente</li>
    <li>Remover Cliente</li>
    <li>Editar Cliente</li>
    <li>Visualizar Cliente</li>
  </ul>

  <h2>Banco Dados</h2>
  <p>Responsável pela manipulação de um arquivo CSV com os dados dos clientes:</p>
  <ul>
    <li>Carregar Clientes</li>
    <li>Salvar Clientes</li>
    <li>Verificar Existência de Cliente</li>
    <li>Cadastrar Novos Clientes</li>
  </ul>

  <h2>Caixa Eletrônico</h2>
  <p>Recebe um objeto "Cliente" para operações bancárias:</p>
  <ul>
    <li>Saques</li>
    <li>Depósitos</li>
    <li>Pagamentos Programados</li>
    <li>Verificação de Histórico</li>
    <li>Solicitação de Crédito</li>
  </ul>
  <h1>Funcionalidades</h1>
  <ul>
    <li>Realizar login como cliente existente ou cadastrar um novo cliente.</li>
    <li>Realizar saques, depósitos e pagamentos programados.</li>
    <li>Verificar histórico de transações.</li>
    <li>Solicitar crédito.</li>
    <li>Cadastrar, remover, editar e visualizar clientes como gerente.</li>
  </ul>

  <h1>Tecnologias Usadas</h1>
  <ul>
    <li>Linguagem Python para desenvolvimento do projeto.</li>
    <li>Biblioteca CSV para manipulação de arquivos.</li>
    <li>Um arquivo de dados CSV para armazenamento dos clientes.</li>
    <li>Utilização do Jupyter Notebook para compilar os trechos de códigos.</li>
  </ul>
