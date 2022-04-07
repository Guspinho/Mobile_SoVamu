# Mobile_SoVamu

Desafio 1:


Pergunta A)	
Com suas palavras defina o que é um sistema de controle de versões (VCS)? (máx 10 linhas)

R: É um sistema que gerencia as versões de um determinado programa, mantendo um log das versões e o que foi alterado.

Pergunta B)
Cite 5 vantagens em utilizar um VCS:

R: 
- LOG de atividades;
- Controle de mudanças;
- Documentação;
- Fácil Manutenção;
- Recuperação de dados (rollback);

Pergunta C) 
Cite 3 exemplos de VCS:

R:
- Visual Studio
- RTC
- GIT 

----------------------------------------------------------------------------------------

Desafio 2.

Sobre Layout

P: Cite as principais view de Layout para a criação de telas e para que servem respectivamente. Dê exemplos de situações reais de onde são usadas;

R: 

TextView - Utilizamos essa view quando precisamos inserir algum texto dentro do layout da aplicação.
ImageView - View para adicionar uma imagem dentro do layout.
Button - Estranhamente chamamos de button a view para adicionar um botão dentro da aplicação. 


P: Como criamos a estrutura das views dentro no layout;

R: Precisamos primeiro referênciar o pai dentro da view.d
Após criar a tag do <LinearLayout>, adicionar o tipo de view que querendo (TextView, ImageView, Button, etc).
Cada view precisa ter a propriedade 'android:'+ id, um layout_width, layout_height e um texto.

<LinearLayout android:layout_width=""
              android:layout_height="">
			  
	<TextView 
	android:id=""
	android:layout_width=""
	android:layout_height=""
	android:text="" 
	/>

</LinearLayout>


P: Qual a diferença entre “math_parent” e “wrap_content”
R: wrap_content controla o ajuste da exibição de um conteudo dentro de uma tela.  
   math_parent = faz com que o tamanho do conteudo selecionado tenha o tamanho do pai.
   
   
P) Quais são as boas práticas devemos adotar ao construir projeto android?

R: adicionar os id, mexer no split, pois na visão de design pode dar diferença entre dispositivos, referenciar o pai dentro da view.
