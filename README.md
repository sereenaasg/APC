# Pràctica 1. Regressions

La base de dades que es treballa en aquest informe esta proporcionada per Paulo Cortez, de University of Minho, GuimarÃ£es dins de UCL Machine Learning Repository. 

Les dades fan referència al rendiment dels estudiants de dues escoles: Gabriel Pereira i Mousinho da Silveira. Més concretament tracta sobre les notes finals de matemàtiques dels tres períodes que comprenen un curs en l’educació secundària a Portugal on G1 i G2 són les notes referents a cadascun dels períodes i G3 és la nota final.

Cada mostra fa referència a un alumne d’alguna d’aquestes escoles on tenim diferents atributs amb informació sobre: on viuen, quina edat tenen, dades relacionades amb el seu cercle familiar, la seva situació socioeconòmica i també sobre els seus resultats acadèmics. 

Les estadístiques coloquen a Portugal a la cua d’Europa quan parlem de tasa de fracàs estudiantil, en concret, en referència a les assignatures de Matemàtiques i Llengua Portuguesa. 

La motivació, per tant, d’aquest estudi es intentar saber quins atributs són més rellevants a l’hora de predir la nota final d’un curs, per tal de poder centrar en aquests més atenció i recursos, i així millorar la qualitat de l’educació. Per tant, l’experiment vol respondre, bàsicament preguntes com: ¿Quins factors ajuden a predir el rendiment escolar? ¿Quins atributs no afecten en aquest? ¿És possible predir el rendiment dels estudiants?. 

A la base de dades que se’ns proporciona hi ha tres atributs que poden ser objecte d’estudi i per als quals volem fer la predicció: G1, G2, G3 explicats prèviament. Considerem que l’atribut objectiu ha de ser G3, la nota final del curs. 

De la mateixa forma, hem decidit utilitzar G1 i G2 com a dos característiques més de la base de dades, ja que creiem que aquests dos atributs poden ser determinants per predir la nota de G3. Sobre aquesta hipòtesi, farem les primeres proves de predicció de G3.
