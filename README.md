# Talks in Geometric Representation Theory Learning Seminar 2023
I participated in the learning seminar on quantum groups and R-matrices organized by Prof. Travis Schedler. The seminar covers various topics, from Yang-Baxter equations, Hopf algebras to classical r-matrices.

In chronological order, my talks are:
* Hopf algebras: I introduced the basic objects and quantization of universal enveloping algebras.
* Faddeev-Reshetikhin-Takhtajan construction: I introduced the method given by FRT of constructing an h-formal group from a given solution to the quantum Yang-Baxter equation (an R-matrix).
* h-deformation: in the previous talks, the term deformation was never formally defined. In this talk, I formally defined the h-adic topology on C[[h]], topologically free C[[h]] modules, topological tensor products, and h-deformation. I talked about the h-formal groups, being the deformation of formal groups. I also established the correspondence of h-formal groups and h-deformations and stated a version of FRT on R-matrices satisfying the Hecke relation. This version of the theorem is widely used to construct deformations of Kac-Moody algebras. Finally, the talk ends by describing the Lie bialgebra structure induced by deformation and showing the relation between quantum and classical r-matrices.
* Belavin-Drinfeld classification: following the paper *Triangle Equations and Simple Lie Algebras*, I presented the classification of solutions to the classical Yang-Baxter equation with a spectral parameter (elliptic, rational, and trigonometric). I also sketched the proof of classifications of constant r-matrices via a discrete datum (a Belavin-Drinfeld triple) and a continuous datum (a chosen tensor).

## Errata and Comments
Immediately after each talk, I sent a list of errata and comments to the learning group to correct the mistakes I made during the talk. I thereby copy-paste the lists here for reference.

### Talk 1: Hopf algebras
Hi, here are the slides for today's first talk. I also want to list the errata and comments in the talk.	
* On slide 29, I wrote something like "nice Hopf algebras decompose into a twisted tensor product of U(g) and C[G]". This is actually the Cartier–Gabriel theorem which says all cocommutative Hopf algebras decompose into this sort of thing. Also please note that my annotation there was wrong: the group algebra C[G] is obviously NOT commutative. Moreover, if the Hopf algebra is finite-dimensional we are back to Exercise 4 on slide 17.
* On slide 33, I indicated that the algebra of observables consists of operators on the state space. This is false. Observables are associated with the self-adjoint operators on the state space regarded as a Hilbert space. According to Wikipedia, there are observables that are not given by operators and physically meaningless operators. I can't give further explanations because I don't really understand their physical nature. Please refer to other resources if you are interested.
* On slides 36 and 37, the first fact is questionable. What is true is that there exists a pairing on C^infty(G) and U(g). Furthermore, this pairing gives us an isomorphism between (1) compactly supported distributions on G that are supported by the identity and (2) the universal enveloping algebra. Another result from Cartier–Gabriel is that the restricted dual of C^infty(G), the algebra of distributions with finite supports, is isomorphic to the twisted tensor product of C[G] and U(g).
* A note on the questionable fact: I got that result from a comment in https://math.stackexchange.com/questions/2208800/duality-between-universal-enveloping-algebra-and-algebras-of-functions, but I've never seen this statement elsewhere.
[For the last comment: a precise and correct statement was given in my third talk.]

### Talk 2: FRT constructions
Hello. Here are the (revised) slides for my talk on FRT construction. Please note the following corrections/comments:
* The r form should be defined as r(T_i^m \otimes T_j^n)=c_{ji}^{mn}, so we must switch some rows of c to get the matrix of r. This explains why I did not compute the right thing during the talk.
* The properties of r (for instance the computation of r(x\otimes yz) or r(1\otimes x)) should be considered as a part of the construction of r that makes it into a universal r-form. But the idea is obvious if you recall the axioms of universal r-forms. 
* The FRT construction allows us to construct a quasitriangular bialgebra. The quasitriangular structure is independent of any Hopf structure. Note that by the Tannaka duality, quasitriangular bialgebras correspond to braided monoidal categories; quasitriangular Hopf algebras correspond to rigid braided monoidal categories.

### Talk 3: h-deformations
Hi, I am posting my slides for the talk two weeks ago. I have corrected all the problems in the slides. Completing the proofs where I listed several steps might be very helpful. You could use the axioms about R-matrix in the last talk, or work with specific examples we've covered. One thing to be noticed is that the Hecke relation says things about the eigenvalues of the flip of the R matrix, so in the formula the "q, p" are elements in C[[h]]. They are not matrices.

### Talk 4: Belavin-Drinfeld classifications
[No comments on this talk]
