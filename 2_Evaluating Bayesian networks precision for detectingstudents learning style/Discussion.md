# Evaluating Bayesian networks’ precision for detecting students’ learning styles 

## Keywords : 
Bayesian networks, Felder & Silverman, quantitative & qualitative information, inductive or deductive organization of information,
conditional probability tables  

## Discussion :  

#### Intro 
Learning might be improved when learning and teaching styles match *1*. And all lecturer’s have their own style and it’s the case the student has to adapt to them.  
How it is one of the most desired characteristics of web-based systems to be adaptive and personalised *2*  
States that web based questionnaires can become boring and you wont get true data.  
The used a BN, each node represents different student behaviour. The information gathered is from the student log files.  

#### Related work
Problems with student modelling *3*  
  
Learning models :   
ARTHUR which considers three learning styles (visual-interactive, reading-listener, textual) *4*   
CS388 *5*  
INSPIRE system *6*  
Honey & Mumford *7*  
  
Various techniques to achieve student modelling :  
Rule based *8*  
Fuzzy logic *9*  
Bayesian networks and case-based reasoning *10*  
BN to assess students' state of knowledge and learning preferences, in an intelligent tutoring system. *11*  

#### Learning styles
They've used Felder & Silverman, and discuss the 32 learning styles contained within the model.
They summarise the different type of learners and how they react to and process information in different styles.

#### Bayesian Networks
A BN is a compact, expressive representation of uncertain relationships among parameters in a domain. A BN is a directed acyclic graph where nodes represent random variables and arcs represent probabilistic correlation between variables *12*
They created a simple BN to model the relationships between the participation of a student in chats and forums and the processing style of this student.
They then discuss all of the other factors they record and analyse to determine the student's learning style, like how many examples the student reads, and number of exercises a student does on a topic. 

#### Evaluation of results
They gave a questionnaire to the students to see if the data obtained via the application correlated to the data from the questionnaire.
They only gathered information on 3 aspects of the model as they deemed the rest not applicable to a web application, or redundant because of previous research. 
The precision rates of the 3 varied from 58 - 78%.  
They deemed the reflective learning style popular because the student's did not use the chat or forums and therefore the BN was biased.

## Takeaway notes
Very thorough paper with loads of relevant information and interesting topics for further reading. Their use of the bByesian network seemed easy to implement in some aspect of the learning theory model. The precision of the Bayesion netwrok was overall quite accurate. I liked the way they assessed the factor with the lowest precision and realised the a lot of the student's just were not aware of the chat / forum feature.

## References to look up 
1 
Allinson, C., & Hayes, J. (1996). The cognitive style index: A measure of intuition analysis for organizational research. Journal of Management Studies, 33(1), 119–135; 

Felder, R., & Brent, R. (2005). Understanding student differences. Journal of Engineering Education, 94(1), 57–72.  

2 
Brusilovsky, P., & Peylo, C. (2003). Adaptive and intelligent web-based educational systems. International Journal of Artificial Intelligence in Education, 13(2–4, Special Issue on Adaptive and Intelligent Web-based Educational Systems), 159–172.  
 
Weber, G., Kuhl, H., & Weibelzahl, S. (2001). Developing adaptive internet based courses with the authoring system NetCoach. Lecture Notes in Computer Science, 2266, 226–238; 

Weber, G., & Specht, M. (1997). User modeling and adaptive navigation support in WWW-based tutoring systems. In User modeling: Proceedings of the sixth international conference (UM97) (pp. 289–300).  

3 
Brusilovsky, P., & Peylo, C. (2003). Adaptive and intelligent web-based educational systems. International Journal of Artificial Intelligence in Education, 13(2–4, Special Issue on Adaptive and Intelligent Web-based Educational Systems), 159–172.  

4 
Gilbert, J., & Ham, C. (1999). Adapting instruction in search of a significant difference. Journal of Network and Computer applications, 22.  

5 
Carver, C., Howard, R., & Lavelle, E. (1996). Enhancing student learning by incorporating learning styles into adaptive hypermedia. In ED-MEDIAÕ96 World conference on educational multimedia hypermedia (pp. 118–123).  
 
6 
Papanikolaou, K., Grigoriadou, M., Knornilakis, H., & Magoulas, G. (2003). Personalizing the interaction in a web-
based educational hypermedia system: The case of INSPIRE. User Modeling and User-Adapted Interaction, 13,
213–267.  

Papanikolaou, K., Grigoriadou, M., Magoulas, G., & Kornilakis, H. (2002). Towards new forms of knowledge
communication: The adaptive dimension of a web-based learning environment. Computers and Education, 39,
333–360.  

7 
Honey, P., & Mumford, A. (1992). The manual of learning styles.  

8
Jeremic, Z., & Devedzic, V. (2004). Design patters ITS: Student model implementation. In IEEE International
conference on advanced learning technologies.  

9 
Xu, D., Wang, H., & Su., K. (2002). Intelligent student profiling with fuzzy models. In HICSSÕ02, 35th Annual Hawaii
international conference on system sciences.  

10 
Pen ̃a, C., Marzo, J., de la Rosa, J., & Fabregat, R. (2002). Un sistema de tutor ́ıa inteligente adaptativo considerando
estilos de aprendizaje. In IE 2002.  

11 
Gamboa, H., & Fred, A. (2001). Designing intelligent tutoring systems: A Bayesian approach. In ICEIS 01, 3rd International conference on enterprise information systems.  

12 
Jensen, F. (1996). An Introduction to Bayesian Networks. Springer.  
