## Course: Multiobjective Optimization

General materials for the Multiobjective Optimization Course of [Prof. Igor Machado Coelho](https://igormcoelho.github.io), so as its respective applications in recent courses.

![last-commit](https://img.shields.io/github/last-commit/igormcoelho/course-multiobjective-optimization)

Complete list of modules in repository:

- Still updating...

Materials in PDF-HTML:

1. [Fundamentals](slides/1-fundamentals/1-fundamentals.md): [PDF](slides/1-fundamentals/1-fundamentals.pdf) [Online](https://igormcoelho.github.io/curso-seguranca-informacao/slides/1-fundamentals/index.html)


## Content (in Portuguese)

Introdução e motivação à Otimização com Inteligência Computacional. Problemas de otimização.
Problemas de otimização combinatória. Problema do caixeiro viajante. Problema da mochila. Problemas
de otimização em grafos. Busca inteligente e heurísticas. Heurísticas construtivas. Heurísticas de
refinamento e de busca local. Metaheurísticas. Simulated Annealing. Algoritmos Genéticos. Busca Tabu.
Busca em Vizinhança Variável. Frameworks para o desenvolvimento de algoritmos de otimização.
Introdução a Programação genética e hiper-heurísticas. Frentes e Conjuntos de Pareto. 
Estrutura de Meta-heurísticas multiobjetivas: Fitness Assignment e Diversity Management.
Meta-heurísticas multiobjetivas NSGA-II, SPEA, IBEA. Indicadores de cobertura e hipervolume.

## Bibliography

- Marcone Jamilson Freitas Souza. Notas de Aula "Inteligência Computacional para Otimização", http://www.decom.ufop.br/prof/marcone/Disciplinas/InteligenciaComputacional/InteligenciaComputacional.pdf, 2024.
- El-Ghazali Talbi. Metaheuristics from Design to Implementation, Wiley, 2009.
- Marcos Arenales et al, Pesquisa operacional: para cursos de engenharia, Editora Campus, 2007
- Michel Gendreau, Jean-Yves Potvin, Handbook of Metaheuristics, Springer, 2010
- Ricardo Linden, Algoritmos Genéticos, Editora Brasport Livros e Mutimídia Ltda, 2006.



***Observação:*** **alguns módulos só são oferecidos para cursos específicos.*

-------

## Cursos recentes

- Otimização Multiobjetiva - TCC00XXX - A1
   * [Pós-Graduação 2024.2](./slides/0-intro-curso-uff-2024-2/0-intro-curso.pdf) (ago./2024-dez./2024)
   * Instituto de Computação (IC) - Universidade Federal Fluminense (UFF)

-------

## Sobre gravações

Gravações disponibilizadas no YouTube e Classroom foram feitas com OBS (obrigado pelas dicas Mateus Nazário). Algumas dicas:

- https://medium.com/@igormcoelho/dicas-para-obs-no-linux-para-google-meet-8ac102972183

Utilizei o Okular para marcação do PDF (obrigado Matheus Nohra Haddad pelas dicas).

## Como esses slides foram feitos?

Estes slides foram feitos em `markdown` e `pandoc` (super fácil!) de acordo com o tutorial [ilectures-pandoc](https://github.com/igormcoelho/ilectures-pandoc).

Basicamente, é necessário instalar o pandoc e, opcionalmente, copiar alguns filtros úteis do tutorial (dois arquivos python). Então, é possível gerar, a partir do `markdown`, uma versão PDF LaTeX+Beamer, e outra web utilizando RevealJS. O tutorial explica tudo em detalhes.

O mais legal é que a edição do slide tem uma visualização em tempo real, com plugins disponíveis para editores populares como Atom e VSCode.
Uma demonstração foi colocada no site do ilectures: [https://github.com/igormcoelho/ilectures-pandoc#demonstrations](https://github.com/igormcoelho/ilectures-pandoc#demonstrations).


### Deps

Pandoc + LaTeX

`python3 -m pip install pandoc-source-exec`
`python3 -m pip install pandoc-latex-color`

[pandoc 2.10.1](https://github.com/jgm/pandoc/releases/tag/2.10.1)



### Licença CC-BY 4.0

Você pode: (Share) copiar e redistribuir esse material em qualquer formato; (Adapt) adaptar esse material, mesmo que para uso comercial.

Você deve: (Attribution) dar crédito apropriado, bem como um link para o original e a indicação das mudanças que você fez.

Veja licença original [CreativeCommons CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

```
curso-programacao-orientada-objetos (c) by Igor M. Coelho

curso-programacao-orientada-objetos is licensed under a
Creative Commons Attribution 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by/4.0/>.
```

Copyleft 2024
