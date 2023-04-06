# Flatty

This project describes an optimization method for removing nesting from programs written in EO programming language. The nested structures in the language are composed of objects that form hierarchical structures, which can make it difficult to perform static analysis of such structures. The proposed method reframes expressions in such a way that they no longer contain nested objects, making it easier to perform static analysis. The project provides a formal proof of the correctness of the optimization method. The paper explains the background of EO programming language, $\varphi$-calculus, abstract objects, $\xi$, and $\Delta$, among other related concepts. The project also reviews related work and explains how the proposed optimization method works.

### Run tests

    $  mvn clean install -Pqulice