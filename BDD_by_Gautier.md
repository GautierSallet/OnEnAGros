**Le behavior-driven development (ou BDD)** est une méthode agile qui encourage la collaboration entre les développeurs, les responsables qualités, les intervenants non-techniques et les entreprises participant à un projet de logiciel. Il a été conçu en 2003 par Dan North comme une réponse au Test Driven Development.

Le processus BDD met en avant le langage naturel et les interactions dans le processus de développement logiciel. Les développeurs utilisant le BDD utilisent un langage naturel en combinaison avec le langage du domaine domain driven design pour décrire l'objectif et le bénéfice de leur code. Cela permet aux développeurs de se concentrer sur les raisons pour lesquelles le code doit être créé, plutôt que les détails techniques, et minimise la traduction entre le langage technique dans lequel le code est écrit et le domaine de la langue parlée par les entreprises, les utilisateurs, les intervenants, la gestion de projet…

**Pratiques BDD**
Les pratiques de BDD comprennent :

La participation des parties prenantes dans le processus par le biais de l'extérieur dans le développement de logiciels outside-in software development
L'utilisation d'exemples pour décrire le comportement de la demande, ou d'unités de code
Automatisation de ces exemples pour fournir rapidement des commentaires et des tests de non-régression
Dans le test logiciel, l'utilisation du mot « devrait » contribue à clarifier la responsabilité et permet la remise en cause de la fonctionnalité du logiciel
L'utilisation de «vérifier que» permet de différencier les résultats obtenus dans le champ d'application du code en question en provenance des effets secondaires d'autres éléments du code.
Enfin, l'utilisation de « mocks » en remplacement des modules de code qui n'ont pas encore été écrits

**Vu de l'extérieur**
BDD est motivée par la valeur commerciale, c'est un avantage pour l'entreprise qui revient une fois que l'application est en production. La seule façon dont cet avantage peut être réalisé est par le biais de l'interface utilisateur à la demande, généralement une interface graphique.

De la même manière, chaque morceau de code, à partir de l'interface utilisateur, peut être considéré comme un des intervenants des autres modules de code qu'il utilise. Chaque élément de code prévoit certains aspects de comportement qui, en collaboration avec les autres éléments, prévoit le comportement de l'application. Le premier morceau de code que les développeurs implémentent pour mettre en œuvre BDD est l'interface utilisateur. Les développeurs peuvent alors bénéficier de la rétroaction rapide de savoir si l'interface utilisateur ressemble et se comporte de façon appropriée. Par le biais de code, et en utilisant les principes de bonne conception et de refactoring, les développeurs de découvrir les collaborateurs de l'interface utilisateur, et de chaque unité de code par la suite. Cela les aide à respecter le principe de YAGNI, car chaque morceau de code de production est nécessaire, soit par l'entreprise ou par un autre morceau de code déjà écrit.
