# Quantum mechanics for many-particle systems: a computational perspective

This course gives an introduction to the quantum mechanics of
many-body systems and the methods relevant for many-body
problems in such diverse areas as atomic, molecular, solid-state and
nuclear physics, chemistry and materials science. A theoretical
understanding of the behavior of quantum-mechanical many-body systems, that is, systems containing many interacting particles - is a
considerable challenge in that, normally, no exact solution can be found.
Instead, reliable methods are needed for approximate but accurate
simulations of such systems.

The aim of this course is to present some of the most widely used
many-body methods, starting with the underlying formalism of second
quantization. The topics
covered include second quantization with creation and annivilation operators, Wick's theorem, Feynman diagram rules, microscopic mean-field theories
(Hartree-Fock and Kohn-Sham theories), many-body perturbation theory,
large-scale diagonalization methods, coupled cluster theory,
algorithms from quantum computing, and
Green's function approaches. Both fermionic and bosonic systems are
discussed, depending on the interests of the participants.
Selected physical systems from various fields such as quantum
chemistry, solid-state physics and nuclear physics are studied,
depending on the background and interests of the participants.


## Instructor information
* _Name_: Morten Hjorth-Jensen
* _Email_: morten.hjorth-jensen@fys.uio.no
* _Phone_: +47-48257387
* _Office_: Department of Physics, University of Oslo, Eastern wing, room FØ470 

## Practicalities

1. Four lectures per week, Fall semester, 10 ECTS. Thursday 1015am-12pm and Friday 1015-12pm. The lectures will be recorded and linked to this site;
2. Two hours of exercise sessions for work on projects and exercises, Friday 1215pm-2pm;
3. Two projects which are graded and count 30% each of the final grade and a final oral exam that counts 40% of the final grade;
4. Weekly assignments which are not graded;
5. The course is offered as a so-called _cloned_ course,  FYS4480 at the Master of Science level and FYS9480 as a PhD course;
6. Weekly email with summary of activities will be mailed to all participants;

## Textbooks

_Recommended textbooks_:
There are many good textbooks on many-body physics. In addition to to ourn own collection of lecture notes, we will use material from the following  texts
- Dickhoff and Van Neck at https://www.worldscientific.com/worldscibooks/10.1142/5804#t=aboutBook
- Negele and Orland at https://www.taylorfrancis.com/books/mono/10.1201/9780429497926/quantum-many-particle-systems-john-negele-henri-orland
- Szabo and Ostlund at for example https://www.amazon.com/Modern-Quantum-Chemistry-Introduction-Electronic/dp/0486691861?asin=0486691861&revisionId=&format=4&depth=1
- Shavitt and Bartlett at https://www.cambridge.org/core/books/manybody-methods-in-chemistry-and-physics/D12027E4DAF75CE8214671D842C6B80C

## Topics (not all will be discussed)

- Intro chapter with basic definitions and simple examples and mathematics of many-body functions
     - Definitions of SDs etc, permutation operators,linear algebra reminder including reminder about determinants,
       vector and mtx algebra, tensor products, representations, unitary transformations, link to quantities like
     - one-body and two-body densities, rms radii etc. Discuss ansatze for wave functions and more.
     - Ansaztes for wave functions
- 2nd quantization for bosons and fermions and more
     - Commutation rules and definition of creation and annihilation operators
     - Proof of wick's theorem
     - Discuss Wick's generalized theorem
     - particle-hole picture
     - interaction, Schroedinger and Heisenberg pictures, pros and cons
     - time dependent wick's theorem
     - Gell-Man and Low's theorem
     - Adiabatic switching
     - Derivation of expressions for different parts of Hamiltonians, 1b, 2b, 3b etc
     - Wigner-Jordan transformation and 2nd quantization
     - Baker-Campbell-Hausdorf (BCH)
     - Suzuki-Trotter as an approximation to BCH
- FCI, diagrams and particle-hole representations
     - Basics of FCI
     - Rewriting in terms of a particle-hole picture
     - Slater determinants and similarity transformations and algorithms for solving eigenvalue problems
     - Eigenvector continuation
     - Introduce a diagrammatic representation
- Mean-field theories
     - Hartree-Fock in coordinate space and 2nd quantization
     - Thouless theorem
     - Slater dets in HF theory
     - Density functional theory
     - The electron gas as example
     - FCI and HF, diagrammatic representations and critical discussions
- Many-body perturbation theory
     - Time dependent and time-independent representations
     - Brillouin-Wigner and Rayleigh-Schrødinger pert theory
     - Diagrammatic representation
     - Linked-diagram theorem based on time-dependent theory
- Coupled cluster theories, standard and unitary
     - Derivation of equations for singles and doubles, reminder on unitary transformations
     - Unitary coupled cluster theory
- Green's function theory and parquet theory
- SRG and IMSRG
- Monte Carlo methods
     - Taught in FYS4411
- Quantum computing
     - VQE and unitary CC
- Time-dependent many-body theory
- Applications to different systems like the electron gass, Lipkin model, Pairing model, infinite nuclear matter, and more




## Teaching schedule with links to material

###  Week 34, August 19-23

- Topics to be covered
  - Thursday: Introduction to many-body physics, notations and definitions
    - Video of lecture at https://youtu.be/
  - Friday: Discussion of notations and important properties in many-body physics
    - Video of lecture at https://youtu.be/
- Lecture Material at https://manybodyphysics.github.io/FYS4480/doc/pub/secondquant/html/secondquant-bs.html

###  Week 35, August 26-30

- Topics to be covered
  - Thursday: Fermion state functions and computation of expectation values in first quantization
    - Video of lecture at https://www.youtube.com/watch?v=zG1fy6Wecxo
  - Friday: Introduction of second quantization
    - Video of lecture at https://youtu.be/
- Lecture Material at https://manybodyphysics.github.io/FYS4480/doc/pub/secondquant/html/secondquant-bs.html
- First exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek35.pdf

### Week 36, September 2-6

- Topics to be covered
  - Thursday: Second quantization, operators in second quantization and diagrammatic representation
  - Video of lecture https://youtu.be/
  - Whiteboard	notes https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/HandwrittenNotes/2024/LectureSeptember7.pdf
  - Friday: Second quantization and Wick's theorem
  - Video of lecture at https://youtu.be/
- Lecture Material: These slides, handwritten notes and	Szabo and Ostlund sections 2.3 and 2.4. Sections 3.1-3.3 of Shavitt and Bartlett covers most of the material discussed this week.
- Second exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek36.pdf



### Week 37, September 9-13 

- Topics to be covered
  - Thursday: Wick's theorem
  - Video of lectue at https://youtu.be/
  - Friday: Wrappping up Wick's theorem, Wick's generalized theorem and diagrammatic representation, Particle-hole formalism and definition of new reference state, normalordering of operators
  - Video of lecture at https://youtu.be/S8CFkbbVqVc
- Lecture Material: Slides, handwritten notes and chapter 3 of Shavitt and Bartlett covers most of the material discussed this week.
- Third exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek37.pdf

### Week 38, September 16-20

- Topics to be covered
  - Thursday: Discussion of particle-hole formalism with examples
  - Video of lecture at https://youtu.be/
  - Friday: Particle-hole formalism and definition of new reference state, normalordering of operators
  - Video of lecture at https://youtu.be/
- Lecture Material: These slides, handwritten notes and chapter 3 and 4 of Shavitt and Bartlett covers most of the material discussed this week.
- Fourth exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek38.pdf

###  Week 39, September 23-27
- Topics to be covered
  - Thursday:
    - Repetition  of particle-hole formalism
    - Diagrammatic representation
    - Introduction of full configuration interaction theory
    - Video of lecture at https://youtu.be/
  - Friday: 
    - Full configuration interaction (FCI) theory
    - Lipkin model as an example of applications of FCI theory
    - Video of lecture at https://youtu.be/
- Fifth exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek39.pdf

### Week 40, September 30-October 4
- Topics to be covered
  - Thursday:
    - Repetition  of Full Configuration Interaction theory
    - Start Hartree-Fock theory
    - Video of lecture  at https://youtu.be/
  - Friday: 
    - Hartree-Fock theory and stability of equations
    - Video of lecture at https://youtu.be
- Lecture Material: These slides, handwritten notes and Szabo and Ostlund, sections 3.1-3.4
- Sixth exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek40.pdf

### Week 41, October 7-11, 2024
- Topics to be covered
  - Thursday:
    - Koopman's theorem and repetition  of derivation of Hartree-Fock theory
    - Stability of Hartree-Fock theory and Thouless theorem
    - Video of  lecture at https://youtu.be/
  - Friday:
   - Stability of Hartree-Fock theory and Thouless theorem, continues
   - Video of lecture at https://youtu.be
   - Work on first midterm
- Lecture Material: These slides, handwritten notes and Szabo and Ostlund, chapter 3. See also Shavitt and Bartlett, chapters 3 and 4
 First midterm set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/FirstMidterm2024.pdf

### Week 42, October 14-18, 2024
- Topics to be covered
  - Thursday:
    - The homogeneous electron gas in three dimensions
    - Video of lecture at https://youtu.be/
  o Friday:
    * Work on first midterm
- Lecture Material: These slides and handwritten notes
- First midterm set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/FirstMidterm2024.pdf



###  Week 43, October 21-25, 2024
- Topics to be covered
  - Thursday:
    - Linking Hartree-Fock theory with density functional theory
    - Video of lecture  at https://https://youtu.be/
  - Friday:
    - Electron gas in three dimensions and links with density functional theory
    - Video of lecture at https://youtu.be/
- Lecture Material: These slides, handwritten notes and Shavitt and Bartlett chapter 4 and sections 5.1-5.3
- Seventh exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek43.pdf



###  Week 44, October 28-November 1, 2024
- Topics to be covered
  - Thursday:
    - Time-independent perturbation theory and diagrammatic representation
    - Examples of contributions to perturbation theory
    - Video of lecture at https://youtu.be/
- Friday: 
    - Many-body perturbation theory, basic equations
    - Video of lecture https://youtu.be/
- Lecture Material: Slides, handwritten notes and Shavitt and Bartlett chapter 4-6
- Eight exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek44.pdf

###  Week 45, November 4-8, 2024
- Topics to be covered
  - Thursday:
    - Adiabatic hypothesis and linked diagram theorem
    - Examples of diagrams and discussion of Pauli violating diagrams
  - Friday:
    - Solution of exercises from week 44 and 45
- Lecture Material: Slides at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/src/week45/LatexSlides/slidesweek45.pdf, handwritten notes and Shavitt and Bartlett chapters 4-6
- Ninth exercise set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/ExercisesWeek45.pdf

###  Week 46, November 11-15, 2024
- Topics to be covered
  - Thursday:
    - Diagram rules (whiteboard notes)
    - Examples of diagrams and discussion of Pauli violating diagrams (Whiteboard notes)
    - Video of lecture at https://youtu.be/
  - Friday:
    - Time-dependent perturbation theory, definitions of Schroedinger, Heisenberg and interaction picture, see slides at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/src/week45/LatexSlides/pictures.pdf
    - Video of lecture at https://youtu.be
- Lecture Material: Slides at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/pub/week46/pdf/slidesweek46.pdf, handwritten notes a\
nd Shavitt and Bartlett chapter 4-6
- Work on second midterm set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/SecondMidterm2024.pdf

###  Week 47, November 18-22, 2024

- Topics to be covered
  - Thursday:
    - Time-dependence, Adiabatic hypothesis and linked diagrams
    - Green's functions, basic equations
    - Video of lecture at https://youtu.be/
  - Friday:
    - Green's functions, basic equations
    - Video of lecture at https://youtu.be/
- Lecture Material: Slides for week 47 at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/pub/week47/pdf/slidesweek47.pdf and handwritten notes.
- Work on second midterm set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/SecondMidterm2024.pdf

###  Week 48, November 25-29, 2024
- Topics to be covered
  - Thursday:s
    - Discussion of second midterm
  - Friday:
    - Dyson's equation and perturbative expansions
    - Summary of course and discussion of final oral exam
    - Video of lecture at https://youtu.be/
- Lecture Material: Slides for week 48 at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/pub/week48/pdf/slidesweek48.pdf
- Work on second midterm set at https://github.com/ManyBodyPhysics/FYS4480/blob/master/doc/Exercises/2024/SecondMidterm2024.pdf


###  Week 50, December 16, 2024
- Final oral exam, schedule via	studentweb


