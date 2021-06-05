# Aula01 - Definindo o layout base  
## Definindo o layout base:  
```display: grid;``` Deve ser colocado na tag pai.  
- **Ex:**  
```
.body{
    display: grid;
}
```
- Na tag pai deve-se definir as áreas:  
```
grid-template-areas:
	"cabecalho"
	"conteudo"
	"rodape";
```
```grid-template-columns: auto;``` Define a largura das colunas.  
```grid-template-rows: 50px auto auto;``` Define a altura das linhas.  
```grid-area: cabecalho;``` Colocando no filho, especifica em que área ele pertence.  
- **Ex:**  
```
.cabecalho{
    background-color: green;
    grid-area: cabecalho;
}
```

# Aula02 - Criando o layout da seção de destaques
## Criando a seção destaques:  
```grid-template-columns: 25% 25% 25% 25%;``` É possível definir o tamanho das colunas e a quantidade.  
```grid-template-rows: 33.33% 33.33%;``` O mesmo vale para o tamanho e quantidade de linhas.
```height: calc(100vh - 50px);``` A propriedade height recebe o resultado de 100vh - 50px.  

## Posicionando elementos:  
```grid-column: 1 / 4;``` Começa do bloco 1 até o bloco 4 sem preencher o bloco 4.  
```grid-row : 2 / 2;``` Começa na linha 2 e termina na linha 2.  

## Estilizando os destaques:  
```grid-gap: 0.2rem;``` Cria um espaçamento entre linhas e colunas.