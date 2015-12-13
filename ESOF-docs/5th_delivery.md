Evolução de Software - ESOF 2015/2016
========

# Conteúdos
1. [Introdução](#introdução)
2. [Feature a evoluir](#feature)
3. [Componentes de implementação](#components)
4. [Evolução da feature](#evolution)
5. [Submissão do patch](#submission)
6. [Conclusão](#conclusion)
7. [Bibliografia](#bli)

## *Introdução* <a name="introdução"></a>

* Nesta nova etapa do projecto vamos referir qual a feature a ser implementada, com vista à evolução do projecto,  bem como todos os passos que levaram à sua implementação. Sendo esta uma fase de melhoramento, reparamos que o [Caldroid](https://github.com/roomorama/Caldroid), sendo uma aplicação de calendário apresentava muito poucas funcionalidades para os utilizadores, tornando assim decisão difícil devido as diferentes opções.

## *Feature a evoluir* <a name="feature"></a>

* Depois de uma análise a toda a estrutura da aplicação [Caldroid](https://github.com/roomorama/Caldroid), e também do contacto com os mains contributors do projecto, o grupo chegou à conclusão que a feature implementada deveria ser a criação de eventos num determinado dia por parte do utilizador.

## *Componentes de implementação* <a name="components"></a>

* Para implementação da feature foi necessária a utilização do IDE [Android Studio](http://developer.android.com/sdk/index.html). Esta foi implementada na linguagem de programação *Java* na qual o projecto já se encontrava maioritariamente desenvolvido.

## *Evolução da feature* <a name="evolution"></a>

**Componentes alteradas para implementação da feature**

* *As principais alterações que foram realizadas para a implementação da feature foram efectuadas nos seguintes ficheiros:*

* [CaldroidSampleActivity.java](https://github.com/carvalhofilipe1995/Caldroid/blob/578cd3044d237adde18af625ee583599084c98b3/caldroidSampleActivity/src/main/java/com/caldroidsample/CaldroidSampleActivity.java)

<img src="https://raw.githubusercontent.com/carvalhofilipe1995/Caldroid/master/ESOF-docs/resources/CaldroidSampleActivity.jpg">

A funçao **onSelectDate()** apenas mostrava no ecrã a informaçao do dia em que o utilizador clicou. Como essa função não tinha grande utilidade, decidimos que ao clicar num dia, devia ser possível ao utilizador adicionar tarefas ao dia selecionado e guardá-las. Para isso utilizamos o **textView** para mostrar o dia selecionado e criamos o editText para que o utilizador pudesse introduzir as suas tarefas. Para além disso tivemos de adicionar um handler ao teclado que aparece no ecrã quando o utilizador clica no campo de introdução de texto, para que fosse possivel guardar as tarefas introduzidas num hashmap para posteriormente guardá-lo num ficheiro.





* [activity_main.xml](https://github.com/carvalhofilipe1995/Caldroid/blob/578cd3044d237adde18af625ee583599084c98b3/caldroidSampleActivity/src/main/res/layout/activity_main.xml)

<img src="https://github.com/carvalhofilipe1995/Caldroid/blob/master/ESOF-docs/resources/activity_main.jpg">

Foi adicionado o campo de texto.




**Alterações provocadas ao nível do utilizador**

  * Adicionar evento

<img src="https://github.com/carvalhofilipe1995/Caldroid/blob/master/ESOF-docs/resources/add_event.jpg">

  * Eventos diários

<img src="https://github.com/carvalhofilipe1995/Caldroid/blob/master/ESOF-docs/resources/event_added.jpg">

## *Submissão do patch* <a name="submission"></a>

* A submissão do patch não foi efectuada porque apesar de termos obtido sucesso na criação do evento, o grupo não conseguiu fazer o "save" desse mesmo evento. Ou seja, quando a aplicação é encerrada o evento não é guardado.
O insucesso deveu-se a factores de tempo e de conhecimentos técnicos de Android.

## *Conclusão* <a name="conclusion"></a>

* Depois de concluída esta fase de análise do projecto [Caldroid](https://github.com/roomorama/Caldroid), o grupo chegou à conclusão que existem alguns aspectos que devem ser melhorados, tais como:

  1. Melhorar o método de interação do software com o utilizador;
  2. Melhorar o controlo dos "pull-requests" efectuando testes de eficiência/qualidade.

* Em suma, achamos que se estes pontos fossem abordados no desenvolvimento do projecto iriam ser notadas evoluções em termos de qualidade e eficiência de software.

## *Bibliografia*  <a name="bli"></a>

  * **[Software Evolution](https://moodle.up.pt/pluginfile.php/80714/mod_resource/content/1/software_evolution.pdf)**
  * **[Caldroid](https://github.com/roomorama/Caldroid)**
