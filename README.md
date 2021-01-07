http://ttc.herculano.xyz<br>
[Frontend](https//github.com/herculan0/ttc-front)</br>
[Backend](https://github.com/herculan0/ttc-api)</br>
[Devtools](https://github.com/herculan0/ttc-devtools)</br>


- [x] O desafio consiste em construir uma stack de infraestrutura que provisione um ambiente para rodar duas aplicações e 
- [x] Um banco de dados em dois cloud providers distintos (AWS, Azure ou
GCP) conforme dados abaixo:

- [x] Aplicação 1 - (Cloud Provider 1): backend rest hipotético, em qualquer linguagem, com
- [x] scalling automático em caso de aumento de requisições no mesmo.

- [x] Aplicação 2 - (Cloud Provider 1): Frontend em qualquer linguagem hospedado em duas
instancias de maquinas virtuais, e acessado através de um balanceador de carga, que deverá
- [x] ter reduncia de rede por zona de disponibilidade.

- [ ] Ambas aplicações devem responder pelo mesmo DNS, porém com contextos (paths)
distintos.

- [x] Banco de dados - (Cloud Provider 2): Criar um banco de dados qualquer em um segundo
cloud provider. o acesso ao banco devera ser feito através de outro nome de dns, porem do
mesmo domínio das aplicações. 
- [x] O acesso ao banco de dados deverá ser restrito somente as
duas aplicações acima.

- [x] A comunicação entre as aplicações (cloud provider 1) e o banco de dados (cloud provider 2),
deverá ser feita de forma privada, exemplo VPN.

## Requisitos:
- [x] Ambiente Cloud (AWS, Azure ou GCP)
- [x] Infraestrutura básica de rede (firewall, subnets, etc)
- [x] Load Balancer
- [x] Resolução de DNS para o Load Balancer
- [x] Documentação detalhada e instruções para execução em ambiente real (produção e
desenvolvimento).
- [ ] Comparação/avaliação de custos em relação as diferentes possibilidades técnicas na criação
deste ambiente

## Tecnologias sugeridas:
Pode-se fazer uso das seguintes tecnologias:
- [x] Docker
- [x] Terraform
- [ ] Ansible
- [x] Kubernetes (Gerenciado ou nao)
- [x] Instancias de maquinas virtuais
- [ ] Serviços gerenciados de hospedagem de aplicações (Azure App Service , AWS Beanstalk)
- [x] Banco de dados Gerenciado ou nao

OBS: outras ferramentas/soluções também são bem vindas, desde que funcione de forma
simples e eficiente.

## Será avaliado:
- Organização
- Percentual de entrega
- Criatividade
- Roadmap de futuras melhorias
- Qualidade da documentação
- Uso de ferramentas de automatização
- Elegância na solução proposta
- Simplicidade e eficiência
- Técnicas e boas práticas de segurança

## Entrega:
O código deverá ser entregue em um repositório git hospedado na nuvem (ex: GitHub).

