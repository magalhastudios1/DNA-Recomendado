# DNA Recomendado

## Visão Geral  
Sistema de Recomendação que utiliza computação evolutiva para otimizar a distribuição de estoque entre depósitos e cervejarias.

[Link da Apresentação do Projeto](https://storage.googleapis.com/taikai-storage/others/0cc776d0-385f-11ec-b2fd-37da095ce81aentrega_propotipacao.pdf)

### Problema  
- Otimizar o estoque de produtos nos depósitos para que atinja o estoque balanceado
- Utilizar das melhores rotas das cervejarias aos depósitos para minimizar o
custo com transporte
- Utilizar das melhores quantidades de produtos para envio para evitar
caminhões com pouca carga

### Proposta de solução  
A abordagem da Computação Evolutiva foi escolhida para o problema de otimizar a distribuição de estoque entre depósitos e cervejarias pois os algoritmos genéticos são flexíveis para se adequar as métricas que a Ambev gostaria de maximizar. Além disso são ótimos para lidar com problemas complexos em que se desconhece algum algoritmo ótimo que retorne a resposta em tempo polinomial, pois podem retornar uma boa resposta em um tempo plausível.

# Informações Técnicas
[Detalhamento do Código](code.ipynb)  
## Gráfico explicativo
![](images/pseudocodigo.png)  
> 1. Gera a população inicial
> 2. Verifica se função de parada é satisfeita
>    sim: retorna o melhor cromossomo da população
>    não: continua
> 3. Obtem os scores da população
> 4. Filtra população através de torneio
> 5. População faz reprodução
> 6. População faz mutação
> 7. Retorna ao passo 2

## Pré requisitos
- Conexão com Internet
- Conta Google  
- Navegador compatível com Google Colab

## Processo de instalação e execução
Para executar o código do notebook inteiro faça os seguintes passos:
- 


# Time

[<img src="https://avatars.githubusercontent.com/u/44060813?v=4" width="115"><br><sub>@magalhastudios1</sub>](https://github.com/alexandremendoncaalvaro) 
