## Projeto para a disciplina de Teoria dos Grafos
Programa em python que oferece as seguintes funcionalidades

- Le n, n>0, e as arestas ij, i<j em {0,1,2,...,n-1}=V  
Pede o nome do grafo G. (dado pelo usuário)  
Armazena G=(V,E) na memória.  
- Pede o nome do grafo G e carrega e imprime a matriz de adjacências M{nxn} de G. 
  E o valor de m=|E|.  
 - Produz um grafo de uma classe especial:  
	1. Completo - Nesse caso: Input (n:inteiro positivo) e salva completo_n com a matriz de adjacência correspondente.  
	2. Bipartido completo - Nesse caso: Input (n1,n2:inteiro positivo) e salva bipartido_completo_n1n2 com a matriz de adjacência correspondente.  
	3. Estrela - Nesse caso: Input (n:inteiro positivo) e salva estrela_n com a matriz de adjacência correspondente.
	4. Caminho - Nesse caso: Input (n:inteiro positivo) e salva caminho_n com a matriz de adjacência correspondente.  
	5. Ciclo - Nesse caso: Input (n:inteiro positivo, n>=3) e salva ciclo_n com a matriz de adjacência correspondente.  
	6. Roda - Nesse caso: Input (n:inteiro positivo, n>=3) e salva roda_n com a matriz de adjacência correspondente.  
	7. Cubo - Nesse caso: Input (n:inteiro não negativo) e salva cubo_n com a matriz de adjacência correspondente.  
- Le o nome do grafo. 
Carrega o grafo,  
imprime a matriz de adjacências do grafo,    
Responde se o grafo é conexo.
E diz quantas componentes conexas tem o grafo.

Para rodar, basta baixar os 3 arquivos .py no mesmo diretório e chamar o interpretador com main.py como argumento
