<h2 title='#tecnologias'>
    Capítulo 2
</h2>

#### Um olhar no quadro geral pág 37 (Desafio)

- Falar sobre o setor imobiliário;
- Conjunto de dados da califórnia (1997);
- Métricas: populção, renda média, preço médio do setor imobiliário;
- OBS: grupo de bairros tem (600 a 3 mil pessoas).

<h3 title='#pipeline'>
    Pipeline em Aprendizado de Máquina
</h3>

#### Uma sequência de componentes de processamento de dados é chamado de pipeline de dados. Geralmente roda de forma assicrona. Cada componente do pipeline puxa um conjunto de dados, processa e
envia o resultado para o proximo componente e assim por diante, até chegar ao estágio final do processo. Vale ressaltar que a estrutura pipeline deixa os componentes bastantes
autonomos, podendo cada equipe concentrar em seu determinado componente. Outro aspecto importante é se um componente romper ou tiver algum problema os componentes downstream geralmente
podem continuar a funcionar mesmo que por um tempo, utilizando apenas a ultima saida valida, tornando assim a arquitetura robusta. Contudo é sempre importante ser feito um monitoramento
do componente para que o mesmo não se rompa e passa a ser despercebido. Deixando assim os dados com ruidos e afetando o desempenho do processo e do resutaldo final.




