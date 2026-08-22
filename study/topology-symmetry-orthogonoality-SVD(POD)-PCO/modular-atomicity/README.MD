"Modular atomicity" - Software Engineering paradigms are there to learn from, and build uppon. 
To achieve concurrency control in programming languages and knowledge management in cognitive systems, we may refer toModular Atomicity.
Simple put, by encapsulating indivisible operations into isolated, reusable blocks, systems gain reliability and composability.

It is critical to manage how multiple threads access objects safely.
While individual concurrent objects guarantee that single method calls are atomic (linearizability), combining multiple method calls into a larger atomic block is notoriously difficult, and often breaks the atomicity chain, because the execution of multiple calls on a single reference implies lack of vertical composition.

Some techniques such as Condensability and fworks like Composable Modular Atomicity ( Mohsen Lesani ) mathematically verify that grouped method calls execute atomically without introducing deadlocks or data races.

https://lnkd.in/dxUtenP6

While In productivity and cognitive science, modular atomicity is known as the Principle of Atomicity.
I.E Each discrete note or module of information should contain exactly one single, fundamental concept. 
Instead of saving complex conglomerates of concepts, breaking data into atomic, small, connected notes makes it easy to generalize, decontextualize, and recombine them to fit new needs.

When programming intersects with philosophy - The Principle of Atomicity – On the Difference Between a Principle and Its Implementation

https://lnkd.in/d_Rzea5D

Atomicity as Principle vs Atomicity Implementations

"If you’re a programmer, separation of concerns should ring a familiar bell. I deal with notes in a fashion similar to complex code. Instead of writing classes, I create new note files. Accordingly, patterns emerge: there are argumentative notes; there are notes with term definitions; there are sparks and ideas. Each Zettel pattern fulfills a different purpose."

https://lnkd.in/d_Rzea5D

"The Principle of Atomicity – On the Difference Between a Principle and Its Implementation"
https://lnkd.in/d_Rzea5D


Frashokereti: Non-aborting Optimistically Replicated Objects
"Optimistic replication of objects avoids coordination and brings higher responsiveness and availability. However, when clients issue concurrent operations, conflicts naturally arise which can lead the replicated states to diverge or lose integrity." 
https://lnkd.in/djVH2mKG

Hamava: Fault-tolerant Reconfigurable Geo-Replication on Heterogeneous Clusters

https://lnkd.in/d7nyN6QF
C4: Verified Transactional Objects


What are primord entities or processes ?
O que vem primeiro, entidades ou processos? O tempo vem do espaço ou o espaço do tempo?


 In a network of interrelated abstract concepts, it’s often possible to create many possible “spanning subtrees” of the network (to use some terminology from graph theory), thus tracing many alternative pathways from “foundational” to “derived” concepts.




Memoizacao e MEMO models - fazer live sobre no futuro, ensinando conceitos de memoizacao em inferencia ( deflushing com Regressive Learning e Emergence of Abilities ).

Prende-se o valor em um tempo espaco que "obrigatoriamente" iremos passar sobre, ja que, a pureza nos movimentos respeita estruturas convexas ( i.e. repeticoes, em esferas : o seu todo, seu corpo e elementos - LLMS - semi-esferas e afins ressemblam mecanismos de atencao. em arrays : a sequencia de elementos, Cujos, matematicamente impossiveis de iterar sobre, sem )
Tecnico : 

deflush = FlushBack nativo das redes neurais, aplicados a uma abstracao contextual, gerando memoizacao. Inspirado pelas tecnicas de colecao de lixo e aceleradores de turbina dos interpretadores de JS.
React (e javascript em geral) aplicam Memoizacoes, atraves de conceitos de limpeza de memoria. A base do javascript em termos de memoria, ressembla um DAG, um grafo direto aciclico. Todas instrucoes posteriores, referem-se a um ponto no tempo-estado passado. 

let a
const b = () => { a = 1 }.
const c = () => { a = 2 }.

b() ( a se torna 1, porem o tempo-espaco permanece o mesmo, apenas a chave vetora q altera, durante o turbofan ou akins, pela colecao de memoria )
c() ( a se torna 2, porem ... mesmo anterior ).

Por isso, pra mim, javascript eh a melhor linguagem para iteracao em arvores de dados, linguagens como python tendem a reassignar a variavel, ou gerar um novo ponto de memoria, baguncando uma travessia temporal. 
Memo, de Memoizacao, que na computacao eh a ideia de que, se um valor em um tempo espaco foi assignado, ao iterar sobre certo tempo espaco, caso ele nao tenha sido mudado, podemos recorrer a ele sem problemas, reaproveitar tempos de ponto-espaco, e com isso, tambem, AFERIMOS propriedade e seguranca.
I.E mesmo que queiramos, nao podemos altera-los de fora, eles sao apenas alteraveis por eles mesmos, ja que sao apenas "resultados" de computacao passada. 

Nas LLMS, especificamente em quadrantes de atencao, os mecanismos tendem a gerar novas combinacoes apos a primeira assignacao principal ( cara resposta do modelo eh "Memoizada" , cache e afins q vimos por ai ).

Isso eh o conceito de "deflushing", nativo de mecanismos de atencao, e extensiveis, por meta prompting.
O downside de usar deflushing em tempo de inferencia, eh que as interseccoes do mecanismo sao criadas em memoria ( Placa de video ), e nao necessariamente pre criadas. ( I.E Memoizacao X Travessia ).

