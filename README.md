# DNA Recomendado

Sistema de Recomendação que utiliza computação evolutiva para otimizar a distribuição de estoque entre depósitos e cervejarias.

## Visão Geral  
Esta é uma documentação modelo para os projetos do Academy Hack.  
Aqui você deverá descrever uma visão geral do seu projeto.  

[Link da Apresentação do Projeto](http://caminho.para.o.ppt)

### Problema  
O problema que está sendo resolvido é o problema de otimizar a distribuição de estoque entre depósitos e cervejarias. Sabe-se que cada depósito tem propriedades como: estoque mínimo, estoque máximo, estoque balanceado, e é necessário distribuir os produtos das cervejarias a fim de suprir as demandas locais.

### Proposta de solução  
A abordagem da Computação Evolutiva foi escolhida para o problema pois os algoritmos genéticos são flexíveis para se adequar as métricas que a Ambev gostaria de maximizar. Além disso são ótimos para lidar com problemas complexos em que se desconhece algum algoritmo ótimo que retorne a resposta em tempo polinomial, pois podem retornam uma resposta boa em um tempo plausível.

# Informações Técnicas
## Gráfico explicativo
![](images/pseudocodigo.png)  
> ```
> 1. Gera a população inicial
> 2. Verifica se função de parada é satisfeita
>    sim: retorna o melhor cromossomo da população
>    não: continua
> 3. Obtem os scores da população
> 4. Filtra população através de torneio
> 5. População faz reprodução
> 6. População faz mutação
> 7. Retorna ao passo 2
```

![](images/pseudocodigo.png)  

## Pré requisitos
- Sistema Operacional  
- Linguagem Utilizada  
- Ambiente virtual
- Bibliotecas  

## Processo de instalação e execução
Aqui deve conter um passo a passo auto explicável que possa ser replicado pelos avaliadores para a execução do sistema.
Sugerimos a utilização de virtual enviroment para evitar falhas.


# Time

[<img src="https://avatars.githubusercontent.com/u/44060813?v=4" width="115"><br><sub>@magalhastudios1</sub>](https://github.com/alexandremendoncaalvaro) 
