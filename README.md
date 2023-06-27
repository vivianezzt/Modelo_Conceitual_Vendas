## Formação Desenvolvedor Moderno
## Módulo: Banco de Dados
## Capítulo: Modelo Conceitual

# DESAFIO: Modelo Conceitual Vendas
<p>Tarefa: com base na visão geral de sistema abaixo, faça:</p>
<ul>
  <li>O modelo conceitual usando o diagrama de classes da UML</li>
  <li>Esboce uma instância do modelo, atendendo os requisitos mínimos pedidos</li>
</ul>

# Exercício Proposto

<p>Deseja-se fazer um sistema para armazenar informações de vendas e vendedores de uma empresa.
Cada vendedor possui um id, nome, email e salário base. Cada vendedor pertence a um departamento,
sendo que se deve conhecer a data de início e fim da contratação de cada vendedor no departamento
(nota: se a contração do vendedor no departamento ainda não terminou, a data de fim deverá ser nula).
Ao longo do tempo, o mesmo vendedor pode ser removido de um departamento e contratado para
outro, podendo inclusive ser recontratado para o departamento em uma data futura.</p>

<p>Deseja-se também registrar as vendas realizadas pelos vendedores. Cada venda possui uma data e um
status (pendente, faturada ou cancelada), e pode ter um ou mais itens, sendo que cada item de venda
corresponde a um produto, que pode ser vendido em quantidade 1 ou superior. Os dados do produto
são nome e preço.</p>

<p>Instância mínima:</p>
<ul>
  <li>3 produtos</li>
  <li>2 vendas</li>
  <li>Pelo menos 2 itens por venda</li>
  <li>2 departamentos</li>
  <li>Pelo menos 2 contratações por departamento</li>

## Segue a resolução:

  ### Diagrama de Classes
  <img src="https://github.com/vivianezzt/Modelo_Conceitual_Vendas/blob/main/ModeloConceitualVendas/diagramadeclassesvendas.png">

  ### Diagrama Classe Auxiliar

  <img src="https://github.com/vivianezzt/Modelo_Conceitual_Vendas/blob/main/ModeloConceitualVendas/Enum.png">

  ### Diagrama de Objetos

  <img src="https://github.com/vivianezzt/Modelo_Conceitual_Vendas/blob/main/ModeloConceitualVendas/diagrama-objetos.png">
</ul>

<h3> CRÉDITOS &copy;</h3>
<h4> Este desafio foi proposto pelo Prof. <a href="https://www.instagram.com/devsuperior.ig/">Nélio Alves</a> no Módulo - Programação Moderna (JAVA)
</h4><a href="https://devsuperior.com.br/evento-sds">DEVSUPERIOR - Faça parte você támbem</a>
