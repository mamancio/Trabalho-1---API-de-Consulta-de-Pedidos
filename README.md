## ATIVIDADE 1 - API DE CONSULTA DE PEDIDOS

Modelagem de Serviços

1.Considere as instuação abaixo para a modelagem na abordagem API First do design da api.
Uma empresa deseja expor a consulta de seus pedidos via API seguindo a arquitetura Restful;
esta API inicialmente será aberta aos clientes dessa plataforma e, adiante, poderá ser ofertada monetizada.
O pedido é caracterizado, sob o contexto de negócio com as seguintes informações:

![image](https://github.com/mamancio/Trabalho-1---API-de-Consulta-de-Pedidos/assets/41075397/7f91540b-cb2e-4ab5-a0b8-3106b88ef31e)

Cada pedido é constituído por um ou mais itens, que consistem em:

![image](https://github.com/mamancio/Trabalho-1---API-de-Consulta-de-Pedidos/assets/41075397/a7149221-8472-4bfc-8e35-e19434b58cc4)

A API deverá disponibilizar a consulta dos pedidos e dos seus respectivos itens.
Vale dizer que nesta empresa um pedido pode ter inúmeros itens, o que sugere ser adequada a consulta de itens a partir de apenas 1 pedido.

As necessidades de filtros para a consulta são:

* código do pedido
* código do cliente
* CPF do cliente
* status
* data do pedido: maior e menos que