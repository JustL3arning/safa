- ### Índice:

- <a name="01-Sobre-o-ambiente-shell"></a>
 [01 - Sobre o ambiente shell](#01-Sobre-o-ambiente-shell)
  
-

- ## Introdução

- Este documento, apresentará na ordem correta, o que/como eu estudei e quais foram algumas das minhas fontes de pesquisas na minha preparação para a certificação [Linux Professional Institute Nível 1](https://www.lpi.org/pt-br/our-certifications/lpic-1-overview/), realizada em sua versão 5.0

	-
	  > O guia foi desenvolvido juntamente com o meu irmão, a medida em que nós progredíamos nos assuntos. Caso você queira conferir o mesmo guia, porém com a visão dele sobre essa introdução do aprendizado, é possível encontra-lo em [GitHub do Pedrinho](www.github.com)  
  
- ##### Antes de começarmos com o conteúdo, veremos algumas informações sobre minha situação pré início da preparação: ( Caso queira ir direto ao ponto, pule para 00 - Ordem + principais fontes dos estudos. )
  query-table:: true

	- Meu nível de experiência ao iniciar os estudos para a prova, era o de um usuário básico de Windows — *com algumas familiaridades a mais, pelo fato de sempre ter usado computadores* —

	- Resolvia problemas simples de configurações através de pesquisas na internet, instalava e configurava programas, conseguia otimizar de uma maneira básica o sistema, tinha um conhecimento básico sobre peças, funcionamento de um computador, e na maior parte do tempo na frente das telas, jogava alguns jogos.

-
---

- ### Timestamp

- 18th Jul 2024 Dei início aos estudos do GNU/Linux em conjunto com meu irmão, que já tinha um conhecimento prévio sobre algumas partes do conteúdo da prova e de computação no geral, porém decidiu reiniciar seus estudos e começar do zero comigo, afim de me auxiliar e também solidificar o que já havia aprendido, se sentindo mais seguro com a realização do exame.
  Tivemos um hiato ocasionado por motivos pessoais, que durou 1 mês e uma semana, então, começando os estudos em 18th Jul 2024, realizando a última parte do exame no dia 18th Feb 2025 e desconsiderando nossa pausa, levamos 5 meses e 3 semanas para passar nas duas partes da prova.  
  
	-
 > [!IMPORTANT]
> É posssível passar na prova em um tempo menor, porém, decidimos nos aprofundarmos nos conteúdos para aproveitar a motivação de obter a certificação. Nosso objetivo era realmente aprender o máximo sobre cada conteúdo estudado, mesmo que no exame fosse cobrado de forma mais superficial. Caso você tenha tempo, minha recomendação é de que faça o mesmo, aproveite o foco nos tópicos para estudar de forma mais detalhada cada assunto, além de te deixar mais seguro para a realização do exame, te proporcionará um ótimo ganho a longo prazo.  
  
-
---

- ### 00 - Ordem + principais fontes dos estudos.

	- Ao longo do guia poderão ser incluídos alguns links específicos de conteúdos usados para aprender determinado assunto, mas de maneira geral, os principais locais e que recomendo o uso para realizar seus próprios estudos são:

		- `$ man` - O jeito mais básico de obter informações sobre algo no Linux. Sempre que disponível, leia o manual e posteriormente faça buscas mais detalhadas.

		- [LPI Learning](https://learning.lpi.org/pt/learning-materials/101-500/) - O site disponibilizado pela própria empresa que aplica o exame. Nele você obtém pequenas aulas sobre cada tópico, e ao final de cada um são passadas algumas lições sobre o conteúdo apresentado.

		- [GNU Manuals](https://www.gnu.org/manual/manual.html) - Aqui você irá encontrar exemplos e explicações consideravelmente mais detalhadas do que encontraria utilizando o *man*

		- Canais do Youtube - Os principais canais com conteúdo em português sobre todo o universo do GNU/Linux, que eu posso recomendar com tranquilidade: o do [Paulo Kretcheu](https://www.youtube.com/@kretcheu2001) e o [debxp](https://www.youtube.com/@debxp/videos) do Blau Araujo.

-

- ### [01 - Sobre o ambiente shell](#01-Sobre-o-ambiente-shell)  

	- Quando pensamos em "aprender Linux", o que na verdade estamos buscando, é um entendimento sobre como o *Kernel* (Linux) funciona, e suas interações com o resto dos componentes de um computador. Mas onde entra a ação do usuário nisso tudo?

- **Shell: a interface em linha de comando entre o usuário e o Kernel do Sistema operacional.**

	- O shell é um programa utilizado através de um terminal, que nos permite interagir e controlar o sistema operacional de uma maneira mais simples, através de comandos.

	- Também podemos juntar vários desses comandos ,  e assim obtemos um **script shell**

-

-

-
