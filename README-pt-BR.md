# Top-down learning path: Machine Learning for Software Engineers
Inspired by [Google Interview University](https://github.com/jwasham/google-interview-university).

_Se você gostou deste projeto, por favor me dê uma estrela_ &#9733; _e ajude a divulgar o material._ ;)

<a href="https://twitter.com/intent/tweet?text=Plano%20de%20estudos%20para%20Engenheiros%20de%20Machine%20Learning%20https://github.com/ZuzooVn/machine-learning-for-software-engineers%20por%20@zuzoovn" target="_blank">
Compartilhe no Twitter</a>

## O que é?

Este é meu plano de estudo para ir de desenvolvedor mobile (autodidata, sem diploma) para Engenheiro de Machine Learning.
Meu principal objetivo era encontrar uma abordagem para estudar Machine Learning, que é principalmente hands-on (aprender fazendo) e abstrair a maioria da matemática para o iniciante. Esta abordagem não é convencional porque ela é uma abordagem top-down e resultados-primeiro projetada para engenheiros de software.

Por favor, sinta-se livre para fazer qualquer contribuição que você achar que pode o tornar melhor.

---

## Tabela de conteúdo

- [O que é?](#o-que-é)
- [Por que usar?](#por-que-usar)
- [Como usar](#como-usar)
- [Siga-me](#siga-me)
- [Não sinta que não é inteligente o bastante](#não-sinta-que-não-é-inteligente-o-bastante)
- [Sobre Video Resources](#sobre-video-resources)
- [Conhecimento prévio](#conhecimento-prévio)
- [O Plano diário](#o-plano-diário)
- [Motivação](#motivação)
- [Visão geral do Machine Learning](#visão-geral-do-machine-learning)
- [Maestria do Machine Learning](#maestria-do-machine-learning)
- [Machine Learning é divertido](#machine-learning-é-divertido)
- [Machine learning: um guia profundo, não técnico](#machine-learning-um-guia-profundo-não-técnico)
- [Relatos e experiências](#relatos-e-experiências)
- [Livros para iniciantes](#livros-para-iniciantes)
- [Livros para prática](#livros-para-prática)
- [Competições de conhecimento Kaggle](#competições-de-conhecimento-kaggle)
- [Video Series](#video-series)
- [MOOC](#mooc)
- [Pesquisas](pesquisas)
- [Torna-se um contribuidor Open Source](#torne-se-um-contribuidor-open-sourse)
- [Communidades](#comunidades)
- [My admired companies](#my-admired-companies)

---

## Por que usar?

Eu estou seguindo este plano para me preparar para meu próximo futuro emprego: Engenheiro de Machine Learning. Venho construindo aplicativos nativos móveis (iOS/Android/Blackberry) desde 2011. Eu tenho um diploma de engenharia de Software, não um diploma de Ciência da Computação. Tenho um pouco de conhecimentos básicos sobre: cálculo, Álgebra Linear, matemática discreta, probabilidade e estatística na Universidade.

Pense sobre meu interesse em Machine Learning:

- [Posso aprender e arrumar um emprego em Machine Learning sem estudar mestrado e Phd em Ciência da Computação?](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD)
    - *"Você pode, mas isto é muito mais difícil do que quando eu entrei no campo."* [Drac Smith](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD/answer/Drac-Smith?srid=oT0p)

- [Como eu consigo um emprego em Machine Learning como um programador de software que auto-estudou  Machine Learning, mas nunca teve a chance de usar isso no trabalho?](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work)
    - *"Estou contratando especialistas de Machine Learning para minha equipe e seu MOOC não vai conseguir para você o trabalho (há melhores notícias abaixo). Na verdade, muitas pessoas com um mestrado em Machine Learning não terão o emprego porque eles (e a maioria que tomaram MOOC) não têm uma compreensão profunda que vai me ajudar a resolver os meus problemas."* [Ross C. Taylor](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work/answer/Ross-C-Taylor?srid=oT0p)

- [Que habilidades são necessárias para trabalhos de Machine Learning?](http://programmers.stackexchange.com/questions/79476/what-skills-are-needed-for-machine-learning-jobs)
    - *"Primeiramente, você precisa ter um decente background de Ciência da Computação/Matemática. ML é um tópico avançado, então a maioria dos livros didáticos assumem que você tem esse background. Por segundo, Machine Learning é um tema muito geral com várias sub especialidades que exigem habilidades únicas. Você pode querer procurar o currículo de um programa de MS em Machine Learning para ver o curso, o currículo e livro didático."* [Uri](http://softwareengineering.stackexchange.com/a/79717)
    - *"Estatística, propabilidade, computação distribuída e estatística."* [Hydrangea](http://softwareengineering.stackexchange.com/a/79575)

Eu me encontro em tempos difíceis.

AFAIK, [Há dois lados para Machine Learning](http://machinelearningmastery.com/programmers-can-get-into-machine-learning/):
- Prática de Machine Learning: Isto é sobre bancos de dados de consultas, limpeza de dados, escrevendo scripts para transformar dados e colagem de algoritmo e bibliotecas juntos e escrever código personalizado para espremer respostas confiáveis de dados para satisfazer as perguntas difíceis e mal definidas. É a porcaria da realidade.
- Teoria de Machine Learning: Isto é sobre matemática e abstração e cenários idealizados e limites e beleza e informando o que é possível. É muito mais puro e mais limpo e removido da confusão da realidade.

Eu acho que a melhor maneira para metodologia centrada na prática é algo como ['prática - aprendizagem - prática'](http://machinelearningmastery.com/machine-learning-for-programmers/#comment-358985), que significa onde estudantes primeiro vêm com alguns projetos existentes com problemas e soluções (prática) para se familiarizar com os métodos tradicionais na área e talvez também com sua metodologia.Depois de praticar com algumas experiências elementares, podem ir para os livros e estudar a teoria subjacente, que serve para guiar a sua futura prática avançada e reforçará a sua caixa de ferramentas de solução de problemas práticos. Estudar a teoria também melhora ainda mais sua compreensão sobre as experiências elementares e irá ajudá-los a adquirir experiências avançadas mais rapidamente.

É um plano longo. Isso vai demorar anos para mim. Se você já está familiarizado com bastante disso já, você levará muito menos tempo.

## Como usar
Tudo abaixo é uma estrutura de tópicos, e você deve enfrentar os itens em ordem de cima para baixo.

Eu estou usando o especial Markdown do Github, incluindo a lista de tarefas para verificar o progresso.

- [x] Crie um novo branch, então você poderá verificar itens como esse, apenas coloque um x entre os colchetes.

[More about Github-flavored markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

## Siga-me
Eu sou um engenheiro de Software vietnamita que é realmente apaixonado e quer trabalhar nos EUA.

Quanto eu trabalhei durante este plano? Aproximadamente 4 horas/noite após um dia longo no trabalho.

Eu estou na jornada.

| ![Nam Vu - Top-down learning path: machine learning for software engineers](http://sv1.upsieutoc.com/2016/10/08/331f241c8da44d0c43e9324d55440db6.md.jpg)|
|:---:|
| USA as heck |

## Não sinta que não é inteligente o bastante
Fico desencorajado por livros e cursos que me dizem que o quanto antes eu puder, cálculo multivariável, inferencial e álgebra linear são pré-requisitos. Ainda não sei como começar...

- [What if I'm Not Good at Mathematics](http://machinelearningmastery.com/what-if-im-not-good-at-mathematics/)
- [5 Techniques To Understand Machine Learning Algorithms Without the Background in Mathematics](http://machinelearningmastery.com/techniques-to-understand-machine-learning-algorithms-without-the-background-in-mathematics/)
- [How do I learn machine learning?](https://www.quora.com/Machine-Learning/How-do-I-learn-machine-learning-1)

## Sobre Video Resources

Alguns vídeos estão disponíveis apenas registrando-se em uma classe Coursera ou EdX. É de graça, mas às vezes as classes já não estão em sessão, então você tem que esperar uns meses, se não, não terá acesso.
Eu vou estar adicionando mais vídeos de fontes públicas e substituindo os vídeos do curso on-line ao longo do tempo. Eu gosto de usar palestras de universidade.

## Conhecimento prévio

Esta seção curta foram pré-requisitos/informações interessantes que eu queria aprender antes de começar o plano diário.

- [ ] [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](https://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)
- [ ] [Learning How to Learn](https://www.coursera.org/learn/learning-how-to-learn)
- [ ] [Don't Break The Chain](http://lifehacker.com/281626/jerry-seinfelds-productivity-secret)
- [ ] [How to learn on your own](https://metacademy.org/roadmaps/rgrosse/learn_on_your_own)

## O Plano Diário

Cada assunto não requer um dia inteiro para ser capaz de compreendê-lo totalmente, e você pode fazer vários desses em um dia.

Cada dia eu pego um assunto da lista abaixo, leia de capa a capa, tome nota, faça os exercícios e escreva uma implementação em Python ou R.

# Motivação
- [ ] [Dream](https://www.youtube.com/watch?v=g-jwWYX7Jlo)

## Visão geral do Machine learning
- [ ] [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [ ] [A Gentle Guide to Machine Learning](https://blog.monkeylearn.com/a-gentle-guide-to-machine-learning/)
- [ ] [Machine Learning basics for a newbie](https://www.analyticsvidhya.com/blog/2015/06/machine-learning-basics/)

## Maestria do Machine learning
- [ ] [The Machine Learning Mastery Method](http://machinelearningmastery.com/machine-learning-mastery-method/)
- [ ] [Machine Learning for Programmers](http://machinelearningmastery.com/machine-learning-for-programmers/)
- [ ] [Applied Machine Learning with Machine Learning Mastery](http://machinelearningmastery.com/start-here/)
- [ ] [Python Machine Learning Mini-Course](http://machinelearningmastery.com/python-machine-learning-mini-course/)
- [ ] [Machine Learning Algorithms Mini-Course](http://machinelearningmastery.com/machine-learning-algorithms-mini-course/)

## Machine learning é divertido
- [ ] [Machine Learning is Fun!](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.37ue6caww)
- [ ] [Part 2: Using Machine Learning to generate Super Mario Maker levels](https://medium.com/@ageitgey/machine-learning-is-fun-part-2-a26a10b68df3#.kh7qgvp1b)
- [ ] [Part 3: Deep Learning and Convolutional Neural Networks](https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721#.44rhxy637)
- [ ] [Part 4: Modern Face Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78#.3rwmq0ddc)
- [ ] [Part 5: Language Translation with Deep Learning and the Magic of Sequences](https://medium.com/@ageitgey/machine-learning-is-fun-part-5-language-translation-with-deep-learning-and-the-magic-of-sequences-2ace0acca0aa#.wyfthap4c)

## Machine learning: um guia profundo, não técnico
- [ ] [Overview, goals, learning types, and algorithms](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide/)
- [ ] [Data selection, preparation, and modeling](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-2/)
- [ ] [Model evaluation, validation, complexity, and improvement](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-3/)
- [ ] [Model performance and error analysis](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-4/)
- [ ] [Unsupervised learning, related fields, and machine learning in practice](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-5/)

## Relatos e experiências
- [ ] [Machine Learning in a Week](https://medium.com/learning-new-stuff/machine-learning-in-a-week-a0da25d59850#.tk6ft2kcg)
- [ ] [Machine Learning in a Year](https://medium.com/learning-new-stuff/machine-learning-in-a-year-cdb0b0ebd29c#.hhcb9fxk1)
- [ ] [Learning Path : Your mentor to become a machine learning expert](https://www.analyticsvidhya.com/learning-path-learn-machine-learning/)
- [ ] [You Too Can Become a Machine Learning Rock Star! No PhD](https://backchannel.com/you-too-can-become-a-machine-learning-rock-star-no-phd-necessary-107a1624d96b#.g9p16ldp7)
- [ ] How to become a Data Scientist in 6 months: A hackerâ€™s approach to career planning
	- [Video](https://www.youtube.com/watch?v=rIofV14c0tc)
	- [Slide](http://www.slideshare.net/TetianaIvanova2/how-to-become-a-data-scientist-in-6-months)
- [ ] [5 Skills You Need to Become a Machine Learning Engineer](http://blog.udacity.com/2016/04/5-skills-you-need-to-become-a-machine-learning-engineer.html)
- [ ] [Are you a self-taught machine learning engineer? If yes, how did you do it & how long did it take you?](https://www.quora.com/Are-you-a-self-taught-machine-learning-engineer-If-yes-how-did-you-do-it-how-long-did-it-take-you)
- [ ] [How can one become a good machine learning engineer?](https://www.quora.com/How-can-one-become-a-good-machine-learning-engineer)

## Livros para iniciantes
- [ ] [Data Smart: Using Data Science to Transform Information into Insight 1st Edition](https://www.amazon.com/Data-Smart-Science-Transform-Information/dp/111866146X)
- [ ] [Data Science for Business: What you need to know about data mining and dataÂ­ analytic-thinking](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323/)
- [ ] [Predictive Analytics: The Power to Predict Who Will Click, Buy, Lie, or Die](https://www.amazon.com/Predictive-Analytics-Power-Predict-Click/dp/1118356853)

## Livros para prática
- [ ] [Machine Learning for Hackers](https://www.amazon.com/Machine-Learning-Hackers-Drew-Conway/dp/1449303714)
	- [GitHub repository](https://github.com/johnmyleswhite/ML_for_Hackers)
- [ ] [Python Machine Learning](https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka-ebook/dp/B00YSILNL0)
	- [GitHub repository](https://github.com/rasbt/python-machine-learning-book)
- [ ] [Programming Collective Intelligence: Building Smart Web 2.0 Applications](https://www.amazon.com/Programming-Collective-Intelligence-Building-Applications-ebook/dp/B00F8QDZWG)
- [ ] [Machine Learning: An Algorithmic Perspective, Second Edition](https://www.amazon.com/Machine-Learning-Algorithmic-Perspective-Recognition/dp/1466583282)
	- [GitHub repository](https://github.com/alexsosn/MarslandMLAlgo)
	- [Resource repository](http://seat.massey.ac.nz/personal/s.r.marsland/MLbook.html)
- [ ] [Introduction to Machine Learning with Python: A Guide for Data Scientists](http://shop.oreilly.com/product/0636920030515.do)
	- [GitHub repository](https://github.com/amueller/introduction_to_ml_with_python)
- [ ] [Data Mining: Practical Machine Learning Tools and Techniques, Third Edition](https://www.amazon.com/Data-Mining-Practical-Techniques-Management/dp/0123748569)
	- Teaching material
		- [Slides for Chapters 1-5 (zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch1-5.zip)
		- [Slides for Chapters 6-8 (zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch6-8.zip)
- [ ] [Machine Learning in Action](https://www.amazon.com/Machine-Learning-Action-Peter-Harrington/dp/1617290181/)
	- [GitHub repository](https://github.com/pbharrin/machinelearninginaction)
- [ ] [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)

## Competições de conhecimento Kaggle
- [ ] [Kaggle Competitions: How and where to begin?](https://www.analyticsvidhya.com/blog/2015/06/start-journey-kaggle/)
- [ ] [How a Beginner Used Small Projects To Get Started in Machine Learning and Compete on Kaggle](http://machinelearningmastery.com/how-a-beginner-used-small-projects-to-get-started-in-machine-learning-and-compete-on-kaggle)
- [ ] [Master Kaggle By Competing Consistently](http://machinelearningmastery.com/master-kaggle-by-competing-consistently/)


## Video Series
- [ ] [Machine Learning for Hackers](https://www.youtube.com/playlist?list=PL2-dafEMk2A4ut2pyv0fSIXqOzXtBGkLj)
- [ ] [Fresh Machine Learning](https://www.youtube.com/playlist?list=PL2-dafEMk2A6Kc7pV6gHH-apBFxwFjKeY)
- [ ] [Machine Learning Recipes with Josh Gordon](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
- [ ] [Everything You Need to know about Machine Learning in 30 Minutes or Less](https://vimeo.com/43547079)

## MOOC
- [ ] [Udacity's Intro to Machine Learning](https://www.udacity.com/course/intro-to-machine-learning--ud120)
	- [Udacity Intro to Machine Learning Review](http://hamelg.blogspot.com/2014/12/udacity-intro-to-machine-learning-review.html)
- [ ] [Udacity's Supervised, Unsupervised & Reinforcement](https://www.udacity.com/course/machine-learning--ud262)
- [ ] [Machine Learning Foundations: A Case Study Approach](https://www.coursera.org/learn/ml-foundations)
- [ ] [Coursera's Machine Learning](https://www.coursera.org/learn/machine-learning)
	- [Video only](https://www.youtube.com/playlist?list=PLZ9qNFMHZ-A4rycgrgOYma6zxF4BZGGPW)
	- [Coursera Machine Learning review](https://rayli.net/blog/data/coursera-machine-learning-review/)
	- [Coursera: Machine Learning Roadmap](https://metacademy.org/roadmaps/cjrd/coursera_ml_supplement)

## Pesquisas
- [ ] [Machine Learning for Developers](https://xyclade.github.io/MachineLearning/)
- [ ] [Machine Learning Advice for Developers](https://dev.to/thealexlavin/machine-learning-advice-for-developers)
- [ ] [Machine Learning For Complete Beginners](http://pythonforengineers.com/machine-learning-for-complete-beginners/)
- [ ] [Machine Learning Self-study Resources](https://ragle.sanukcode.net/articles/machine-learning-self-study-resources/)
- [ ] [Level-Up Your Machine Learning](https://metacademy.org/roadmaps/cjrd/level-up-your-ml)
- [ ] [Enough Machine Learning to Make Hacker News Readable Again](https://speakerdeck.com/pycon2014/enough-machine-learning-to-make-hacker-news-readable-again-by-ned-jackson-lovely)

## Torne-se um contribuidor Open Sourse
- [ ] [tensorflow/magenta: Magenta: Music and Art Generation with Machine Intelligence](https://github.com/tensorflow/magenta)
- [ ] [tensorflow/tensorflow: Computation using data flow graphs for scalable machine learning](https://github.com/tensorflow/tensorflow)
- [ ] [cmusatyalab/openface: Face recognition with deep neural networks.](https://github.com/cmusatyalab/openface)
- [ ] [tensorflow/models/syntaxnet: Neural Models of Syntax.](https://github.com/tensorflow/models/tree/master/syntaxnet)

## Comunidades
- ### Quora
	- [Machine Learning](https://www.quora.com/topic/Machine-Learning)
	- [Statistics](https://www.quora.com/topic/Statistics-academic-discipline)
	- [Data Mining](https://www.quora.com/topic/Data-Mining)

- ### Reddit
	- [Machine Learning](https://www.reddit.com/r/machinelearning)

- ### [Data Tau](http://www.datatau.com/)

## My admired companies
- [ ] [ELSA - Your virtual pronunciation coach](https://www.elsanow.io/home)
