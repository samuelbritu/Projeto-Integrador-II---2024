

# Projeto-Integrador-II---2024


> <img src="ifam-logo.png" alt="Minha Imagem" width="20" > Instituto Federal do Amazonas - *Campus* Eirunepé 


Este projeto está vinculado à disciplina Projeto Integrador II ofertada ao Curso Técnico de Nível Médio em Informática do IFAM - Campus Eirunepé , no ano de 2024.

Ele estará disponível para que os alunos possam acessar os materiais e atividades desenvolvidos ao longo da disciplina.


# Orientações iniciais
## Sobre atividades avaliativas

Em toda e qualquer atividade avaliativa deve-se indicar referências e ferramentas utilizadas. Não precisa ser nas normas da ABNT. Pode-se, por exemplo, adicionar ao README de cada projeto, um tópico indicando as ferramentas utilizadas, INCLUSIVE ferramentas de IA, se for o caso.
## Usando o git e git-hub

1. Realizar cadastro na [Plataforma Git-Hub](https://github.com).

2. Criar pasta do primeiro projeto no PC (pode ser com o nome da disciplina).

3. Criar repositório no GitHub com o mesmo nome da pasta no PC.

4. Realizar os procedimentos trabalhados em aula.



- Artigos iniciais para usar o Gi-Hub :books: :book: 

	:book: [repositório GitTutorial da @github.com/rafaballerini](https://github.com/rafaballerini/GitTutorial)

	:book: [Comece seu percurso](https://docs.github.com/pt/get-started/start-your-journey)
	
	:book: [Olá, Mundo: Siga este exercício Hello World para aprender o fluxo de trabalho da solicitação de pull do GitHub.](https://docs.github.com/pt/get-started/start-your-journey/hello-world)

	:book: [Sintaxe básica de gravação e formatação no GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

- Vídeos :movie_camera: :film_strip: 

	:film_strip: [O que é Git e Git-hub por  @github.com/rafaballerini](https://youtu.be/DqTITcMq68k)

	:film_strip: [Como usar o Git e Git-Hub por  @github.com/rafaballerini](https://www.youtube.com/watch?v=UBAX-13g8OM)
	
	:film_strip: [Entendendo o GIT | (não é um tutorial!) por @Akitando ](https://www.youtube.com/watch?v=6Czd1Yetaac&pp=ygUEZ2l0IA%3D%3D)


## Comandos iniciais no GitBash

`git init` - Adiciona uma pasta .git com arquivos do versionamento

`git clone` - Criar uma copia de um projeto que já existe remotamente

`git add` - Encena uma mudança. É a primeira parte de um processo de dois passos para incluir mudanças realizadas

`git commit` salva as instâncias no histórico do projeto.

`git status` - mostrar estatos das mudanças

`git branch` - mostrar as ramificações existentes

`git merge` - mescla as ramificações 

`git remote` - gerenciar projetos remotos. 

`git push` - empurra mudanças, ou seja, atualizar o repositório remoto com as mudanças locais

`git pull` - Puxa mudanças, ou seja, atualiza o projeto local com as atualizações existentes no repositório remoto. 

## Comandos mínimos no GitBash

### Primeira vez no projeto

`` cd /pasta-do-projeto ``

`` git init ``

`` git add .``

`` git status ``

`` git commit -m "mensagem do commit" ``

`` git brach -M main  ``

Criar um repositório com o mesmo nome da pasta. 

`` git remote add origin https://github.com/reuperfil/seuprojeto.git ``

`` git push -u origin main ``

### Modificações, após o projeto já criado no PC e no GitHub - PUSH 

`` cd /pasta-do-projeto/ ``

`` git add . ``

`` git commit - m "mensagem para identificar commit" ``

`` git status ``

`` git merge ``

`` git push origin main ``

### Atualizar projeto no PC a partir de alterações no repositório remoto - PULL

# Atividades

## Atividade I - Criar Currículo

1. Currículo acadêmico

Criar um currículo acadêmico na [Plataforma Lattes](https://lattes.cnpq.br/)

2. Currículo corporativo online

Criar um perfil no [Linkedin](https://br.linkedin.com/)

3. Criar um repositório no PC e Git-hub sobre o seu currículo.

	3.1 no README.md 
		
	a. Informações do projeto:
			Este projeto faz parte da disciplna tal
			
    b. Informações mínimas sobre currículo (conforme modelo enviado)
		
	 - links do lattes e do linkedin 

	 - Formação acadêmica
		
	 - Formação complementar
		
		- certificados

			> [Veja o aquivo de exemplo ](modelo.md)

	
	3.2 Salvar na mesma pasta todos os documentos acadêmicos, como certificados, entre outros

## Atividade II - Seguir tutorial para aprender fluxo de trabalho

1. Criar repositório Wello Word pelo GitHub

	1.2 Seguir o tutorial [Olá, Mundo](https://docs.github.com/pt/get-started/start-your-journey/hello-world) para criar um projeto como projeto _Olá, Mundo_, como descrito.

## Atividade III - Criar repositório com exemplos de arquivos do Office

2. Criar repositório exemplos de arquivos do Office 

	2.1 Criar uma planilha listando um conjunto de equipamentos do local de seu estágio, ao menos 5 equipamenos;
	
	2.2 Estabelecer uma relação de consumo de usando as seguintes colunas:
	
	 2.2.1 Equipamentos
	
	 2.2.2 Potência (W)
	
	 2.2.3 Comsumo diário (h)
	
	 2.2.4 Comsumo mensal (h)
	
	 2.2.5 Custo do consumo mensal (R$)
	
	 2.2.6 Percentagem do consumo
	
	 2.2.7 LINHA ou CÉLULAS com valores totais.
	
    2.3 Criar gráfico em pizza exibindo porcentagens de uso por equipamento.
	
	2.4 Criar slide de apresentação;
	
	2.5 Criar arquivo de text.
	
	2.6 Todos os arquivos trararão do mesmo tema.


### Resumo da atividade III:

O Repositório deve conter:
		   
1. Planilha;
2. gráfico de pizza (png ou jpeg);
3. slide;
4. docx;
5. README.md
6. Inserir figura no README



```
![Texto Alternativo](URL_da_Imagem)
```

ou 
			   
```			   
<img src="URL_da_Imagem" alt="Texto Alternativo">
```
## Atividade IV : fork e pull request

1. Crie um Fork do repositório;

2. Adicione, abaixo do seu nome, o endereço dos seus três repositórios, conforme solicitações acima.

3. Envie um pull request ao proprietário do projeto (este).


## Projetos dos alunos

### ALINE XAVIER MORAES


[Atividade I](https://github.com/4L1N3X4V13R/ProjetoIntegrador2.git)

### ANA LUIZA CARANHA DA SILVA

[Atividade I](https://github.com/analuuuzz/ProjetoIntegrador2.git)

[Atividade II](https://github.com/analuuuzz/hello-world.git)

### CINDY LAUREN DE SOUZA FEITOZA

[Atividade I]()
[Atividade II](https://github.com/analuuuzz/hello-world.git)
[Atividade III](https://github.com/sondyloren/PIjojovsq.git)

### DANIELE INACIO LOPES

[Atividade I]()
### HERBERT NATAN ALVES DE SOUZA
[Atividade I](https://github.com/herbertnatan/ProjetoIntegrador2.git)

### JOAO ANTONIO FAUSTINO DE BARROS
### JOAO GABRIEL CAVALCANTE LEITAO
[Atividade II](https://github.com/GabrielCavalcante123/hello-world.git)
### JOAO LUCAS CUNHA DA COSTA
### JUNIOR ALMEIDA DAS CHAGAS
### LAISSA ALCANTARA GOMES
### LARIANE PEREIRA DE ARAUJO
### LEOSMARA COLAÇO MINELVINO
### MARIA ITAUANA DE ALMEIDA SARAIVA
### MURILO GABRIEL DA SILVA ARAUJO
### OLIVER BRYAN CAVALCANTE GUILHERME
[AtividadeI](https://github.com/OliverBryanCavalcante/projeto-integrador-2-)

[AtvidadeII](https://github.com/OliverBryanCavalcante/hello-word-)

[AtividadeIII](https://github.com/OliverBryanCavalcante/Exemplos-do-Office)
### PEDRO RENNECK DE SOUZA
### RILARY CAVALCANTE DE SOUZA
### RITA DE CASSIA ALVES GOIANO
### SAMUEL BRITO DE LIMA CARDOSO
[Atvidade I](https://github.com/samuelbritu/Projeto-Integrador-II.git)
[Atividade III](https://github.com/samuelbritu/Atividade-III/tree/main)

[Atividade II](https://github.com/samuelbritu/hello-world.git)
### THALIEL DA SILVA XAVIER
[Atividade I](https://github.com/ThalesDeMileto/Projeto-Integrador-II.git)

[Atividade II](https://github.com/ThalesDeMileto/Wello-Word.git)

[Atividade III](https://github.com/ThalesDeMileto/Projeto_IntegradorII.git)

### WESLEY KAINAN DE SOUZA OLIVEIRA
### YASMIM LUCAS BARBOSA
			   
	
