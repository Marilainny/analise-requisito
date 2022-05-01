<!-- Configuração do git README.md no site: https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax-->

# analise-requisito
Repositório público com arquivos de analise de requisitos.

<h1>Importância da Análise de Requisitos</h1>
<p>
    <strong>
        <li>Garante a entrega de qualidade</li>
    </strong>
    <strong>
        <li>Possibilita um planejamento mais próximo do real</li>
    </strong>
    <strong>
        <li>Diminuição de retrabalho</li>
    </strong>
</p>
<h1>Ciclo de Vida do Desenvolvimento de Sistema</h1>
<img align="center" alt="Rafa-Ts" height="200" width="700"
    src="https://github.com/Marilainny/analise-requisito/blob/main/imagem/ciclodesenvolvimento.png">

<h2>Conceitos de Análise de Requisitos</h2>
<p>
    <strong>Requisito - </strong> funcionalidade que o sistema deve possuir ou uma restrição que deve sastifazer uma
    necessidade do cliente. Podendo ser dos seguintes tipos:
    </br>
    <strong>Requisito Funcional</strong>
    <li>Recursos do sistema.</li>
    <li>O que se espera que o sistema faça, independente de como isso será implementado.</li>
    Exemplo: "A aplicação deve gerar relatórios"
    <li>O que o sistema não pode fazer.</li>
    <br>
    <strong>Requisito Não Funcional </strong>
    <li>Qualidade gerais ou restrições do sistema como facilidade de utilização, facilidade de manutenção, segurança,
        desempenho, dentre outros.</li>
    Exemplo: "O sistema deve ser baseado em linux."
</p>

<h1>Processo de Engenharia de Requisitos</h1>
<li><strong>Estudo de viabilidade</strong></li>
<li><strong>Elicitação de Requisitos</strong></li>
<li><strong>Análise de requisitos</strong></li>
<li><strong>Especificação de requisitos</strong></li>
<li><strong>Validação de requisitos</strong></li>
<li><strong>Gerenciamento de requisitos</strong></li>

<h2>Elicitação e Análise de Requisitos</h2>
<img align="center" alt="Rafa-Ts" height="300" width="600" src="https://github.com/Marilainny/analise-requisito/blob/main/imagem/elicitacao.png">
<h2>Dificuldades na Elicitação dos Requisitos</h2>
<p>
    <li><i>Stakeholders</i> não sabem o que querem do softaware.</li>
    <li><i>Stakeholders</i> não sabem explicar o que querem do softaware.</li>
    <li><i>Stakeholders</i> podem fazer exigências inviáveis.</li>
    <li><i>Stakeholders</i> usam sua própria linguagem.</li>
    <li><i>Stakeholders</i> podem ter requisitos conflitantes.</li>
    <li>Fatores organizacionais podem influênciar como mudança de legislação.</li>
    <li>Requisitos mudam durante a engenharia de requisitos.</li>    
</p>
<img align="center" alt="Rafa-Ts" height="600" width="700" src="https://github.com/Marilainny/analise-requisito/blob/main/imagem/charge.jpeg">

<h1>Descoberta Dos Requisitos</h1>
<li>Fontes: documentação, <i>Stakeholders</i>, especificações de sistemas similares.</li>
<li>Técnica de extração de requisitos: entrevistas, etnografia (observação do ambiente de trabalho), prototipação, casos de uso.</li>
<li>Artefatos gerados: documento de requisito ou especificação de requisitos de software.</li>
<li>Casos de usos.</li>
<li>Detalhamento dos requisitos.</li>
<li>Protótipos.</li>

<h2>Contexto dos Exemplos dos Artefatos</h2>
<p>
    <li>Considere como exemplo nos artefatos um sistema em que o <i>Stakeholder</i> (usário final) tenha pedido um sistema CRM de Vendas que inicialmente será feito somente o cadastro de clientes, de usuários e a autenticação do usuário</li>
    <li>O cadastro de cliente deve conter os campos CPF, nome e telefone do cliente, que são campos obrigatórios. Deve permitir cadastrar, editar, excluir e consular clientes.</li>
    <li>O cadastro de usuários deve conter os campos de login (CPF), nome e senha.</li>
    <li>Deve permitir que o usuário autentique no sistema informando login e senha.</li>
    <li>Este sistema deve ser online. Deve ser feito na linguagem de programação Java e com banco de dados MySQL.</li>
</p>
<h1>Como criar Documento de Requisto</h1>
<li><strong>Introdução</strong> - Objetivo do documento e o público alvo do escopo</li>
<li><strong>Justificativa do projeto</strong></li>
<div style="text-indent: 5px">
- Objetivos
- Escopo do projeto de forma geral
- Cenário atual do sistema, caso seja uma melhoria.
- Escopo não contemplado, caso seja necessário.
</div>
<li><strong>Requisito Funcionais</strong> - principais funcionalidades que o sistema de softaware deve ter em formato de tabela.</li>
<li><strong>Requisito Não Funcional</strong> - contém as restrições e qualidades do sistema também em formato de tabela.</li>
<li><strong>Protótipos</strong> -  link das imagens ou HTML dos protótipos do sistema (opcional).</li>
<li><strong>Diagramas</strong> - link ou imagem dos diagramas (opcional).</li>
<li><strong>Fornecedor do requisitos</strong>nome dos Fornecedores de requisitos</li>
