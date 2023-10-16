# Memory Model Reading Group
Public Reading group timetable for Memory Model/Compiler Verification Reading Group I run at Arm.

A place to collect all papers related to Memory Models, Compiler Verification, and anything with Cats!

## Current Timetable for Reading

Upcoming reading goes here, initial notes and errata will appear in each `paper`'s directory (`papers/01`, `02` etc...) as they are read.

- George Necula. _Translation Validation for an Optimizing Compiler_. [link](http://people.cse.iitd.ernet.in/~sbansal/csl862-soft/readings/translation_validation.pdf)

## Questions to Evaluate a Paper By

When reading, we aim try and answer the following (or question why they cannot be answered), Thank Nathan Chong for this template:
 - What’s the big picture? What is the project trying to accomplish?
 - How big is the project: people and KLOC? How much effort has it taken?
 - What are the important components and how do they fit together?
 - What exactly is being verified? Is it a neat statement, or is it a connection of properties… and, if so, what do they add up to?
 - What are the key ideas? Underlying techniques? How applicable are they outside of C compilers?
 - What assumptions are being made? Are they implicit or explicit? Are they reasonable?
 - What is the trusted computing base needed to believe the result(s)?
 - [optional] How are the projects related? Similar? Different? (this makes more sense if we cover a family of related papers)
 - [optional] What key feature related to the writing of the paper stands out to you? is it the style of writing or the structure of the argument? etc...

 No doubt on second reads, and in context, these questions may get different answers but this is a good first approximation.

## Papers in the Pipeline

Papers we should read after the above.

- Jaroslav Sevcik. _Safe Optimisations for Shared-Memory Concurrent Programs_. [link](https://www.cl.cam.ac.uk/~pes20/weakmemory/transsafety.pdf).
- Jaroslav Sevcik et. al. _CompCertTSO: A Verified Compiler for Relaxed-Memory Concurrency_. [link](https://people.mpi-sws.org/~viktor/papers/jacm-compcerttso.pdf)
- Viktor Vafeiadis and Francesco Zappa Nardelli. _Verifying Fence Elimination Optimisations_. [link](https://www.cl.cam.ac.uk/~pes20/CompCertTSO/doc/fenceelim.pdf)
- Mark Batty et. al, _Clarifying and Compiling C/C++ Concurrency: from C++11 to POWER_. [link](https://www.cl.cam.ac.uk/~pes20/cppppc/popl079-batty.pdf)
- Mark Batty et. al. _Mathematizing C++ Concurrency_. [link](https://www.cl.cam.ac.uk/~pes20/cpp/popl085ap-sewell.pdf)
- Dennis Shasha and Marc Snir. _Efficient and correct execution of parallel programs that share memory_. [link](https://dl.acm.org/doi/10.1145/42190.42277)
- Sarita Adve and Kourosh Gharcaloo. _Shared Memory Consistency Models: A Tutorial_. [link](https://www.hpl.hp.com/techreports/Compaq-DEC/WRL-95-7.pdf)
- Thomas Sewell, Magnus Myreen, and Gerwin Klein. _Translation Validation for a Verified OS Kernel_, [link](https://ts.data61.csiro.au/publications/nicta_full_text/6449.pdf)
- Xavier Leroy and Sandrine Blazy. _Formal verification of a C-like memory model and its uses for verifying program transformations_. [link](https://xavierleroy.org/publi/memory-model-journal.pdf)
- Zachary Tatlock and Sorin Lerner. _Bringing Extensibility to Verified Compilers_. [link](https://cseweb.ucsd.edu/~lerner/papers/pldi10-xcert.html)
- Jean-Baptiste Tristan and Xavier Leroy. _Formal verification of translation validators: A case study on instruction scheduling optimizations_. [link](https://hal.inria.fr/inria-00289540/document)
- Lennart Beringer et. al. _Verified Compilation for Shared-memory C_: [link](https://www.cs.princeton.edu/~appel/papers/shmemc.pdf)
- Venkatesh Srinivasan and Thomas Reps. _Partial Evaluation of Machine Code_: [link](https://dl.acm.org/doi/pdf/10.1145/2858965.2814321)
- Tachio Terauchi and Alex Aiken. _Secure Information Flow As a Safety Problem_ [link](https://theory.stanford.edu/~aiken/publications/papers/sas05b.pdf)
- Luke Nelson, et.al _Hyperkernel: Push-Button Verification of an OS Kernel_. [link](https://unsat.cs.washington.edu/papers/nelson-hyperkernel.pdf).
- Martin Abadi et. al _Control-Flow integrity_, [link](http://www.cs.columbia.edu/~suman/secure_sw_devel/p340-abadi.pdf)
- Sergey Bratus et.al _From Buffer Overflows to “Weird Machines” and Theory of Computation_, [link](https://www.cs.dartmouth.edu/~sergey/langsec/papers/Bratus.pdf)
- Martin Abadi. _Protection in Programming-Language Translations_, [link](https://www.hpl.hp.com/techreports/Compaq-DEC/SRC-RR-154.pdf)
- Marco Patrignani et. al. _Formal Approaches to Secure Compilation_, [link](https://theory.stanford.edu/~mp/mp/Publications_files/main-full.pdf)
- Carmine Abate et. al. _Journey Beyond Full Abstraction: Exploring Robust Property Preservation for Secure Compilation_, [link](https://arxiv.org/abs/1807.04603)
- Marco Patrignani and Deepak Garg. _Secure compilation and hyperproperty preservation_, [link](https://people.mpi-sws.org/~dg/papers/csf17-hyperproperties.pdf)
- Carmine Abate. et. al. _Trace-Relating Compiler Correctness and Secure Compilation_, [link](https://arxiv.org/abs/1907.05320)
- Rebecca Shapiro et. al. _“Weird Machines” in ELF: A Spotlight on the Underappreciated Metadata_. [link](https://www.usenix.org/conference/woot13/workshop-program/presentation/shapiro)
- Sebastian Poeplau and Aurélien Francillon. _Symbolic execution with SYMCC: Don’t interpret, compile!_, [link](http://www.s3.eurecom.fr/docs/usenixsec20_symcc.pdf)
- Steven Schäfer,  Sigurd Schneider, and Gert Smolka. _Axiomatic Semantics for Compiler Verification_. [link](https://dl.acm.org/doi/abs/10.1145/2854065.2854083)
- Leslie Lamport. _win and sin: predicate transformers for concurrency_. [link](https://dl.acm.org/doi/10.1145/78969.78970)
- Susan Owicki and David Gries. _Verifying properties of parallel programs: an axiomatic approach_. [link](https://dl.acm.org/doi/10.1145/360051.360224)
- Rahul Sharma et. al. _Data-Driven Equivalence Checking_. [link](https://cs.stanford.edu/people/eschkufz/docs/oopsla_13.pdf).
- Benjamin Goldberg et. al. _Into the loops: Practical issues in translation validation for optimizing compilers_. [link](http://theory.stanford.edu/~barrett/pubs/GZB05.pdf).
- Sudipta Kundu et. al. _Automated refinement checking of concurrent systems_. [link](https://cseweb.ucsd.edu/~lerner/papers/arccos.pdf).
- Sorin Lerner. et. al. _Automatically Proving the Correctness of Compiler Optimizations_. [link](http://web.cs.ucla.edu/~todd/research/pldi03.pdf).
- Jean-Baptiste Tristan and Xavier Leroy. _Verified Validation of lazy code motion_. [link](https://hal.inria.fr/inria-00415865/file/validation-LCM.pdf).
- Lenore Zuck et. al. _Translation and run-time validation of loop transformations_. [link](http://theory.stanford.edu/~barrett/pubs/ZPG+05.pdf).
- Xavier Rival. _Symbolic transfer function-based approaches to certified compilation_. [link](https://www.di.ens.fr/~rival/papers/popl04.pdf).
- Ross Tate et. al. _Equality saturation: A new approach to optimization_. [link](http://www.cs.cornell.edu/~ross/publications/eqsat/eqsat_tate_popl09.pdf)

## Past Papers

- Xavier Leroy, _Formal verification of a realistic compiler_, [link](https://xavierleroy.org/publi/compcert-CACM.pdf)
- Zhao et. al. _Formalizing the LLVM Intermediate Representation for Verified Program Transformations (Vellvm)_, [link](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1597&context=cis_papers)
- Jean-Baptiste Tristan and Xavier Leroy. _A simple, verified validator for software pipe-lining_, [link](https://xavierleroy.org/bibrefs/Tristan-Leroy-softpipe.html)
- Luke Nelson et. al, _Scaling symbolic evaluation for automated verification of systems code with Serval_, [link](https://unsat.cs.washington.edu/papers/nelson-serval.pdf)
- Thomas Dullian, _Weird machines, exploitability, and provable unexploitability_, [link](http://www.dullien.net/thomas/weird-machines-exploitability.pdf)
- Jennifer Paykin et. al, _Weird Machines as Insecure Compilation_, [link](https://arxiv.org/abs/1911.00157#:~:text=Weird%20machines%20are%20the%20sets,are%20witnesses%20to%20insecure%20compilation.)
- Soham Chakraborty and Viktor Vafeiadis. _Validating Optimizations of Concurrent C/C++ Programs (this is also translation validation)_, [link](http://plv.mpi-sws.org/validc/paper.pdf)
- Jean-Baptiste, Paul Govereau, and Greg Morisset. _Evaluating Value-graph translation validation for LLVM_, [link](https://dash.harvard.edu/bitstream/handle/1/4762396/pldi84-tristan.pdf)
- Sudipta Kundu, Zachary Tatlock, Sorin Lerner. _Proving optimizations correct using parameterized program equivalence_, [link](https://cseweb.ucsd.edu/~lerner/papers/pldi09-pec.pdf)
- Viktor Vafeiadis et. al. _Common Compiler Optimisations are Invalid in the C11 Memory Model and what we can do about it_. [link](https://fzn.fr/readings/c11comp.pdf).
- Jade Alglave et. al. _Don’t Sit on the Fence: A Static Analysis Approach to Automatic Fence Insertion_. [link](https://dl.acm.org/doi/10.1145/2994593).
- Jade Alglave et. al. _Software Verification for Weak Memory via Program Transformation_. [link](https://arxiv.org/abs/1207.7264).
- Jade Alglave et. al. _Fences in Weak Memory Models_. [link](https://dl.acm.org/doi/10.1007/978-3-642-14295-6_25)
- Jade Alglave et. al. _Herding Cats - Modelling, simulation, testing, and data-mining for weak memory_. [link](https://arxiv.org/abs/1308.6810).
- Robin Morisset et. al. _Compiler Testing via a Theory of Sound Optimisations in the C11/C++11 Memory Model_. [link](https://fzn.fr/projects/wmc/readings/pldi13.pdf)
- Armstrong et. al. _Isla: Integrating full-scale ISA semantics and axiomatic concurrency models_. [link](https://ucl-pplv.github.io/CAV21/poster_P_41/#tab-extended)
- Michalis Kokologiannakis and Viktor Vadeiadis. GenMC: A ModelC Checker for Weak Memory Models. [link](https://ucl-pplv.github.io/CAV21/poster_P_313/)
- Leslie Lamport. _How to Make a Correct Multiprocess Program Execute Correctly on a Multiprocessor_ [link](https://lamport.azurewebsites.net/pubs/lamport-how-to-make.pdf)
- Christopher Lidbury et. al, _Many-Core Compiler Fuzzing_. [link](https://dl.acm.org/doi/10.1145/2737924.2737986)
- Le et. al. _Compiler validation via equivalence modulo inputs_.[link](https://dl.acm.org/doi/10.1145/2666356.2594334)
- Leslie Lamport. _Time, Clocks, and the Ordering of Events in a Distributed System_. [link](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)
t






