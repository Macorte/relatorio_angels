# Métircas de KYC dos Atendimentos dos Angels
## Introdução:
O time de logistica vem apontando problemas relacionados as metas de KYC check, nesse relatório vamos buscar respostas para as metas não estarem sendo batidas.
### Dados de KYC check em relação a data das visitas
![image](https://user-images.githubusercontent.com/62664736/123815011-84ed3c00-d8cc-11eb-9982-16e2f4930b98.png)

- **diff:** Número total de visitas em usuários que ativaram o KYC
- **ativacao_dps_visita:** Número total de ativações feitas após a visita do Angel.
- **ativacao_na_visita:** Número total de ativações feitas no dia da visita do Angel.
- **ativacao_antes_visita:** Número total de ativações feitas antes da visita.

## Análise:
Com esses dados é possível determinar que a grande parte das ativações é feita antes da visita do Angel(65,89%), impossibilitando o mesmo de fazer a ativação do KYC assim gerando uma conturbação quanto a meta de ativação do KYC, para facilitar a visualização segue o gráfico abaixo:

![image](https://user-images.githubusercontent.com/62664736/123816531-c6cab200-d8cd-11eb-9212-1798cc875129.png)

Somando as ativações no dia de visita com as feitas após a visita o número sobe para 77.472(34,11%), sendo ainda sim uma parcela pequena do total das ativações representadas abaixo:

![image](https://user-images.githubusercontent.com/62664736/123817528-9f281980-d8ce-11eb-97e3-446ac56618a2.png)

Indo mais afundo na análise separei as ativações posterioeres em dois grupos, ativações feitas superior a 9 dias depois da visita = 31.419(40,56%) e ativações até 9 dias depois da visita = 46.053(59,44%), essa separação foi feita para analisar o impacto da visita na ativação do KYC, tendo em vista que foi considerado que após 9 dias a ativação provavelmente não teria relação com a visita do angel, segue abaixo a vizualização:

![image](https://user-images.githubusercontent.com/62664736/123818826-b0255a80-d8cf-11eb-8d59-5acf7fed42c0.png)

Para análise foi tirada a média de dias que leva para um cliente fazer o KYC check após a visita do angel, sendo essa média = 30,2, porém é notável que a amplitude dos dados é muito grande fazendo com que haja disparidades gigantes entre os dias onde o KYC foi checado, dessa forma a média de dias que um cliente leva para fazer o KYC check após a visita do angel não parece ser um bom indicador.

## Conclusão
Se compararmos as ativações possivelmente relacionadas com a visita dos angels(ou seja feitas até 9 dias depois da visita) com o total de de ativações = 227.097, vemos que as ativações possivelmente relacionadas as visitas representam apenas 20,28% do total e considerando que a maior parte das ativações é feita antes da visita do angel(65,89% do total), a métrica de KYC check não aparenta ser o melhor método para avaliar o desepenho de um Angel. 
