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