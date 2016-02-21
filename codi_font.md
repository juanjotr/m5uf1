___1.2. Codi font, codi objecte i codi excutable: m�quines virtuals___

Un cop s�ha acabat d�escriure el programa, el conjunt de fitxers de text
resultants, on es troben les instruccions, es diu que contenen el **codi font**.
Aquest codi font pot ser des d�un nivell molt alt, molt a prop del llenguatge
hum�, fins a un de nivell m�s baix, m�s proper al codi de les m�quines, com
ara el codi assemblador

El **codi objecte** �s el codi font tradu�t (pel compilador) a codi m�quina, per�
aquest codi encara no pot ser executat per l�ordinador
 
El **codi executable** �s la traducci� completa a codi m�quina, duta a terme per
l�enlla�ador (en angl�s, linker). El codi executable �s interpretat directament
per l�ordinador

L� **enlla�ador** �s l�encarregat d�inserir al codi objecte les funcions de les llibreries
que s�n necess�ries per al programa i de dur a terme el proc�s de muntatge
generant un arxiu executable

Una **llibreria** �s un col�lecci� de codi predefinit que facilita la tasca del programador
a l�hora de codificar un programa.

La **compilaci�** consta de dues fases:

� La primera parteix del codi font a un llenguatge intermedi obtenint un
programa equivalent amb un menor nivell d�abstracci� que l�original i que
no pot ser directament executat.

� La segona fase tradueix el llenguatge intermedi a un llenguatge comprensible
per la m�quina.
