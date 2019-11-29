Argomenti di teoria applicati in "TestContoBancario":

-Ereditarietà

-Polimorfismo

-This


EREDITARIETA:

Il concetto di ereditarietà serve per unire diverse classi, creando un sistema di "Superclassi" e "Sottoclassi".
La Sottoclasse eredita dalla Superclasse gli attributi e i metodi, permettendo così di poterli utilizzare in entrembe le classi.

Nel progetto in questione la classe ContoEsteso eredita gli attributi nomeConto e bilancio dalla superclasse ContoBancario, permettendo cosi di usare i 2 attributi anche nella sottoclasse.


POLIMORFISMO:

E' il riutilizzo di un dato metodo ereditato da una superclasse cambiando ciò che fa quel metodo, viene contrassegnato con "@Override".

Il polimorfismo serve per riscrivere dei metodi che magari devono svolgere una funzione simile ma algoritmicamente diversa o più specifica.

 In questo progetto è stato ridefinito, nella classe derivata ContoEsteso, il metodo "preleva", già presente nella classe ContoBancario.
 
 
 THIS:
 
La parola chiave "this" nel linguaggio Java serve per specificare l'attributo dell'oggetto corrente nel caso una variabile abbia lo stesso nome dell'attributo che si vuole usare.Si scrive il comando seguito da un punto e dall'attributo che si vuole usare.
