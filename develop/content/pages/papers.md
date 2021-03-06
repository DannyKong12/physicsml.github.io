Title: Papers
Date: 2016-10-27 11:00

## Applying Machine Learning to Physics

- ["QuCumber: wavefunction reconstruction with neural networks"](
http://arxiv.org/abs/1812.09329v1
"As we enter a new era of quantum technology, it is increasingly important to
develop methods to aid in the accurate preparation of quantum states for a
variety of materials, matter, and devices. Computational techniques can be used
to reconstruct a state from data, however the growing number of qubits demands
ongoing algorithmic advances in order to keep pace with experiments. In this
paper, we present an open-source software package called QuCumber that uses
machine learning to reconstruct a quantum state consistent with a set of
projective measurements. QuCumber uses a restricted Boltzmann machine to
efficiently represent the quantum wavefunction for a large number of qubits.
New measurements can be generated from the machine to obtain physical
observables not easily accessible from the original data."),
Matthew J. S. Beach, Isaac De Vlugt, Anna Golubeva, Patrick Huembeli, Bohdan Kulchytskyy, Xiuzhe Luo, Roger G. Melko, Ejaaz Merali, Giacomo Torlai,
arXiv: [1812.09329](http://arxiv.org/abs/1812.09329v1),
12/2018

- ["Deep ToC: A New Method for Estimating the Solutions of PDEs"](
http://arxiv.org/abs/1812.08625v1
"This article presents a new methodology called deep ToC that estimates the
solutions of partial differential equations (PDEs) by combining neural networks
with the Theory of Connections (ToC). ToC is used to transform PDEs with
boundary conditions into unconstrained optimization problems by embedding the
boundary conditions into a "constrained expression" that contains a neural
network. The loss function for the unconstrained optimization problem is taken
to be the square of the residual of the PDE. Then, the neural network is
trained in an unsupervised manner to solve the unconstrained optimization
problem. This methodology has two major advantages over other popular methods
used to estimate the solutions of PDEs. First, this methodology does not need
to discretize the domain into a grid, which becomes prohibitive as the
dimensionality of the PDE increases. Instead, this methodology randomly samples
points from the domain during the training phase. Second, after training, this
methodology represents a closed form, analytical, differentiable approximation
of the solution throughout the entire training domain. In contrast, other
popular methods require interpolation if the estimated solution is desired at
points that do not lie on the discretized grid. The deep ToC method for
estimating the solution of PDEs is demonstrated on four problems with a variety
of boundary conditions."),
Carl Leake,
arXiv: [1812.08625](http://arxiv.org/abs/1812.08625v1),
12/2018

- ["Optimizing Quantum Error Correction Codes with Reinforcement Learning"](
http://arxiv.org/abs/1812.08451v1
"Quantum error correction is widely thought to be the key to fault-tolerant
quantum computation. However, determining the most suited encoding for unknown
error channels or specific laboratory setups is highly challenging. Here, we
present a reinforcement learning framework for optimizing and fault-tolerantly
adapting quantum error correction codes. We consider a reinforcement learning
agent tasked with modifying a quantum memory until a desired logical error rate
is reached. Using efficient simulations of a surface code quantum memory with
about 70 physical qubits, we demonstrate that such a reinforcement learning
agent can determine near-optimal solutions, in terms of the number of physical
qubits, for various error models of interest. Moreover, we show that agents
trained on one task are able to transfer their experience to similar tasks.
This ability for transfer learning showcases the inherent strengths of
reinforcement learning and the applicability of our approach for optimization
both in off-line simulations and on-line under laboratory conditions."),
Hendrik Poulsen Nautrup, Nicolas Delfosse, Vedran Dunjko, Hans J. Briegel, Nicolai Friis,
arXiv: [1812.08451](http://arxiv.org/abs/1812.08451v1),
12/2018

- ["Parameters optimization and real-time calibration of
  Measurement-Device-Independent Quantum Key Distribution Network based on Back
  Propagation Artificial Neural Network"](
http://arxiv.org/abs/1812.08388v2
"The parameters choosing (such as probabilities of choosing X-basis or
Z-basis, intensity of signal state and decoy state, etc.) and system
calibrating will be more challenging when the number of users of a
measurement-device-independent quantum key distribution(MDI-QKD) network
becomes larger. At present, people usually use optimization algorithms to
search the best parameters. This method can find the optimized parameters
accurately but may cost lots of time and hardware resources. It's a big problem
in large scale MDI-QKD network. Here, we present a new method, using Back
Propagation Artificial Neural Network(BPNN) to predict, rather than searching
the optimized parameters. Compared with optimization algorithms, our BPNN is
faster and more lightweight, it can save system resources. Another big problem
brought by large scale MDI-QKD network is system recalibration. BPNN can
support this work in real time, and it only needs to use some discarded data
generated from communication process, rather than require us to add additional
devices or scan the system"),
Feng-Yu Lu, Zhen-Qiang Yin, Chao Wang, Chao-Han Cui, Jun Teng, Shuang Wang, Wei Chen, Wei Huang, Bing-Jie Xu, Guang-Can Guo, Zheng-Fu Han,
arXiv: [1812.08388](http://arxiv.org/abs/1812.08388v2),
12/2018

- ["Machine Learning for Optimal Parameter Prediction in Quantum Key
  Distribution"](
http://arxiv.org/abs/1812.07724v1
"For quantum key distribution (QKD) with finite-size effects, parameter
optimization - the choice of intensities and probabilities of sending them - is
a crucial step to gain optimal performance. Traditionally, such an optimization
relies on brute-force search, or local search algorithm such as Coordinate
Descent. Here we present a new method of using a neural network to learn to
predict the optimal point for the convex optimization of parameters for QKD
with any given set of experiment devices and quantum channel conditions.
Selecting one protocol (symmetric 4-intensity measurement-device-independent
QKD) as an example, we show that with neural-network-predicted parameters we
can achieve over 99.99% of the optimal key rate. Harnessing the parallel
processing power of a graphical processing unit (GPU), the neural network
allows us to efficiently pre-generate on a desktop PC a large "look-up table"
of optimal parameters for all possible experimental parameter and channel
conditions, up to a finite resolution, and deploy this table to low-power
devices. This eliminates the need for any on-device computation, and allows us
to deploy finite-size QKD with optimal parameter setting to low-power mobile
QKD devices that have limited computing power, short communication time, and
quickly changing channel losses and experimental parameters (e.g. misalignment
and background noise), such as in satellite, drone, or handheld QKD systems. We
show that, on a Raspberry Pi 3 single-board computer, using look-up table is up
to 15-25 times faster than local search. In addition to the look-up table
method, we also point out the potential to directly deploy neural networks to
an increasing number of mobile devices equipped with neural processing units
for real-time fast parameter optimization."),
Wenyuan Wang, Hoi-Kwong Lo,
arXiv: [1812.07724](http://arxiv.org/abs/1812.07724v1),
12/2018

- ["Machine Learning as a universal tool for quantitative investigations of
  phase transition"](
http://arxiv.org/abs/1812.06726v1
"The problem of identifying the phase of a given system for a certain value of
the temperature can be reformulated as a classification problem in Machine
Learning. Taking as a prototype the Ising model and using the Support Vector
Machine as a tool to classify Monte Carlo generated configurations, we show
that the critical region of the system can be clearly identified and the
symmetry that drives the transition can be reconstructed from the performance
of the learning process. The role of the discrete symmetry of the system in
obtaining this result is discussed. A finite size analysis of the learned
Support Vector Machine decision function allows us to determine the critical
temperature and critical exponents with a precision that is comparable to that
of the most efficient numerical approaches relying on a known Hamiltonian
description of the system. For the determination of the critical temperature
and of the critical exponent connected with the divergence of the correlation
length, other than the availability of a range of temperatures having
information on both phases, the method we propose does not rest on any physical
input on the system, and in particular is agnostic to its Hamiltonian, its
symmetry properties and its order parameter. Hence, our investigation provides
a first significant step in the direction of devising robust tools for
quantitative analyses of phase transitions in cases in which an order parameter
is not known."),
Cinzia Giannetti, Biagio Lucini, Davide Vadacchino,
arXiv: [1812.06726](http://arxiv.org/abs/1812.06726v1),
12/2018

- ["Adaptive Quantum State Tomography with Neural Networks"](
http://arxiv.org/abs/1812.06693v1
"Quantum State Tomography is the task of determining an unknown quantum state
by making measurements on identical copies of the state. Current algorithms are
costly both on the experimental front -- requiring vast numbers of measurements
-- as well as in terms of the computational time to analyze those measurements.
In this paper, we address the problem of analysis speed and flexibility,
introducing \textit{Neural Adaptive Quantum State Tomography} (NA-QST), a
machine learning based algorithm for quantum state tomography that adapts
measurements and provides orders of magnitude faster processing while retaining
state-of-the-art reconstruction accuracy. Our algorithm is inspired by particle
swarm optimization and Bayesian particle-filter based adaptive methods, which
we extend and enhance using neural networks. The resampling step, in which a
bank of candidate solutions -- particles -- is refined, is in our case learned
directly from data, removing the computational bottleneck of standard methods.
We successfully replace the Bayesian calculation that requires computational
time of $O(\mathrm{poly}(n))$ with a learned heuristic whose time complexity
empirically scales as $O(\log(n))$ with the number of copies measured $n$,
while retaining the same reconstruction accuracy. This corresponds to a factor
of a million speedup for $10^7$ copies measured. We demonstrate that our
algorithm learns to work with basis, symmetric informationally complete (SIC),
as well as other types of POVMs. We discuss the value of measurement adaptivity
for each POVM type, demonstrating that its effect is significant only for basis
POVMs. Our algorithm can be retrained within hours on a single laptop for a
two-qubit situation, which suggests a feasible time-cost when extended to
larger systems. It can also adapt to a subset of possible states, a choice of
the type of measurement, and other experimental details."),
Yihui Quek, Stanislav Fort, Hui Khoon Ng,
arXiv: [1812.06693](http://arxiv.org/abs/1812.06693v1),
12/2018

- ["A hybrid machine-learning algorithm for designing quantum experiments"](
http://arxiv.org/abs/1812.03183v1
"We introduce a hybrid machine-learning algorithm for designing quantum optics
experiments that produce specific quantum states. Our algorithm successfully
found experimental schemes to produce all 5 states we asked it to, including
Schr\"odinger cat states and cubic phase states, all to a fidelity of over
$96\%$. Here we specifically focus on designing realistic experiments, and
hence all of the algorithm's designs only contain experimental elements that
are available with current technology. The core of our algorithm is a genetic
algorithm that searches for optimal arrangements of the experimental elements,
but to speed up the initial search we incorporate a neural network that
classifies quantum states. The latter is of independent interest, as it quickly
learned to accurately classify quantum states given their photon-number
distributions."),
L. O'Driscoll, R. Nichols, P. A. Knott,
arXiv: [1812.03183](http://arxiv.org/abs/1812.03183v1),
12/2018

- ["Enhancing the efficiency of quantum annealing via reinforcement: A
  path-integral Monte Carlo simulation of the quantum reinforcement algorithm"](
http://arxiv.org/abs/1812.02569v1
"The standard quantum annealing algorithm tries to approach the ground state
of a classical system by slowly decreasing the hopping rates of a quantum
random walk in the configuration space of the problem, where the on-site
energies are provided by the classical energy function. In a quantum
reinforcement algorithm, the annealing works instead by increasing gradually
the strength of the on-site energies according to the probability of finding
the walker on each site of the configuration space. Here, by using the
path-integral Monte Carlo simulations of the quantum algorithms, we show that
annealing via reinforcement can significantly enhance the success probability
of the quantum walker. More precisely, we implement a local version of the
quantum reinforcement algorithm, where the system wave function is replaced by
an approximate wave function using the local expectation values of the system.
We use this algorithm to find solutions to a prototypical constraint
satisfaction problem (XORSAT) close to the satisfiability to unsatisfiability
phase transition. The study is limited to small problem sizes (a few hundreds
of variables), nevertheless, the numerical results suggest that quantum
reinforcement may provide a useful strategy to deal with other computationally
hard problems and larger problem sizes even as a classical optimization
algorithm."),
A. Ramezanpour,
arXiv: [1812.02569](http://arxiv.org/abs/1812.02569v1),
12/2018

- ["Boltzmann Generators - Sampling Equilibrium States of Many-Body Systems
  with Deep Learning"](
http://arxiv.org/abs/1812.01729v1
"Computing equilibrium states in condensed-matter many-body systems, such as
solvated proteins, is a long-standing challenge. Lacking methods for generating
statistically independent equilibrium samples directly, vast computational
effort is invested for simulating these system in small steps, e.g., using
Molecular Dynamics. Combining deep learning and statistical mechanics, we here
develop Boltzmann Generators, that are shown to generate statistically
independent samples of equilibrium states of representative condensed matter
systems and complex polymers. Boltzmann Generators use neural networks to learn
a coordinate transformation of the complex configurational equilibrium
distribution to a distribution that can be easily sampled. Accurate computation
of free energy differences, and discovery of new system states are
demonstrated, providing a new statistical mechanics tool that performs orders
of magnitude faster than standard simulation methods."),
Frank Noé, Hao Wu,
arXiv: [1812.01729](http://arxiv.org/abs/1812.01729v1),
12/2018

- ["Phase transition encoded in neural network"](
http://arxiv.org/abs/1812.01522v1
"We discuss an aspect of neural networks for the purpose of phase transition
detection. To this end, we first train the neural network by feeding
Ising/Potts configurations with labels of temperature so that it can predict
the temperature of input. We do not explicitly supervise if the configurations
are in ordered/disordered phase. Nevertheless, we can identify the critical
temperature from the parameters (weights and biases) of trained neural network.
We attempt to understand how temperature-supervised neural networks capture the
information of phase transition by paying attention to what quantities they
learn. Our detailed analyses reveal that it learns different physical
quantities depending on how well it is trained. Main observation in this study
is how the weights in the trained neural-network can have information of the
phase transition in addition to temperature."),
Kouji Kashiwa, Yuta Kikuchi, Akio Tomiya,
arXiv: [1812.01522](http://arxiv.org/abs/1812.01522v1),
12/2018

- ["Approximating the solution to wave propagation using deep neural
  networks"](
http://arxiv.org/abs/1812.01609v1
"Humans gain an implicit understanding of physical laws through observing and
interacting with the world. Endowing an autonomous agent with an understanding
of physical laws through experience and observation is seldom practical: we
should seek alternatives. Fortunately, many of the laws of behaviour of the
physical world can be derived from prior knowledge of dynamical systems,
expressed through the use of partial differential equations. In this work, we
suggest a neural network capable of understanding a specific physical
phenomenon: wave propagation in a two-dimensional medium. We define
`understanding' in this context as the ability to predict the future evolution
of the spatial patterns of rendered wave amplitude from a relatively small set
of initial observations. The inherent complexity of the wave equations --
together with the existence of reflections and interference -- makes the
prediction problem non-trivial. A network capable of making approximate
predictions also unlocks the opportunity to speed-up numerical simulations for
wave propagation. To this aim, we created a novel dataset of simulated wave
motion and built a predictive deep neural network comprising of three main
blocks: an encoder, a propagator made by 3 LSTMs, and a decoder. Results show
reasonable predictions for as long as 80 time steps into the future on a
dataset not seen during training. Furthermore, the network is able to
generalize to an initial condition that is qualitatively different from those
seen during training."),
Wilhelm E. Sorteberg, Stef Garasto, Alison S. Pouplin, Chris D. Cantwell, Anil A. Bharath,
arXiv: [1812.01609](http://arxiv.org/abs/1812.01609v1),
12/2018

- ["Designing quantum experiments with a genetic algorithm"](
http://arxiv.org/abs/1812.01032v1
"We introduce a genetic algorithm that designs quantum optics experiments for
engineering quantum states with specific properties. Our algorithm is powerful
and flexible, and can easily be modified to find methods of engineering states
for a range of applications. Here we focus on quantum metrology. First, we
consider the noise-free case, and use the algorithm to find quantum states with
a large quantum Fisher information (QFI). We find methods, which only involve
experimental elements that are available with current technology, for
engineering quantum states with up to a 100-fold improvement over the best
classical state, and a 20-fold improvement over the optimal Gaussian state.
Such states are a superposition of the vacuum with a large number of photons
(around 80), and can hence be seen as Schr\"odinger-cat-like states. We then
apply the two most dominant noise sources in our setting -- photon loss and
imperfect heralding -- and use the algorithm to find quantum states that still
improve over the optimal Gaussian state with realistic levels of noise. This
will open up experimental and technological work in using exotic non-Gaussian
states for quantum-enhanced phase measurements. Finally, we use the Bayesian
mean square error to look beyond the regime of validity of the QFI, finding
quantum states with precision enhancements over the alternatives even when the
experiment operates in the regime of limited data."),
Rosanna Nichols, Lana Mineh, Jesús Rubio, Jonathan C. F. Matthews, Paul A. Knott,
arXiv: [1812.01032](http://arxiv.org/abs/1812.01032v1),
12/2018

- ["Divergence of predictive model output as indication of phase transitions"](
http://arxiv.org/abs/1812.00895v1
"We introduce a new method to identify phase boundaries in physical systems.
It is based on training a predictive model such as a neural network to infer a
physical system's parameters from its state. The deviation of the inferred
parameters from the underlying correct parameters will be most susceptible and
diverge maximally in the vicinity of phase boundaries. Therefore, peaks in the
divergence of the model's predictions are used as indication of phase
transitions. Our method is applicable for phase diagrams of arbitrary parameter
dimension and without prior information about the phases. Application to both
the two-dimensional Ising model and the dissipative Kuramoto-Hopf model show
promising results."),
Frank Schäfer, Niels Lörch,
arXiv: [1812.00895](http://arxiv.org/abs/1812.00895v1),
12/2018

- ["Quantum topology identification with deep neural networks and quantum
  walks"](
http://arxiv.org/abs/1811.12630v1
"Topologically ordered materials may serve as a platform for new quantum
technologies such as fault-tolerant quantum computers. To fulfil this promise,
efficient and general methods are needed to discover and classify new
topological phases of matter. We demonstrate that deep neural networks
augmented with external memory can use the density profiles formed in quantum
walks to efficiently identify properties of a topological phase as well as
phase transitions. On a trial topological ordered model, our method's accuracy
of topological phase identification reaches 97% and is shown to be robust to
noise on the data. Our approach is generally applicable and may be used for
topology identification with a variety of quantum materials."),
Yurui Ming, Chin-Teng Lin, Stephen D. Bartlett, Wei-Wei Zhang,
arXiv: [1811.12630](http://arxiv.org/abs/1811.12630v1),
11/2018

- ["Designing neural network based decoders for surface codes"](
http://arxiv.org/abs/1811.12456v2
"Recent works have shown that small distance quantum error correction codes
can be efficiently decoded by employing machine learning techniques like neural
networks. Various techniques employing neural networks have been used to
increase the decoding performance, however, there is no framework that analyses
a step-by-step procedure in designing such a neural network based decoder. The
main objective of this work is to present a detailed framework that
investigates the way that various neural network parameters affect the decoding
performance, the training time and the execution time of a neural network based
decoder. We focus on neural network parameters such as the size of the training
dataset, the structure, and the type of the neural network, the batch size and
the learning rate used during training. We compare various decoding strategies
and showcase how these influence the objectives for different error models. For
the noiseless syndrome measurements, we reach up to 50\% improvement against
the benchmark algorithm (Blossom) and for the noisy syndrome measurements, we
show efficient decoding performance up to 97 qubits for the rotated Surface
code. Furthermore, we show that the scaling of the execution time (time
calculated during the inference phase) is linear with the number of qubits,
which is a significant improvement compared to existing classical decoding
algorithms that scale polynomially with the number of qubits."),
Savvas Varsamopoulos, Koen Bertels, Carmen G. Almudever,
arXiv: [1811.12456](http://arxiv.org/abs/1811.12456v2),
11/2018

- ["Variational optimization in the AI era: Computational Graph States and
  Supervised Wave-function Optimization"](
http://arxiv.org/abs/1811.12423v1
"Representing a target quantum state by a compact, efficient variational
wave-function is an important approach to the quantum many-body problem. In
this approach, the main challenges include the design of a suitable variational
ansatz and optimization of its parameters. In this work, we address both of
these challenges. First, we define the variational class of Computational Graph
States (CGS) which gives a uniform framework for describing all computable
variational ansatz. Secondly, we develop a novel optimization scheme,
supervised wave-function optimization (SWO), which systematically improves the
optimized wave-function by drawing on ideas from supervised learning. While SWO
can be used independently of CGS, utilizing them together provides a flexible
framework for the rapid design, prototyping and optimization of variational
wave-functions. We demonstrate CGS and SWO by optimizing for the ground state
wave-function of 1D and 2D Heisenberg models on nine different variational
architectures including architectures not previously used to represent quantum
many-body wave-functions and find they are energetically competitive to other
approaches. One interesting application of this architectural exploration is
that we show that fully convolution neural network wave-functions can be
optimized for one system size and, using identical parameters, produce accurate
energies for a range of system sizes. We expect these methods to increase the
rate of discovery of novel variational ansatz and bring further insights to the
quantum many body problem."),
Dmitrii Kochkov, Bryan K. Clark,
arXiv: [1811.12423](http://arxiv.org/abs/1811.12423v1),
11/2018

- ["Classifying Snapshots of the Doped Hubbard Model with Machine Learning"](
http://arxiv.org/abs/1811.12425v1
"Quantum gas microscopes for ultracold atoms can provide high-resolution
real-space snapshots of complex many-body systems. We implement machine
learning to analyze and classify such snapshots of ultracold atoms.
Specifically, we compare the data from an experimental realization of the
two-dimensional Fermi-Hubbard model to two theoretical approaches: a doped
quantum spin liquid state of resonating valence bond type, and the geometric
string theory, describing a state with hidden spin order. This approach
considers all available information without a potential bias towards one
particular theory by the choice of an observable and can therefore select the
theory which is more predictive in general. Up to intermediate doping values,
our algorithm tends to classify experimental snapshots as
geometric-string-like, as compared to the doped spin liquid. Our results
demonstrate the potential for machine learning in processing the wealth of data
obtained through quantum gas microscopy for new physical insights."),
Annabelle Bohrdt, Christie S. Chiu, Geoffrey Ji, Muqing Xu, Daniel Greif, Markus Greiner, Eugene Demler, Fabian Grusdt, Michael Knap,
arXiv: [1811.12425](http://arxiv.org/abs/1811.12425v1),
11/2018

- ["Using a Recurrent Neural Network to Reconstruct Quantum Dynamics of a
  Superconducting Qubit from Physical Observations"](
http://arxiv.org/abs/1811.12420v3
"At its core, Quantum Mechanics is a theory developed to describe fundamental
observations in the spectroscopy of solids and gases. Despite these practical
roots, however, quantum theory is infamous for being highly counterintuitive,
largely due to its intrinsically probabilistic nature. Neural networks have
recently emerged as a powerful tool that can extract non-trivial correlations
in vast datasets. They routinely outperform state-of-the-art techniques in
language translation, medical diagnosis and image recognition. It remains to be
seen if neural networks can be trained to predict stochastic quantum evolution
without a priori specifying the rules of quantum theory. Here, we demonstrate
that a recurrent neural network can be trained in real time to infer the
individual quantum trajectories associated with the evolution of a
superconducting qubit under unitary evolution, decoherence and continuous
measurement from raw observations only. The network extracts the system
Hamiltonian, measurement operators and physical parameters. It is also able to
perform tomography of an unknown initial state without any prior calibration.
This method has potential to greatly simplify and enhance tasks in quantum
systems such as noise characterization, parameter estimation, feedback and
optimization of quantum control."),
Emmanuel Flurin, Leigh S. Martin, Shay Hacohen-Gourgy, Irfan Siddiqi,
arXiv: [1811.12420](http://arxiv.org/abs/1811.12420v3),
11/2018

- ["Quantum error correction for the toric code using deep reinforcement
  learning"](
http://arxiv.org/abs/1811.12338v1
"We implement a quantum error correction algorithm for bit-flip errors on the
topological toric code using deep reinforcement learning. An action-value
Q-function encodes the discounted value of moving a defect to a neighboring
site on the square grid (the action) depending on the full set of defects on
the torus (the syndrome or state). The Q-function is represented by a deep
convolutional neural network. Using the translational invariance on the torus
allows for viewing each defect from a central perspective which significantly
simplifies the state space representation independently of the number of defect
pairs. The training is done using experience replay, where data from the
algorithm being played out is stored and used for batch upgrade of the
Q-network. We find performance which is close to that achieved by the Minimum
Weight Perfect Matching algorithm for code distances up to $d=7$, which shows
that the deep Q-network is highly versatile in dealing with varying numbers of
syndrome defects."),
Philip Andreasson, Joel Johansson, Simon Liljestrand, Mats Granath,
arXiv: [1811.12338](http://arxiv.org/abs/1811.12338v1),
11/2018

- ["Developing a Bubble Chamber Particle Discriminator Using Semi-Supervised
  Learning"](
http://arxiv.org/abs/1811.11308v1
"The identification of non-signal events is a major hurdle to overcome for
bubble chamber dark matter experiments such as PICO-60. The current practice of
manually developing a discriminator function to eliminate background events is
difficult when available calibration data is frequently impure and present only
in small quantities. In this study, several different discriminator
input/preprocessing formats and neural network architectures are applied to the
task. First, they are optimized in a supervised learning context. Next, two
novel semi-supervised learning algorithms are trained, and found to replicate
the Acoustic Parameter (AP) discriminator previously used in PICO-60 with a
mean of 97% accuracy."),
B. Matusch, C. Amole, M. Ardid, I. J. Arnquist, D. M. Asner, D. Baxter, E. Behnke, M. Bressler, B. Broerman, G. Cao, C. J. Chen, U. Chowdhury, K. Clark, J. I. Collar, P. S. Cooper, C. B. Coutu, C. Cowles, M. Crisler, G. Crowder, N. A. Cruz-Venegas, C. E. Dahl, M. Das, S. Fallows, J. Farine, I. Felis, R. Filgas, F. Girard, G. Giroux, J. Hall, C. Hardy, O. Harris, T. Hillier, E. W. Hoppe, C. M. Jackson, M. Jin, L. Klopfenstein, C. B. Krauss, M. Laurin, I. Lawson, A. Leblanc, I. Levine, C. Licciardi, W. H. Lippincott, B. Loer, F. Mamedov, P. Mitra, C. Moore, T. Nania, R. Neilson, A. J. Noble, P. Oedekerk, A. Ortega, M. -C. Piro, A. Plante, R. Podviyanuk, S. Priya, A. E. Robinson, S. Sahoo, O. Scallon, S. Seth, A. Sonnenschein, N. Starinski, I. Štekl, T. Sullivan, F. Tardif, E. Vázquez-Jáuregui, N. Walkowski, E. Weima, U. Wichoski, K. Wierman, Y. Yan, V. Zacek, J. Zhang,
arXiv: [1811.11308](http://arxiv.org/abs/1811.11308v1),
11/2018

- ["Estimating of the inertial manifold dimension for a chaotic attractor of
  complex Ginzburg-Landau equation using a neural network"](
http://arxiv.org/abs/1811.11851v1
"Dimension of an inertial manifold for a chaotic attractor of spatially
distributed system is estimated using autoencoder neural network. The inertial
manifold is a low dimensional manifold where the chaotic attractor is embedded.
The autoencoder maps system state vectors onto themselves letting them pass
through an inner state with a reduced dimension. The training processes of the
autoencoder is shown to depend dramatically on the reduced dimension: a
learning curve saturates when the dimension is too small and decays if it is
sufficient for a lossless information transfer. The smallest sufficient value
is considered as a dimension of the inertial manifold, and the autoencoder
implements a mapping onto the inertial manifold and back. The correctness of
the computed dimension is confirmed by its remarkable coincidence with the one
obtained as a number of covariant Lyapunov vectors with vanishing pairwise
angles. These vectors are called physical modes. Unlike never having zero
angles residual ones they are known to span a tangent subspace for the inertial
manifold."),
Pavel V. Kuptsov, Anna V. Kuptsova,
arXiv: [1811.11851](http://arxiv.org/abs/1811.11851v1),
11/2018

- ["Deep Learning and Density Functional Theory"](
http://arxiv.org/abs/1811.08928v1
"Density functional theory (DFT) is used for quantum mechanical simulations of
electrons in molecules and materials, for applications in chemistry, physics,
materials science, and engineering. However, usage of DFT for large numbers of
atoms is hindered by typical scaling of $\mathcal{O}(N^3)$. Demonstration of a
sufficiently accurate reduced model with deep neural networks would enable
widespread application of DFT on larger, more complex systems for new
scientific discoveries. We show that deep neural networks can be integrated
into, or fully replace, the Kohn-Sham density functional theory scheme for
multi-electron systems in simple harmonic oscillator and random external
potentials. We first show that self-consistent charge densities can be used as
input to an extensive deep neural network to make predictions for correlation,
exchange, external, kinetic and total energies simultaneously. Additionally, we
show that one can also make all of the same predictions with the external
potential rather than the self-consistent charge density, which allows one to
circumvent the Kohn-Sham scheme altogether. We then show that a self-consistent
charge density found from a non-local exchange-correlation functional can be
used to make energy predictions for a semi-local exchange-correlation
functional. Lastly, we use a deep convolutional inverse graphics network to
predict the charge density given an external potential and asses the viability
of the predicted charge densities. This work shows that extensive deep neural
networks are generalizable and transferable given the variability of the
potentials and the fact that they can scale to an arbitrary system size with an
$\mathcal{O}(N)$ computational cost."),
Kevin Ryczko, David Strubbe, Isaac Tamblyn,
arXiv: [1811.08928](http://arxiv.org/abs/1811.08928v1),
11/2018

- ["Extrapolation of quantum observables with Gaussian processes"](
http://arxiv.org/abs/1901.00854v1
"For applications in chemistry and physics, machine learning is generally used
to solve one of three problems: interpolation, classification or clustering.
These problems use information about physical systems in a certain range of
parameters or variables in order to make predictions at unknown values of these
variables within the same range. The present work considers the application of
machine learning to {\it extrapolation} of physical properties beyond the range
of the training parameters. We show that Gaussian processes can be used to
build machine learning models capable of extrapolating the quantum properties
of complex systems across quantum phase transitions. The approach is based on
training Gaussian process models of variable complexity by the evolution of the
physical functions. We show that, as the complexity of the models increases,
they become capable of predicting new transitions. We also show that, where the
evolution of the physical functions is analytic and relatively simple (the
function considered here is $a + b/x + c/x^3$), Gaussian process models with
simple kernels (such as a simple Gaussian) yield accurate extrapolation
results. We thus argue that Gaussian processes can be used as a meaningful
extrapolation tool for a wide variety of problems in physics and chemistry. We
discuss strategies to prevent overfitting and obtain meaningful extrapolation
results without validation."),
Rodrigo A. Vargas-Hernández, Roman V. Krems,
arXiv: [1901.00854](http://arxiv.org/abs/1901.00854v1),
11/2018

- ["Energy Levels of One Dimensional Anharmonic Oscillator via Neural
  Networks"](
http://arxiv.org/abs/1811.08893v1
"In this work, we obtained energy levels of one dimensional quartic anharmonic
oscillator by using neural network system. Quartic anharmonic oscillator is a
very important tool in quantum mechanics and also in quantum field theory. Our
results are in good agreement in high accuracy with the reference studies."),
Halil Mutuk,
arXiv: [1811.08893](http://arxiv.org/abs/1811.08893v1),
11/2018

- ["Advances in Quantum Reinforcement Learning"](
http://arxiv.org/abs/1811.08676v1
"In recent times, there has been much interest in quantum enhancements of
machine learning, specifically in the context of data mining and analysis.
Reinforcement learning, an interactive form of learning, is, in turn, vital in
artificial intelligence-type applications. Also in this case, quantum mechanics
was shown to be useful, in certain instances. Here, we elucidate these results,
and show that quantum enhancements can be achieved in a new setting: the
setting of learning models which learn how to improve themselves -- that is,
those that meta-learn. While not all learning models meta-learn, all
non-trivial models have the potential of being "lifted", enhanced, to
meta-learning models. Our results show that also such models can be
quantum-enhanced to make even better learners. In parallel, we address one of
the bottlenecks of current quantum reinforcement learning approaches: the need
for so-called oracularized variants of task environments. Here we elaborate on
a method which realizes these variants, with minimal changes in the setting,
and with no corruption of the operative specification of the environments. This
result may be important in near-term experimental demonstrations of quantum
reinforcement learning."),
Vedran Dunjko, Jacob M. Taylor, Hans J. Briegel,
arXiv: [1811.08676](http://arxiv.org/abs/1811.08676v1),
11/2018

- ["Physics-aware Deep Generative Models for Creating Synthetic
  Microstructures"](
http://arxiv.org/abs/1811.09669v1
"A key problem in computational material science deals with understanding the
effect of material distribution (i.e., microstructure) on material performance.
The challenge is to synthesize microstructures, given a finite number of
microstructure images, and/or some physical invariances that the microstructure
exhibits. Conventional approaches are based on stochastic optimization and are
computationally intensive. We introduce three generative models for the fast
synthesis of binary microstructure images. The first model is a WGAN model that
uses a finite number of training images to synthesize new microstructures that
weakly satisfy the physical invariances respected by the original data. The
second model explicitly enforces known physical invariances by replacing the
traditional discriminator in a GAN with an invariance checker. Our third model
combines the first two models to reconstruct microstructures that respect both
explicit physics invariances as well as implicit constraints learned from the
image data. We illustrate these models by reconstructing two-phase
microstructures that exhibit coarsening behavior. The trained models also
exhibit interesting latent variable interpolation behavior, and the results
indicate considerable promise for enforcing user-defined physics constraints
during microstructure synthesis."),
Rahul Singh, Viraj Shah, Balaji Pokuri, Soumik Sarkar, Baskar Ganapathysubramanian, Chinmay Hegde,
arXiv: [1811.09669](http://arxiv.org/abs/1811.09669v1),
11/2018

- ["fPINNs: Fractional Physics-Informed Neural Networks"](
http://arxiv.org/abs/1811.08967v1
"Physics-informed neural networks (PINNs) are effective in solving
integer-order partial differential equations (PDEs) based on scattered and
noisy data. PINNs employ standard feedforward neural networks (NNs) with the
PDEs explicitly encoded into the NN using automatic differentiation, while the
sum of the mean-squared PDE-residuals and the mean-squared error in
initial/boundary conditions is minimized with respect to the NN parameters. We
extend PINNs to fractional PINNs (fPINNs) to solve space-time fractional
advection-diffusion equations (fractional ADEs), and we demonstrate their
accuracy and effectiveness in solving multi-dimensional forward and inverse
problems with forcing terms whose values are only known at randomly scattered
spatio-temporal coordinates (black-box forcing terms). A novel element of the
fPINNs is the hybrid approach that we introduce for constructing the residual
in the loss function using both automatic differentiation for the integer-order
operators and numerical discretization for the fractional operators. We
consider 1D time-dependent fractional ADEs and compare white-box (WB) and
black-box (BB) forcing. We observe that for the BB forcing fPINNs outperform
FDM. Subsequently, we consider multi-dimensional time-, space-, and
space-time-fractional ADEs using the directional fractional Laplacian and we
observe relative errors of $10^{-4}$. Finally, we solve several inverse
problems in 1D, 2D, and 3D to identify the fractional orders, diffusion
coefficients, and transport velocities and obtain accurate results even in the
presence of significant noise."),
Guofei Pang, Lu Lu, George Em Karniadakis,
arXiv: [1811.08967](http://arxiv.org/abs/1811.08967v1),
11/2018

- ["Neural Belief-Propagation Decoders for Quantum Error-Correcting Codes"](
http://arxiv.org/abs/1811.07835v1
"Belief-propagation (BP) decoders play a vital role in modern coding theory,
but they are not suitable to decode quantum error-correcting codes because of a
unique quantum feature called error degeneracy. Inspired by an exact mapping
between BP and deep neural networks, we train neural BP decoders for quantum
low-density parity-check (LDPC) codes with a loss function tailored to error
degeneracy. Training substantially improves the performance of BP decoders for
all families of codes we tested and may solve the degeneracy problem which
plagues the decoding of quantum LDPC codes."),
Ye-Hua Liu, David Poulin,
arXiv: [1811.07835](http://arxiv.org/abs/1811.07835v1),
11/2018

- ["Experimental Simultaneous Learning of Multiple Non-Classical
  Correlations"](
http://arxiv.org/abs/1811.06658v1
"Non-classical correlations can be regarded as resources for quantum
information processing. However, the classification problem of non-classical
correlations for quantum states remains a challenge, even for finite-size
systems. Although there exist a set of criteria for determining individual
non-classical correlations, a unified framework that is capable of
simultaneously classifying multiple correlations is still missing. In this
work, we experimentally explored the possibility of applying machine-learning
methods for simultaneously identifying non-classical correlations such as
entanglement, non-locality, and quantum steering, using the same set of
features. In particular, we constructed quantum-state classifiers from three
different machine-learning approaches, including neural network, support vector
machine, and decision tree. We found that for a family of quantum states, all
three approaches can achieve high accuracy for the classification problem, but
the runtimes are very different. Overall, we found that support vector machine
can significantly reduce the computing time with a mild loss of accuracy,
compared with the neural network. Finally, we further demonstrated the
scalability of this approach by analyzing the learn ability of the
quantum-state classifiers from labels generated by semi-definite programming."),
Mu Yang, Chang-liang Ren, Yue-chi Ma, Ya Xiao, Xiang-Jun Ye, Lu-Lu Song, Jin-Shi Xu, Man-Hong Yung, Chuan-Feng Li, Guang-Can Guo,
arXiv: [1811.06658](http://arxiv.org/abs/1811.06658v1),
11/2018

- ["Neural network state estimation for full quantum state tomography"](
http://arxiv.org/abs/1811.06654v2
"An efficient state estimation model, neural network estimation (NNE),
empowered by machine learning techniques, is presented for full quantum state
tomography (FQST). A parameterized function based on neural network is applied
to map the measurement outcomes to the estimated quantum states. Parameters are
updated with supervised learning procedures. From the computational complexity
perspective our algorithm is the most efficient one among existing state
estimation algorithms for full quantum state tomography. We perform numerical
tests to prove both the accuracy and scalability of our model."),
Qian Xu, Shuqi Xu,
arXiv: [1811.06654](http://arxiv.org/abs/1811.06654v2),
11/2018

- ["Efficient prediction of 3D electron densities using machine learning"](
http://arxiv.org/abs/1811.06255v1
"The Kohn-Sham scheme of density functional theory is one of the most widely
used methods to solve electronic structure problems for a vast variety of
atomistic systems across different scientific fields. While the method is fast
relative to other first principles methods and widely successful, the
computational time needed is still not negligible, making it difficult to
perform calculations for very large systems or over long time-scales. In this
submission, we revisit a machine learning model capable of learning the
electron density and the corresponding energy functional based on a set of
training examples. It allows us to bypass solving the Kohn-Sham equations,
providing a significant decrease in computation time. We specifically focus on
the machine learning formulation of the Hohenberg-Kohn map and its
decomposability. We give results and discuss challenges, limits and future
directions."),
Mihail Bogojeski, Felix Brockherde, Leslie Vogt-Maranto, Li Li, Mark E. Tuckerman, Kieron Burke, Klaus-Robert Müller,
arXiv: [1811.06255](http://arxiv.org/abs/1811.06255v1),
11/2018

- ["Adversarial Uncertainty Quantification in Physics-Informed Neural
  Networks"](
http://arxiv.org/abs/1811.04026v1
"We present a deep learning framework for quantifying and propagating
uncertainty in systems governed by non-linear differential equations using
physics-informed neural networks. Specifically, we employ latent variable
models to construct probabilistic representations for the system states, and
put forth an adversarial inference procedure for training them on data, while
constraining their predictions to satisfy given physical laws expressed by
partial differential equations. Such physics-informed constraints provide a
regularization mechanism for effectively training deep generative models as
surrogates of physical systems in which the cost of data acquisition is high,
and training data-sets are typically small. This provides a flexible framework
for characterizing uncertainty in the outputs of physical systems due to
randomness in their inputs or noise in their observations that entirely
bypasses the need for repeatedly sampling expensive experiments or numerical
simulators. We demonstrate the effectiveness of our approach through a series
of examples involving uncertainty propagation in non-linear conservation laws,
and the discovery of constitutive laws for flow through porous media directly
from noisy data."),
Yibo Yang, Paris Perdikaris,
arXiv: [1811.04026](http://arxiv.org/abs/1811.04026v1),
11/2018

- ["Artificial neural networks for density-functional optimizations in
  fermionic systems"](
http://arxiv.org/abs/1811.03774v1
"In this work we propose an artificial neural network functional to the
ground-state energy of fermionic interacting particles in homogeneous chains
described by the Hubbard model. Our neural network functional was proven to has
an excellent performance: it deviates from numerically exact calculations by
less than $0.15\%$ for all the regimes of filling factors and magnetizations,
and for a vast regime of interactions. When compared to analytical functionals,
the neural functional was found to be more precise for all the regimes of
parameters, being particularly superior at the weakly interacting regime: where
the analytical parametrization fails the most, $\sim7\%$, against only
$\sim0.1\%$ for the neural functional. We have also applied our homogeneous
functional to finite, localized impurities and harmonically confined systems
within density-functional theory (DFT) methods. The results show that while our
artificial neural network approach is substantially more accurate than other
equivalently simple and fast DFT treatments, it has similar performance than
more costly DFT calculations and other independent many-body calculations, at a
fraction of the computational cost."),
C. A. Custodio, E. R. Filletti, V. V. França,
arXiv: [1811.03774](http://arxiv.org/abs/1811.03774v1),
11/2018

- ["Machine learning for molecular dynamics with strongly correlated
  electrons"](
http://arxiv.org/abs/1811.01914v1
"We use machine learning to enable large-scale molecular dynamics (MD) of a
correlated electron model under the Gutzwiller approximation scheme. This model
exhibits a Mott transition as a function of on-site Coulomb repulsion $U$.
Repeated solution of the Gutzwiller self-consistency equations would be
prohibitively expensive for large-scale MD simulations. We show that machine
learning models of the Gutzwiller potential energy can be remarkably accurate.
The models, which are trained with $N=33$ atoms, enable highly accurate MD
simulations at much larger scales ($N\gtrsim10^{3}$). We investigate the
physics of the smooth Mott crossover in the fluid phase."),
Hidemaro Suwa, Justin S. Smith, Nicholas Lubbers, Cristian D. Batista, Gia-Wei Chern, Kipton Barros,
arXiv: [1811.01914](http://arxiv.org/abs/1811.01914v1),
11/2018

- ["Deep Learning of Robust and High-Precision Quantum Controls"](
http://arxiv.org/abs/1811.01884v1
"Robust and high-precision quantum control is extremely important but
challenging for scalable quantum computation. In this letter, we show that this
hard problem can be translated to a supervised machine learning task by
treating the time-ordered controlled quantum evolution as a layer-ordered deep
neural network (DNN). The finding of robust quantum controls is then equivalent
to training a DNN with high generalizability. In this way, powerful DNN tuning
skills matured in deep learning (DL) can be employed for the discovery of
highly robust and precise quantum controls, which opens up a door through which
a large family of learning algorithms can be developed. We exemplify this
DL-inspired potential by introducing the commonly used trick of batch-based
optimization. The resulting b-GRAPE algorithm is demonstrated to be able to
remarkably enhance the control robustness while maintaining high fidelity in
the implementation of a three-qubit quantum gate."),
Re-Bing Wu, Haijin Ding, Daoyi Dong, Xiaoting Wang,
arXiv: [1811.01884](http://arxiv.org/abs/1811.01884v1),
11/2018





- ["An Artificial Neural Network Approach to the Analytic Continuation
  Problem"](
http://arxiv.org/abs/1810.00913v1
"Inverse problems are encountered in many domains of physics, with analytic
continuation of the imaginary Green's function into the real frequency domain
being a particularly important example. However, the analytic continuation
problem is ill-defined and currently no analytic transformation for solving it
is known. We present a general framework for building an artificial neural
network that efficiently solves this task with a supervised learning approach,
provided that the forward problem is sufficiently stable for creating a large
training dataset of physically relevant examples. By comparing with the
commonly used maximum entropy approach, we show that our method can reach the
same level of accuracy for low-noise input data while performing significantly
better when the noise strength increases. We also demonstrate that adding an
unsupervised denoising step significantly improves the accuracy of the maximum
entropy predictions for noisy inputs. The computational cost of the proposed
neural network approach is reduced by almost three orders of magnitude compared
to the maximum entropy method."),
Romain Fournier, Lei Wang, Oleg V. Yazyev, QuanSheng Wu,
arXiv: [1810.00913](http://arxiv.org/abs/1810.00913v1),
10/2018


- ["Efficient Representation of Topologically Ordered States with Restricted
  Boltzmann Machines"](
http://arxiv.org/abs/1810.02352v1
"Representation by neural networks, in particular by restricted Boltzmann
machines (RBM), has provided a powerful computational tool to solve quantum
many-body problems. An important open question is how to characterize which
class of quantum states can be efficiently represented with the RBM. Here, we
show that the RBM can efficiently represent a wide class of many-body entangled
states with rich exotic topological orders. This includes: (1) ground states of
double semion and twisted quantum double models with intrinsic topological
orders; (2) states of the AKLT model and 2D CZX model with symmetry protected
topological order; (3) states of Haah code model with fracton topological
order; (4) generalized stabilizer states and hypergraph states that are
important for quantum information protocols. One twisted quantum double model
state considered here harbors non-abelian anyon excitations. Our result shows
that it is possible to study a variety of quantum models with exotic
topological orders and rich physics using the RBM computational toolbox."),
Sirui Lu, X. Gao, L. -M. Duan,
arXiv: [1810.02352](http://arxiv.org/abs/1810.02352v1),
10/2018


- ["Super-resolving the Ising model with convolutional neural networks"](
http://arxiv.org/abs/1810.02372v1
"Machine learning is becoming widely used in condensed matter physics.
Inspired by the concept of image super-resolution, we propose a method to
increase the size of lattice spin configurations using deep convolutional
neural networks. Through supervised learning on Monte Carlo (MC) generated spin
configurations, we train networks that invert real-space renormalization
decimations. We demonstrate that super-resolution can reproduce thermodynamic
observables that agree with MC calculations for the one and two-dimensional
Ising model at various temperatures. We find that it is possible to predict
thermodynamic quantities for lattice sizes larger than those used in training
by extrapolating the parameters of the network. We use this method to
extrapolate the exponents of the 2D Ising critical point towards the
thermodynamic limit, which results in good agreement with theory."),
Stavros Efthymiou, Matthew J. S. Beach, Roger G. Melko,
arXiv: [1810.02372](http://arxiv.org/abs/1810.02372v1),
10/2018


- ["Learning multiple order parameters with interpretable machines"](
http://arxiv.org/abs/1810.05538v2
"Machine learning techniques are evolving into an subsidiary tool for studying
phase transitions in many-body systems. However, most studies are tied to
situations involving only one phase transition and one order parameter. Systems
that accommodate multiple phases of coexisting and competing orders, which are
common in condensed matter physics, remain largely unexplored from a machine
learning perspective. In this paper, we investigate multiclassification of
phases using Support Vector Machines (SVMs) and apply a recently introduced
kernel method for detecting hidden spin and orbital orders to learn multiple
phases and their analytical order parameters. Our focus is on multipolar orders
and their tensorial order parameters whose identification is difficult with
traditional methods. The importance of interpretability is emphasized for
physical applications of multiclassification. Furthermore, we discuss an
intrinsic parameter of SVM, the bias, which allows for a special interpretation
in the classification of phases, and its utility in diagnosing the existence of
phase transitions. We show that it can be exploited as an efficient way to
explore the topology of unknown phase diagrams where the supervision is
entirely delegated to the machine."),
Ke Liu, Jonas Greitemann, Lode Pollet,
arXiv: [1810.05538](http://arxiv.org/abs/1810.05538v2),
10/2018

- ["Nonequilibrium fluctuations of a driven quantum heat engine via machine
  learning"](
http://arxiv.org/abs/1810.05913v1
"We propose a machine learning approach based on artificial neural network to
gain faster insights on the role of geometric contributions to the
nonequilibrium fluctuations of an adiabatically temperature-driven quantum heat
engine coupled to a cavity. Using the artificial neural network we have
explored the interplay between bunched and antibunched photon exchange
statistics for different engine parameters. We report that beyond a pivotal
cavity temperature, the Fano factor oscillates between giant and low values as
a function of phase difference between the driving protocols. We further
observe that the standard thermodynamic uncertainty relation is not valid when
there are finite geometric contributions to the fluctuations, but holds true
for zero phase difference even in presence of coherences."),
Sajal Kumar Giri, Himangshu Prabal Goswami,
arXiv: [1810.05913](http://arxiv.org/abs/1810.05913v1),
10/2018

- ["Reinforcement Learning Decoders for Fault-Tolerant Quantum Computation"](
http://arxiv.org/abs/1810.07207v1
"Topological error correcting codes, and particularly the surface code,
currently provide the most feasible roadmap towards large-scale fault-tolerant
quantum computation. As such, obtaining fast and flexible decoding algorithms
for these codes, within the experimentally relevant context of faulty syndrome
measurements, is of critical importance. In this work, we show that the problem
of decoding such codes, in the full fault-tolerant setting, can be naturally
reformulated as a process of repeated interactions between a decoding agent and
a code environment, to which the machinery of reinforcement learning can be
applied to obtain decoding agents. As a demonstration, by using deepQ learning,
we obtain fast decoding agents for the surface code, for a variety of
noise-models."),
Ryan Sweke, Markus S. Kesselring, Evert P. L. van Nieuwenburg, Jens Eisert,
arXiv: [1810.07207](http://arxiv.org/abs/1810.07207v1),
10/2018

- ["Thermodynamics and Feature Extraction by Machine Learning"](
http://arxiv.org/abs/1810.08179v1
"Machine learning methods are powerful in distinguishing different phases of
matter in an automated way and provide a new perspective on the study of
physical phenomena. We train a Restricted Boltzmann Machine (RBM) on data
constructed with spin configurations sampled from the Ising Hamiltonian at
different values of temperature and external magnetic field using Monte Carlo
methods. From the trained machine we obtain the flow of iterative
reconstruction of spin state configurations to faithfully reproduce the
observables of the physical system. We find that the flow of the trained RBM
approaches the spin configurations of the maximal possible specific heat which
resemble the near criticality region of the Ising model. In the special case of
the vanishing magnetic field the trained RBM converges to the critical point of
the Renormalization Group (RG) flow of the lattice model. Our results suggest
an alternative explanation of how the machine identifies the physical phase
transitions, by recognizing certain properties of the configuration like the
maximization of the specific heat, instead of associating directly the
recognition procedure with the RG flow and its fixed points. Then from the
reconstructed data we deduce the critical exponent associated to the
magnetization to find satisfactory agreement with the actual physical value. We
assume no prior knowledge about the criticality of the system and its
Hamiltonian."),
Shotaro Shiba Funai, Dimitrios Giataganas,
arXiv: [1810.08179](http://arxiv.org/abs/1810.08179v1),
10/2018

- ["Emulating quantum computation with artificial neural networks"](
http://arxiv.org/abs/1810.10335v1
"We demonstrate, that artificial neural networks (ANN) can be trained to
emulate single or multiple basic quantum operations. In order to realize a
quantum state, we implement a novel "quantumness gate" that maps an arbitrary
matrix to the real representation of a positive hermitean normalized density
matrix. We train the CNOT gate, the Hadamard gate and a rotation in Hilbert
space as basic building blocks for processing the quantum density matrices of
two entangled qubits. During the training process the neural networks learn to
represent the complex structure, the hermiticity, the normalization and the
positivity of the output matrix. The requirement of successful training allows
us to find a critical bottleneck dimension which reflects the relevant quantum
information. Chains of individually trained neural quantum gates can be
constructed to realize any unitary transformation. For scaling to larger
quantum systems, we propose to use correlations of stochastic macroscopic
two-level observables or classical bits. This novel concept provides a path for
a classical implementation of computationally relevant quantum information
processing on classical neural networks, in particular on neuromorphic
computing machines featuring stochastic operations."),
Christian Pehle, Karlheinz Meier, Markus Oberthaler, Christof Wetterich,
arXiv: [1810.10335](http://arxiv.org/abs/1810.10335v1),
10/2018

- ["Reconstructing quantum states with generative models"](
http://arxiv.org/abs/1810.10584v1
"A major bottleneck in the quest for scalable many-body quantum technologies
is the difficulty in benchmarking their preparations, which suffer from an
exponential `curse of dimensionality' inherent to their quantum states. We
present an experimentally friendly method for density matrix reconstruction
based on deep neural-network generative models. The learning procedure comes
with a built-in approximate certificate of the reconstruction and makes no
assumptions on the state under scrutiny, making it both reliable and
unconditional. It can efficiently handle a broad class of complex systems
including prototypical states in quantum information, as well as ground states
of local spin models common to condensed matter physics. The key insight is to
reduce the state tomography task to an unsupervised learning problem of the
statistics of an informationally complete set of quantum measurements. This
constitutes a modern machine learning approach to the validation of large
quantum devices, which may prove relevant as a neural-network ansatz over mixed
states suitable for variational optimization."),
Juan Carrasquilla, Giacomo Torlai, Roger G. Melko, Leandro Aolita,
arXiv: [1810.10584](http://arxiv.org/abs/1810.10584v1),
10/2018

- ["Machine learning density functional theory for the Hubbard model"](
http://arxiv.org/abs/1810.12700v1
"The solution of complex many-body lattice models can often be found by
defining an energy functional of the relevant density of the problem. For
instance, in the case of the Hubbard model the spin-resolved site occupation is
enough to describe the system total energy. Similarly to standard density
functional theory, however, the exact functional is unknown and suitable
approximations need to be formulated. By using a deep-learning neural network
trained on exact-diagonalization results we demonstrate that one can construct
an exact functional for the Hubbard model. In particular, we show that the
neural network returns a ground-state energy numerically indistinguishable from
that obtained by exact diagonalization and, most importantly, that the
functional satisfies the two Hohenberg-Kohn theorems: for a given ground-state
density it yields the external potential and it is fully variational in the
site occupation."),
James Nelson, Rajarshi Tiwari, Stefano Sanvito,
arXiv: [1810.12700](http://arxiv.org/abs/1810.12700v1),
10/2018


- ["Approaching the adiabatic timescale with machine-learning"](
http://arxiv.org/abs/1809.03124v2
"The control and manipulation of quantum systems without excitation is
challenging, due to the complexities in fully modeling such systems accurately
and the difficulties in controlling these inherently fragile systems
experimentally. For example, while protocols to decompress Bose-Einstein
condensates (BEC) faster than the adiabatic timescale (without excitation or
loss) have been well developed theoretically, experimental implementations of
these protocols have yet to reach speeds faster than the adiabatic timescale.
In this work, we experimentally demonstrate an alternative approach based on a
machine learning algorithm which makes progress towards this goal. The
algorithm is given control of the coupled decompression and transport of a
metastable helium condensate, with its performance determined after each
experimental iteration by measuring the excitations of the resultant BEC. After
each iteration the algorithm adjusts its internal model of the system to create
an improved control output for the next iteration. Given sufficient control
over the decompression, the algorithm converges to a novel solution that sets
the current speed record in relation to the adiabatic timescale, beating out
other experimental realizations based on theoretical approaches. This method
presents a feasible approach for implementing fast state preparations or
transformations in other quantum systems, without requiring a solution to a
theoretical model of the system. Implications for fundamental physics and
cooling are discussed."),
Bryce M. Henson, Dong K. Shin, Kieran F. Thomas, Jacob A. Ross, Michael R. Hush, Sean S. Hodgman, Andrew G. Truscott,
arXiv: [1809.03124](http://arxiv.org/abs/1809.03124v2),
9/2018

- ["Projective quantum Monte Carlo simulations guided by unrestricted neural
  network states"](
http://arxiv.org/abs/1809.03562v1
"We investigate the use of variational wave-functions that mimic stochastic
recurrent neural networks, specifically, unrestricted Boltzmann machines, as
guiding functions in projective quantum Monte Carlo (PQMC) simulations of
quantum spin models. As a preliminary step, we investigate the accuracy of such
unrestricted neural network states as variational Ans\"atze for the ground
state of the ferromagnetic quantum Ising chain. We find that by optimizing just
three variational parameters, independently on the system size, accurate
ground-state energies are obtained, comparable to those previously obtained
using restricted Boltzmann machines with few variational parameters per spin.
Chiefly, we show that if one uses optimized unrestricted neural network states
as guiding functions for importance sampling the efficiency of the PQMC
algorithms is greatly enhanced, drastically reducing the most relevant
systematic bias, namely that due to the finite random-walker population. The
scaling of the computational cost with the system size changes from the
exponential scaling characteristic of PQMC simulations performed without
importance sampling, to a polynomial scaling, even at the ferromagnetic quantum
critical point. The important role of the protocol chosen to sample
hidden-spins configurations, in particular at the critical point, is analyzed.
We discuss the implications of these findings for what concerns the problem of
simulating adiabatic quantum optimization using stochastic algorithms on
classical computers."),
E. M. Inack, G. E. Santoro, L. Dell'Anna, S. Pilati,
arXiv: [1809.03562](http://arxiv.org/abs/1809.03562v1),
9/2018

- ["Supervised machine learning of ultracold atoms with speckle disorder"](
http://arxiv.org/abs/1809.04679v1
"We analyze how accurately supervised machine learning techniques can predict
the lowest energy levels of one-dimensional noninteracting ultracold atoms
subject to the correlated disorder due to an optical speckle field. Deep neural
networks with different numbers of hidden layers and neurons per layer are
trained on large sets of instances of the speckle field, whose energy levels
have been preventively determined via a high-order finite difference technique.
The Fourier components of the speckle field are used as feature vector to
represent the speckle-field instances. A comprehensive analysis of the details
that determine the possible success of supervised machine learning tasks,
namely the depth and the width of the neural network, the size of the training
set, and the magnitude of the regularization parameter, is presented. It is
found that ground state energies of previously unseen instances can be
predicted with essentially arbitrary accuracy. First and second excited state
energies can be predicted too, albeit with slightly lower accuracy and using
more layers of hidden neurons."),
S. Pilati, P. Pieri,
arXiv: [1809.04679](http://arxiv.org/abs/1809.04679v1),
9/2018


- ["GANs for generating EFT models"](
http://arxiv.org/abs/1809.02612v1
"We initiate a way of generating models by the computer, satisfying both
experimental and theoretical constraints. In particular, we present a framework
which allows the generation of effective field theories. We use Generative
Adversarial Networks to generate these models and we generate examples which go
beyond the examples known to the machine. As a starting point, we apply this
idea to the generation of supersymmetric field theories. In this case, the
machine knows consistent examples of supersymmetric field theories with a
single field and generates new examples of such theories. In the generated
potentials we find distinct properties, here the number of minima in the scalar
potential, with values not found in the training data. We comment on potential
further applications of this framework."),
Harold Erbin, Sven Krippendorf,
arXiv: [1809.02612](http://arxiv.org/abs/1809.02612v1),
9/2018


- ["Identifying Quantum Phase Transitions using Artificial Neural Networks
  on Experimental Data"](
http://arxiv.org/abs/1809.05519v1
"Machine learning techniques such as artificial neural networks are currently
revolutionizing many technological areas and have also proven successful in
quantum physics applications. Here we employ an artificial neural network and
deep learning techniques to identify quantum phase transitions from single-shot
experimental momentum-space density images of ultracold quantum gases and
obtain results, which were not feasible with conventional methods. We map out
the complete two-dimensional topological phase diagram of the Haldane model and
provide an accurate characterization of the superfluid-to-Mott-insulator
transition in an inhomogeneous Bose-Hubbard system. Our work points the way to
unravel complex phase diagrams of general experimental systems, where the
Hamiltonian and the order parameters might not be known."),
Benno S. Rem, Niklas Käming, Matthias Tarnowski, Luca Asteria, Nick Fläschner, Christoph Becker, Klaus Sengstock, Christof Weitenberg,
arXiv: [1809.05519](http://arxiv.org/abs/1809.05519v1),
9/2018

- ["Neural Network Decoders for Large-Distance 2D Toric Codes"](
http://arxiv.org/abs/1809.06640v1
"We still do not have the perfect decoders for topological codes that can
satisfy all needs of different experimental setups. Recently, a few neural
network based decoders have been studied, with the motivation that they can
adapt to a wide range of noise models, and can easily run on dedicated chips
without a full-fledged computer. The later feature might lead to fast speed and
the ability to operate in low temperature. However, a question which has not
been addressed in previous works is whether neural network decoders can handle
2D topological codes with large distances. In this work, we provide a positive
answer for the toric code. The structure of our neural network decoder is
inspired by the renormalization group decoder. With a fairly strict policy on
training time, when the bit-flip error rate is lower than $9\%$, the neural
network decoder performs better when code distance increases. With a less
strict policy, we find it is not hard for the neural decoder to achieve a
performance close to the minimum-weight perfect matching algorithm. The
numerical simulation is done up to code distance $d=64$. Last but not least, we
describe and analyze a few failed approaches. They guide us to the final design
of our neural decoder, but also serve as a caution when we gauge the
versatility of stock deep neural networks."),
Xiaotong Ni,
arXiv: [1809.06640](http://arxiv.org/abs/1809.06640v1),
9/2018

- ["Phase Diagram of Disordered Higher Order Topological Insulator: a
  Machine Learning Study"](
http://arxiv.org/abs/1809.09865v1
"A higher order topological insulator is a new concept of topological states
of matter, which is characterized by the emergent boundary states whose
dimensionality is lower by more than two compared with that of the bulk, and
draws a considerable interest. Yet, its robustness against disorders is still
unclear. Here we investigate a phase diagram of higher order topological
insulator phases in a breathing Kagome model in the presence of disorders, by
using a state-of-the-art machine learning technique. We find that the corner
states survive against the finite strength of disorder potential as long as the
energy gap is not closed, indicating the stability of the higher order
topological phases against the disorders."),
Hiromu Araki, Tomonari Mizoguchi, Yasuhiro Hatsugai,
arXiv: [1809.09865](http://arxiv.org/abs/1809.09865v1),
9/2018

- ["A machine learning approach to the Berezinskii-Kosterlitz-Thouless
  transition in classical and quantum models"](
http://arxiv.org/abs/1809.09927v1
"The Berezinskii-Kosterlitz-Thouless transition is a very specific phase
transition where all thermodynamic quantities are smooth. Therefore, it is
difficult to determine the critical temperature in a precise way. In this paper
we demonstrate how neural networks can be used to perform this task. In
particular, we study how the accuracy of the transition identification depends
on the way the neural networks are trained. We apply our approach to three
different systems: (i) the classical XY model, (ii) the phase-fermion model,
where classical and quantum degrees of freedom are coupled and (iii) the
quantum XY model."),
M. Richter-Laskowska, H. Khan, N. Trivedi, M. M. Maśka,
arXiv: [1809.09927](http://arxiv.org/abs/1809.09927v1),
9/2018

- ["Self-organizing maps as a method for detecting phase transitions and
  phase identification"](
http://arxiv.org/abs/1809.10419v1
"Originating from image recognition, methods of machine learning allow for
effective feature extraction and dimensionality reduction in multidimensional
datasets, thereby providing an extraordinary tool to deal with classical and
quantum models in many-body physics. In this study, we employ a specific
unsupervised machine learning technique -- self-organizing maps -- to create a
low-dimensional representation of microscopic states, relevant for macroscopic
phase identification and detecting phase transitions. We explore the properties
of spin Hamiltonians of two archetype model system: a two-dimensional
Heisenberg ferromagnet and a three-dimensional crystal, Fe in the body centered
cubic structure. The method of self-organizing maps, that is known to conserve
connectivity of the initial dataset, is compared to the cumulant method theory
and is shown to be as accurate while being computationally more efficient in
determining a phase transition temperature. We argue that the method proposed
here can be applied to explore a broad class of second-order phase transition
systems, not only magnetic systems but also, for example, order-disorder
transitions in alloys."),
Albert A. Shirinyan, Valerii K. Kozin, Johan Hellsvik, Manuel Pereiro, Olle Eriksson, Dmitry Yudin,
arXiv: [1809.10419](http://arxiv.org/abs/1809.10419v1),
9/2018

- ["Solving Statistical Mechanics using Variational Autoregressive Networks"](
http://arxiv.org/abs/1809.10606v1
"We propose a general framework for solving statistical mechanics of systems
with a finite size. The approach extends the celebrated variational mean-field
approaches using autoregressive neural networks which support direct sampling
and exact calculation of normalized probability of configurations. The network
computes variational free energy, estimates physical quantities such as
entropy, magnetizations and correlations, and generates uncorrelated samples
all at once. Training of the network employs the policy gradient approach in
reinforcement learning, which unbiasedly estimates the gradient of variational
parameters. We apply our approach to several classical systems, including 2-d
Ising models, Hopfield model, Sherrington--Kirkpatrick spin glasses, and the
inverse Ising model, for demonstrating its advantages over existing variational
mean-field methods. Our approach sheds light on solving statistical physics
problems using modern deep generative neural networks."),
Dian Wu, Lei Wang, Pan Zhang,
arXiv: [1809.10606](http://arxiv.org/abs/1809.10606v1),
9/2018

- ["Extracting many-particle entanglement entropy from observables using
  supervised machine learning"](
http://arxiv.org/abs/1810.00346v1
"Entanglement, which quantifies non-local correlations in quantum mechanics,
is the fascinating concept behind much of aspiration towards quantum
technologies. Nevertheless, directly measuring the entanglement of a
many-particle system is very challenging. Here we show that via supervised
machine learning using a convolutional neural network, we can infer the
entanglement from a measurable observable for a disordered interacting quantum
many-particle system. Several structures of neural networks were tested and a
convolutional neural network akin to structures used for image and speech
recognition performed the best. After training on a set of 500 realizations of
disorder, the network was applied to 200 new realizations and its results for
the entanglement entropy were compared to a direct computation of the
entanglement entropy. Excellent agreement was found, except for several rare
region which in a previous study were identified as belonging to an inclusion
of a Griffiths-like quantum phase. Training the network on a test set with
different parameters (in the same phase) also works quite well."),
Richard Berkovits,
arXiv: [1810.00346](http://arxiv.org/abs/1810.00346v1),
9/2018


- ["Deep learning, quantum chaos, and pseudorandom evolution"](
http://arxiv.org/abs/1808.10498v1
"By modeling quantum chaotic dynamics with ensembles of random operators, we
explore how a deep learning architecture known as a convolutional neural
network (CNN) can be used to detect pseudorandom behavior in qubit systems. We
analyze samples consisting of pieces of correlation functions and find that a
CNN is capable of determining the degree of pseudorandomness which a system is
subject to. This is done without computing any correlators explicitly.
Interestingly, even samples drawn from two-point functions are found to be
sufficient to solve this classification problem. This presents the possibility
of using deep learning algorithms to explore late time behavior in chaotic
quantum systems which have been inaccessible to simulation."),
Daniel W. F. Alves, Michael O. Flynn,
arXiv: [1808.10498](http://arxiv.org/abs/1808.10498v1),
8/2018

- ["Quantum Neural Network States"](
http://arxiv.org/abs/1808.10601v1
"In this work, we investigate the possibility of using artificial neural
network to build ansatz quantum many-body states. The progresses on
representing quantum many body states by stochastic recurrent neural network,
restricted or unrestricted Boltzmann machine, are reviewed. Besides, we discuss
the possibility of representing quantum states using feed-forward neural
network which is relatively less studied in literatures. At last, entanglement
features of the quantum neural network states are discussed for comparison with
the tensor network states."),
Zhih-Ahn Jia, Biao Yi, Rui Zhai, Yu-Chun Wu, Guang-Can Guo, Guo-Ping Guo,
arXiv: [1808.10601](http://arxiv.org/abs/1808.10601v1),
8/2018


- ["Reconstruction of a Photonic Qubit State with Quantum Reinforcement
  Learning"](
http://arxiv.org/abs/1808.09241v1
"Extracting information from an unknown quantum state is an important task in
quantum information. For the most general quantum state tomography, one has to
measure the averages of a set of observables for reconstructing the density
matrix. However, this method requires enough copies of the unknown state to be
provided. In this work, we perform an experiment to reconstruct an unknown
photonic quantum state with a limited amount of copies. We employ a quantum
reinforcement learning approach to adapt one qubit state, an 'agent', to an
unknown quantum state, an `environment', by successive single-shot measurements
and feedback, in order to achieve maximum overlap. Our experimental learning
device, composed of a quantum photonics setup, can adjust the corresponding
parameters to rotate the agent system based on the measurement outcomes `0' or
`1' on the environment (i.e., reward/punishment signals). Our results show
that, when assisted by such a quantum machine learning technique, the
fidelities of the deterministic single-photon agent states can achieve over
$88\%$ under a proper reward/punishment ratio within 50 iterations. Therefore,
only 50 photonic copies of the environment system are consumed. Meanwhile,
these results all surpass the fidelities obtained by standard quantum
tomography methods with the same number of photons as a resource. This protocol
offers a tool for reconstructing an unknown quantum state when only limited
copies are provided, and can also be extended to high dimensions, multipartite,
and mixed quantum state scenarios."),
Shang Yu, F. Albarran-Arriagada, J. C. Retamal, Yi-Tao Wang, Wei Liu, Zhi-Jin Ke, Yu Meng, Zhi-Peng Li, Jian-Shun Tang, E. Solano, L. Lamata, Chuan-Feng Li, Guang-Can Guo,
arXiv: [1808.09241](http://arxiv.org/abs/1808.09241v1),
8/2018

- ["Policy Guided Monte Carlo: Reinforcement Learning Markov Chain Dynamics"](
http://arxiv.org/abs/1808.09095v1
"We introduce \textit{Policy Guided Monte Carlo} (PGMC), a computational
paradigm using reinforcement learning to improve Markov Chain Monte Carlo
(MCMC) sampling. The methodology is generally applicable, unbiased and opens up
a new path to automated discovery of efficient MCMC samplers. After developing
a general theory, we demonstrate some of PGMCs prospects on an Ising model on
the kagome lattice, including when the model is its computationally challenging
kagome spin ice regime. Here, we show that PGMC is able to automatically
machine learn efficient MCMC updates without a priori knowledge of the physics
at hand."),
Troels Arnfred Bojesen,
arXiv: [1808.09095](http://arxiv.org/abs/1808.09095v1),
8/2018

- ["Machine learning non-local correlations"](
http://arxiv.org/abs/1808.07069v1
"The ability to witness non-local correlations lies at the core of
foundational aspects of quantum mechanics and its application in the processing
of information. Commonly, this is achieved via the violation of Bell
inequalities. Unfortunately, however, their systematic derivation quickly
becomes unfeasible as the scenario of interest grows in complexity. To cope
with that, we propose here a machine learning approach for the detection and
quantification of non-locality. It consists of an ensemble of multilayer
perceptrons blended with genetic algorithms achieving a high performance in a
number of relevant Bell scenarios. Our results offer a novel method and a
proof-of-principle for the relevance of machine learning for understanding
non-locality."),
Askery Canabarro, Samuraí Brito, Rafael Chaves,
arXiv: [1808.07069](http://arxiv.org/abs/1808.07069v1),
8/2018

- ["Smart energy models for atomistic simulations using a DFT-driven
  multifidelity approach"](
http://arxiv.org/abs/1808.06935v2
"The reliability of atomistic simulations depends on the quality of the
underlying energy models providing the source of physical information, for
instance for the calculation of migration barriers in atomistic Kinetic Monte
Carlo simulations. Accurate (high-fidelity) methods are often available, but
since they are usually computationally expensive, they must be replaced by less
accurate (low-fidelity) models that introduce some degrees of approximation.
Machine-learning techniques such as artificial neural networks are usually
employed to work around this limitation and extract the needed parameters from
large databases of high-fidelity data, but the latter are often computationally
expensive to produce. This work introduces an alternative method based on the
multifidelity approach, where correlations between high-fidelity and
low-fidelity outputs are exploited to make an educated guess of the
high-fidelity outcome based only on quick low-fidelity estimations, hence
without the need of running full expensive high-fidelity calculations. With
respect to neural networks, this approach is expected to require less training
data because of the lower amount of fitting parameters involved. The method is
tested on the prediction of ab initio formation and migration energies of
vacancy diffusion in iron-copper alloys, and compared with the neural networks
trained on the same database."),
Luca Messina, Alessio Quaglino, Alexandra Goryaeva, Mihai-Cosmin Marinica, Christophe Domain, Nicolas Castin, Giovanni Bonny, Rolf Krause,
arXiv: [1808.06935](http://arxiv.org/abs/1808.06935v2),
8/2018

- ["Machine Learning Configuration Interaction"](
http://arxiv.org/abs/1808.05787v1
"We propose the concept of machine learning configuration interaction (MLCI)
whereby an artificial neural network is trained on-the-fly to predict important
new configurations in an iterative selected configuration interaction
procedure. We demonstrate that the neural network can discriminate between
important and unimportant configurations, that it has not been trained on, much
better than by chance. MLCI is then used to find compact wavefunctions for
carbon monoxide at both stretched and equilibrium geometries. We also consider
the multireference problem of the water molecule with elongated bonds. Results
are contrasted with those from other ways of selecting configurations:
first-order perturbation, random selection and Monte Carlo configuration
interaction. Compared with these other serial calculations, this prototype MLCI
is competitive in its accuracy, converges in significantly fewer iterations
than the stochastic approaches, and requires less time for the higher-accuracy
computations."),
J. P. Coe,
arXiv: [1808.05787](http://arxiv.org/abs/1808.05787v1),
8/2018

- ["CosmoFlow: Using Deep Learning to Learn the Universe at Scale"](
http://arxiv.org/abs/1808.04728v1
"Deep learning is a promising tool to determine the physical model that
describes our universe. To handle the considerable computational cost of this
problem, we present CosmoFlow: a highly scalable deep learning application
built on top of the TensorFlow framework. CosmoFlow uses efficient
implementations of 3D convolution and pooling primitives, together with
improvements in threading for many element-wise operations, to improve training
performance on Intel(C) Xeon Phi(TM) processors. We also utilize the Cray PE
Machine Learning Plugin for efficient scaling to multiple nodes. We demonstrate
fully synchronous data-parallel training on 8192 nodes of Cori with 77%
parallel efficiency, achieving 3.5 Pflop/s sustained performance. To our
knowledge, this is the first large-scale science application of the TensorFlow
framework at supercomputer scale with fully-synchronous training. These
enhancements enable us to process large 3D dark matter distribution and predict
the cosmological parameters $\Omega_M$, $\sigma_8$ and n$_s$ with unprecedented
accuracy."),
Amrita Mathuriya, Deborah Bard, Peter Mendygral, Lawrence Meadows, James Arnemann, Lei Shao, Siyu He, Tuomas Karna, Daina Moise, Simon J. Pennycook, Kristyn Maschoff, Jason Sewall, Nalini Kumar, Shirley Ho, Mike Ringenburg, Prabhat, Victor Lee,
arXiv: [1808.04728](http://arxiv.org/abs/1808.04728v1),
8/2018

- ["A machine-learning solver for modified diffusion equations"](
http://arxiv.org/abs/1808.04519v1
"A feed-forward neural network has a remarkable property which allows the
network itself to be a universal approximator for any functions.Here we present
a universal, machine-learning based solver for multi-variable partial
differential equations. The algorithm approximates the target functions by
neural networks and adjusts the network parameters to approach the desirable
solutions.The idea can be easily adopted for dealing with multi-variable,
coupled integrodifferential equations, such as those in the self-consistent
field theory for predicting polymer microphase-separated structures."),
Qianshi Wei, Ying Jiang, Jeff Z. Y. Chen,
arXiv: [1808.04519](http://arxiv.org/abs/1808.04519v1),
8/2018

- ["Model Reduction with Memory and the Machine Learning of Dynamical
  Systems"](
http://arxiv.org/abs/1808.04258v1
"The well-known Mori-Zwanzig theory tells us that model reduction leads to
memory effect. For a long time, modeling the memory effect accurately and
efficiently has been an important but nearly impossible task in developing a
good reduced model. In this work, we explore a natural analogy between
recurrent neural networks and the Mori-Zwanzig formalism to establish a
systematic approach for developing reduced models with memory. Two training
models-a direct training model and a dynamically coupled training model-are
proposed and compared. We apply these methods to the Kuramoto-Sivashinsky
equation and the Navier-Stokes equation. Numerical experiments show that the
proposed method can produce reduced model with good performance on both
short-term prediction and long-term statistical properties."),
Chao Ma, Jianchun Wang, Weinan E,
arXiv: [1808.04258](http://arxiv.org/abs/1808.04258v1),
8/2018

- ["Learning Parameters and Constitutive Relationships with Physics Informed
  Deep Neural Networks"](
http://arxiv.org/abs/1808.03398v2
"We present a physics informed deep neural network (DNN) method for estimating
parameters and unknown physics (constitutive relationships) in partial
differential equation (PDE) models. We use PDEs in addition to measurements to
train DNNs to approximate unknown parameters and constitutive relationships as
well as states. The proposed approach increases the accuracy of DNN
approximations of partially known functions when a limited number of
measurements is available and allows for training DNNs when no direct
measurements of the functions of interest are available. We employ physics
informed DNNs to estimate the unknown space-dependent diffusion coefficient in
a linear diffusion equation and an unknown constitutive relationship in a
non-linear diffusion equation. For the parameter estimation problem, we assume
that partial measurements of the coefficient and states are available and
demonstrate that under these conditions, the proposed method is more accurate
than state-of-the-art methods. For the non-linear diffusion PDE model with a
fully unknown constitutive relationship (i.e., no measurements of constitutive
relationship are available), the physics informed DNN method can accurately
estimate the non-linear constitutive relationship based on state measurements
only. Finally, we demonstrate that the proposed method remains accurate in the
presence of measurement noise."),
Alexandre M. Tartakovsky, Carlos Ortiz Marrero, Paris Perdikaris, Guzel D. Tartakovsky, David Barajas-Solano,
arXiv: [1808.03398](http://arxiv.org/abs/1808.03398v2),
8/2018

- ["Generalized Transfer Matrix States from Artificial Neural Networks"](
http://arxiv.org/abs/1808.02069v1
"Identifying variational wavefunctions that efficiently parametrize the
physically relevant states in the exponentially large Hilbert space is one of
the key tasks towards solving the quantum many-body problem. Powerful tools in
this context such as tensor network states have recently been complemented by
states derived from artificial neural networks (ANNs). Here, we propose and
investigate a new family of quantum states, coined generalized transfer matrix
states (GTMS), which bridges between the two mentioned approaches in the
framework of deep ANNs. In particular, we show by means of a constructive
embedding that the class of GTMS contains generic matrix product states while
at the same time being capable of capturing more long-ranged quantum
correlations that go beyond the area-law entanglement properties of tensor
networks. While generic deep ANNs are hard to contract, meaning that the
corresponding state amplitude can not be exactly evaluated, the GTMS network is
shown to be analytically contractible using transfer matrix methods. With
numerical simulations, we demonstrate how the GTMS network learns random matrix
product states in a supervised learning scheme, and how augmenting the network
by long-ranged couplings leads to the onset of volume-law entanglement scaling.
We argue that this capability of capturing long-range quantum correlations
makes GTMS a promising candidate for the study of critical and dynamical
quantum many-body systems."),
Lorenzo Pastori, Raphael Kaubruegger, Jan Carl Budich,
arXiv: [1808.02069](http://arxiv.org/abs/1808.02069v1),
8/2018

- ["Machine Learning Phase Transition: An Iterative Methodology"](
http://arxiv.org/abs/1808.01731v2
"Machine learning provides new techniques to investigate phase transitions in
physics. Here, we propose an iterative methodology to find the critical
temperature for the two-dimensional Ising model based on machine-learning
techniques. Making use of dimension-reduction algorithm, we obtain the
incipient phase boundaries and labels for some samples which would be used by a
convolutional neural network to find the critical temperature in an iterative
manner. During the finding process, the newly labelled samples would be put in
the training set and the phase boundaries would be updated toward each other.
Meanwhile, the average of the boundaries would converge to the theoretical
value. We also compare the relation between the capability of recognition of
the convolutional neural network and magnetic susceptibility near the critical
point. This work not only offers a methodology to explore unexplored phase
transitions for statistical models but also put forward the motivation to study
the deep connections between statistical physical models and neural networks."),
X. L. Zhao, L. B. Fu,
arXiv: [1808.01731](http://arxiv.org/abs/1808.01731v2),
8/2018

- ["Modelling Non-Markovian Quantum Processes with Recurrent Neural Networks"](
http://arxiv.org/abs/1808.01374v1
"Quantum systems interacting with an unknown environment are notoriously
difficult to model, especially in presence of non-Markovian and
non-perturbative effects. Here we introduce a neural network based approach,
which has the mathematical simplicity of the
Gorini-Kossakowski-Sudarshan-Lindblad master equation, but is able to model
non-Markovian effects in different regimes. This is achieved by using recurrent
neural networks for defining Lindblad operators that can keep track of memory
effects. Building upon this framework, we also introduce a neural network
architecture that is able to reproduce the entire quantum evolution, given an
initial state. As an application we study how to train these models for quantum
process tomography, showing that recurrent neural networks are accurate over
different times and regimes."),
Leonardo Banchi, Edward Grant, Andrea Rocchetto, Simone Severini,
arXiv: [1808.01374](http://arxiv.org/abs/1808.01374v1),
8/2018

- ["From Bloch Oscillations to Many Body Localization in Clean Interacting
  Systems"](
http://arxiv.org/abs/1808.00471v1
"In this work we demonstrate that non-random mechanisms that lead to
single-particle localization may also lead to many-body localization, even in
the absence of disorder. In particular, we consider interacting spins and
fermions in the presence of a linear potential. In the non-interacting limit,
these models show the well known Wannier-Stark localization. We analyze the
fate of this localization in the presence of interactions. Remarkably, we find
that beyond a critical value of the potential gradient, these models exhibit
non-ergodic behavior as indicated by their spectral and dynamical properties.
These models, therefore, constitute a new class of generic non-random models
that fail to thermalize. As such, they suggest new directions for
experimentally exploring and understanding the phenomena of many-body
localization. We supplement our work by showing that by employing machine
learning techniques, the level statistics of a system may be calculated without
generating and diagonalizing the Hamiltonian, which allows a generation of
large statistics."),
Evert P. L. van Nieuwenburg, Yuval Baum, Gil Refael,
arXiv: [1808.00471](http://arxiv.org/abs/1808.00471v1),
8/2018

- ["Unsupervised machine learning for detection of phase transitions in
  off-lattice systems I. Foundations"](
http://arxiv.org/abs/1808.00084v1
"We demonstrate the utility of an unsupervised machine learning tool for the
detection of phase transitions in off-lattice systems. We focus on the
application of principal component analysis (PCA) to detect the freezing
transitions of two-dimensional hard-disk and three-dimensional hard-sphere
systems as well as liquid-gas phase separation in a patchy colloid model. As we
demonstrate, PCA autonomously discovers order-parameter-like quantities that
report on phase transitions, mitigating the need for a priori construction or
identification of a suitable order parameter--thus streamlining the routine
analysis of phase behavior. In a companion paper, we further develop the method
established here to explore the detection of phase transitions in various model
systems controlled by compositional demixing, liquid crystalline ordering, and
non-equilibrium active forces."),
R. B. Jadrich, B. A. Lindquist, T. M. Truskett,
arXiv: [1808.00084](http://arxiv.org/abs/1808.00084v1),
7/2018

- ["Backflow Transformations via Neural Networks for Quantum Many-Body
  Wave-Functions"](
http://arxiv.org/abs/1807.10770v1
"Obtaining an accurate ground state wave function is one of the great
challenges in the quantum many-body problem. In this paper, we propose a new
class of wave functions, neural network backflow (NNB). The backflow approach,
pioneered originally by Feynman, adds correlation to a mean-field ground state
by transforming the single-particle orbitals in a configuration-dependent way.
NNB uses a feed-forward neural network to find the optimal transformation. NNB
directly dresses a mean-field state, can be systematically improved and
directly alters the sign structure of the wave-function. It generalizes the
standard backflow which we show how to explicitly represent as a NNB. We
benchmark the NNB on a Hubbard model at intermediate doping finding that it
significantly decreases the relative error, restores the symmetry of both
observables and single-particle orbitals, and decreases the double-occupancy
density. Finally, we illustrate interesting patterns in the weights and bias of
the optimized neural network."),
Di Luo, Bryan K. Clark,
arXiv: [1807.10770](http://arxiv.org/abs/1807.10770v1),
7/2018

- ["Discovering physical concepts with neural networks"](
http://arxiv.org/abs/1807.10300v1
"The formalism of quantum physics is built upon that of classical mechanics.
In principle, considering only experimental data without prior knowledge could
lead to an alternative quantum formalism without conceptual issues like the
measurement problem. As a first step towards finding such an alternative, we
introduce a neural network architecture that models the physical reasoning
process and can be used to extract physical concepts from experimental data in
an unbiased way. We apply the neural network to a variety of simple physical
examples in classical and quantum mechanics, like damped pendulums,
two-particle collisions, and qubits. The network finds the physically relevant
parameters, exploits conservation laws to make predictions, and can be used to
gain conceptual insights. For example, given a time series of the positions of
the Sun and Mars as observed from Earth, the network discovers the heliocentric
model of the solar system - that is, it encodes the data into the angles of the
two planets as seen from the Sun."),
Raban Iten, Tony Metger, Henrik Wilming, Lidia del Rio, Renato Renner,
arXiv: [1807.10300](http://arxiv.org/abs/1807.10300v1),
7/2018

- ["Fusing numerical relativity and deep learning to detect higher-order
  multipole waveforms from eccentric binary black hole mergers"](
http://arxiv.org/abs/1807.09787v1
"Motivated by recent electromagnetic observations which suggest the existence
of compact binary populations in the Galactic Cluster M22 [Nature 490, 71
(2012)] and in the Galactic center [Nature 556, 70 (2018)], and considering
that eccentricity provides one of the cleanest signatures to identify these
compact binary populations, in this article we study the importance of
including higher-order waveform multipoles to enable gravitational wave
observations of eccentric binary black hole mergers. Using a catalog of
Einstein Toolkit numerical relativity simulations that describe eccentric,
non-spinning black holes mergers with mass-ratios $1\leq q \leq 10$, and
eccentricities $e_0\lesssim0.2$ ten cycles before merger, we determine the
mass-ratio, eccentricity and binary inclination angle combinations that
maximize the contribution of the higher-order waveform multipoles $(\ell, \,
|m|)= \{(2,\,2),\, (2,\,1),\, (3,\,3),\, (3,\,2), \, (3,\,1),\,
(4,\,4),\,(4,\,3),$ $(4,\,2),\,(4,\,1)\}$ for gravitational wave detection. We
then explore the implications of these results in the context of stellar mass
black holes that are detectable by LIGO detectors at design sensitivity, and
show that compared to models that only include the $(\ell, \, |m|)=(2,\,2)$
mode, the inclusion of higher-order waveform multipoles can increase the
signal-to-noise ratio of eccentric binary black hole mergers by up to
$\sim45\%$ for mass-ratio binaries $q\leq10$. Furthermore, building upon our
pioneering deep learning work [George & Huerta Phys. Rev. D 97, 044039 (2018);
George & Huerta Physics Letters B 778, 64 (2018)], we show for the first time
that machine learning can accurately reconstruct higher-order waveform
multipole signals from eccentric binary black hole mergers embedded in real
LIGO data."),
Adam Rebei, E. A. Huerta, Sibo Wang, Sarah Habib, Roland Haas, Daniel Johnson, Daniel George,
arXiv: [1807.09787](http://arxiv.org/abs/1807.09787v1),
7/2018

- ["Solving frustrated quantum many-particle models with convolutional
  neural networks"](
http://arxiv.org/abs/1807.09422v1
"Recently, there has been significant progress in solving quantum
many-particle problem via machine learning based on restricted Boltzmann
machine (RBM). However, it is still highly challenging to solve frustrated
models via machine learning, which has not been demonstrated so far. In this
work, we design a brand new convolutional neural network (CNN) to solve such
quantum many-particle problems. We demonstrate, for the first time, of solving
the highly frustrated spin-1/2 J$_1$-J$_2$ antiferromagnetic Heisenberg model
on square lattices via CNN. The energy per site achieved by the CNN is even
better than previous string-bond-state calculations. Our work therefore open up
a new routine to solve challenging frustrated quantum many-particle problems
using machine learning."),
Xiao Liang, Wen-Yuan Liu, Pei-Ze Lin, Guang-Can Guo, Yong-Sheng Zhang, Lixin He,
arXiv: [1807.09422](http://arxiv.org/abs/1807.09422v1),
7/2018

- ["Machine learning study of the relationship between the geometric and
  entropy discord"](
http://arxiv.org/abs/1807.07470v1
"As an important resource to realize quantum information, quantum correlation
displays different behaviors, freezing phenomenon and non-localization, which
are dissimilar to the entanglement and classical correlation, respectively. In
our setup, the ordering of quantum correlation is represented for different
quantization methods by considering an open quantum system scenario. The
machine learning method (neural network method) is then adopted to train for
the construction of a bridge between the R\`{e}nyi discord ($\alpha=2$) and the
geometric discord (Bures distance) for $X$ form states. Our results clearly
demonstrate that the machine learning method is useful for studying the
differences and commonalities of different quantizing methods of quantum
correlation."),
Xiao-Yu Li, Qin-Sheng Zhu, Ming-Zheng Zhu, Yi-Ming Huang, Hao Wu, Shao-Yi Wu,
arXiv: [1807.07470](http://arxiv.org/abs/1807.07470v1),
7/2018

- ["Local-measurement-based quantum state tomography via neural networks"](
http://arxiv.org/abs/1807.07445v1
"Quantum state tomography is a daunting challenge of experimental quantum
computing even in moderate system size. One way to boost the efficiency of
state tomography is via local measurements on reduced density matrices, but the
reconstruction of the full state thereafter is hard. Here, we present a machine
learning method to recover the full quantum state from its local information,
where a fully-connected neural network is built to fulfill the task with up to
seven qubits. In particular, we test the neural network model with a practical
dataset, that in a 4-qubit nuclear magnetic resonance system our method yields
global states via 2-local information with high accuracy. Our work paves the
way towards scalable state tomography in large quantum systems."),
Tao Xin, Sirui Lu, Ningping Cao, Galit Anikeeva, Dawei Lu, Jun Li, Guilu Long, Bei Zeng,
arXiv: [1807.07445](http://arxiv.org/abs/1807.07445v1),
7/2018

- ["Solving Many-Electron Schrödinger Equation Using Deep Neural Networks"](
http://arxiv.org/abs/1807.07014v2
"We introduce a new family of trial wave-functions based on deep neural
networks to solve the many-electron Sch\"rondinger equation. The Pauli
exclusion principle is dealt with explicitly to ensure that the trial
wave-functions are physical. The optimal trial wave-function is obtained
through variational Monte Carlo and the computational cost scales quadratically
with the number of electrons. The algorithm does not make use of any prior
knowledge such as atomic orbitals. Yet it is able to represent accurately the
ground-states of the tested systems, including He, H2, Be, B, LiH, and a chain
of 10 hydrogen atoms. This opens up new possibilities for solving large-scale
many-electron Schr\"ondinger equation."),
Jiequn Han, Linfeng Zhang, Weinan E,
arXiv: [1807.07014](http://arxiv.org/abs/1807.07014v2),
7/2018

- ["irbasis: Open-source database and software for
  intermediate-representation basis functions of imaginary-time Green's
  function"](
http://arxiv.org/abs/1807.05237v1
"The open-source library, irbasis, provides easy-to-use tools for two sets of
orthogonal functions named intermediate representation (IR). The IR basis
enables a compact representation of the Matsubara Green's function and
efficient calculations of quantum models. The IR basis functions are defined as
the solution of an integral equation whose analytical solution is not available
for this moment. The library consists of a database of pre-computed
high-precision numerical solutions and computational code for evaluating the
functions from the database. This paper describes technical details and
demonstrates how to use the library."),
Naoya Chikano, Kazuyoshi Yoshimi, Junya Otsuki, Hiroshi Shinaoka,
arXiv: [1807.05237](http://arxiv.org/abs/1807.05237v1),
7/2018

- ["Many-body (de)localization in large quantum chains"](
http://arxiv.org/abs/1807.05051v1
"We theoretically study the quench dynamics for an isolated Heisenberg spin
chain with a random on-site magnetic field, which is one of the paradigmatic
models of a many-body localization transition. We use the time-dependent
variational principle as applied to matrix product states, which allows us to
controllably study chains of a length up to $L=100$ spins, i.e., much larger
than $L \simeq 20$ that can be treated via exact diagonalization. For the
analysis of the data, three complementary approaches are used: (i)
determination of the exponent $\beta$ which characterizes the power-law decay
of the antiferromagnetic imbalance with time; (ii) similar determination of the
exponent $\beta_\Lambda$ which characterizes the decay of a Schmidt gap in the
entanglement spectrum, (iii) machine learning with the use, as an input, of the
time dependence of the spin densities in the whole chain. We find that the
consideration of the larger system sizes substantially increases the estimate
for the critical disorder $W_c$ that separates the ergodic and many-body
localized regimes, compared to the values of $W_c$ in the literature. On the
ergodic side of the transition, there is a broad interval of the strength of
disorder with slow subdiffusive transport. In this regime, the exponents
$\beta$ and $\beta_\Lambda$ increase, with increasing $L$, for relatively small
$L$ but saturate for $L \simeq 50$, indicating that these slow power laws
survive in the thermodynamic limit. From a technical perspective, we develop an
adaptation of the ``learning by confusion'' machine learning approach that can
determine $W_c$."),
Elmer V. H. Doggen, Frank Schindler, Konstantin S. Tikhonov, Alexander D. Mirlin, Titus Neupert, Dmitry G. Polyakov, Igor V. Gornyi,
arXiv: [1807.05051](http://arxiv.org/abs/1807.05051v1),
7/2018

- ["Self-learning Monte Carlo method with Behler-Parrinello neural networks"](
http://arxiv.org/abs/1807.04955v1
"Self-learning Monte Carlo method (SLMC) is a general-purpose numerical method
that speeds up Monte Carlo simulations by training an effective model to
propose uncorrelated configurations in the Markov chain. Its applications are,
however, limited. This is because it is not obvious to find the explicit form
of the effective Hamiltonians. Particularly, it is difficult to make effective
Hamiltonians including many body interactions. In order to overcome this
critical difficulty, we introduce the Behler-Parrinello neural networks (BPNNs)
as ``effective Hamiltonian'' without any prior knowledge, which is used to
construct the potential-energy surfaces in interacting many particle systems
for molecular dynamics. We construct self-learning continuous-time
interaction-expansion quantum Monte Carlo method with BPNNs and apply it to
quantum impurity models. We observed significant improvement of the acceptance
ratio from 0.01 (the effective Hamiltonian with the explicit form) to 0.76
(BPNN). This drastic improvement implies that the BPNN effective Hamiltonian
includes many body interaction, which is omitted in the effective Hamiltonian
with the explicit forms. The BPNNs make SLMC more promising."),
Yuki Nagai, Masahiko Okumura, Akinori Tanaka,
arXiv: [1807.04955](http://arxiv.org/abs/1807.04955v1),
7/2018

- ["An introductory example of machine learning enhanced global optimization"](
http://arxiv.org/abs/1807.04605v1
"We show how to speed up global optimization of molecular structures using
machine learning methods. To represent the molecular structures we introduce
the auto-bag feature vector that combines: i) a local feature vector for each
atom, ii) an unsupervised clustering of such feature vectors for many atoms
across several structures, and iii) a count for a given structure of how many
times each cluster is represented. During subsequent global optimization
searches, accumulated structure-energy relations of relaxed structural
candidates are used to assign local energies to each atom using supervised
learning. Specifically, the local energies follow from assigning energies to
each cluster of local feature vectors and demanding the sum of local energies
to amount to the structural energies in the least squares sense. The usefulness
of the method is demonstrated in basin hopping searches for 19-atom structures
described by single- or double-well Lennard- Jones type potentials and for
24-atom carbon structures described by density functional theory (DFT). In all
cases, utilizing the local energy information derived on-the-fly enhances the
rate at which the global minimum energy structure is found."),
Søren A. Meldgaard, Esben L. Kolsbjerg, Bjørk Hammer,
arXiv: [1807.04605](http://arxiv.org/abs/1807.04605v1),
7/2018

- ["Neural networks as "hidden" variable models for quantum systems"](
http://arxiv.org/abs/1807.03910v1
"We successfully model the behavior of two-spin systems using neural networks
known as conditional Restricted Boltzmann Machines (cRBMs). The result gives
local "hidden" variable models for product states and entangled states,
including the singlet state used in the EPR-Bohm experiment. Bell's theorem is
circumvented because the state of the system is dependent not only on the
preparation but also on the measurement setup (the detector settings). Though
at first glance counterintuitive, the apparent "retrocausality" in these models
has a historical precedent in the absorber theory of Wheeler and Feynman and an
intuitive analog in the simple AC circuit of an electric guitar."),
Steven Weinstein,
arXiv: [1807.03910](http://arxiv.org/abs/1807.03910v1),
7/2018

- ["Symmetries and many-body excited states with neural-network quantum
  states"](
http://arxiv.org/abs/1807.03325v1
"Artificial neural networks have been recently introduced as a general ansatz
to compactly represent many- body wave functions. In conjunction with
Variational Monte Carlo, this ansatz has been applied to find Hamil- tonian
ground states and their energies. Here we provide extensions of this method to
study properties of ex- cited states, a central task in several many-body
quantum calculations. First, we give a prescription that allows to target
eigenstates of a (nonlocal) symmetry of the Hamiltonian. Second, we give an
algorithm that allows to compute low-lying excited states without symmetries.
We demonstrate our approach with both Restricted Boltzmann machines states and
feedforward neural networks as variational wave-functions. Results are shown
for the one-dimensional spin-1/2 Heisenberg model, and for the one-dimensional
Bose-Hubbard model. When comparing to available exact results, we obtain good
agreement for a large range of excited-states energies. Interestingly, we also
find that deep networks typically outperform shallow architectures for
high-energy states."),
Kenny Choo, Giuseppe Carleo, Nicolas Regnault, Titus Neupert,
arXiv: [1807.03325](http://arxiv.org/abs/1807.03325v1),
7/2018

- ["Interpretable Machine Learning for Inferring the Phase Boundaries in a
  Non-equilibrium System"](
http://arxiv.org/abs/1807.02468v1
"At the heart of much debate is the question whether machine learning is
capable of going beyond black-box modeling of complex physical systems.
  We investigate the generalizing and interpretability properties of learning
algorithms. To this end we use supervised and unsupervised learning to infer
the phase boundaries of the Active Ising Model (AIM) starting from an ensemble
of configurations of the system. We illustrate that unsupervised learning
techniques are powerful at identifying the phase boundaries in the phase space
of control variables, even in situations of coexistent phases. It is
demonstrated that supervised learning with neural networks is capable of
learning the characteristics about the phase diagram, such that the obtained
knowledge at a specific set of control variables can be used to trace the phase
boundaries across the phase diagram. In this way we demonstrate that properly
designed supervised learning provides predictive power to regions in the phase
space of control variables that are not included in the training phase of the
algorithm. We show that by scrutinizing the inner workings of the classifier,
we can extract the physically relevant density and magnetization patterns."),
C. Casert, T. Vieijra, J. Nys, J. Ryckebusch,
arXiv: [1807.02468](http://arxiv.org/abs/1807.02468v1),
7/2018



- ["Quantum Codes from Neural Networks"](
http://arxiv.org/abs/1806.08781v1
"We report on the usefulness of using neural networks as a variational state
ansatz for many-body quantum systems in the context of quantum
information-processing tasks. In the neural network state ansatz, the complex
amplitude function of a quantum state is computed by a neural network. The
resulting multipartite entanglement structure captured by this ansatz has
proven rich enough to describe the ground states and unitary dynamics of
various physical systems of interest.
  In the present paper, we supply further evidence for the usefulness of neural
network states to describe multipartite entanglement. We demonstrate that
neural network states are capable of efficiently representing quantum codes for
quantum information transmission and quantum error correction. In particular,
we show that a) neural network states yield quantum codes with a high coherent
information for two important quantum channels, the depolarizing channel and
the dephrasure channel; b) neural network states can be used to represent
absolutely maximally entangled states, a special type of quantum error
correction codes. In both cases, the neural network state ansatz provides an
efficient and versatile means as variational parametrization of these states."),
Johannes Bausch, Felix Leditzky,
arXiv: [1806.08781](http://arxiv.org/abs/1806.08781v1),
6/2018

- ["Analytic continuation via 'domain-knowledge free' machine learning"](
http://arxiv.org/abs/1806.03841v1
"We present a machine-learning approach to a long-standing issue in quantum
many-body physics, namely, analytic continuation. This notorious
ill-conditioned problem of obtaining spectral function from imaginary time
Green's function has been a focus of new method developments for past decades.
Here we demonstrate the usefulness of modern machine-learning techniques
including convolutional neural networks and the variants of stochastic gradient
descent optimiser. Machine-learning continuation kernel is successfully
realized without any 'domain knowledge' and the outstanding performance is
achieved for both insulating and metallic band structure. Our
machine-learning-based approach not only provides the more accurate spectrum
than the conventional methods in terms of peak positions and heights, but is
also more robust against the noise which is the required key feature for any
continuation technique to be successful. Furthermore, its computation speed is
$10^4$ - $10^5$ times faster than maximum entropy method."),
Hongkee Yoon, Jae-Hoon Sim, Myung Joon Han,
arXiv: [1806.03841](http://arxiv.org/abs/1806.03841v1),
6/2018

- ["Machine-learning Skyrmions"](
http://arxiv.org/abs/1806.03749v1
"Principles of machine learning (ML) are applied to models that support
skyrmion phases in two dimensions. Most successful predictions were found when
a convolutional neural network (CNN) layer was inserted as well as several
layers of neural networks. A new training scheme based on features of the input
configuration such as magnetization and spin chirality is introduced to make
reliable predictions on the mixed phases, consisting of either a mixture of
spiral and skyrmions or of skyrmions and ferromagnets. It proved possible to
further train external parameters such as the external magnetic field and
temperature and make reliable predictions on them. The predictive capacity of
the ML continued to apply to configurations that are not generated by the
original Hamiltonian used in the training stage, but a different Hamiltonian
adiabatically connected to the original one."),
Vinit Kumar Singh, Jung Hoon Han,
arXiv: [1806.03749](http://arxiv.org/abs/1806.03749v1),
6/2018

- ["Machine learning of quantum phase transitions"](
http://arxiv.org/abs/1806.00829v1
"Machine learning algorithms provide a new perspective on the study of
physical phenomena. In this paper, we explore the nature of quantum phase
transitions using multi-color convolutional neural-network (CNN) in combination
with quantum Monte Carlo simulations. We propose a method that compresses $d+1$
dimensional space-time configurations to a manageable size and then use them as
the input for a CNN. We test our approach on two models and show that both
continuous and discontinuous quantum phase transitions can be well detected and
characterized. Moreover we show that intermediate phases, which were not
trained, can also be identified using our approach."),
Xiao-Yu Dong, Frank Pollmann, Xue-Feng Zhang,
arXiv: [1806.00829](http://arxiv.org/abs/1806.00829v1),
6/2018

- ["Adversarial quantum circuit learning for pure state approximation"](
http://arxiv.org/abs/1806.00463v1
"Adversarial learning is one of the most successful approaches to modelling
high-dimensional probability distributions from data. The quantum computing
community has recently begun to generalize this idea and to look for potential
applications. In this work, we derive an adversarial algorithm for the problem
of approximating an unknown quantum pure state. Although this could be done on
error-corrected quantum computers, the adversarial formulation enables us to
execute the algorithm on near-term quantum computers. Two ansatz circuits are
optimized in tandem: One tries to approximate the target state, the other tries
to distinguish between target and approximated state. Supported by numerical
simulations, we show that resilient backpropagation algorithms perform
remarkably well in optimizing the two circuits. We use the bipartite
entanglement entropy to design an efficient heuristic for the stopping
criteria. Our approach may find application in quantum state tomography."),
Marcello Benedetti, Edward Grant, Leonard Wossnig, Simone Severini,
arXiv: [1806.00463](http://arxiv.org/abs/1806.00463v1),
6/2018

- ["Automated discovery of characteristic features of phase transitions in
  many-body localization"](
http://arxiv.org/abs/1806.00419v1
"We identify a new "order parameter" for the disorder driven many-body
localization (MBL) transition by leveraging artificial intelligence. This
allows us to pin down the transition, as the point at which the physics changes
qualitatively, from vastly fewer disorder realizations and in an objective and
cleaner way than is possible with the existing zoo of quantities. Contrary to
previous studies, our method is almost entirely unsupervised. A game theoretic
process between neural networks defines an adversarial setup with conflicting
objectives to identify what characteristic features to base efficient
predictions on. This reduces the numerical effort for mapping out the phase
diagram by a factor of ~100x. This approach of automated discovery is
applicable specifically to poorly understood phase transitions and exemplifies
the potential of machine learning assisted research in physics."),
Patrick Huembeli, Alexandre Dauphin, Peter Wittek, Christian Gogolin,
arXiv: [1806.00419](http://arxiv.org/abs/1806.00419v1),
6/2018

- ["Machine learning many-body localization: Search for the elusive
  nonergodic metal"](
http://arxiv.org/abs/1805.12138v1
"The many-body localization transition in isolated quantum systems with a
single-particle mobility edge is an intriguing subject that has not yet been
fully understood. In particular, whether a nonergodic metallic phase associated
with a many-body mobility edge exists or not is under active debate. In this
Letter, we construct a neural network classifier to investigate the existence
of the nonergodic metallic phase in a prototype model using many-body
entanglement spectra as the sole diagnostic. We find that such a classifier is
able to identify with high confidence the nonergodic metallic phase existing
between the many-body localized and the thermal phase. Our neural network based
approach shows how supervised machine learning can be applied not only in
locating phase boundaries, but also in providing a way to definitively examine
the existence of a novel phase whose existence is unclear."),
Yi-Ting Hsu, Xiao Li, Dong-Ling Deng, S. Das Sarma,
arXiv: [1805.12138](http://arxiv.org/abs/1805.12138v1),
5/2018

- ["Deep Learning Topological Invariants of Band Insulators"](
http://arxiv.org/abs/1805.10503v2
"In this work we design and train deep neural networks to predict topological
invariants for one-dimensional four-band insulators in AIII class whose
topological invariant is the winding number, and two-dimensional two-band
insulators in A class whose topological invariant is the Chern number. Given
Hamiltonians in the momentum space as the input, neural networks can predict
topological invariants for both classes with accuracy close to or higher than
90%, even for Hamiltonians whose invariants are beyond the training data set.
Despite the complexity of the neural network, we find that the output of
certain intermediate hidden layers resembles either the winding angle for
models in AIII class or the solid angle (Berry curvature) for models in A
class, indicating that neural networks essentially capture the mathematical
formula of topological invariants. Our work demonstrates the ability of neural
networks to predict topological invariants for complicated models with local
Hamiltonians as the only input, and offers an example that even a deep neural
network is understandable."),
Ning Sun, Jinmin Yi, Pengfei Zhang, Huitao Shen, Hui Zhai,
arXiv: [1805.10503](http://arxiv.org/abs/1805.10503v2),
5/2018

- ["Identifying topological order via unsupervised machine learning"](
http://arxiv.org/abs/1805.05961v1
"Machine learning of topological phase transitions has proven to be
challenging due to their inherent non-local nature. We propose an unsupervised
approach based on diffusion maps that learns topological phase transitions from
raw data without the need of manual feature engineering. Using bare spin
configurations as input, the approach is shown to be capable of classifying
samples of the two-dimensional XY model by winding number and capture the
Berezinskii-Kosterlitz-Thouless transition. We also discuss a connection
between the output of diffusion maps and the eigenstates of a quantum-well
Hamiltonian."),
Joaquin F. Rodriguez-Nieva, Mathias S. Scheurer,
arXiv: [1805.05961](http://arxiv.org/abs/1805.05961v1),
5/2018

- ["Quantum artificial intelligence to simulate many body quantum systems"](
http://arxiv.org/abs/1805.05462v1
"We conduct experimental simulations of many body quantum systems using a
\emph{hybrid} classical-quantum algorithm. In our setup, the wave function of
the transverse field quantum Ising model is represented by a restricted
Boltzmann machine. This neural network is then trained using variational Monte
Carlo assisted by a D-Wave quantum sampler to find the ground state energy. Our
results clearly demonstrate that already the first generation of quantum
computers can be harnessed to tackle non-trivial problems concerning physics of
many body quantum systems."),
Bartłomiej Gardas, Marek M. Rams, Jacek Dziarmaga,
arXiv: [1805.05462](http://arxiv.org/abs/1805.05462v1),
5/2018

- ["Optimal universal learning machines for quantum state discrimination"](
http://arxiv.org/abs/1805.03477v1
"We consider the problem of correctly classifying a given quantum two-level
system (qubit) which is known to be in one of two equally probable quantum
states. We assume that this task should be performed by a quantum machine which
does not have at its disposal a complete classical description of the two
template states, but can only have partial prior information about their level
of purity and mutual orthogonality. Moreover, similarly to the classical
supervised learning paradigm, we assume that the machine can be trained by $n$
qubits prepared in the first template state and by $n$ more qubits prepared in
the second template state. In this situation we are interested in the optimal
process which correctly classifies the input qubit with the largest probability
allowed by quantum mechanics. The problem is studied in its full generality for
a number of different prior information scenarios and for an arbitrary size $n$
of the training data. Finite size corrections around the asymptotic limit
$n\rightarrow \infty$ are also derived."),
Marco Fanizza, Andrea Mari, Vittorio Giovannetti,
arXiv: [1805.03477](http://arxiv.org/abs/1805.03477v1),
5/2018



- ["Multiparameter optimisation of a magneto-optical trap using deep
  learning"](
http://arxiv.org/abs/1805.00654v1
"Many important physical processes have dynamics that are too complex to
completely model analytically. Optimisation of such processes often relies on
intuition, trial-and-error, or the construction of empirical models. Machine
learning based on artificial neural networks has emerged as an efficient means
to develop empirical models of complex systems. We implement a deep artificial
neural network to optimise the magneto-optic cooling and trapping of neutral
atomic ensembles. Cold atomic ensembles have become commonplace in laboratories
around the world, however, many-body interactions give rise to complex dynamics
that preclude precise analytic optimisation of the cooling and trapping
process. The solution identified by machine learning is radically different to
the smoothly varying adiabatic solutions currently used. Despite this, the
solutions vastly outperform best known solutions producing higher optical
densities. This may provide a pathway to a new understanding of the dynamics of
the cooling and trapping processes in cold atomic ensembles."),
Aaron D. Tranter, Harry J. Slatyer, Michael R. Hush, Anthony C. Leung, Jesse L. Everett, Karun V. Paul, Pierre Vernaz-Gris, Ping Koy Lam, Ben C. Buchler, Geoff T. Campbell,
arXiv: [1805.00654](http://arxiv.org/abs/1805.00654v1),
5/2018

- ["Probing Hidden Spin Order with Interpretable Machine Learning"](
http://arxiv.org/abs/1804.08557v1
"Machine learning shows promise for improving our understanding of many-body
problems. Tackling an unsolved problem, or classifying intricate phases,
remains however a daunting task. Building on a recently introduced
interpretable supervised learning scheme, we introduce a generic protocol to
probe and identify nonlinear orientational spin order. We extract the tensorial
order parameter up to rank 6. Moreover, we find that our approach yields
reliable results already for a modest amount of training data and without
knowledge of the exact transition temperature. Our approach may prove useful
for identifying novel spin order and ruling out spurious spin liquid
candidates."),
Jonas Greitemann, Ke Liu, Lode Pollet,
arXiv: [1804.08557](http://arxiv.org/abs/1804.08557v1),
4/2018

- ["Learning non-Higgsable gauge groups in 4D F-theory"](
http://arxiv.org/abs/1804.07296v3
"We apply machine learning techniques to solve a specific classification
problem in 4D F-theory. For a divisor $D$ on a given complex threefold base, we
want to read out the non-Higgsable gauge group on it using local geometric
information near $D$. The input features are the triple intersection numbers
among divisors near $D$ and the output label is the non-Higgsable gauge group.
We use decision tree to solve this problem and achieved 85%-98% out-of-sample
accuracies for different classes of divisors, where the data sets are generated
from toric threefold bases without (4,6) curves. We have explicitly generated a
large number of analytic rules directly from the decision tree and proved a
small number of them. As a crosscheck, we applied these decision trees on bases
with (4,6) curves as well and achieved high accuracies. Additionally, we have
trained a decision tree to distinguish toric (4,6) curves as well. Finally, we
present an application of these analytic rules to reversely construct local
base configurations with interesting gauge groups such as SU(3)."),
Yi-Nan Wang, Zhibai Zhang,
arXiv: [1804.07296](http://arxiv.org/abs/1804.07296v3),
4/2018



- ["A sequential sampling strategy for extreme event statistics in nonlinear
  dynamical systems"](
http://arxiv.org/abs/1804.07240v1
"We develop a method for the evaluation of extreme event statistics associated
with nonlinear dynamical systems, using a small number of samples. From an
initial dataset of design points, we formulate a sequential strategy that
provides the 'next-best' data point (set of parameters) that when evaluated
results in improved estimates of the probability density function (pdf) for a
scalar quantity of interest. The approach utilizes Gaussian process regression
to perform Bayesian inference on the parameter-to-observation map describing
the quantity of interest. We then approximate the desired pdf along with
uncertainty bounds utilizing the posterior distribution of the inferred map.
The 'next-best' design point is sequentially determined through an optimization
procedure that selects the point in parameter space that maximally reduces
uncertainty between the estimated bounds of the pdf prediction. Since the
optimization process utilizes only information from the inferred map it has
minimal computational cost. Moreover, the special form of the metric emphasizes
the tails of the pdf. The method is practical for systems where the
dimensionality of the parameter space is of moderate size, i.e. order O(10). We
apply the method to estimate the extreme event statistics for a very
high-dimensional system with millions of degrees of freedom: an offshore
platform subjected to three-dimensional irregular waves. It is demonstrated
that the developed approach can accurately determine the extreme event
statistics using limited number of samples."),
Mustafa A. Mohamad, Themistoklis P. Sapsis,
arXiv: [1804.07240](http://arxiv.org/abs/1804.07240v1),
4/2018

- ["Method to solve quantum few-body problems with artificial neural
  networks"](
http://arxiv.org/abs/1804.06521v1
"A machine learning technique to obtain the ground states of quantum few-body
systems using artificial neural networks is developed. Bosons in continuous
space are considered and a neural network is optimized in such a way that when
particle positions are input into the network, the ground-state wave function
is output from the network. The method is applied to the Calogero-Sutherland
model in one-dimensional space and Efimov bound states in three-dimensional
space."),
Hiroki Saito,
arXiv: [1804.06521](http://arxiv.org/abs/1804.06521v1),
4/2018

- ["Classicalization Clearly: Quantum Transition into States of Maximal
  Memory Storage Capacity"](
http://arxiv.org/abs/1804.06154v1
"Classicalization is a phenomenon of redistribution of energy - initially
stored in few hard quanta - into the high occupation numbers of the soft modes,
described by a final state that is approximately classical. Using an effective
Hamiltonian, we first show why the transition amplitudes that increase
occupation numbers are exponentially suppressed and how a very special family
of classicalizing theories compensates this suppression. This is thanks to a
large micro-state entropy generated by the emergent gapless modes around the
final classical state. The dressing of the process by the super-soft quanta of
these modes compensates the exponential suppression of the transition
probability. Hence, an unsuppressed classicalization takes place exclusively
into the states of exponentially enhanced memory storage capacity. Next, we
describe this phenomenon in the language of a quantum neural network, in which
the neurons are represented as interconnected quantum modes with gravity-like
negative-energy synaptic connections. We show that upon an injection of energy
in form of a hard quantum stimulus, the network reaches the classicalized state
of exponentially enhanced memory capacity with order one probability. We
construct a simple model in which the transition results into classical states
that carry an area-law micro-state entropy. In this language, a non-Wilsonian
UV-completion of the Standard Model via classicalization implies that above
cutoff energy the theory operates as a brain network that softens the high
energy quanta by bringing itself into the state of a maximal memory capacity. A
similar interpretation applies to black hole formation in particle collision."),
Gia Dvali,
arXiv: [1804.06154](http://arxiv.org/abs/1804.06154v1),
4/2018

- ["Machine learning of phase transitions in the percolation and XY models"](
http://arxiv.org/abs/1804.02709v1
"In this paper, we apply machine learning methods to study phase transitions
in certain statistical mechanical models, whose transitions involve non-local
or topological properties,including site and bond percolations, the XY model
and the generalized XY model.We find that using just one-hidden-layer in a
fully-connected neural network, the percolation transition can be learned and
the data-collapse by using the average output layer gives correct estimate of
the critical exponent $\nu$. We also study the Berezinskii-Kosterlitz-Thouless
transition, which involves binding and unbinding of topological
defects---vortices and anti-vortices, in the classical XY model. As pointed out
by M. Beach, A. Golubeva and R. Melko [Phys. Rev. B {\bf 97}, 045207 (2018)],
using spin orientations (i.e. angles) rather than vortex configuration gives
better results in learning the transition, we thus try alternatively the spin
components as the input information in a convolutional neural network and
verify that this indeed works for learning the transition in the XY model on
both the square and honeycomb lattices. To go beyond the XY model, we apply
also the machine learning methods to the generalized XY model, which consists
of a nematic phase, in addition to the paramagnetic and the quasi-long-range
ferromagnetic phase. We find that the use of spin configurations (either angles
or spin components) works and, additionally, using the histograms of the spin
orientations also works for both the XY model and the generalized XY model in
learning the transition. We use such a feature engineering approach to train
the network to learn the three phases in the generalized XY model. We obtain a
consistent phase diagram from the network trained with only data along the
temperature axis at two particular parameter values, i.e. $\Delta=0$ and
$\Delta=1$."),
Wanzhou Zhang, Jiayu Liu, Tzu-Chieh Wei,
arXiv: [1804.02709](http://arxiv.org/abs/1804.02709v1),
4/2018

- ["Complex energy landscapes in spiked-tensor and simple glassy models:
  ruggedness, arrangements of local minima and phase transitions"](
http://arxiv.org/abs/1804.02686v1
"We study rough high-dimensional landscapes in which an increasingly stronger
preference for a given configuration emerges. Such energy landscapes arise in
glass physics and inference. In particular we focus on random Gaussian
functions, and on the spiked-tensor model and generalizations. We thoroughly
analyze the statistical properties of the corresponding landscapes and
characterize the associated geometrical phase transitions. In order to perform
our study, we develop a framework based on the Kac-Rice method that allows to
compute the complexity of the landscape, i.e. the logarithm of the typical
number of stationary points and their Hessian. This approach generalizes the
one used to compute rigorously the annealed complexity of mean-field glass
models. We discuss its advantages with respect to previous frameworks, in
particular the thermodynamical replica method which is shown to lead to
partially incorrect predictions."),
Valentina Ros, Gerard Ben Arous, Giulio Biroli, Chiara Cammarota,
arXiv: [1804.02686](http://arxiv.org/abs/1804.02686v1),
4/2018

- ["Smallest Neural Network to Learn the Ising Criticality"](
http://arxiv.org/abs/1804.02171v1
"Learning with an artificial neural network encodes the system behavior in a
feed-forward function with a number of parameters optimized by data-driven
training. An open question is whether one can minimize the network complexity
without loss of performance to reveal how and why it works. Here we investigate
the learning of the phase transition in the Ising model and find that having
two hidden neurons can be enough for an accurate prediction of critical
temperature. We show that the networks learn the scaling dimension of the order
parameter while being trained as a phase classifier, explaining why the trained
network works universally for different lattices of the same criticality."),
Dongkyu Kim, Dong-Hee Kim,
arXiv: [1804.02171](http://arxiv.org/abs/1804.02171v1),
4/2018

- ["Learning quantum models from quantum or classical data"](
http://arxiv.org/abs/1803.11278v2
"We propose to generalise classical maximum likelihood learning to density
matrices. As the objective function, we propose a quantum likelihood that is
related to the cross entropy between density matrices. We apply this learning
criterion to the quantum Boltzmann machine (QBM), previously proposed by
\cite{amin2016quantum}. We demonstrate for the first time learning a quantum
Hamiltonian from quantum statistics. For the anti-ferromagnetic Heisenberg and
XYZ model we recover the true ground state wave function and Hamiltonian. The
second contribution is to apply quantum learning to learn from classical data.
Quantum learning uses in addition to the classical statistics also quantum
statistics for learning. These statistics may violate the Bell inequality, as
in the quantum case. Maximizing the quantum likelihood yields results that are
significantly more accurate than the classical maximum likelihood approach in
several cases. We give an example how the QBM can learn a strongly non-linear
problem such as the parity problem. The solution shows entanglement, quantified
by the entanglement entropy."),
Hilbert J Kappen,
arXiv: [1803.11278](http://arxiv.org/abs/1803.11278v2),
3/2018


- ["Extrapolating quantum observables with machine learning: Inferring
  multiple phase transitions from properties of a single phase"](
http://arxiv.org/abs/1803.08195v2
"We present a machine-learning method for predicting sharp transitions in a
Hamiltonian phase diagram by extrapolating the properties of quantum systems.
The method is based on Gaussian Process regression with a combination of
kernels chosen through an iterative procedure maximizing the predicting power
of the kernels. The method is capable of extrapolating across the transition
lines. The calculations within a given phase can be used to predict not only
the closest sharp transition, but also a transition removed from the available
data by a separate phase. This makes the present method particularly valuable
for searching phase transitions in the parts of the parameter space that cannot
be probed experimentally or theoretically."),
Rodrigo A. Vargas-Hernández, John Sous, Mona Berciu, Roman V. Krems,
arXiv: [1803.08195](http://arxiv.org/abs/1803.08195v2),
3/2018


- ["Universal Quantum Control through Deep Reinforcement Learning"](
http://arxiv.org/abs/1803.01857v2
"Emerging reinforcement learning techniques using deep neural networks have
shown great promise in control optimization. They harness non-local
regularities of noisy control trajectories and facilitate transfer learning
between tasks. To leverage these powerful capabilities for quantum control
optimization, we propose a new control framework to simultaneously optimize the
speed and fidelity of quantum computation against both leakage and stochastic
control errors. For a broad family of two-qubit unitary gates that are
important for quantum simulation of many-electron systems, we improve the
control robustness by adding control noise into training environments for
reinforcement learning agents trained with trusted-region-policy-optimization.
The agent control solutions demonstrate a two-order-of-magnitude reduction in
average-gate-error over baseline stochastic-gradient-descent solutions and up
to a one-order-of-magnitude reduction in gate time from optimal gate synthesis
counterparts."),
Murphy Yuezhen Niu, Sergio Boixo, Vadim Smelyanskiy, Hartmut Neven,
arXiv: [1803.01857](http://arxiv.org/abs/1803.01857v2),
3/2018


- ["Deep Learning Phase Segregation"](
http://arxiv.org/abs/1803.08993v1
"Phase segregation, the process by which the components of a binary mixture
spontaneously separate, is a key process in the evolution and design of many
chemical, mechanical, and biological systems. In this work, we present a
data-driven approach for the learning, modeling, and prediction of phase
segregation. A direct mapping between an initially dispersed, immiscible binary
fluid and the equilibrium concentration field is learned by conditional
generative convolutional neural networks. Concentration field predictions by
the deep learning model conserve phase fraction, correctly predict phase
transition, and reproduce area, perimeter, and total free energy distributions
up to 98% accuracy."),
Amir Barati Farimani, Joseph Gomes, Rishi Sharma, Franklin L. Lee, Vijay S. Pande,
arXiv: [1803.08993](http://arxiv.org/abs/1803.08993v1),
3/2018

- ["A high-bias, low-variance introduction to Machine Learning for
  physicists"](
http://arxiv.org/abs/1803.08823v1
"Machine Learning (ML) is one of the most exciting and dynamic areas of modern
research and application. The purpose of this review is to provide an
introduction to the core concepts and tools of machine learning in a manner
easily understood and intuitive to physicists. The review begins by covering
fundamental concepts in ML and modern statistics such as the bias-variance
tradeoff, overfitting, regularization, and generalization before moving on to
more advanced topics in both supervised and unsupervised learning. Topics
covered in the review include ensemble models, deep learning and neural
networks, clustering and data visualization, energy-based models (including
MaxEnt models and Restricted Boltzmann Machines), and variational methods.
Throughout, we emphasize the many natural connections between ML and
statistical physics. A notable aspect of the review is the use of Python
notebooks to introduce modern ML/statistical packages to readers using
physics-inspired datasets (the Ising Model and Monte-Carlo simulations of
supersymmetric decays of proton-proton collisions). We conclude with an
extended outlook discussing possible uses of machine learning for furthering
our understanding of the physical world as well as open problems in ML where
physicists maybe able to contribute. (Notebooks are available at
https://physics.bu.edu/~pankajm/MLnotebooks.html )"),
Pankaj Mehta, Marin Bukov, Ching-Hao Wang, Alexandre G. R. Day, Clint Richardson, Charles K. Fisher, David J. Schwab,
arXiv: [1803.08823](http://arxiv.org/abs/1803.08823v1),
3/2018


- ["Parameter diagnostics of phases and phase transition learning by neural
  networks"](
http://arxiv.org/abs/1802.09876v1
"We present an analysis of neural network-based machine learning schemes for
phases and phase transitions in theoretical condensed matter research, focusing
on neural networks with a single hidden layer. Such shallow neural networks
were previously found to be efficient in classifying phases and locating phase
transitions of various basic model systems. In order to rationalize the
emergence of the classification process and for identifying any underlying
physical quantities, it is feasible to examine the weight matrices and the
convolutional filter kernels that result from the learning process of such
shallow networks. Furthermore, we demonstrate how the learning-by-confusing
scheme can be used, in combination with a simple threshold-value classification
method, to diagnose the learning parameters of neural networks. In particular,
we study the classification process of both fully-connected and convolutional
neural networks for the two-dimensional Ising model with extended domain wall
configurations included in the low-temperature regime. Moreover, we consider
the two-dimensional XY model and contrast the performance of the
learning-by-confusing scheme and convolutional neural networks trained on bare
spin configurations to the case of preprocessed samples with respect to vortex
configurations. We discuss these findings in relation to similar recent
investigations and possible further applications."),
Philippe Suchsland, Stefan Wessel,
arXiv: [1802.09876](http://arxiv.org/abs/1802.09876v1),
2/2018

- ["Advantages of versatile neural-network decoding for topological codes"](
http://arxiv.org/abs/1802.08680v1
"Finding optimal correction of errors in generic stabilizer codes is a
computationally hard problem, even for simple noise models. While this task can
be simplified for codes with some structure, such as topological stabilizer
codes, developing good and efficient decoders still remains a challenge. In our
work, we systematically study a very versatile class of decoders based on
feedforward neural networks. To demonstrate adaptability, we apply neural
decoders to the triangular color and toric codes under various noise models
with realistic features, such as spatially-correlated errors. We report that
neural decoders provide significant improvement over leading efficient decoders
in terms of the error-correction threshold. Using neural networks simplifies
the process of designing well-performing decoders, and does not require prior
knowledge of the underlying noise model."),
Nishad Maskara, Aleksander Kubica, Tomas Jochym-O'Connor,
arXiv: [1802.08680](http://arxiv.org/abs/1802.08680v1),
2/2018

- ["Reinforcement Learning with Neural Networks for Quantum Feedback"](
http://arxiv.org/abs/1802.05267v1
"Artificial neural networks are revolutionizing science. While the most
prevalent technique involves supervised training on queries with a known
correct answer, more advanced challenges often require discovering answers
autonomously. In reinforcement learning, control strategies are improved
according to a reward function. The power of this approach has been highlighted
by spectactular recent successes, such as playing Go. So far, it has remained
an open question whether neural-network-based reinforcement learning can be
successfully applied in physics. Here, we show how to use this method for
finding quantum feedback schemes, where a network-based "agent" interacts with
and occasionally decides to measure a quantum system. We illustrate the utility
by finding gate sequences that preserve the quantum information stored in a
small collection of qubits against noise. This specific application will help
to find hardware-adapted feedback schemes for small quantum modules while
demonstrating more generally the promise of neural-network based reinforcement
learning in physics."),
Thomas Fösel, Petru Tighineanu, Talitha Weiss, Florian Marquardt,
arXiv: [1802.05267](https://arxiv.org/abs/1802.05267v2),
2/2018

- ["Online Learning of Quantum States"](
http://arxiv.org/abs/1802.09025v1
"Suppose we have many copies of an unknown $n$-qubit state $\rho$. We measure
some copies of $\rho$ using a known two-outcome measurement $E_{1}$, then other
copies using a measurement $E_{2}$, and so on. At each stage $t$, we generate a
current hypothesis $\sigma_{t}$ about the state $\rho$, using the outcomes of
the previous measurements. We show that it is possible to do this in a way that
guarantees that $|\operatorname{Tr}(E_{i} \sigma_{t}) -
\operatorname{Tr}(E_{i}\rho) |$, the error in our prediction for the next
measurement, is at least $\varepsilon$ at most $\operatorname{O}\!\left(n /
\varepsilon^2 \right) $ times. Even in the "non-realizable" setting---where
there could be arbitrary noise in the measurement outcomes---we show how to
output hypothesis states that do significantly worse than the best possible
states at most $\operatorname{O}\!\left(\sqrt {Tn}\right) $ times on the first
$T$ measurements. These results generalize a 2007 theorem by Aaronson on the
PAC-learnability of quantum states, to the online and regret-minimization
settings. We give three different ways to prove our results---using convex
optimization, quantum postselection, and sequential fat-shattering
dimension---which have different advantages in terms of parameters and
portability."),
Scott Aaronson, Xinyi Chen, Elad Hazan, Ashwin Nayak,
arXiv: [1802.09025](http://arxiv.org/abs/1802.09025v1),
2/2018


- ["Deep neural decoders for near term fault-tolerant experiments"](
http://arxiv.org/abs/1802.06441v1
"Finding efficient decoders for quantum error correcting codes adapted to
realistic experimental noise in fault-tolerant devices represents a significant
challenge. In this paper we introduce several decoding algorithms complemented
by deep neural decoders and apply them to analyze several fault-tolerant error
correction protocols such as the surface code as well as Steane and Knill error
correction. Our methods require no knowledge of the underlying noise model
afflicting the quantum device making them appealing for real-world experiments.
Our analysis is based on a full circuit-level noise model. It considers both
distance-three and five codes, and is performed near the codes pseudo-threshold
regime. Training deep neural decoders in low noise rate regimes appears to be a
challenging machine learning endeavour. We provide a detailed description of
our neural network architectures and training methodology. We then discuss both
the advantages and limitations of deep neural decoders. Lastly, we provide a
rigorous analysis of the decoding runtime of trained deep neural decoders and
compare our methods with anticipated gate times in future quantum devices.
Given the broad applications of our decoding schemes, we believe that the
methods presented in this paper could have practical applications for near term
fault-tolerant experiments."),
Christopher Chamberland, Pooya Ronagh,
arXiv: [1802.06441](http://arxiv.org/abs/1802.06441v1),
2/2018

- ["Neural Network Renormalization Group"](
http://arxiv.org/abs/1802.02840v1
"We present a variational renormalization group approach using deep generative
model composed of bijectors. The model can learn hierarchical transformations
between physical variables and renormalized collective variables. It can
directly generate statistically independent physical configurations by
iterative refinement at various length scales. The generative model has an
exact and tractable likelihood, which provides renormalized energy function of
the collective variables and supports unbiased rejection sampling of the
physical variables. To train the neural network, we employ probability density
distillation, in which the training loss is a variational upper bound of the
physical free energy. The approach could be useful for automatically
identifying collective variables and effective field theories."),
Shuo-Hui Li, Lei Wang,
arXiv: [1802.02840](http://arxiv.org/abs/1802.02840v1),
2/2018

- ["Deep UQ: Learning deep neural network surrogate models for high
  dimensional uncertainty quantification"](
http://arxiv.org/abs/1802.00850v1
"State-of-the-art computer codes for simulating real physical systems are
often characterized by a vast number of input parameters. Performing
uncertainty quantification (UQ) tasks with Monte Carlo (MC) methods is almost
always infeasible because of the need to perform hundreds of thousands or even
millions of forward model evaluations in order to obtain convergent statistics.
One, thus, tries to construct a cheap-to-evaluate surrogate model to replace
the forward model solver. For systems with large numbers of input parameters,
one has to deal with the curse of dimensionality - the exponential increase in
the volume of the input space, as the number of parameters increases linearly.
In this work, we demonstrate the use of deep neural networks (DNN) to construct
surrogate models for numerical simulators. We parameterize the structure of the
DNN in a manner that lends the DNN surrogate the interpretation of recovering a
low dimensional nonlinear manifold. The model response is a parameterized
nonlinear function of the low dimensional projections of the input. We think of
this low dimensional manifold as a nonlinear generalization of the notion of
the active subspace. Our approach is demonstrated with a problem on uncertainty
propagation in a stochastic elliptic partial differential equation (SPDE) with
uncertain diffusion coefficient. We deviate from traditional formulations of
the SPDE problem by not imposing a specific covariance structure on the random
diffusion coefficient. Instead, we attempt to solve a more challenging problem
of learning a map between an arbitrary snapshot of the diffusion field and the
response."),
Rohit Tripathy, Ilias Bilionis,
arXiv: [1802.00850](http://arxiv.org/abs/1802.00850v1),
2/2018

- ["Experimentally detecting a quantum change point via Bayesian inference"](
http://arxiv.org/abs/1801.07508v1
"Detecting a change point is a crucial task in statistics that has been
recently extended to the quantum realm. A source state generator that emits a
series of single photons in a default state suffers an alteration at some point
and starts to emit photons in a mutated state. The problem consists in
identifying the point where the change took place. In this work, we consider a
learning agent that applies Bayesian inference on experimental data to solve
this problem. This learning machine adjusts the measurement over each photon
according to the past experimental results finds the change position in an
online fashion. Our results show that the local-detection success probability
can be largely improved by using such a machine learning technique. This
protocol provides a tool for improvement in many applications where a sequence
of identical quantum states is required."),
Shang Yu, Chang-Jiang Huang, Jian-Shun Tang, Zhih-Ahn Jia, Yi-Tao Wang, Zhi-Jin Ke, Wei Liu, Xiao Liu, Zong-Quan Zhou, Ze-Di Cheng, Jin-Shi Xu, Yu-Chun Wu, Yuan-Yuan Zhao, Guo-Yong Xiang, Chuan-Feng Li, Guang-Can Guo, Gael Sentís, Ramon Muñoz-Tapia,
arXiv: [1801.07508](http://arxiv.org/abs/1801.07508v1),
1/2018

- ["Generative Models for Stochastic Processes Using Convolutional Neural
  Networks"](
http://arxiv.org/abs/1801.03523v1
"The present paper aims to demonstrate the usage of Convolutional Neural
Networks as a generative model for stochastic processes, enabling researchers
from a wide range of fields (such as quantitative finance and physics) to
develop a general tool for forecasts and simulations without the need to
identify/assume a specific system structure or estimate its parameters."),
Fernando Fernandes Neto,
arXiv: [1801.03523](http://arxiv.org/abs/1801.03523v1),
1/2018

- ["Pattern recognition techniques for Boson Sampling validation"](
http://arxiv.org/abs/1712.06863v1
"The difficulty of validating large-scale quantum devices, such as Boson
Samplers, poses a major challenge for any research program that aims to show
quantum advantages over classical hardware. To address this problem, we propose
a novel data-driven approach wherein models are trained to identify common
pathologies using unsupervised machine learning methods. We illustrate this
idea by training a classifier that exploits K-means clustering to distinguish
between Boson Samplers that use indistinguishable photons from those that do
not. We train the model on numerical simulations of small-scale Boson Samplers
and then validate the pattern recognition technique on larger numerical
simulations as well as on photonic chips in both traditional Boson Sampling and
scattershot experiments. The effectiveness of such method relies on
particle-type-dependent internal correlations present in the output
distributions. This approach performs substantially better on the test data
than previous methods and underscores the ability to further generalize its
operation beyond the scope of the examples that it was trained on."),
Iris Agresti, Niko Viggianiello, Fulvio Flamini, Nicolò Spagnolo, Andrea Crespi, Roberto Osellame, Nathan Wiebe, Fabio Sciarrino,
arXiv: [1712.06863](http://arxiv.org/abs/1712.06863v1),
12/2017

- ["Towards reduction of autocorrelation in HMC by machine learning"](
http://arxiv.org/abs/1712.03893v1
"In this paper we propose new algorithm to reduce autocorrelation in Markov
chain Monte-Carlo algorithms for euclidean field theories on the lattice. Our
proposing algorithm is the Hybrid Monte-Carlo algorithm (HMC) with restricted
Boltzmann machine. We examine the validity of the algorithm by employing the
phi-fourth theory in three dimension. We observe reduction of the
autocorrelation both in symmetric and broken phase as well. Our proposing
algorithm provides consistent central values of expectation values of the
action density and one-point Green's function with ones from the original HMC
in both the symmetric phase and broken phase within the statistical error. On
the other hand, two-point Green's functions have slight difference between one
calculated by the HMC and one by our proposing algorithm in the symmetric
phase. Furthermore, near the criticality, the distribution of the one-point
Green's function differs from the one from HMC. We discuss the origin of
discrepancies and its improvement."),
Akinori Tanaka, Akio Tomiya,
arXiv: [1712.03893](http://arxiv.org/abs/1712.03893v1),
12/2017

- ["Deep Neural Network Detects Quantum Phase Transition"](
http://arxiv.org/abs/1712.00371v1
"We detect the quantum phase transition of a quantum many-body system by
mapping the observed results of the quantum state onto a neural network. In the
present study, we utilized the simplest case of a quantum many-body system,
namely a one-dimensional chain of Ising spins with the transverse Ising model.
We prepared several spin configurations, which were obtained using repeated
observations of the model for a particular strength of the transverse field, as
input data for the neural network. Although the proposed method can be employed
using experimental observations of quantum many-body systems, we tested our
technique with spin configurations generated by a quantum Monte Carlo
simulation without initial relaxation. The neural network successfully
classified the strength of transverse field only from the spin configurations,
leading to consistent estimations of the critical point of our model $\Gamma_c
=J$."),
Shunta Arai, Masayuki Ohzeki, Kazuyuki Tanaka,
arXiv: [1712.00371](http://arxiv.org/abs/1712.00371v1),
12/2017

- ["Experimental learning of quantum states"](
http://arxiv.org/abs/1712.00127v1
"The number of parameters describing a quantum state is well known to grow
exponentially with the number of particles. This scaling clearly limits our
ability to do tomography to systems with no more than a few qubits and has been
used to argue against the universal validity of quantum mechanics itself.
However, from a computational learning theory perspective, it can be shown
that, in a probabilistic setting, quantum states can be approximately learned
using only a linear number of measurements. Here we experimentally demonstrate
this linear scaling in optical systems with up to 6 qubits. Our results
highlight the power of computational learning theory to investigate quantum
information, provide the first experimental demonstration that quantum states
can be "probably approximately learned" with access to a number of copies of
the state that scales linearly with the number of qubits, and pave the way to
probing quantum states at new, larger scales."),
Andrea Rocchetto, Scott Aaronson, Simone Severini, Gonzalo Carvacho, Davide Poderini, Iris Agresti, Marco Bentivegna, Fabio Sciarrino,
arXiv: [1712.00127](http://arxiv.org/abs/1712.00127v1),
11/2017

- ["Machine learning vortices at the Kosterlitz-Thouless transition"](
http://arxiv.org/abs/1710.09842v1
"Efficient and automated classification of phases from minimally processed
data is one goal of machine learning in condensed matter and statistical
physics. Supervised algorithms trained on raw samples of microstates can
successfully detect conventional phase transitions via learning a bulk feature
such as an order parameter. In this paper, we investigate whether neural
networks can learn to classify phases based on topological defects. We address
this question on the two-dimensional classical XY model which exhibits a
Kosterlitz-Thouless transition. We find significant feature engineering of the
raw spin states is required to convincingly claim that features of the vortex
configurations are responsible for learning the transition temperature. We
further show a single-layer network does not correctly classify the phases of
the XY model, while a convolutional network easily performs classification by
learning the global magnetization. Finally, we design a deep network capable of
learning vortices without feature engineering. We demonstrate the detection of
vortices does not necessarily result in the best classification accuracy,
especially for lattices of less than approximately 1000 spins. For larger
systems, it remains a difficult task to learn vortices."),
Matthew J. S. Beach, Anna Golubeva, Roger G. Melko,
arXiv: [1710.09842](http://arxiv.org/abs/1710.09842v1),
10/2017

- ["Machine learning out-of-equilibrium phases of matter"](
http://arxiv.org/abs/1711.00020v1
"Neural network based machine learning is emerging as a powerful tool for
obtaining phase diagrams when traditional regression schemes using local
equilibrium order parameters are not available, as in many-body localized or
topological phases. Nevertheless, instances of machine learning offering new
insights have been rare up to now. Here we show that a single feed-forward
neural network can decode the defining structures of two distinct MBL phases
and a thermalizing phase, using entanglement spectra obtained from individual
eigenstates. For this, we introduce a simplicial geometry based method for
extracting multi-partite phase boundaries. We find that this method outperforms
conventional metrics (like the entanglement entropy) for identifying MBL phase
transitions, revealing a sharper phase boundary and shedding new insight into
the topology of the phase diagram. Furthermore, the phase diagram we acquire
from a single disorder configuration confirms that the machine-learning based
approach we establish here can enable speedy exploration of large phase spaces
that can assist with the discovery of new MBL phases. To our knowledge this
work represents the first example of a machine learning approach revealing new
information beyond conventional knowledge."),
Jordan Venderley, Vedika Khemani, Eun-Ah Kim,
arXiv: [1711.00020](http://arxiv.org/abs/1711.00020v1),
10/2017

- ["Learning hard quantum distributions with variational autoencoders"](
http://arxiv.org/abs/1710.00725v1
"Studying general quantum many-body systems is one of the major challenges in
modern physics because it requires an amount of computational resources that
scales exponentially with the size of the system.Simulating the evolution of a
state, or even storing its description, rapidly becomes intractable for exact
classical algorithms. Recently, machine learning techniques, in the form of
restricted Boltzmann machines, have been proposed as a way to efficiently
represent certain quantum states with applications in state tomography and
ground state estimation. Here, we introduce a new representation of states
based on variational autoencoders. Variational autoencoders are a type of
generative model in the form of a neural network. We probe the power of this
representation by encoding probability distributions associated with states
from different classes. Our simulations show that deep networks give a better
representation for states that are hard to sample from, while providing no
benefit for random states. This suggests that the probability distributions
associated to hard quantum states might have a compositional structure that can
be exploited by layered neural networks. Specifically, we consider the
learnability of a class of quantum states introduced by Fefferman and Umans.
Such states are provably hard to sample for classical computers, but not for
quantum ones, under plausible computational complexity assumptions. The good
level of compression achieved for hard states suggests these methods can be
suitable for characterising states of the size expected in first generation
quantum hardware."),
Andrea Rocchetto, Edward Grant, Sergii Strelchuk, Giuseppe Carleo, Simone Severini,
arXiv: [1710.00725](http://arxiv.org/abs/1710.00725v1),
10/2017

- ["Combining Machine Learning and Physics to Understand Glassy Systems"](
http://arxiv.org/abs/1709.08015v1
"Our understanding of supercooled liquids and glasses has lagged significantly
behind that of simple liquids and crystalline solids. This is in part due to
the many possibly relevant degrees of freedom that are present due to the
disorder inherent to these systems and in part to non-equilibrium effects which
are difficult to treat in the standard context of statistical physics. Together
these issues have resulted in a field whose theories are under-constrained by
experiment and where fundamental questions are still unresolved. Mean field
results have been successful in infinite dimensions but it is unclear to what
extent they apply to realistic systems and assume uniform local structure. At
odds with this are theories premised on the existence of structural defects.
However, until recently it has been impossible to find structural signatures
that are predictive of dynamics. Here we summarize and recast the results from
several recent papers offering a data driven approach to building a
phenomenological theory of disordered materials by combining machine learning
with physical intuition."),
Samuel S. Schoenholz,
arXiv: [1709.08015](http://arxiv.org/abs/1709.08015v1),
9/2017



- ["By-passing the Kohn-Sham equations with machine learning"](
http://arxiv.org/abs/1609.02815v3
"Last year, at least 30,000 scientific papers used the Kohn-Sham scheme of
density functional theory to solve electronic structure problems in a wide
variety of scientific fields, ranging from materials science to biochemistry to
astrophysics. Machine learning holds the promise of learning the kinetic energy
functional via examples, by-passing the need to solve the Kohn-Sham equations.
This should yield substantial savings in computer time, allowing either larger
systems or longer time-scales to be tackled, but attempts to machine-learn this
functional have been limited by the need to find its derivative. The present
work overcomes this difficulty by directly learning the density-potential and
energy-density maps for test systems and various molecules. Both improved
accuracy and lower computational cost with this method are demonstrated by
reproducing DFT energies for a range of molecular geometries generated during
molecular dynamics simulations. Moreover, the methodology could be applied
directly to quantum chemical calculations, allowing construction of density
functionals of quantum-chemical accuracy."),
Felix Brockherde, Leslie Vogt, Li Li, Mark E. Tuckerman, Kieron Burke, Klaus-Robert Müller,
arXiv: [1609.02815](http://arxiv.org/abs/1609.02815v3),
9/2016

- ["Learning Disordered Topological Phases by Statistical Recovery of
  Symmetry"](
http://arxiv.org/abs/1709.05790v2
"In this letter, we apply the artificial neural network in a supervised manner
to map out the quantum phase diagram of disordered topological superconductor
in class DIII. Given the disorder that keeps the discrete symmetries of the
ensemble as a whole, translational symmetry which is broken in the
quasiparticle distribution individually is recovered statistically by taking an
ensemble average. By using this, we classify the phases by the artificial
neural network that learned the quasiparticle distribution in the clean limit,
and show that the result is totally consistent with the calculation by the
transfer matrix method or noncommutative geometry approach. If all three
phases, namely the $\mathbb{Z}_2$, trivial, and the thermal metal phases appear
in the clean limit, the machine can classify them with high confidence over the
entire phase diagram. If only the former two phases are present, we find that
the machine remains confused in the certain region, leading us to conclude the
detection of the unknown phase which is eventually identified as the thermal
metal phase. In our method, only the first moment of the quasiparticle
distribution is used for input, but application to a wider variety of systems
is expected by the inclusion of higher moments."),
Nobuyuki Yoshioka, Yutaka Akagi, Hosho Katsura,
arXiv: [1709.05790](http://arxiv.org/abs/1709.05790v2),
9/2017

- ["Restricted-Boltzmann-Machine Learning for Solving Strongly Correlated
  Quantum Systems"](
http://arxiv.org/abs/1709.06475v2
"We develop a machine learning method to construct accurate ground-state wave
functions of strongly interacting and entangled quantum spin as well as
fermionic models on lattices. A restricted Boltzmann machine algorithm in the
form of an artificial neural network is combined with a conventional
variational Monte Carlo method with pair product (geminal) wave functions and
quantum number projections. The combination allows an application of the
machine learning scheme to interacting fermionic systems. The combined method
substantially improves the accuracy beyond that ever achieved by each method
separately, in the Heisenberg as well as Hubbard models on square lattices,
thus proving its power as a highly accurate quantum many-body solver."),
Yusuke Nomura, Andrew S. Darmawan, Youhei Yamaji, Masatoshi Imada,
arXiv: [1709.06475](http://arxiv.org/abs/1709.06475v2),
9/2017

- ["Identifying Product Order with Restricted Boltzmann Machines"](
http://arxiv.org/abs/1709.02597v1
"Unsupervised machine learning via a restricted Boltzmann machine is an useful
tool in distinguishing an ordered phase from a disordered phase. Here we study
its application on the two-dimensional Ashkin-Teller model, which features a
partially ordered product phase. We train the neural network with spin
configuration data generated by Monte Carlo simulations and show that distinct
features of the product phase can be learned from non-ergodic samples resulting
from symmetry breaking. Careful analysis of the weight matrices inspires us to
define a nontrivial machine-learning motivated quantity of the product form,
which resembles the conventional product order parameter."),
Wen-Jia Rao, Zhenyu Li, Qiong Zhu, Mingxing Luo, Xin Wan,
arXiv: [1709.02597](http://arxiv.org/abs/1709.02597v1),
9/2017

- ["Machine learning & artificial intelligence in the quantum domain"](
http://arxiv.org/abs/1709.02779v1
"Quantum information technologies, and intelligent learning systems, are both
emergent technologies that will likely have a transforming impact on our
society. The respective underlying fields of research -- quantum information
(QI) versus machine learning (ML) and artificial intelligence (AI) -- have
their own specific challenges, which have hitherto been investigated largely
independently. However, in a growing body of recent work, researchers have been
probing the question to what extent these fields can learn and benefit from
each other. QML explores the interaction between quantum computing and ML,
investigating how results and techniques from one field can be used to solve
the problems of the other. Recently, we have witnessed breakthroughs in both
directions of influence. For instance, quantum computing is finding a vital
application in providing speed-ups in ML, critical in our "big data" world.
Conversely, ML already permeates cutting-edge technologies, and may become
instrumental in advanced quantum technologies. Aside from quantum speed-up in
data analysis, or classical ML optimization used in quantum experiments,
quantum enhancements have also been demonstrated for interactive learning,
highlighting the potential of quantum-enhanced learning agents. Finally, works
exploring the use of AI for the very design of quantum experiments, and for
performing parts of genuine research autonomously, have reported their first
successes. Beyond the topics of mutual enhancement, researchers have also
broached the fundamental issue of quantum generalizations of ML/AI concepts.
This deals with questions of the very meaning of learning and intelligence in a
world that is described by quantum mechanics. In this review, we describe the
main ideas, recent developments, and progress in a broad spectrum of research
investigating machine learning and artificial intelligence in the quantum
domain."),
Vedran Dunjko, Hans J. Briegel,
arXiv: [1709.02779](http://arxiv.org/abs/1709.02779v1),
9/2017

- ["Phase Diagrams of Three-Dimensional Anderson and Quantum Percolation
  Models using Deep Three-Dimensional Convolutional Neural Network"](
http://arxiv.org/abs/1709.00812v2
"The three-dimensional Anderson model is a well-studied model of disordered
electron systems that shows the delocalization--localization transition. As in
our previous papers on two- and three-dimensional (2D, 3D) quantum phase
transitions [J. Phys. Soc. Jpn. {\bf 85}, 123706 (2016), {\bf 86}, 044708
(2017)], we used an image recognition algorithm based on a multilayered
convolutional neural network. However, in contrast to previous papers in which
2D image recognition was used, we applied 3D image recognition to analyze
entire 3D wave functions. We show that a full phase diagram of the
disorder-energy plane is obtained once the 3D convolutional neural network has
been trained at the band center. We further demonstrate that the full phase
diagram for 3D quantum bond and site percolations can be drawn by training the
3D Anderson model at the band center."),
Tomohiro Mano, Tomi Ohtsuki,
arXiv: [1709.00812](http://arxiv.org/abs/1709.00812v2),
9/2017

- ["Machine Learning Spatial Geometry from Entanglement Features"](
http://arxiv.org/abs/1709.01223v2
"Motivated by the close relations of the renormalization group with both the
holography duality and the deep learning, we propose that the holographic
geometry can emerge from deep learning the entanglement feature of a quantum
many-body state. We develop a concrete algorithm, call the entanglement feature
learning (EFL), based on the random tensor network (RTN) model for the tensor
network holography. We show that each RTN can be mapped to a Boltzmann machine,
trained by the entanglement entropies over all subregions of a given quantum
many-body state. The goal is to construct the optimal RTN that best reproduce
the entanglement feature. The RTN geometry can then be interpreted as the
emergent holographic geometry. We demonstrate the EFL algorithm on 1D free
fermion system and observe the emergence of the hyperbolic geometry (AdS$_3$
spatial geometry) as we tune the fermion system towards the gapless critical
point (CFT$_2$ point)."),
Yi-Zhuang You, Zhao Yang, Xiao-Liang Qi,
arXiv: [1709.01223](http://arxiv.org/abs/1709.01223v2),
9/2017

- ["Machine Learning Topological Invariants with Neural Networks"](
http://arxiv.org/abs/1708.09401v3
"In this Letter we supervisedly train neural networks to distinguish different
topological phases in the context of topological band insulators. After
training with Hamiltonians of one-dimensional insulators with chiral symmetry,
the neural network can predict their topological winding numbers with nearly
100% accuracy, even for Hamiltonians with larger winding numbers that are not
included in the training data. These results show a remarkable success that the
neural network can capture the global and nonlinear topological features of
quantum phases from local inputs. By opening up the neural network, we confirm
that the network does learn the discrete version of the winding number formula.
We also make a couple of remarks regarding the role of the symmetry and the
opposite effect of regularization techniques when applying machine learning to
physical systems."),
Pengfei Zhang, Huitao Shen, Hui Zhai,
arXiv: [1708.09401](http://arxiv.org/abs/1708.09401v3),
8/2017

- ["Extensive deep neural networks"](
http://arxiv.org/abs/1708.06686v1
"We present a procedure for training and evaluating a deep neural network
which can efficiently infer extensive parameters of arbitrarily large systems,
doing so with O(N) complexity. We use a form of domain decomposition for
training and inference, where each sub-domain (tile) is comprised of a
non-overlapping focus region surrounded by an overlapping context region. The
relative sizes of focus and context are physically motivated and depend on the
locality length scale of the problem. Extensive deep neural networks (EDNN) are
a formulation of convolutional neural networks which provide a flexible and
general approach, based on physical constraints, to describe multi-scale
interactions. They are well suited to massively parallel inference, as no
inter-thread communication is necessary during evaluation. Example uses for
learning simple spin models, Laplacian (derivative) operator, and approximating
many-body quantum mechanical operators (within the density functional theory
approach) are demonstrated."),
Iryna Luchak, Kyle Mills, Kevin Ryczko, Adam Domurad, Isaac Tamblyn,
arXiv: [1708.06686](http://arxiv.org/abs/1708.06686v1),
8/2017

- ["Learning Fermionic Critical Points"](
http://arxiv.org/abs/1708.04762v2
"We use determinant Quantum Monte Carlo (DQMC), in combination with the
principal component analysis (PCA) approach to unsupervised learning, to
extract information about phase transitions in several of the most fundamental
Hamiltonians describing strongly correlated materials. We first explore the
zero temperature antiferromagnet to singlet transition in the Periodic Anderson
Model, the Mott insulating transition in the Hubbard model on a honeycomb
lattice, and the magnetic transition in the 1/6-filled Lieb lattice. We then
discuss the prospects for learning finite temperature superconducting
transitions in the attractive Hubbard model, for which there is no sign
problem. Finally, we investigate finite temperature CDW transitions in the
Holstein model, where the electrons are coupled to phonon degrees of freedom.
We examine the different behaviors associated with providing
Hubbard-Stratonovich auxiliary fields configurations on both the entire
space-time lattice and on a single imaginary time slice, or other quantities,
such as equal-time Green's and pair-pair correlation functions."),
Natanael C. Costa, Wenjian Hu, Z. J. Bai, Richard T. Scalettar, Rajiv R. P. Singh,
arXiv: [1708.04762](http://arxiv.org/abs/1708.04762v2),
8/2017

- ["Deep Learning the Ising Model Near Criticality"](
http://arxiv.org/abs/1708.04622v1
"It is well established that neural networks with deep architectures perform
better than shallow networks for many tasks in machine learning. In statistical
physics, while there has been recent interest in representing physical data
with generative modelling, the focus has been on shallow neural networks. A
natural question to ask is whether deep neural networks hold any advantage over
shallow networks in representing such data. We investigate this question by
using unsupervised, generative graphical models to learn the probability
distribution of a two-dimensional Ising system. Deep Boltzmann machines, deep
belief networks, and deep restricted Boltzmann networks are trained on thermal
spin configurations from this system, and compared to the shallow architecture
of the restricted Boltzmann machine. We benchmark the models, focussing on the
accuracy of generating energetic observables near the phase transition, where
these quantities are most difficult to approximate. Interestingly, after
training the generative networks, we observe that the accuracy essentially
depends only on the number of neurons in the first hidden layer of the network,
and not on other model details such as network depth or model type. This is
evidence that shallow networks are more efficient than deep networks at
representing physical probability distributions associated with Ising systems
near criticality."),
Alan Morningstar, Roger G. Melko,
arXiv: [1708.04622](http://arxiv.org/abs/1708.04622v1),
8/2017

- ["Spectral Dynamics of Learning Restricted Boltzmann Machines"](
http://arxiv.org/abs/1708.02917v2
"The Restricted Boltzmann Machine (RBM), an important tool used in machine
learning in particular for unsupervized learning tasks, is investigated from
the perspective of its spectral properties. Starting from empirical
observations, we propose a generic statistical ensemble for the weight matrix
of the RBM and characterize its mean evolution. This let us show how in the
linear regime, in which the RBM is found to operate at the beginning of the
training, the statistical properties of the data drive the selection of the
unstable modes of the weight matrix. A set of equations characterizing the
non-linear regime is then derived, unveiling in some way how the selected modes
interact in later stages of the learning procedure and defining a deterministic
learning curve for the RBM."),
Aurélien Decelle, Giancarlo Fissore, Cyril Furtlehner,
arXiv: [1708.02917](http://arxiv.org/abs/1708.02917v2),
8/2017

- ["Solving the Bose-Hubbard model with machine learning"](
http://arxiv.org/abs/1707.09723v1
"Motivated by the recent successful application of artificial neural networks
to quantum many-body problems [G. Carleo and M. Troyer, Science {\bf 355}, 602
(2017)], a method to calculate the ground state of the Bose-Hubbard model using
a feedforward neural network is proposed. The results are in good agreement
with those obtained by exact diagonalization and the Gutzwiller approximation.
The method of neural-network quantum states is promising for solving quantum
many-body problems of ultracold atoms in optical lattices."),
Hiroki Saito,
arXiv: [1707.09723](http://arxiv.org/abs/1707.09723v1),
7/2017

- ["Quantum dynamics in transverse-field Ising models from classical
  networks"](
http://arxiv.org/abs/1707.06656v4
"The efficient representation of quantum many-body states with classical
resources is a key challenge in quantum many-body theory. In this work we
analytically construct classical networks for the description of the quantum
dynamics in transverse-field Ising models that can be solved efficiently using
Monte Carlo techniques. Our perturbative construction encodes time-evolved
quantum states of spin-1/2 systems in a network of classical spins with local
couplings and can be directly generalized to other spin systems and higher
spins. Using this construction we compute the transient dynamics in one, two,
and three dimensions including local observables, entanglement production, and
Loschmidt amplitudes using Monte Carlo algorithms and demonstrate the accuracy
of this approach by comparisons to exact results. We include a mapping to
equivalent artificial neural networks, which were recently introduced to
provide a universal structure for classical network wave functions."),
Markus Schmitt, Markus Heyl,
arXiv: [1707.06656](http://arxiv.org/abs/1707.06656v4),
7/2017

- ["Learning the Einstein-Podolsky-Rosen correlations on a Restricted
  Boltzmann Machine"](
http://arxiv.org/abs/1707.03114v2
"We construct a hidden variable model for the EPR correlations using a
Restricted Boltzmann Machine. The model reproduces the expected correlations
and thus violates the Bell inequality, as required by Bell's theorem. Unlike
most hidden-variable models, this model does not violate the $locality$
assumption in Bell's argument. Rather, it violates $measurement$
$independence$, albeit in a decidedly non-conspiratorial way."),
Steven Weinstein,
arXiv: [1707.03114](http://arxiv.org/abs/1707.03114v2),
7/2017

- ["Quantum phase recognition via unsupervised machine learning"](
http://arxiv.org/abs/1707.00663v1
"The application of state-of-the-art machine learning techniques to
statistical physic problems has seen a surge of interest for their ability to
discriminate phases of matter by extracting essential features in the many-body
wavefunction or the ensemble of correlators sampled in Monte Carlo simulations.
Here we introduce a gener- alization of supervised machine learning approaches
that allows to accurately map out phase diagrams of inter- acting many-body
systems without any prior knowledge, e.g. of their general topology or the
number of distinct phases. To substantiate the versatility of this approach,
which combines convolutional neural networks with quantum Monte Carlo sampling,
we map out the phase diagrams of interacting boson and fermion models both at
zero and finite temperatures and show that first-order, second-order, and
Kosterlitz-Thouless phase transitions can all be identified. We explicitly
demonstrate that our approach is capable of identifying the phase transition to
non-trivial many-body phases such as superfluids or topologically ordered
phases without supervision."),
Peter Broecker, Fakher F. Assaad, Simon Trebst,
arXiv: [1707.00663](http://arxiv.org/abs/1707.00663v1),
7/2017

- ["Deep neural networks for direct, featureless learning through
  observation: the case of 2d spin models"](
http://arxiv.org/abs/1706.09779v1
"We train a deep convolutional neural network to accurately predict the
energies and magnetizations of Ising model configurations, using both the
traditional nearest-neighbour Hamiltonian, as well as a long-range screened
Coulomb Hamiltonian. We demonstrate the capability of a convolutional deep
neural network in predicting the nearest-neighbour energy of the 4x4 Ising
model. Using its success at this task, we motivate the study of the larger 8x8
Ising model, showing that the deep neural network can learn the
nearest-neighbour Ising Hamiltonian after only seeing a vanishingly small
fraction of configuration space. Additionally, we show that the neural network
has learned both the energy and magnetization operators with sufficient
accuracy to replicate the low-temperature Ising phase transition. Finally, we
teach the convolutional deep neural network to accurately predict a long-range
interaction through a screened Coulomb Hamiltonian. In this case, the benefits
of the neural network become apparent; it is able to make predictions with a
high degree of accuracy, 1600 times faster than a CUDA-optimized "exact"
calculation."),
K. Mills, I. Tamblyn,
arXiv: [1706.09779](http://arxiv.org/abs/1706.09779v1),
6/2017

- ["Inverse Ising inference by combining Ornstein-Zernike theory with deep
  learning"](
http://arxiv.org/abs/1706.08466v1
"Inferring a generative model from data is a fundamental problem in machine
learning. It is well-known that the Ising model is the maximum entropy model
for binary variables which reproduces the sample mean and pairwise
correlations. Learning the parameters of the Ising model from data is the
challenge. We establish an analogy between the inverse Ising problem and the
Ornstein-Zernike formalism in liquid state physics. Rather than analytically
deriving the closure relation, we use a deep neural network to learn the
closure from simulations of the Ising model. We show, using simulations as well
as biochemical datasets, that the deep neural network model outperforms
systematic field-theoretic expansions and can generalize well beyond the
parameter regime of the training data. The neural network is able to learn from
synthetic data, which can be generated with relative ease, to give accurate
predictions on real world datasets."),
Alpha A. Lee,
arXiv: [1706.08466](http://arxiv.org/abs/1706.08466v1),
6/2017

- ["Unsupervised Learning of Frustrated Classical Spin Models I: Principle
  Component Analysis"](
http://arxiv.org/abs/1706.07977v2
"This work aims at the goal whether the artificial intelligence can recognize
phase transition without the prior human knowledge. If this becomes successful,
it can be applied to, for instance, analyze data from quantum simulation of
unsolved physical models. Toward this goal, we first need to apply the machine
learning algorithm to well-understood models and see whether the outputs are
consistent with our prior knowledge, which serves as the benchmark of this
approach. In this work, we feed the compute with data generated by the
classical Monte Carlo simulation for the XY model in frustrated triangular and
union jack lattices, which has two order parameters and exhibits two phase
transitions. We show that the outputs of the principle component analysis agree
very well with our understanding of different orders in different phases, and
the temperature dependences of the major components detect the nature and the
locations of the phase transitions. Our work offers promise for using machine
learning techniques to study sophisticated statistical models, and our results
can be further improved by using principle component analysis with kernel
tricks and the neural network method."),
Ce Wang, Hui Zhai,
arXiv: [1706.07977](http://arxiv.org/abs/1706.07977v2),
6/2017

- ["Self-Learning Phase Boundaries by Active Contours"](
http://arxiv.org/abs/1706.08111v1
"We introduce a fully automatic self-learning scheme for detecting phase
boundaries. This method extends the previously introduced confusion scheme for
learning phase transitions, by using a cooperative network that learns to
optimize the guess for the transition point. The networks together are capable
of finding transition points for fully unlabeled data. This improvement allows
us to efficiently study 1D and 2D parameter spaces, where for the latter we
utilize an active contour model -- the snake -- from computer vision as a
representation of the learned phase boundary. The snakes, equipped with neural
networks, can learn while they move in the parameter space and thereby detect
phase boundaries automatically."),
Ye-Hua Liu, Evert P. L. van Nieuwenburg,
arXiv: [1706.08111](http://arxiv.org/abs/1706.08111v1),
6/2017

- ["Active learning machine learns to create new quantum experiments"](
http://arxiv.org/abs/1706.00868v3
"How useful can machine learning be in a quantum laboratory? Here we raise the
question of the potential of intelligent machines in the context of scientific
research. A major motivation for the present work is the unknown reachability
of various entanglement classes in quantum experiments. We investigate this
question by using the projective simulation model, a physics-oriented approach
to artificial intelligence. In our approach, the projective simulation system
is challenged to design complex photonic quantum experiments that produce
high-dimensional entangled multiphoton states, which are of high interest in
modern quantum experiments. The artificial intelligence system learns to create
a variety of entangled states, and improves the efficiency of their
realization. In the process, the system autonomously (re)discovers experimental
techniques which are only now becoming standard in modern quantum optical
experiments - a trait which was not explicitly demanded from the system but
emerged through the process of learning. Such features highlight the
possibility that machines could have a significantly more creative role in
future research."),
Alexey A. Melnikov, Hendrik Poulsen Nautrup, Mario Krenn, Vedran Dunjko, Markus Tiersch, Anton Zeilinger, Hans J. Briegel,
arXiv: [1706.00868](http://arxiv.org/abs/1706.00868v3),
6/2017

- ["Machine-learning-assisted correction of correlated qubit errors in a
  topological code"](
http://arxiv.org/abs/1705.07855v3
"A fault-tolerant quantum computation requires an efficient means to detect
and correct errors that accumulate in encoded quantum information. In the
context of machine learning, neural networks are a promising new approach to
quantum error correction. Here we show that a recurrent neural network can be
trained, using only experimentally accessible data, to detect errors in a
widely used topological code, the surface code, with a performance above that
of the established minimum-weight perfect matching (or blossom) decoder. The
performance gain is achieved because the neural network decoder can detect
correlations between bit-flip (X) and phase-flip (Z) errors. The machine
learning algorithm adapts to the physical system, hence no noise model is
needed. The long short-term memory layers of the recurrent neural network
maintain their performance over a large number of quantum error correction
cycles, making it a practical decoder for forthcoming experimental realizations
of the surface code."),
P. Baireuther, T. E. O'Brien, B. Tarasinski, C. W. J. Beenakker,
arXiv: [1705.07855](http://arxiv.org/abs/1705.07855v3),
5/2017

- ["Self-Learning Monte Carlo Method: Continuous-Time Algorithm"](
http://arxiv.org/abs/1705.06724v2
"The recently-introduced self-learning Monte Carlo method is a general-purpose
numerical method that speeds up Monte Carlo simulations by training an
effective model to propose uncorrelated configurations in the Markov chain. We
implement this method in the framework of continuous time Monte Carlo method
with auxiliary field in quantum impurity models. We introduce and train a
diagram generating function (DGF) to model the probability distribution of
auxiliary field configurations in continuous imaginary time, at all orders of
diagrammatic expansion. By using DGF to propose global moves in configuration
space, we show that the self-learning continuous-time Monte Carlo method can
significantly reduce the computational complexity of the simulation."),
Yuki Nagai, Huitao Shen, Yang Qi, Junwei Liu, Liang Fu,
arXiv: [1705.06724](http://arxiv.org/abs/1705.06724v2),
5/2017

- ["Criticality & Deep Learning II: Momentum Renormalisation Group"](
http://arxiv.org/abs/1705.11023v1
"Guided by critical systems found in nature we develop a novel mechanism
consisting of inhomogeneous polynomial regularisation via which we can induce
scale invariance in deep learning systems. Technically, we map our deep
learning (DL) setup to a genuine field theory, on which we act with the
Renormalisation Group (RG) in momentum space and produce the flow equations of
the couplings; those are translated to constraints and consequently interpreted
as "critical regularisation" conditions in the optimiser; the resulting
equations hence prove to be sufficient conditions for - and serve as an elegant
and simple mechanism to induce scale invariance in any deep learning setup."),
Dan Oprisa, Peter Toth,
arXiv: [1705.11023](http://arxiv.org/abs/1705.11023v1),
5/2017

- ["Construction of Hamiltonians by supervised learning of energy and
  entanglement spectra"](
http://arxiv.org/abs/1705.05372v4
"Correlated many-body problems ubiquitously appear in various fields of
physics such as condensed matter physics, nuclear physics, and statistical
physics. However, due to the interplay of the large number of degrees of
freedom, it is generically impossible to treat these problems from first
principles. Thus the construction of a proper model, namely effective
Hamiltonian, is essential. Here, we propose a simple scheme of constructing
Hamiltonians from given energy or entanglement spectra with machine learning.
We apply the proposed scheme to the Hubbard model at the half-filling, and
compare the obtained effective low-energy spin-1/2 model with several analytic
results based on the high order perturbation theory which have been
inconsistent with each other. We also show that our approach can be used to
construct the entanglement Hamiltonian of a quantum many-body state from its
entanglement spectrum as well. We exemplify this using the ground states of the
$S=1/2$ two-leg Heisenberg ladders. We observe a qualitative difference between
the entanglement Hamiltonians of the two phases (the Haldane phase and the Rung
Singlet phase) of the model due to the different origin of the entanglement. In
the Haldane phase, we find that the entanglement Hamiltonian is non-local by
nature, and the locality can be restored by introducing the anisotropy and
turning the system into the large-$D$ phase. Possible applications to the study
of strongly-correlated systems and the model construction from experimental
data are discussed."),
Hiroyuki Fujita, Yuya O. Nakagawa, Sho Sugiura, Masaki Oshikawa,
arXiv: [1705.05372](http://arxiv.org/abs/1705.05372v4),
5/2017


- ["Machine Learning of Explicit Order Parameters: From the Ising Model to
  SU(2) Lattice Gauge Theory"](
http://arxiv.org/abs/1705.05582v1
"We present a procedure for reconstructing the decision function of an
artificial neural network as a simple function of the input, provided the
decision function is sufficiently symmetric. In this case one can easily deduce
the quantity by which the neural network classifies the input. The procedure is
embedded into a pipeline of machine learning algorithms able to detect the
existence of different phases of matter, to determine the position of phase
transitions and to find explicit expressions of the physical quantities by
which the algorithm distinguishes between phases. We assume no prior knowledge
about the Hamiltonian or the order parameters except Monte Carlo-sampled
configurations. The method is applied to the Ising Model and SU(2) lattice
gauge theory. In both systems we deduce the explicit expressions of the known
order parameters from the decision functions of the neural networks."),
Sebastian Johann Wetzel, Manuel Scherzer,
arXiv: [1705.05582](http://arxiv.org/abs/1705.05582v1),
5/2017


- ["Machine Learning $Z_2$ Quantum Spin Liquids with
  Quasi-particle Statistics"](
http://arxiv.org/abs/1705.01947v2
"After decades of progress and effort, obtaining a phase diagram for a
strongly-correlated topological system still remains a challenge. Although in
principle one could turn to Wilson loops and long-range entanglement,
evaluating these non-local observables at many points in phase space can be
prohibitively costly. With growing excitement over topological quantum
computation comes the need for an efficient approach for obtaining topological
phase diagrams. Here we turn to machine learning using quantum loop topography
(QLT), a notion we have recently introduced. Specifically, we propose a
construction of QLT that is sensitive to quasi-particle statistics. We then use
mutual statistics between the spinons and visons to detect a $Z_2$
quantum spin liquid in a multi-parameter phase space. We successfully obtain
the quantum phase boundary between the topological and trivial phases using a
simple feed-forward neural network. Furthermore, we demonstrate advantages of
our approach for the evaluation of phase diagrams relating to speed and
storage. Such statistics-based machine learning of topological phases opens new
efficient routes to studying topological phase diagrams in strongly correlated
systems."),
Yi Zhang, Roger G. Melko, Eun-Ah Kim,
arXiv: [1705.01947](http://arxiv.org/abs/1705.01947v2),
5/2017

- ["Decoding Small Surface Codes with Feedforward Neural Networks"](
http://arxiv.org/abs/1705.00857v1
"Surface codes reach high error thresholds when decoded with known algorithms,
but the decoding time will likely exceed the available time budget, especially
for near-term implementations. To decrease the decoding time, we reduce the
decoding problem to a classification problem that a feedforward neural network
can solve. We investigate quantum error correction and fault tolerance at small
code distances using neural network-based decoders, demonstrating that the
neural network can generalize to inputs that were not provided during training
and that they can reach similar or better decoding performance compared to
previous algorithms. We conclude by discussing the time required by a
feedforward neural network decoder in hardware."),
Savvas Varsamopoulos, Ben Criger, Koen Bertels,
arXiv: [1705.00857](http://arxiv.org/abs/1705.00857v1),
5/2017

- ["A Separability-Entanglement Classifier via Machine Learning"](
http://arxiv.org/abs/1705.01523v3
"The problem of determining whether a given quantum state is entangled lies at
the heart of quantum information processing, which is known to be an NP-hard
problem in general. Despite the proposed many methods such as the positive
partial transpose (PPT) criterion and the k-symmetric extendibility criterion
to tackle this problem in practice, none of them enables a general, effective
solution to the problem even for small dimensions. Explicitly, separable states
form a high-dimensional convex set, which exhibits a vastly complicated
structure. In this work, we build a new separability-entanglement classifier
underpinned by machine learning techniques. Our method outperforms the existing
methods in generic cases in terms of both speed and accuracy, opening up the
avenues to explore quantum entanglement via the machine learning approach."),
Sirui Lu, Shilin Huang, Keren Li, Jun Li, Jianxin Chen, Dawei Lu, Zhengfeng Ji, Yi Shen, Duanlu Zhou, Bei Zeng,
arXiv: [1705.01523](http://arxiv.org/abs/1705.01523v3),
5/2017

- ["Reinforcement Learning in Different Phases of Quantum Control"](
http://arxiv.org/abs/1705.00565v2
"The ability to prepare a physical system in a desired quantum state is
central to many areas of physics such as nuclear magnetic resonance, cold
atoms, and quantum computing. Preparing states quickly and with high fidelity
remains a formidable challenge. In this work we implement cutting-edge
Reinforcement Learning (RL) techniques and show that their performance rivals
gradient-based optimal control methods at the task of finding short,
high-fidelity driving protocols from an initial to a target state in
non-integrable many-body quantum systems of interacting qubits. The quantum
state preparation problem, viewed as an optimization problem, is shown to
exhibit a spin-glass-like phase transition in the space of protocols as a
function of the protocol duration. Our RL-aided approach helps identify
variational protocols with nearly optimal fidelity, even in the glassy phase,
where optimal state preparation appears exponentially hard. This study
highlights the usefulness of RL for applications in out-of-equilibrium quantum
physics."),
Marin Bukov, Alexandre G. R. Day, Dries Sels, Phillip Weinberg, Anatoli Polkovnikov, Pankaj Mehta,
arXiv: [1705.00565](http://arxiv.org/abs/1705.00565v2),
5/2017


- ["Deterministic Quantum Annealing Expectation-Maximization Algorithm"](
http://arxiv.org/abs/1704.05822v1
"Maximum likelihood estimation (MLE) is one of the most important methods in
machine learning, and the expectation-maximization (EM) algorithm is often used
to obtain maximum likelihood estimates. However, EM heavily depends on initial
configurations and fails to find the global optimum. On the other hand, in the
field of physics, quantum annealing (QA) was proposed as a novel optimization
approach. Motivated by QA, we propose a quantum annealing extension of EM,
which we call the deterministic quantum annealing expectation-maximization
(DQAEM) algorithm. We also discuss its advantage in terms of the path integral
formulation. Furthermore, by employing numerical simulations, we illustrate how
it works in MLE and show that DQAEM outperforms EM."),
Hideyuki Miyahara, Koji Tsumura, Yuki Sughiyama,
arXiv: [1704.05822](http://arxiv.org/abs/1704.05822v1),
4/2017


- ["Nonequilibrium Thermodynamics of Restricted Boltzmann Machines"](
http://arxiv.org/abs/1704.08724v1
"In this work, we analyze the nonequilibrium thermodynamics of a class of
neural networks known as Restricted Boltzmann Machines (RBMs) in the context of
unsupervised learning. We show how the network is described as a discrete
Markov process and how the detailed balance condition and the Maxwell-Boltzmann
equilibrium distribution are sufficient conditions for a complete
thermodynamics description, including nonequilibrium fluctuation theorems.
Numerical simulations in a fully trained RBM are performed and the heat
exchange fluctuation theorem is verified with excellent agreement to the
theory. We observe how the contrastive divergence functional, mostly used in
unsupervised learning of RBMs, is closely related to nonequilibrium
thermodynamic quantities. We also use the framework to interpret the estimation
of the partition function of RBMs with the Annealed Importance Sampling method
from a thermodynamics standpoint. Finally, we argue that unsupervised learning
of RBMs is equivalent to a work protocol in a system driven by the laws of
thermodynamics in the absence of labeled data."),
Domingos S. P. Salazar,
arXiv: [1704.08724](http://arxiv.org/abs/1704.08724v1),
4/2017


- ["Mutual Information, Neural Networks and the Renormalization Group"](
http://arxiv.org/abs/1704.06279v1
"Physical systems differing in their microscopic details often display
strikingly similar behaviour when probed at low energies. Those universal
properties, largely determining their physical characteristics, are revealed by
the powerful renormalization group (RG) procedure, which systematically retains
"slow" degrees of freedom and integrates out the rest. However, the important
degrees of freedom may be difficult to identify. Here we demonstrate a machine
learning (ML) algorithm capable of identifying the relevant degrees of freedom
without any prior knowledge about the system. We introduce an artificial neural
network based on a model-independent, information-theoretic characterization of
a real-space RG procedure, performing this task. We apply the algorithm to
classical statistical physics problems in two dimensions."),
Maciej Koch-Janusz, Zohar Ringel,
arXiv: [1704.06279](http://arxiv.org/abs/1704.06279v1),
4/2017


- ["Kernel methods for interpretable machine learning of order parameters"](
http://arxiv.org/abs/1704.05848v1
"Machine learning is capable of discriminating phases of matter, and finding
associated phase transitions, directly from large data sets of raw state
configurations. In the context of condensed matter physics, most progress in
the field of supervised learning has come from employing neural networks as
classifiers. Although very powerful, such algorithms suffer from a lack of
interpretability, which is usually desired in scientific applications in order
to associate learned features with physical phenomena. In this paper, we
explore support vector machines (SVMs) which are a class of supervised kernel
methods that provide interpretable decision functions. We find that SVMs can
learn the mathematical form of physical discriminators, such as order
parameters and Hamiltonian constraints, for a set of two-dimensional spin
models: the ferromagnetic Ising model, a conserved-order-parameter Ising model,
and the Ising gauge theory. The ability of SVMs to provide interpretable
classification highlights their potential for automating feature detection in
both synthetic and experimental data sets for condensed matter and other
many-body systems."),
Pedro Ponte, Roger G. Melko,
arXiv: [1704.05848](http://arxiv.org/abs/1704.05848v1),
4/2017


- ["Approximating quantum many-body wave-functions using artificial neural
  networks"](
http://arxiv.org/abs/1704.05148v4
"In this paper, we demonstrate the expressibility of artificial neural
networks (ANNs) in quantum many-body physics by showing that a feed-forward
neural network with a small number of hidden layers can be trained to
approximate with high precision the ground states of some notable quantum
many-body systems. We consider the one-dimensional free bosons and fermions,
spinless fermions on a square lattice away from half-filling, as well as
frustrated quantum magnetism with a rapidly oscillating ground-state
characteristic function. In the latter case, an ANN with a standard
architecture fails, while that with a slightly modified one successfully learns
the frustration-induced complex sign rule in the ground state and approximates
the ground states with high precisions. As an example of practical use of our
method, we also perform the variational method to explore the ground state of
an anti-ferromagnetic $J_1-J_2$ Heisenberg model."),
Zi Cai, Jinguo Liu,
arXiv: [1704.05148](http://arxiv.org/abs/1704.05148v4),
4/2017


- ["Probing many-body localization with neural networks"](
http://arxiv.org/abs/1704.01578v2
"We show that a simple artificial neural network trained on entanglement
spectra of individual states of a many-body quantum system can be used to
determine the transition between a many-body localized and a thermalizing
regime. Specifically, we study the Heisenberg spin-1/2 chain in a random
external field. We employ a multilayer perceptron with a single hidden layer,
which is trained on labeled entanglement spectra pertaining to the fully
localized and fully thermal regimes. We then apply this network to classify
spectra belonging to states in the transition region. For training, we use a
cost function that contains, in addition to the usual error and regularization
parts, a term that favors a confident classification of the transition region
states. The resulting phase diagram is in good agreement with the one obtained
by more conventional methods and can be computed for small systems. In
particular, the neural network outperforms conventional methods in classifying
individual eigenstates pertaining to a single disorder realization. It allows
us to map out the structure of these eigenstates across the transition with
spatial resolution. Furthermore, we analyze the network operation using the
dreaming technique to show that the neural network correctly learns by itself
the power-law structure of the entanglement spectra in the many-body localized
regime."),
Frank Schindler, Nicolas Regnault, Titus Neupert,
arXiv: [1704.01578](http://arxiv.org/abs/1704.01578v2),
4/2017


- ["Discovering Phases, Phase Transitions and Crossovers through
  Unsupervised Machine Learning: A critical examination"](
http://arxiv.org/abs/1704.00080v2
"We apply unsupervised machine learning techniques, mainly principal component
analysis (PCA), to compare and contrast the phase behavior and phase
transitions in several classical spin models - the square and
triangular-lattice Ising models, the Blume-Capel model, a highly degenerate
biquadratic-exchange spin-one Ising (BSI) model, and the 2D XY model, and
examine critically what machine learning is teaching us. We find that
quantified principal components from PCA not only allow exploration of
different phases and symmetry-breaking, but can distinguish phase transition
types and locate critical points. We show that the corresponding weight vectors
have a clear physical interpretation, which is particularly interesting in the
frustrated models such as the triangular antiferromagnet, where they can point
to incipient orders. Unlike the other well-studied models, the properties of
the BSI model are less well known. Using both PCA and conventional Monte Carlo
analysis, we demonstrate that the BSI model shows an absence of phase
transition and macroscopic ground-state degeneracy. The failure to capture the
`charge' correlations (vorticity) in the BSI model (XY model) from raw spin
configurations points to some of the limitations of PCA. Finally, we employ a
nonlinear unsupervised machine learning procedure, the `antoencoder method',
and demonstrate that it too can be trained to capture phase transitions and
critical points."),
Wenjian Hu, Rajiv R. P. Singh, Richard T. Scalettar,
arXiv: [1704.00080](http://arxiv.org/abs/1704.00080v2),
3/2017


- ["Many-body quantum state tomography with neural networks"](
http://arxiv.org/abs/1703.05334v2
"The experimental realization of increasingly complex synthetic quantum
systems calls for the development of general theoretical methods, to validate
and fully exploit quantum resources. Quantum-state tomography (QST) aims at
reconstructing the full quantum state from simple measurements, and therefore
provides a key tool to obtain reliable analytics. Brute-force approaches to
QST, however, demand resources growing exponentially with the number of
constituents, making it unfeasible except for small systems. Here we show that
machine learning techniques can be efficiently used for QST of highly-entangled
states, in both one and two dimensions. Remarkably, the resulting approach
allows one to reconstruct traditionally challenging many-body quantities - such
as the entanglement entropy - from simple, experimentally accessible
measurements. This approach can benefit existing and future generations of
devices ranging from quantum computers to ultra-cold atom quantum simulators."),
Giacomo Torlai, Guglielmo Mazzola, Juan Carrasquilla, Matthias Troyer, Roger Melko, Giuseppe Carleo,
arXiv: [1703.05334](http://arxiv.org/abs/1703.05334v2),
3/2017


- ["Unsupervised learning of phase transitions: from principal component
  analysis to variational autoencoders"](
http://arxiv.org/abs/1703.02435v2
"We employ unsupervised machine learning techniques to learn latent parameters
which best describe states of the two-dimensional Ising model and the
three-dimensional XY model. These methods range from principal component
analysis to artificial neural network based variational autoencoders. The
states are sampled using a Monte-Carlo simulation above and below the critical
temperature. We find that the predicted latent parameters correspond to the
known order parameters. The latent representation of the states of the models
in question are clustered, which makes it possible to identify phases without
prior knowledge of their existence or the underlying Hamiltonian. Furthermore,
we find that the reconstruction loss function can be used as a universal
identifier for phase transitions."),
Sebastian Johann Wetzel,
arXiv: [1703.02435](http://arxiv.org/abs/1703.02435v2),
3/2017


- ["Neural network representation of tensor network and chiral states"](
http://arxiv.org/abs/1701.06246v1
"We study the representational power of a Boltzmann machine (a type of neural
network) in quantum many-body systems. We prove that any (local) tensor network
state has a (local) neural network representation. The construction is almost
optimal in the sense that the number of parameters in the neural network
representation is almost linear in the number of nonzero parameters in the
tensor network representation. Despite the difficulty of representing (gapped)
chiral topological states with local tensor networks, we construct a
quasi-local neural network representation for a chiral p-wave superconductor.
This demonstrates the power of Boltzmann machines."),
Yichen Huang, Joel E. Moore,
arXiv: [1701.06246](http://arxiv.org/abs/1701.06246v1),
1/2017


- ["Equivalence of restricted Boltzmann machines and tensor network states"](
http://arxiv.org/abs/1701.04831v2
"The restricted Boltzmann machine (RBM) is one of the fundamental building
blocks of deep learning. RBM finds wide applications in dimensional reduction,
feature extraction, and recommender systems via modeling the probability
distributions of a variety of input data including natural images, speech
signals, and customer ratings, etc. We build a bridge between RBM and tensor
network states (TNS) widely used in quantum many-body physics research. We
devise efficient algorithms to translate an RBM into the commonly used TNS.
Conversely, we give sufficient and necessary conditions to determine whether a
TNS can be transformed into an RBM of given architectures. Revealing these
general and constructive connections can cross-fertilize both deep learning and
quantum many-body physics. Notably, by exploiting the entanglement entropy
bound of TNS, we can rigorously quantify the expressive power of RBM on complex
data sets. Insights into TNS and its entanglement capacity can guide the design
of more powerful deep learning architectures. On the other hand, RBM can
represent quantum many-body states with fewer parameters compared to TNS, which
may allow more efficient classical simulations."),
Jing Chen, Song Cheng, Haidong Xie, Lei Wang, Tao Xiang,
arXiv: [1701.04831](http://arxiv.org/abs/1701.04831v2),
1/2017


- ["Efficient Representation of Quantum Many-body States with Deep Neural
  Networks"](
http://arxiv.org/abs/1701.05039v1
"The challenge of quantum many-body problems comes from the difficulty to
represent large-scale quantum states, which in general requires an
exponentially large number of parameters. Recently, a connection has been made
between quantum many-body states and the neural network representation
(\textit{arXiv:1606.02318}). An important open question is what characterizes
the representational power of deep and shallow neural networks, which is of
fundamental interest due to popularity of the deep learning methods. Here, we
give a rigorous proof that a deep neural network can efficiently represent most
physical states, including those generated by any polynomial size quantum
circuits or ground states of many body Hamiltonians with polynomial-size gaps,
while a shallow network through a restricted Boltzmann machine cannot
efficiently represent those states unless the polynomial hierarchy in
computational complexity theory collapses."),
Xun Gao, Lu-Ming Duan,
arXiv: [1701.05039](http://arxiv.org/abs/1701.05039v1),
1/2017


- ["Quantum Entanglement in Neural Network States"](
http://arxiv.org/abs/1701.04844v3
"Machine learning, one of today's most rapidly growing interdisciplinary
fields, promises an unprecedented perspective for solving intricate quantum
many-body problems. Understanding the physical aspects of the representative
artificial neural-network states is recently becoming highly desirable in the
applications of machine learning techniques to quantum many-body physics. Here,
we study the quantum entanglement properties of neural-network states, with a
focus on the restricted-Boltzmann-machine (RBM) architecture. We prove that the
entanglement of all short-range RBM states satisfies an area law for arbitrary
dimensions and bipartition geometry. For long-range RBM states we show by using
an exact construction that such states could exhibit volume-law entanglement,
implying a notable capability of RBM in representing efficiently quantum states
with massive entanglement. We further examine generic RBM states with random
weight parameters. We find that their averaged entanglement entropy obeys
volume-law scaling and meantime strongly deviates from the Page-entropy of the
completely random pure states. We show that their entanglement spectrum has no
universal part associated with random matrix theory and bears a Poisson-type
level statistics. Using reinforcement learning, we demonstrate that RBM is
capable of finding the ground state (with power-law entanglement) of a model
Hamiltonian with long-range interaction. In addition, we show, through a
concrete example of the one-dimensional symmetry-protected topological cluster
states, that the RBM representation may also be used as a tool to analytically
compute the entanglement spectrum. Our results uncover the unparalleled power
of artificial neural networks in representing quantum many-body states, which
paves a novel way to bridge computer science based machine learning techniques
to outstanding quantum condensed matter physics problems."),
Dong-Ling Deng, Xiaopeng Li, S. Das Sarma,
arXiv: [1701.04844](http://arxiv.org/abs/1701.04844v3),
1/2017


- ["Restricted Boltzmann Machines for the Long Range Ising Models"](
http://arxiv.org/abs/1701.00246v1
"We set up Restricted Boltzmann Machines (RBM) to reproduce the Long Range
Ising (LRI) models of the Ohmic type in one dimension. The RBM parameters are
tuned by using the standard machine learning procedure with an additional
method of Configuration with Probability (CwP). The quality of resultant RBM
are evaluated through the susceptibility with respect to the magnetic external
field. We compare the results with those by Block Decimation Renormalization
Group (BDRG) method, and our RBM clear the test with satisfactory precision."),
Ken-Ichi Aoki, Tamao Kobayashi,
arXiv: [1701.00246](http://arxiv.org/abs/1701.00246v1),
1/2017


- ["Reinforcement Learning Using Quantum Boltzmann Machines"](
http://arxiv.org/abs/1612.05695v2
"We investigate whether quantum annealers with select chip layouts can
outperform classical computers in reinforcement learning tasks. We associate a
transverse field Ising spin Hamiltonian with a layout of qubits similar to that
of a deep Boltzmann machine (DBM) and use simulated quantum annealing (SQA) to
numerically simulate quantum sampling from this system. We design a
reinforcement learning algorithm in which the set of visible nodes representing
the states and actions of an optimal policy are the first and last layers of
the deep network. In absence of a transverse field, our simulations show that
DBMs train more effectively than restricted Boltzmann machines (RBM) with the
same number of weights. Since sampling from Boltzmann distributions of a DBM is
not classically feasible, this is evidence of advantage of a non-Turing
sampling oracle. We then develop a framework for training the network as a
quantum Boltzmann machine (QBM) in the presence of a significant transverse
field for reinforcement learning. This further improves the reinforcement
learning method using DBMs."),
Daniel Crawford, Anna Levit, Navid Ghadermarzy, Jaspreet S. Oberoi, Pooya Ronagh,
arXiv: [1612.05695](http://arxiv.org/abs/1612.05695v2),
12/2016


- ["Self-Learning Monte Carlo Method in Fermion Systems"](
http://arxiv.org/abs/1611.09364v1
"We develop the self-learning Monte Carlo (SLMC) method, a general-purpose
numerical method recently introduced to simulate many-body systems, for
studying interacting fermion systems. Our method uses a highly-efficient update
algorithm, which we design and dub "cumulative update", to generate new
candidate configurations in the Markov chain based on a self-learned bosonic
effective model. From general analysis and numerical study of the double
exchange model as an example, we find the SLMC with cumulative update
drastically reduces the computational cost of the simulation, while remaining
statistically exact. Remarkably, its computational complexity is far less than
the conventional algorithm with local updates."),
Junwei Liu, Huitao Shen, Yang Qi, Zi Yang Meng, Liang Fu,
arXiv: [1611.09364](http://arxiv.org/abs/1611.09364v1),
11/2016


- ["Sampling algorithms for validation of supervised learning models for
  Ising-like systems"](
http://arxiv.org/abs/1611.05891v1
"In this paper, we build and explore supervised learning models of
ferromagnetic system behavior, using Monte-Carlo sampling of the spin
configuration space generated by the 2D Ising model. Given the enormous size of
the space of all possible Ising model realizations, the question arises as to
how to choose a reasonable number of samples that will form physically
meaningful and non-intersecting training and testing datasets. Here, we propose
a sampling technique called ID-MH that uses the Metropolis-Hastings algorithm
creating Markov process across energy levels within the predefined
configuration subspace. We show that application of this method retains phase
transitions in both training and testing datasets and serves the purpose of
validation of a machine learning algorithm. For larger lattice dimensions,
ID-MH is not feasible as it requires knowledge of the complete configuration
space. As such, we develop a new "block-ID" sampling strategy: it decomposes
the given structure into square blocks with lattice dimension no greater than 5
and uses ID-MH sampling of candidate blocks. Further comparison of the
performance of commonly used machine learning methods such as random forests,
decision trees, k nearest neighbors and artificial neural networks shows that
the PCA-based Decision Tree regressor is the most accurate predictor of
magnetizations of the Ising model. For energies, however, the accuracy of
prediction is not satisfactory, highlighting the need to consider more
algorithmically complex methods (e.g., deep learning)."),
Nataliya Portman, Isaac Tamblyn,
arXiv: [1611.05891](http://arxiv.org/abs/1611.05891v1),
11/2016

- ["Quantum Loop Topography for Machine Learning"](
http://arxiv.org/abs/1611.01518v2
"Despite rapidly growing interest in harnessing machine learning in the study
of quantum many-body systems, training neural networks to identify quantum
phases is a nontrivial challenge. The key challenge is in efficiently
extracting essential information from the many-body Hamiltonian or wave
function and turning the information into an image that can be fed into a
neural network. When targeting topological phases, this task becomes
particularly challenging as topological phases are defined in terms of
non-local properties. Here we introduce quantum loop topography (QLT): a
procedure of constructing a multi-dimensional image from the "sample"
Hamiltonian or wave function by evaluating two-point operators that form loops
at independent Monte Carlo steps. The loop configuration is guided by
characteristic response for defining the phase, which is Hall conductivity for
the cases at hand. Feeding QLT to a fully-connected neural network with a
single hidden layer, we demonstrate that the architecture can be effectively
trained to distinguish Chern insulator and fractional Chern insulator from
trivial insulators with high fidelity. In addition to establishing the first
case of obtaining a phase diagram with topological quantum phase transition
with machine learning, the perspective of bridging traditional condensed matter
theory with machine learning will be broadly valuable."),
Yi Zhang, Eun-Ah Kim,
arXiv: [1611.01518](http://arxiv.org/abs/1611.01518v2),
11/2016

- ["Learning phase transitions by confusion"](
http://arxiv.org/abs/1610.02048v1
"Classifying phases of matter is a central problem in physics. For quantum
mechanical systems, this task can be daunting owing to the exponentially large
Hilbert space. Thanks to the available computing power and access to ever
larger data sets, classification problems are now routinely solved using
machine learning techniques. Here, we propose to use a neural network based
approach to find phase transitions depending on the performance of the neural
network after training it with deliberately incorrectly labelled data. We
demonstrate the success of this method on the topological phase transition in
the Kitaev chain, the thermal phase transition in the classical Ising model,
and the many-body-localization transition in a disordered quantum spin chain.
Our method does not depend on order parameters, knowledge of the topological
content of the phases, or any other specifics of the transition at hand. It
therefore paves the way to a generic tool to identify unexplored phase
transitions."),
Evert P. L. van Nieuwenburg, Ye-Hua Liu, Sebastian D. Huber,
arXiv: [1610.02048](http://arxiv.org/abs/1610.02048v1),
10/2016

- ["A Neural Decoder for Topological Codes"](
http://arxiv.org/abs/1610.04238v1
"We present an algorithm for error correction in topological codes that
exploits modern machine learning techniques. Our decoder is constructed from a
stochastic neural network called a Boltzmann machine, of the type extensively
used in deep learning. We provide a general prescription for the training of
the network and a decoding strategy that is applicable to a wide variety of
stabilizer codes with very little specialization. We demonstrate the neural
decoder numerically on the well-known two dimensional toric code with
phase-flip errors."),
Giacomo Torlai, Roger G. Melko,
arXiv: [1610.04238](http://arxiv.org/abs/1610.04238v1),
10/2016

- ["Self-Learning Monte Carlo Method"](
http://arxiv.org/abs/1610.03137v2
"Monte Carlo simulation is an unbiased numerical tool for studying classical
and quantum many-body systems. One of its bottlenecks is the lack of general
and efficient update algorithm for large size systems close to phase transition
or with strong frustrations, for which local updates perform badly. In this
work, we propose a new general-purpose Monte Carlo method, dubbed self-learning
Monte Carlo (SLMC), in which an efficient update algorithm is first learned
from the training data generated in trial simulations and then used to speed up
the actual simulation. We demonstrate the efficiency of SLMC in a spin model at
the phase transition point, achieving a 10-20 times speedup."),
Junwei Liu, Yang Qi, Zi Yang Meng, Liang Fu,
arXiv: [1610.03137](http://arxiv.org/abs/1610.03137v2),
10/2016

- ["Accelerate Monte Carlo Simulations with Restricted Boltzmann Machines"](
http://arxiv.org/abs/1610.02746v2
"Despite their exceptional flexibility and popularity, the Monte Carlo methods
often suffer from slow mixing times for challenging statistical physics
problems. We present a general strategy to overcome this difficulty by adopting
ideas and techniques from the machine learning community. We fit the
unnormalized probability of the physical model to a feedforward neural network
and reinterpret the architecture as a restricted Boltzmann machine. Then,
exploiting its feature detection ability, we utilize the restricted Boltzmann
machine for efficient Monte Carlo updates and to speed up the simulation of the
original physical system. We implement these ideas for the Falicov-Kimball
model and demonstrate improved acceptance ratio and autocorrelation time near
the phase transition point."),
Li Huang, Lei Wang,
arXiv: [1610.02746](http://arxiv.org/abs/1610.02746v2),
10/2016

- ["Machine Learning Topological States"](
http://arxiv.org/abs/1609.09060v2
"Artificial neural networks and machine learning have now reached a new era
after several decades of improvement where applications are to explode in many
fields of science, industry, and technology. Here, we use artificial neural
networks to study an intriguing phenomenon in quantum physics--- the
topological phases of matter. We find that certain topological states, either
symmetry-protected or with intrinsic topological order, can be represented with
classical artificial neural networks. This is demonstrated by using three
concrete spin systems, the one-dimensional (1D) symmetry-protected topological
cluster state and the 2D and 3D toric code states with intrinsic topological
orders. For all three cases we show rigorously that the topological ground
states can be represented by short-range neural networks in an \textit{exact}
and \textit{efficient} fashion---the required number of hidden neurons is as
small as the number of physical spins and the number of parameters scales only
\textit{linearly} with the system size. For the 2D toric-code model, we find
that the proposed short-range neural networks can describe the excited states
with abelain anyons and their nontrivial mutual statistics as well. In
addition, by using reinforcement learning we show that neural networks are
capable of finding the topological ground states of non-integrable Hamiltonians
with strong interactions and studying their topological phase transitions. Our
results demonstrate explicitly the exceptional power of neural networks in
describing topological quantum states, and at the same time provide valuable
guidance to machine learning of topological phases in generic lattice models."),
Dong-Ling Deng, Xiaopeng Li, S. Das Sarma,
arXiv: [1609.09060](http://arxiv.org/abs/1609.09060v2),
9/2016

- ["Pure density functional for strong correlations and the thermodynamic
  limit from machine learning"](
http://arxiv.org/abs/1609.03705v1
"We use density-matrix renormalization group, applied to a one-dimensional
model of continuum Hamiltonians, to accurately solve chains of hydrogen atoms
of various separations and numbers of atoms. We train and test a
machine-learned approximation to $F[n]$, the universal part of the electronic
density functional, to within quantum chemical accuracy. Our calculation (a)
bypasses the standard Kohn-Sham approach, avoiding the need to find orbitals,
(b) includes the strong correlation of highly-stretched bonds without any
specific difficulty (unlike all standard DFT approximations) and (c) is so
accurate that it can be used to find the energy in the thermodynamic limit to
quantum chemical accuracy."),
Li Li, Thomas E. Baker, Steven R. White, Kieron Burke,
arXiv: [1609.03705](http://arxiv.org/abs/1609.03705v1),
9/2016

- ["Machine Learning Phases of Strongly Correlated Fermions"](
http://arxiv.org/abs/1609.02552v3
"Machine learning offers an unprecedented perspective for the problem of
classifying phases in condensed matter physics. We employ neural-network
machine learning techniques to distinguish finite-temperature phases of the
strongly correlated fermions on cubic lattices. We show that a three
dimensional convolutional network trained on auxiliary field configurations
produced by quantum Monte Carlo simulations of the Hubbard model can correctly
predict the magnetic phase diagram of the model at the average density of one
(half filling). We then use the network, trained at half filling, to explore
the trend in the transition temperature as the system is doped away from half
filling. This transfer learning approach predicts that the instability to the
magnetic phase extends to at least 5% doping in this region. Our results pave
the way for other machine learning applications in correlated quantum many-body
systems."),
Kelvin Ch'ng, Juan Carrasquilla, Roger G. Melko, Ehsan Khatami,
arXiv: [1609.02552](http://arxiv.org/abs/1609.02552v3),
9/2016

- ["Machine learning quantum phases of matter beyond the fermion sign
  problem"](
http://arxiv.org/abs/1608.07848v1
"State-of-the-art machine learning techniques promise to become a powerful
tool in statistical mechanics via their capacity to distinguish different
phases of matter in an automated way. Here we demonstrate that convolutional
neural networks (CNN) can be optimized for quantum many-fermion systems such
that they correctly identify and locate quantum phase transitions in such
systems. Using auxiliary-field quantum Monte Carlo (QMC) simulations to sample
the many-fermion system, we show that the Green's function (but not the
auxiliary field) holds sufficient information to allow for the distinction of
different fermionic phases via a CNN. We demonstrate that this QMC + machine
learning approach works even for systems exhibiting a severe fermion sign
problem where conventional approaches to extract information from the Green's
function, e.g.~in the form of equal-time correlation functions, fail. We expect
that this capacity of hierarchical machine learning techniques to circumvent
the fermion sign problem will drive novel insights into some of the most
fundamental problems in statistical physics."),
Peter Broecker, Juan Carrasquilla, Roger G. Melko, Simon Trebst,
arXiv: [1608.07848](http://arxiv.org/abs/1608.07848v1),
8/2016

- ["Quantum gate learning in engineered qubit networks: Toffoli gate with
  always-on interactions"](
http://arxiv.org/abs/1509.04298v2
"We put forward a strategy to encode a quantum operation into the unmodulated
dynamics of a quantum network without the need of external control pulses,
measurements or active feedback. Our optimization scheme, inspired by
supervised machine learning, consists in engineering the pairwise couplings
between the network qubits so that the target quantum operation is encoded in
the natural reduced dynamics of a network section. The efficacy of the proposed
scheme is demonstrated by the finding of uncontrolled four-qubit networks that
implement either the Toffoli gate, the Fredkin gate, or remote logic
operations. The proposed Toffoli gate is stable against imperfections, has a
high-fidelity for fault tolerant quantum computation, and is fast, being based
on the non-equilibrium dynamics."),
Leonardo Banchi, Nicola Pancotti, Sougato Bose,
arXiv: [1509.04298](http://arxiv.org/abs/1509.04298v2),
9/2015

- ["Learning Thermodynamics with Boltzmann Machines"](
http://arxiv.org/abs/1606.02718v1
"A Boltzmann machine is a stochastic neural network that has been extensively
used in the layers of deep architectures for modern machine learning
applications. In this paper, we develop a Boltzmann machine that is capable of
modelling thermodynamic observables for physical systems in thermal
equilibrium. Through unsupervised learning, we train the Boltzmann machine on
data sets constructed with spin configurations importance-sampled from the
partition function of an Ising Hamiltonian at different temperatures using
Monte Carlo (MC) methods. The trained Boltzmann machine is then used to
generate spin states, for which we compare thermodynamic observables to those
computed by direct MC sampling. We demonstrate that the Boltzmann machine can
faithfully reproduce the observables of the physical system. Further, we
observe that the number of neurons required to obtain accurate results
increases as the system is brought close to criticality."),
Giacomo Torlai, Roger G. Melko,
arXiv: [1606.02718](http://arxiv.org/abs/1606.02718v1),
6/2016

- ["Solving the Quantum Many-Body Problem with Artificial Neural Networks"](
http://arxiv.org/abs/1606.02318v1
"The challenge posed by the many-body problem in quantum physics originates
from the difficulty of describing the non-trivial correlations encoded in the
exponential complexity of the many-body wave function. Here we demonstrate that
systematic machine learning of the wave function can reduce this complexity to
a tractable computational form, for some notable cases of physical interest. We
introduce a variational representation of quantum states based on artificial
neural networks with variable number of hidden neurons. A
reinforcement-learning scheme is then demonstrated, capable of either finding
the ground-state or describing the unitary time evolution of complex
interacting quantum systems. We show that this approach achieves very high
accuracy in the description of equilibrium and dynamical properties of
prototypical interacting spins models in both one and two dimensions, thus
offering a new powerful tool to solve the quantum many-body problem."),
Giuseppe Carleo, Matthias Troyer,
arXiv: [1606.02318](http://arxiv.org/abs/1606.02318v1),
6/2016

- ["Discovering Phase Transitions with Unsupervised Learning"](
http://arxiv.org/abs/1606.00318v2
"Unsupervised learning is a discipline of machine learning which aims at
discovering patterns in big data sets or classifying the data into several
categories without being trained explicitly. We show that unsupervised learning
techniques can be readily used to identify phases and phases transitions of
many body systems. Starting with raw spin configurations of a prototypical
Ising model, we use principal component analysis to extract relevant low
dimensional representations the original data and use clustering analysis to
identify distinct phases in the feature space. This approach successfully finds
out physical concepts such as order parameter and structure factor to be
indicators of the phase transition. We discuss future prospects of discovering
more complex phases and phase transitions using unsupervised learning
techniques."),
Lei Wang,
arXiv: [1606.00318](http://arxiv.org/abs/1606.00318v2),
6/2016

- ["Machine learning phases of matter"](
http://arxiv.org/abs/1605.01735v1
"Neural networks can be used to identify phases and phase transitions in
condensed matter systems via supervised machine learning. Readily programmable
through modern software libraries, we show that a standard feed-forward neural
network can be trained to detect multiple types of order parameter directly
from raw state configurations sampled with Monte Carlo. In addition, they can
detect highly non-trivial states such as Coulomb phases, and if modified to a
convolutional neural network, topological phases with no conventional order
parameter. We show that this classification occurs within the neural network
without knowledge of the Hamiltonian or even the general locality of
interactions. These results demonstrate the power of machine learning as a
basic research tool in the field of condensed matter and statistical physics."),
Juan Carrasquilla, Roger G. Melko,
arXiv: [1605.01735](http://arxiv.org/abs/1605.01735v1),
5/2016



- ["Automated Search for new Quantum Experiments"](
http://arxiv.org/abs/1509.02749v2
"Quantum mechanics predicts a number of at first sight counterintuitive
phenomena. It is therefore a question whether our intuition is the best way to
find new experiments. Here we report the development of the computer algorithm
Melvin which is able to find new experimental implementations for the creation
and manipulation of complex quantum states. And indeed, the discovered
experiments extensively use unfamiliar and asymmetric techniques which are
challenging to understand intuitively. The results range from the first
implementation of a high-dimensional Greenberger-Horne-Zeilinger (GHZ) state,
to a vast variety of experiments for asymmetrically entangled quantum states --
a feature that can only exist when both the number of involved parties and
dimensions is larger than 2. Additionally, new types of high-dimensional
transformations are found that perform cyclic operations. Melvin autonomously
learns from solutions for simpler systems, which significantly speeds up the
discovery rate of more complex experiments. The ability to automate the design
of a quantum experiment can be applied to many quantum systems and allows the
physical realization of quantum states previously thought of only on paper."),
Mario Krenn, Mehul Malik, Robert Fickler, Radek Lapkiewicz, Anton Zeilinger,
arXiv: [1509.02749](http://arxiv.org/abs/1509.02749v2),
9/2015


- ["Understanding Machine-learned Density Functionals"](
http://arxiv.org/abs/1404.1333v2
"Kernel ridge regression is used to approximate the kinetic energy of
non-interacting fermions in a one-dimensional box as a functional of their
density. The properties of different kernels and methods of cross-validation
are explored, and highly accurate energies are achieved. Accurate {\em
constrained optimal densities} are found via a modified Euler-Lagrange
constrained minimization of the total energy. A projected gradient descent
algorithm is derived using local principal component analysis. Additionally, a
sparse grid representation of the density can be used without degrading the
performance of the methods. The implications for machine-learned density
functional approximations are discussed."),
Li Li, John C. Snyder, Isabelle M. Pelaschier, Jessica Huang, Uma-Naresh Niranjan, Paul Duncan, Matthias Rupp, Klaus-Robert Müller, Kieron Burke,
arXiv: [1404.1333](http://arxiv.org/abs/1404.1333v2),
4/2014


- ["Analysis of magnetic domain patterns by a perceptron neural network"](
http://stacks.iop.org/0295-5075/50/i=1/a=094
"It is shown that magnetic bubble films behaviour can be described by using a 2D super-Ising Hamiltonian. Calculated hysteresis curves and magnetic domain patterns are successfully compared with experimental results taken in the literature. The reciprocal problem of finding parameters of the super-Ising model to reproduce computed or experimental magnetic domain pictures is solved by using a perceptron neural network."),
S. Courtin and S. Padovani,
4/2000



## Physics-Inspired Ideas Applied to Machine Learning

- ["Variational quantum simulation of general processes"](
http://arxiv.org/abs/1812.08778v1
"Hybrid variational quantum algorithms have been proposed for simulating
many-body quantum systems with shallow quantum circuits, and are therefore
relevant to Noisy Intermediate Scale Quantum devices. These algorithms are
often discussed as a means to solve static energy spectra and simulate the
dynamics of real and imaginary time evolutions. Here we consider broader uses
of the variational method to simulate general processes. We first show a
variational algorithm for simulating the generalised time evolution with a
non-hermitian Hamiltonian. Then we consider matrix multiplication, a vital
component of diverse applications in many fields including machine learning and
optimisation. We first convert matrix multiplication into a matrix evolution
problem and show how it can be simulated with the algorithm for generalised
time evolution. Meanwhile, when considering matrices that are products of small
matrices, we propose an alternative variational algorithm that can realise
matrix multiplication with a simpler circuit. Finally, we focus on open quantum
systems and apply the developed methods to the variational simulation of
stochastic master equations. We numerically test our theory with a single qubit
system suffering dephasing noise."),
Suguru Endo, Ying Li, Simon Benjamin, Xiao Yuan,
arXiv: [1812.08778](http://arxiv.org/abs/1812.08778v1),
12/2018





- ["Simple coarse graining and sampling strategies for image recognition"](
http://arxiv.org/abs/1809.02599v1
"A conceptually simple way to recognize images is to directly compare test-set
data and training-set data. The accuracy of this approach is limited by the
method of comparison used, and by the extent to which the training-set data
covers the required configuration space. Here we show that this coverage can be
substantially increased using simple strategies of coarse graining (replacing
groups of images by their centroids) and sampling (using distinct sets of
centroids in combination). We use the MNIST data set to show that coarse
graining can be used to convert a subset of training images into about an order
of magnitude fewer image centroids, with no loss of accuracy of classification
of test-set images by direct (nearest-neighbor) classification. Distinct
batches of centroids can be used in combination as a means of sampling
configuration space, and can classify test-set data more accurately than can
the unaltered training set. The approach works most naturally with multiple
processors in parallel."),
Stephen Whitelam,
arXiv: [1809.02599](http://arxiv.org/abs/1809.02599v1),
9/2018

- ["The jamming transition as a paradigm to understand the loss landscape of
  deep neural networks"](
http://arxiv.org/abs/1809.09349v2
"Deep learning has been immensely successful at a variety of tasks, ranging
from classification to AI. Learning corresponds to fitting training data, which
is implemented by descending a very high-dimensional loss function.
Understanding under which conditions neural networks do not get stuck in poor
minima of the loss, and how the landscape of that loss evolves as depth is
increased remains a challenge. Here we predict, and test empirically, an
analogy between this landscape and the energy landscape of repulsive ellipses.
We argue that in FC networks a phase transition delimits the over- and
under-parametrized regimes where fitting can or cannot be achieved. In the
vicinity of this transition, properties of the curvature of the minima of the
loss are critical. This transition shares direct similarities with the jamming
transition by which particles form a disordered solid as the density is
increased, which also occurs in certain classes of computational optimization
and learning problems such as the perceptron. Our analysis gives a simple
explanation as to why poor minima of the loss cannot be encountered in the
overparametrized regime, and puts forward the surprising result that the
ability of fully connected networks to fit random data is independent of their
depth. Our observations suggests that this independence also holds for real
data. We also study a quantity $\Delta$ which characterizes how well
($\Delta<0$) or badly ($\Delta>0$) a datum is learned. At the critical point it
is power-law distributed, $P_+(\Delta)\sim\Delta^\theta$ for $\Delta>0$ and
$P_-(\Delta)\sim(-\Delta)^{-\gamma}$ for $\Delta<0$, with $\theta\approx0.3$
and $\gamma\approx0.2$. This observation suggests that near the transition the
loss landscape has a hierarchical structure and that the learning dynamics is
prone to avalanche-like dynamics, with abrupt changes in the set of patterns
that are learned."),
Mario Geiger, Stefano Spigler, Stéphane d'Ascoli, Levent Sagun, Marco Baity-Jesi, Giulio Biroli, Matthieu Wyart,
arXiv: [1809.09349](http://arxiv.org/abs/1809.09349v2),
9/2018

- ["Monge-Ampère Flow for Generative Modeling"](
http://arxiv.org/abs/1809.10188v1
"We present a deep generative model, named Monge-Amp\`ere flow, which builds
on continuous-time gradient flow arising from the Monge-Amp\`ere equation in
optimal transport theory. The generative map from the latent space to the data
space follows a dynamical system, where a learnable potential function guides a
compressible fluid to flow towards the target density distribution. Training of
the model amounts to solving an optimal control problem. The Monge-Amp\`ere
flow has tractable likelihoods and supports efficient sampling and inference.
One can easily impose symmetry constraints in the generative model by designing
suitable scalar potential functions. We apply the approach to unsupervised
density estimation of the MNIST dataset and variational calculation of the
two-dimensional Ising model at the critical point. This approach brings
insights and techniques from Monge-Amp\`ere equation, optimal transport, and
fluid dynamics into reversible flow-based generative models."),
Linfeng Zhang, Weinan E, Lei Wang,
arXiv: [1809.10188](http://arxiv.org/abs/1809.10188v1),
9/2018

- ["Deep learning systems as complex networks"](
http://arxiv.org/abs/1809.10941v1
"Thanks to the availability of large scale digital datasets and massive
amounts of computational power, deep learning algorithms can learn
representations of data by exploiting multiple levels of abstraction. These
machine learning methods have greatly improved the state-of-the-art in many
challenging cognitive tasks, such as visual object recognition, speech
processing, natural language understanding and automatic translation. In
particular, one class of deep learning models, known as deep belief networks,
can discover intricate statistical structure in large data sets in a completely
unsupervised fashion, by learning a generative model of the data using
Hebbian-like learning mechanisms. Although these self-organizing systems can be
conveniently formalized within the framework of statistical mechanics, their
internal functioning remains opaque, because their emergent dynamics cannot be
solved analytically. In this article we propose to study deep belief networks
using techniques commonly employed in the study of complex networks, in order
to gain some insights into the structural and functional properties of the
computational graph resulting from the learning process."),
Alberto Testolin, Michele Piccolini, Samir Suweis,
arXiv: [1809.10941](http://arxiv.org/abs/1809.10941v1),
9/2018

- ["Topographic Representation for Quantum Machine Learning"](
http://arxiv.org/abs/1810.06992v1
"This paper proposes a brain-inspired approach to quantum machine learning
with the goal of circumventing many of the complications of other approaches.
The fact that quantum processes are unitary presents both opportunities and
challenges. A principal opportunity is that a large number of computations can
be carried out in parallel in linear superposition, that is, quantum
parallelism. The challenge is that the process is linear, and most approaches
to machine learning depend significantly on nonlinear processes. Fortunately,
the situation is not hopeless, for we know that nonlinear processes can be
embedded in unitary processes, as is familiar from the circuit model of quantum
computation. This paper explores an approach to the quantum implementation of
machine learning involving nonlinear functions operating on information
represented topographically (by computational maps), as common in neural
cortex."),
Bruce MacLennan,
arXiv: [1810.06992](http://arxiv.org/abs/1810.06992v1),
10/2018

- ["Free energies of Boltzmann Machines: self-averaging, annealed and
  replica symmetric approximations in the thermodynamic limit"](
http://arxiv.org/abs/1810.11075v1
"Restricted Boltzmann machines (RBMs) constitute one of the main models for
machine statistical inference and they are widely employed in Artificial
Intelligence as powerful tools for (deep) learning. However, in contrast with
countless remarkable practical successes, their mathematical formalization has
been largely elusive: from a statistical-mechanics perspective these systems
display the same (random) Gibbs measure of bi-partite spin-glasses, whose
rigorous treatment is notoriously difficult. In this work, beyond providing a
brief review on RBMs, we aim to contribute to their analytical investigation,
by considering two distinct realizations of their weights (i.e., Boolean and
Gaussian) and studying the properties of their related free energies. More
precisely, focusing on a RBM characterized by digital couplings, we first
extend the Pastur-Shcherbina-Tirozzi method (originally developed for the
Hopfield model) to prove the self-averaging property for the free energy, over
its quenched expectation, in the infinite volume limit, then we explicitly
calculate its simplest approximation, namely its annealed bound. Next, focusing
on a RBM characterized by analogical weights, we extend Guerra's interpolating
scheme to obtain a control of the quenched free-energy under the assumption of
replica symmetry: we get self-consistencies for the order parameters (in full
agreement with the existing Literature) as well as the critical line for
ergodicity breaking that turns out to be the same obtained in AGS theory. As we
discuss, this analogy stems from the slow-noise universality. Finally, glancing
beyond replica symmetry, we analyze the fluctuations of the overlaps for a
correct estimation of the (slow) noise affecting the retrieval of the signal,
and by a stability analysis we recover the Aizenman-Contucci identities typical
of glassy systems."),
Elena Agliari, Adriano Barra, Brunello Tirozzi,
arXiv: [1810.11075](http://arxiv.org/abs/1810.11075v1),
10/2018

- ["A jamming transition from under- to over-parametrization affects loss
  landscape and generalization"](
http://arxiv.org/abs/1810.09665v1
"We argue that in fully-connected networks a phase transition delimits the
over- and under-parametrized regimes where fitting can or cannot be achieved.
Under some general conditions, we show that this transition is sharp for the
hinge loss. In the whole over-parametrized regime, poor minima of the loss are
not encountered during training since the number of constraints to satisfy is
too small to hamper minimization. Our findings support a link between this
transition and the generalization properties of the network: as we increase the
number of parameters of a given model, starting from an under-parametrized
network, we observe that the generalization error displays three phases: (i)
initial decay, (ii) increase until the transition point --- where it displays a
cusp --- and (iii) power law decay toward a constant for the rest of the
over-parametrized regime. Thereby we identify the region where the classical
phenomenon of over-fitting takes place, and the region where the model keeps
improving, in line with previous empirical observations for modern neural
networks. The theoretical results presented here appeared elsewhere for a
physics audience. The results on generalization are new."),
Stefano Spigler, Mario Geiger, Stéphane d'Ascoli, Levent Sagun, Giulio Biroli, Matthieu Wyart,
arXiv: [1810.09665](http://arxiv.org/abs/1810.09665v1),
10/2018

- ["The Role of Data in Model Building and Prediction: A Survey Through
  Examples"](
http://arxiv.org/abs/1810.10446v1
"The goal of Science is to understand phenomena and systems in order to
predict their development and gain control over them. In the scientific process
of knowledge elaboration, a crucial role is played by models which, in the
language of quantitative sciences, mean abstract mathematical or algorithmical
representations. This short review discusses a few key examples from Physics,
taken from dynamical systems theory, biophysics, and statistical mechanics,
representing three paradigmatic procedures to build models and predictions from
available data. In the case of dynamical systems we show how predictions can be
obtained in a virtually model-free framework using the methods of analogues,
and we briefly discuss other approaches based on machine learning methods. In
cases where the complexity of systems is challenging, like in biophysics, we
stress the necessity to include part of the empirical knowledge in the models
to gain the minimal amount of realism. Finally, we consider many body systems
where many (temporal or spatial) scales are at play and show how to derive from
data a dimensional reduction in terms of a Langevin dynamics for their slow
components."),
Marco Baldovin, Fabio Cecconi, Massimo Cencini, Andrea Puglisi, Angelo Vulpiani,
arXiv: [1810.10446](http://arxiv.org/abs/1810.10446v1),
10/2018

- ["Toward an AI Physicist for Unsupervised Learning"](
http://arxiv.org/abs/1810.10525v2
"We investigate opportunities and challenges for improving unsupervised
machine learning using four common strategies with a long history in physics:
divide-and-conquer, Occam's Razor, unification, and lifelong learning. Instead
of using one model to learn everything, we propose a novel paradigm centered
around the learning and manipulation of *theories*, which parsimoniously
predict both aspects of the future (from past observations) and the domain in
which these predictions are accurate. Specifically, we propose a novel
generalized-mean-loss to encourage each theory to specialize in its
comparatively advantageous domain, and a differentiable description length
objective to downweight bad data and "snap" learned theories into simple
symbolic formulas. Theories are stored in a "theory hub", which continuously
unifies learned theories and can propose theories when encountering new
environments. We test our implementation, the "AI Physicist" learning agent, on
a suite of increasingly complex physics environments. From unsupervised
observation of trajectories through worlds involving random combinations of
gravity, electromagnetism, harmonic motion and elastic bounces, our agent
typically learns faster and produces mean-squared prediction errors about a
billion times smaller than a standard feedforward neural net of comparable
complexity, typically recovering integer and rational theory parameters
exactly. Our agent successfully identifies domains with different laws of
motion also for a nonlinear chaotic double pendulum in a piecewise constant
force field."),
Tailin Wu, Max Tegmark,
arXiv: [1810.10525](http://arxiv.org/abs/1810.10525v2),
10/2018



- ["The effect of retardation in the random networks of excitable nodes
  embeddable in the Euclidean space"](
http://arxiv.org/abs/1808.08495v1
"Some features of random networks with excitable nodes that are embeddable in
the Euclidean space are not describable in terms of the conventional integrate
and fire model (IFM) alone, and some further details should be involved. In the
present paper we consider the effect of the retardation, i.e. the time that is
needed for a signal to traverse between two agents. This effect becomes
important to discover the differences between e.g. the neural networks with low
and fast axon conduct times. We show that the inclusion of the retardation
effects makes some important changes in the statistical properties of the
system. It considerably suppresses/restricts the amplitude of the possible
oscillations in the random network. Additionally, it causes the critical
exponents in the critical regime to considerably change."),
M. N. Najafi, M. Rahimi,
arXiv: [1808.08495](http://arxiv.org/abs/1808.08495v1),
8/2018

- ["Statistical Neurodynamics of Deep Networks: Geometry of Signal Spaces"](
http://arxiv.org/abs/1808.07169v1
"Statistical neurodynamics studies macroscopic behaviors of randomly connected
neural networks. We consider a deep layered feedforward network where input
signals are processed layer by layer. The manifold of input signals is embedded
in a higher dimensional manifold of the next layer as a curved submanifold,
provided the number of neurons is larger than that of inputs. We show
geometrical features of the embedded manifold, proving that the manifold
enlarges or shrinks locally isotropically so that it is always embedded
conformally. We study the curvature of the embedded manifold. The scalar
curvature converges to a constant or diverges to infinity slowly. The distance
between two signals also changes, converging eventually to a stable fixed
value, provided both the number of neurons in a layer and the number of layers
tend to infinity. This causes a problem, since when we consider a curve in the
input space, it is mapped as a continuous curve of fractal nature, but our
theory contradictorily suggests that the curve eventually converges to a
discrete set of equally spaced points. In reality, the numbers of neurons and
layers are finite and thus, it is expected that the finite size effect causes
the discrepancies between our theory and reality. We need to further study the
discrepancies to understand their implications on information processing."),
Shun-ichi Amari, Ryo Karakida, Masafumi Oizumi,
arXiv: [1808.07169](http://arxiv.org/abs/1808.07169v1),
8/2018

- ["Artificial Neural Networks in Fluid Dynamics: A Novel Approach to the
  Navier-Stokes Equations"](
http://arxiv.org/abs/1808.06604v1
"Neural networks have been used to solve different types of large data related
problems in many different fields.This project takes a novel approach to
solving the Navier-Stokes Equations for turbulence by training a neural network
using Bayesian Cluster and SOM neighbor weighting to map ionospheric velocity
fields based on 3-dimensional inputs. Parameters used in this problem included
the velocity, Reynolds number, Prandtl number, and temperature. In this project
data was obtained from Johns-Hopkins University to train the neural network
using MATLAB. The neural network was able to map the velocity fields within a
sixty-seven percent accuracy of the validation data used. Further studies will
focus on higher accuracy and solving further non-linear differential equations
using convolutional neural networks."),
Megan McCracken,
arXiv: [1808.06604](http://arxiv.org/abs/1808.06604v1),
8/2018

- ["Geometry and symmetry in quantum Boltzmann machine"](
http://arxiv.org/abs/1808.04567v1
"Quantum Boltzmann machine extends the classical Boltzmann machine learning to
the quantum regime, which makes its power to simulate the quantum states beyond
the classical probability distributions. We develop the BFGS algorithm to study
the corresponding optimization problem in quantum Boltzmann machine, especially
focus on the target states being a family of states with parameters. As an
typical example, we study the target states being the real symmetric two-qubit
pure states, and we find two obvious features shown in the numerical results on
the minimal quantum relative entropy: First, the minimal quantum relative
entropy in the first and the third quadrants is zero; Second, the minimal
quantum relative entropy is symmetric with the axes $y=x$ and $y=-x$ even with
one qubit hidden layer. Then we theoretically prove these two features from the
geometric viewpoint and the symmetry analysis. Our studies show that the
traditional physical tools can be used to help us to understand some
interesting results from quantum Boltzmann machine learning."),
Hai-Jing Song, Tieling Song, Qi-Kai He, Yang Liu, D. L. Zhou,
arXiv: [1808.04567](http://arxiv.org/abs/1808.04567v1),
8/2018

- ["Geometry of energy landscapes and the optimizability of deep neural
  networks"](
http://arxiv.org/abs/1808.00408v1
"Deep neural networks are workhorse models in machine learning with multiple
layers of non-linear functions composed in series. Their loss function is
highly non-convex, yet empirically even gradient descent minimisation is
sufficient to arrive at accurate and predictive models. It is hitherto unknown
why are deep neural networks easily optimizable. We analyze the energy
landscape of a spin glass model of deep neural networks using random matrix
theory and algebraic geometry. We analytically show that the multilayered
structure holds the key to optimizability: Fixing the number of parameters and
increasing network depth, the number of stationary points in the loss function
decreases, minima become more clustered in parameter space, and the tradeoff
between the depth and width of minima becomes less severe. Our analytical
results are numerically verified through comparison with neural networks
trained on a set of classical benchmark datasets. Our model uncovers generic
design principles of machine learning models."),
Simon Becker, Yao Zhang, Alpha A. Lee,
arXiv: [1808.00408](http://arxiv.org/abs/1808.00408v1),
8/2018

- ["TherML: Thermodynamics of Machine Learning"](
http://arxiv.org/abs/1807.04162v2
"In this work we offer a framework for reasoning about a wide class of
existing objectives in machine learning. We develop a formal correspondence
between this work and thermodynamics and discuss its implications."),
Alexander A. Alemi, Ian Fischer,
arXiv: [1807.04162](http://arxiv.org/abs/1807.04162v2),
7/2018



- ["Supervised learning with generalized tensor networks"](
http://arxiv.org/abs/1806.05964v1
"Tensor networks have found a wide use in a variety of applications in physics
and computer science, recently leading to both theoretical insights as well as
practical algorithms in machine learning. In this work we explore the
connection between tensor networks and probabilistic graphical models, and show
that it motivates the definition of generalized tensor networks where
information from a tensor can be copied and reused in other parts of the
network. We discuss the relationship between generalized tensor network
architectures used in quantum physics, such as String-Bond States and Entangled
Plaquette States, and architectures commonly used in machine learning. We
provide an algorithm to train these networks in a supervised learning context
and show that they overcome the limitations of regular tensor networks in
higher dimensions, while keeping the computation efficient. A method to combine
neural networks and tensor networks as part of a common deep learning
architecture is also introduced. We benchmark our algorithm for several
generalized tensor network architectures on the task of classifying images and
sounds, and show that they outperform previously introduced tensor network
algorithms. Some of the models we consider can be realized on a quantum
computer and may guide the development of near-term quantum machine learning
architectures."),
Ivan Glasser, Nicola Pancotti, J. Ignacio Cirac,
arXiv: [1806.05964](http://arxiv.org/abs/1806.05964v1),
6/2018

- ["Universal Statistics of Fisher Information in Deep Neural Networks: Mean
  Field Approach"](
http://arxiv.org/abs/1806.01316v1
"This study analyzes the Fisher information matrix (FIM) by applying
mean-field theory to deep neural networks with random weights. We theoretically
find novel statistics of the FIM, which are universal among a wide class of
deep networks with any number of layers and various activation functions.
Although most of the FIM's eigenvalues are close to zero, the maximum
eigenvalue takes on a huge value and the eigenvalue distribution has an
extremely long tail. These statistics suggest that the shape of a loss
landscape is locally flat in most dimensions, but strongly distorted in the
other dimensions. Moreover, our theory of the FIM leads to quantitative
evaluation of learning in deep networks. First, the maximum eigenvalue enables
us to estimate an appropriate size of a learning rate for steepest gradient
methods to converge. Second, the flatness induced by the small eigenvalues is
connected to generalization ability through a norm-based capacity measure."),
Ryo Karakida, Shotaro Akaho, Shun-ichi Amari,
arXiv: [1806.01316](http://arxiv.org/abs/1806.01316v1),
6/2018

- ["Entropy and mutual information in models of deep neural networks"](
http://arxiv.org/abs/1805.09785v1
"We examine a class of deep learning models with a tractable method to compute
information-theoretic quantities. Our contributions are three-fold: (i) We show
how entropies and mutual informations can be derived from heuristic statistical
physics methods, under the assumption that weight matrices are independent and
orthogonally-invariant. (ii) We extend particular cases in which this result is
known to be rigorously exact by providing a proof for two-layers networks with
Gaussian random weights, using the recently introduced adaptive interpolation
method. (iii) We propose an experiment framework with generative models of
synthetic datasets, on which we train deep neural networks with a weight
constraint designed so that the assumption in (i) is verified during learning.
We study the behavior of entropies and mutual informations throughout learning
and conclude that, in the proposed setting, the relationship between
compression and generalization remains elusive."),
Marylou Gabrié, Andre Manoel, Clément Luneau, Jean Barbier, Nicolas Macris, Florent Krzakala, Lenka Zdeborová,
arXiv: [1805.09785](http://arxiv.org/abs/1805.09785v1),
5/2018

- ["Physically optimizing inference"](
http://arxiv.org/abs/1805.07512v2
"Data is scaling exponentially in fields ranging from genomics to neuroscience
to economics. A central question is whether modern machine learning methods can
be applied to construct predictive models based on large data sets drawn from
complex, natural systems like cells and brains. In machine learning, the
predictive power or generalizability of a model is determined by the statistics
of training data. In this paper, we ask how predictive inference is impacted
when training data is generated by the statistical behavior of a physical
system. We develop an information-theoretic analysis of a canonical problem,
spin network inference. Our analysis reveals the essential role that thermal
fluctuations play in determining the efficiency of predictive inference.
Thermal noise drives a system to explore a range of configurations providing
`raw' information for a learning algorithm to construct a predictive model.
Conversely, thermal energy degrades information by blurring energetic
differences between network states. In general, spin networks have an intrinsic
optimal temperature at which inference becomes maximally efficient. Simple
active learning protocols allow optimization of network temperature, without
prior knowledge, to dramatically increase the efficiency of inference. Our
results reveal a fundamental link between physics and information and show how
the physical environment can be tuned to optimize the efficiency of machine
learning."),
Audrey Huang, Benjamin Sheldan, David A. Sivak, Matt Thomson,
arXiv: [1805.07512](http://arxiv.org/abs/1805.07512v2),
5/2018

- ["Neural Networks as Interacting Particle Systems: Asymptotic Convexity of
  the Loss Landscape and Universal Scaling of the Approximation Error"](
http://arxiv.org/abs/1805.00915v2
"Neural networks, a central tool in machine learning, have demonstrated
remarkable, high fidelity performance on image recognition and classification
tasks. These successes evince an ability to accurately represent high
dimensional functions, potentially of great use in computational and applied
mathematics. That said, there are few rigorous results about the representation
error and trainability of neural networks. Here we characterize both the error
and the scaling of the error with the size of the network by reinterpreting the
standard optimization algorithm used in machine learning applications,
stochastic gradient descent, as the evolution of a particle system with
interactions governed by a potential related to the objective or "loss"
function used to train the network. We show that, when the number $n$ of
parameters is large, the empirical distribution of the particles descends on a
convex landscape towards a minimizer at a rate independent of $n$. We establish
a Law of Large Numbers and a Central Limit Theorem for the empirical
distribution, which together show that the approximation error of the network
universally scales as $O(n^{-1})$. Remarkably, these properties do not depend
on the dimensionality of the domain of the function that we seek to represent.
Our analysis also quantifies the scale and nature of the noise introduced by
stochastic gradient descent and provides guidelines for the step size and batch
size to use when training a neural network. We illustrate our findings on
examples in which we train neural network to learn the energy function of the
continuous 3-spin model on the sphere. The approximation error scales as our
analysis predicts in as high a dimension as $d=25$."),
Grant M. Rotskoff, Eric Vanden-Eijnden,
arXiv: [1805.00915](http://arxiv.org/abs/1805.00915v2),
5/2018



- ["Neural networks as Interacting Particle Systems: Asymptotic convexity of
  the Loss Landscape and Universal Scaling of the Approximation Error"](
http://arxiv.org/abs/1805.00915v1
"Neural networks, a central tool in machine learning, have demonstrated
remarkable, high fidelity performance on image recognition and classification
tasks. These successes evince an ability to accurately represent high
dimensional functions, potentially of great use in computational and applied
mathematics. That said, there are few rigorous results about the representation
error and trainability of neural networks, as well as how they scale with the
network size. Here we characterize both the error and scaling by reinterpreting
the standard optimization algorithm used in machine learning applications,
stochastic gradient descent, as the evolution of a particle system with
interactions governed by a potential related to the objective or "loss"
function used to train the network. We show that, when the number $n$ of
parameters is large, the empirical distribution of the particles descends on a
convex landscape towards a minimizer at a rate independent of $n$. We establish
a Law of Large Numbers and a Central Limit Theorem for the empirical
distribution, which together show that the approximation error of the network
universally scales as $o(n^{-1})$. Remarkably, these properties do not depend
on the dimensionality of the domain of the function that we seek to represent.
Our analysis also quantifies the scale and nature of the noise introduced by
stochastic gradient descent and provides guidelines for the step size and batch
size to use when training a neural network. We illustrate our findings on
examples in which we train neural network to learn the energy function of the
continuous 3-spin model on the sphere. The approximation error scales as our
analysis predicts in as high a dimension as $d=25$."),
Grant M. Rotskoff, Eric Vanden-Eijnden,
arXiv: [1805.00915](http://arxiv.org/abs/1805.00915v1),
5/2018



- ["Supervised machine learning algorithms based on generalized Gibbs
  ensembles"](
http://arxiv.org/abs/1804.03546v1
"Machine learning algorithms often take inspiration from established results
and knowledge from statistical physics. A prototypical example is the Boltzmann
machine algorithm for supervised learning, which utilizes knowledge of
classical thermal partition functions and the Boltzmann distribution. Recent
advances in the study of non-equilibrium quantum integrable systems, which
never thermalize, have lead to the exploration of a wider class of statistical
ensembles. These systems may be described by the so-called generalized Gibbs
ensemble, which incorporates a number of "effective temperatures". We propose
that these generalized Gibbs ensembles can be successfully applied as the basis
of a Boltzmann-machine-like learning algorithm, which operates by learning the
optimal values of effective temperatures. We apply our algorithm to the
classification of handwritten digits in the MNIST database. While lower error
rates can be found with other state-of-the-art algorithms, we find that our
algorithm reaches relatively low error rates while learning a much smaller
number of parameters than would be needed in a traditional Boltzmann machine,
thereby reducing computational cost."),
Tatjana Puskarov, Axel Cortes Cubero,
arXiv: [1804.03546](http://arxiv.org/abs/1804.03546v1),
4/2018

- ["The Loss Surface of XOR Artificial Neural Networks"](
http://arxiv.org/abs/1804.02411v1
"Training an artificial neural network involves an optimization process over
the landscape defined by the cost (loss) as a function of the network
parameters. We explore these landscapes using optimisation tools developed for
potential energy landscapes in molecular science. The number of local minima
and transition states (saddle points of index one), as well as the ratio of
transition states to minima, grow rapidly with the number of nodes in the
network. There is also a strong dependence on the regularisation parameter,
with the landscape becoming more convex (fewer minima) as the regularisation
term increases. We demonstrate that in our formulation, stationary points for
networks with $N_h$ hidden nodes, including the minimal network required to fit
the XOR data, are also stationary points for networks with $N_{h} +1$ hidden
nodes when all the weights involving the additional nodes are zero. Hence,
smaller networks optimized to train the XOR data are embedded in the landscapes
of larger networks. Our results clarify certain aspects of the classification
and sensitivity (to perturbations in the input data) of minima and saddle
points for this system, and may provide insight into dropout and network
compression."),
Dhagash Mehta, Xiaojun Zhao, Edgar A. Bernal, David J. Wales,
arXiv: [1804.02411](http://arxiv.org/abs/1804.02411v1),
4/2018




- ["Matrix Product Operators for Sequence to Sequence Learning"](
http://arxiv.org/abs/1803.10908v1
"The method of choice to study one-dimensional strongly interacting many body
quantum systems is based on matrix product states and operators. Such method
allows to explore the most relevant, and numerically manageable, portion of an
exponentially large space. Here we show how to construct a machine learning
model in which matrix product operators are trained to implement sequence to
sequence prediction, i.e. given a sequence at a time step, it allows one to
predict the next sequence. We then apply our algorithm to cellular automata
(for which we show exact analytical solutions in terms of matrix product
operators), and to nonlinear coupled maps. We show advantages of the proposed
algorithm when compared to conditional random fields and bidirectional long
short-term memory neural network. To highlight the flexibility of the
algorithm, we also show how it can perform classification tasks."),
Chu Guo, Zhanming Jie, Wei Lu, Dario Poletti,
arXiv: [1803.10908](http://arxiv.org/abs/1803.10908v1),
3/2018


- ["Protection against Cloning for Deep Learning"](
http://arxiv.org/abs/1803.10995v1
"The susceptibility of deep learning to adversarial attack can be understood
in the framework of the Renormalisation Group (RG) and the vulnerability of a
specific network may be diagnosed provided the weights in each layer are known.
An adversary with access to the inputs and outputs could train a second network
to clone these weights and, having identified a weakness, use them to compute
the perturbation of the input data which exploits it. However, the RG framework
also provides a means to poison the outputs of the network imperceptibly,
without affecting their legitimate use, so as to prevent such cloning of its
weights and thereby foil the generation of adversarial data."),
Richard Kenway,
arXiv: [1803.10995](http://arxiv.org/abs/1803.10995v1),
3/2018

- ["Bridging Many-Body Quantum Physics and Deep Learning via Tensor Networks"](
http://arxiv.org/abs/1803.09780v1
"The harnessing of modern computational abilities for many-body wave-function
representations is naturally placed as a prominent avenue in contemporary
condensed matter physics. Specifically, highly expressive computational schemes
that are able to efficiently represent the entanglement properties of
many-particle systems are of interest. In the seemingly unrelated field of
machine learning, deep network architectures have exhibited an unprecedented
ability to tractably encompass the dependencies characterizing hard learning
tasks such as image classification. However, key questions regarding deep
learning architecture design still have no adequate theoretical answers. In
this paper, we establish a Tensor Network (TN) based common language between
the two disciplines, which allows us to offer bidirectional contributions. By
showing that many-body wave-functions are structurally equivalent to mappings
of ConvACs and RACs, we construct their TN equivalents, and suggest quantum
entanglement measures as natural quantifiers of dependencies in such networks.
Accordingly, we propose a novel entanglement based deep learning design scheme.
In the other direction, we identify that an inherent re-use of information in
state-of-the-art deep learning architectures is a key trait that distinguishes
them from TNs. We suggest a new TN manifestation of information re-use, which
enables TN constructs of powerful architectures such as deep recurrent networks
and overlapping convolutional networks. This allows us to theoretically
demonstrate that the entanglement scaling supported by these architectures can
surpass that of commonly used TNs in 1D, and can support volume law
entanglement in 2D polynomially more efficiently than RBMs. We thus provide
theoretical motivation to shift trending neural-network based wave-function
representations closer to state-of-the-art deep learning architectures."),
Yoav Levine, Or Sharir, Nadav Cohen, Amnon Shashua,
arXiv: [1803.09780](http://arxiv.org/abs/1803.09780v1),
3/2018

- ["Learning architectures based on quantum entanglement: a simple matrix
  product state algorithm for image recognition"](
http://arxiv.org/abs/1803.09111v1
"It is a fundamental, but still elusive question whether methods based on
quantum mechanics, in particular on quantum entanglement, can be used for
classical information processing and machine learning. Even partial answer to
this question would bring important insights to both fields of both machine
learning and quantum mechanics. In this work, we implement simple numerical
experiments, related to pattern/images classification, in which we represent
the classifiers by quantum matrix product states (MPS). Classical machine
learning algorithm is then applied to these quantum states. We explicitly show
how quantum features (i.e., single-site and bipartite entanglement) can emerge
in such represented images; entanglement characterizes here the importance of
data, and this information can be practically used to improve the learning
procedures. Thanks to the low demands on the dimensions and number of the
unitary matrices, necessary to construct the MPS, we expect such numerical
experiments could open new paths in classical machine learning, and shed at
same time lights on generic quantum simulations/computations."),
Yuhan Liu, Xiao Zhang, Maciej Lewenstein, Shi-Ju Ran,
arXiv: [1803.09111](http://arxiv.org/abs/1803.09111v1),
3/2018



- ["Comparing Dynamics: Deep Neural Networks versus Glassy Systems"](
http://arxiv.org/abs/1803.06969v1
"We analyze numerically the training dynamics of deep neural networks (DNN) by
using methods developed in statistical physics of glassy systems. The two main
issues we address are the complexity of the loss-landscape and of the dynamics
within it, and to what extent DNNs share similarities with glassy systems. Our
findings, obtained for different architectures and datasets, suggest that
during the training process the dynamics slows down because of an increasingly
large number of flat directions. At large times, when the loss is approaching
zero, the system diffuses at the bottom of the landscape. Despite some
similarities with the dynamics of mean-field glassy systems, in particular, the
absence of barrier crossing, we find distinctive dynamical behaviors in the two
cases, showing that the statistical properties of the corresponding loss and
energy landscapes are different. In contrast, when the network is
under-parametrized we observe a typical glassy behavior, thus suggesting the
existence of different phases depending on whether the network is
under-parametrized or over-parametrized."),
M. Baity-Jesi, L. Sagun, M. Geiger, S. Spigler, G. Ben Arous, C. Cammarota, Y. LeCun, M. Wyart, G. Biroli,
arXiv: [1803.06969](http://arxiv.org/abs/1803.06969v1),
3/2018

- ["Vulnerability of Deep Learning"](
http://arxiv.org/abs/1803.06111v1
"The Renormalisation Group (RG) provides a framework in which it is possible
to assess whether a deep-learning network is sensitive to small changes in the
input data and hence prone to error, or susceptible to adversarial attack.
Distinct classification outputs are associated with different RG fixed points
and sensitivity to small changes in the input data is due to the presence of
relevant operators at a fixed point. A numerical scheme, based on Monte Carlo
RG ideas, is proposed for identifying the existence of relevant operators and
the corresponding directions of greatest sensitivity in the input data. Thus, a
trained deep-learning network may be tested for its robustness and, if it is
vulnerable to attack, dangerous perturbations of the input data identified."),
Richard Kenway,
arXiv: [1803.06111](http://arxiv.org/abs/1803.06111v1),
3/2018

- ["Thermodynamics of Restricted Boltzmann Machines and related learning
  dynamics"](
http://arxiv.org/abs/1803.01960v1
"We analyze the learning process of the restricted Boltzmann machine (RBM), a
certain type of generative models used in the context of unsupervised learning.
In a first step, we investigate the thermodynamics properties by considering a
realistic statistical ensemble of RBM, assuming the information content of the
RBM to be mainly reflected by spectral properties of its weight matrix W. A
phase diagram is obtained which seems at first sight similar to the one of the
Sherrington-Kirkpatrick (SK) model with ferromagnetic couplings. The main
difference resides in the structure of the ferromagnetic phase which may or may
not be of compositional type, depending mainly on the distribution's kurtosis
of the singular vectors components of W. In a second step the learning dynamics
of an RBM from arbitrary data is studied in thermodynamic limit. A "typical"
learning trajectory is shown to solve an effective dynamical equation, based on
the aforementioned ensemble average and involving explicitly order parameters
obtained from the thermodynamic analysis. This accounts in particular for the
dominant singular values evolution and how this is driven by the input data: in
the linear regime at the beginning of the learning, they correspond to unstable
deformation modes of W reflecting dominant covariance modes of the data. In the
non-linear regime it is seen how the selected modes interact in later stages of
the learning procedure, by eventually imposing a matching between order
parameters with their empirical counterparts estimated from the data.
Experiments on both artificial and real data illustrate these considerations,
showing in particular how the RBM operates in the ferromagnetic compositional
phase."),
Aurélien Decelle, Giancarlo Fissore, Cyril Furtlehner,
arXiv: [1803.01960](http://arxiv.org/abs/1803.01960v1),
3/2018

- ["Energy-entropy competition and the effectiveness of stochastic gradient
  descent in machine learning"](
http://arxiv.org/abs/1803.01927v1
"Finding parameters that minimise a loss function is at the core of many
machine learning methods. The Stochastic Gradient Descent algorithm is widely
used and delivers state of the art results for many problems. Nonetheless,
Stochastic Gradient Descent typically cannot find the global minimum, thus its
empirical effectiveness is hitherto mysterious. We derive a correspondence
between parameter inference and free energy minimisation in statistical
physics. The degree of undersampling plays the role of temperature. Analogous
to the energy-entropy competition in statistical physics, wide but shallow
minima can be optimal if the system is undersampled, as is typical in many
applications. Moreover, we show that the stochasticity in the algorithm has a
non-trivial correlation structure which systematically biases it towards wide
minima. We illustrate our argument with two prototypical models: image
classification using deep learning, and a linear neural network where we can
analytically reveal the relationship between entropy and out-of-sample error."),
Yao Zhang, Andrew M. Saxe, Madhu S. Advani, Alpha A. Lee,
arXiv: [1803.01927](http://arxiv.org/abs/1803.01927v1),
3/2018



- ["Energy-entropy competition and the effectiveness of stochastic gradient
  descent in machine learning"](
http://arxiv.org/abs/1803.01927v1
"Finding parameters that minimise a loss function is at the core of many
machine learning methods. The Stochastic Gradient Descent algorithm is widely
used and delivers state of the art results for many problems. Nonetheless,
Stochastic Gradient Descent typically cannot find the global minimum, thus its
empirical effectiveness is hitherto mysterious. We derive a correspondence
between parameter inference and free energy minimisation in statistical
physics. The degree of undersampling plays the role of temperature. Analogous
to the energy-entropy competition in statistical physics, wide but shallow
minima can be optimal if the system is undersampled, as is typical in many
applications. Moreover, we show that the stochasticity in the algorithm has a
non-trivial correlation structure which systematically biases it towards wide
minima. We illustrate our argument with two prototypical models: image
classification using deep learning, and a linear neural network where we can
analytically reveal the relationship between entropy and out-of-sample error."),
Yao Zhang, Andrew M. Saxe, Madhu S. Advani, Alpha A. Lee,
arXiv: [1803.01927](http://arxiv.org/abs/1803.01927v1),
3/2018


- ["The Mean-Field Approximation: Information Inequalities, Algorithms, and
  Complexity"](
http://arxiv.org/abs/1802.06126v2
"The mean field approximation to the Ising model is a canonical variational
tool that is used for analysis and inference in Ising models. We provide a
simple and optimal bound for the KL error of the mean field approximation for
Ising models on general graphs, and extend it to higher order Markov random
fields. Our bound improves on previous bounds obtained in work in the graph
limit literature by Borgs, Chayes, Lov\'asz, S\'os, and Vesztergombi and
another recent work by Basak and Mukherjee. Our bound is tight up to lower
order terms. Building on the methods used to prove the bound, along with
techniques from combinatorics and optimization, we study the algorithmic
problem of estimating the (variational) free energy for Ising models and
general Markov random fields. For a graph $G$ on $n$ vertices and interaction
matrix $J$ with Frobenius norm $\| J \|_F$, we provide algorithms that
approximate the free energy within an additive error of $\epsilon n \|J\|_F$ in
time $\exp(poly(1/\epsilon))$. We also show that approximation within $(n
\|J\|_F)^{1-\delta}$ is NP-hard for every $\delta > 0$. Finally, we provide
more efficient approximation algorithms, which find the optimal mean field
approximation, for ferromagnetic Ising models and for Ising models satisfying
Dobrushin's condition."),
Vishesh Jain, Frederic Koehler, Elchanan Mossel,
arXiv: [1802.06126](http://arxiv.org/abs/1802.06126v2),
2/2018

- ["Inferring relevant features: from QFT to PCA"](
http://arxiv.org/abs/1802.05756v1
"In many-body physics, renormalization techniques are used to extract aspects
of a statistical or quantum state that are relevant at large scale, or for low
energy experiments. Recent works have proposed that these features can be
formally identified as those perturbations of the states whose
distinguishability most resist coarse-graining. Here, we examine whether this
same strategy can be used to identify important features of an unlabeled
dataset. This approach indeed results in a technique very similar to kernel PCA
(principal component analysis), but with a kernel function that is
automatically adapted to the data, or "learned". We test this approach on
handwritten digits, and find that the most relevant features are significantly
better for classification than those obtained from a simple gaussian kernel."),
Cédric Bény,
arXiv: [1802.05756](http://arxiv.org/abs/1802.05756v1),
2/2018

- ["Critical Percolation as a Framework to Analyze the Training of Deep
  Networks"](
http://arxiv.org/abs/1802.02154v1
"In this paper we approach two relevant deep learning topics: i) tackling of
graph structured input data and ii) a better understanding and analysis of deep
networks and related learning algorithms. With this in mind we focus on the
topological classification of reachability in a particular subset of planar
graphs (Mazes). Doing so, we are able to model the topology of data while
staying in Euclidean space, thus allowing its processing with standard CNN
architectures. We suggest a suitable architecture for this problem and show
that it can express a perfect solution to the classification task. The shape of
the cost function around this solution is also derived and, remarkably, does
not depend on the size of the maze in the large maze limit. Responsible for
this behavior are rare events in the dataset which strongly regulate the shape
of the cost function near this global minimum. We further identify an obstacle
to learning in the form of poorly performing local minima in which the network
chooses to ignore some of the inputs. We further support our claims with
training experiments and numerical analysis of the cost function on networks
with up to $128$ layers."),
Zohar Ringel, Rodrigo de Bem,
arXiv: [1802.02154](http://arxiv.org/abs/1802.02154v1),
2/2018

- ["Scale-invariant Feature Extraction of Neural Network and Renormalization
  Group Flow"](
http://arxiv.org/abs/1801.07172v1
"Theoretical understanding of how deep neural network (DNN) extracts features
from input images is still unclear, but it is widely believed that the
extraction is performed hierarchically through a process of coarse-graining. It
reminds us of the basic concept of renormalization group (RG) in statistical
physics. In order to explore possible relations between DNN and RG, we use the
Restricted Boltzmann machine (RBM) applied to Ising model and construct a flow
of model parameters (in particular, temperature) generated by the RBM. We show
that the unsupervised RBM trained by spin configurations at various
temperatures from $T=0$ to $T=6$ generates a flow along which the temperature
approaches the critical value $T_c=2.27$. This behavior is opposite to the
typical RG flow of the Ising model. By analyzing various properties of the
weight matrices of the trained RBM, we discuss why it flows towards $T_c$ and
how the RBM learns to extract features of spin configurations."),
Satoshi Iso, Shotaro Shiba, Sumito Yokoo,
arXiv: [1801.07172](http://arxiv.org/abs/1801.07172v1),
1/2018

- ["A relativistic extension of Hopfield neural networks via the mechanical
  analogy"](
http://arxiv.org/abs/1801.01743v1
"We propose a modification of the cost function of the Hopfield model whose
salient features shine in its Taylor expansion and result in more than pairwise
interactions with alternate signs, suggesting a unified framework for handling
both with deep learning and network pruning. In our analysis, we heavily rely
on the Hamilton-Jacobi correspondence relating the statistical model with a
mechanical system. In this picture, our model is nothing but the relativistic
extension of the original Hopfield model (whose cost function is a quadratic
form in the Mattis magnetization which mimics the non-relativistic Hamiltonian
for a free particle). We focus on the low-storage regime and solve the model
analytically by taking advantage of the mechanical analogy, thus obtaining a
complete characterization of the free energy and the associated
self-consistency equations in the thermodynamic limit. On the numerical side,
we test the performances of our proposal with MC simulations, showing that the
stability of spurious states (limiting the capabilities of the standard Hebbian
construction) is sensibly reduced due to presence of unlearning contributions
in this extended framework."),
Adriano Barra, Matteo Beccaria, Alberto Fachechi,
arXiv: [1801.01743](http://arxiv.org/abs/1801.01743v1),
1/2018

- ["Learning Relevant Features of Data with Multi-scale Tensor Networks"](
http://arxiv.org/abs/1801.00315v1
"Inspired by coarse-graining approaches used in physics, we show how similar
algorithms can be adapted for data. The resulting algorithms are based on
layered tree tensor networks and scale linearly with both the dimension of the
input and the training set size. Computing most of the layers with an
unsupervised algorithm, then optimizing just the top layer for supervised
classification of the MNIST and fashion-MNIST data sets gives very good
results. We also discuss mixing a prior guess for supervised weights together
with an unsupervised representation of the data, yielding a smaller number of
features nevertheless able to give good performance."),
E. M. Stoudenmire,
arXiv: [1801.00315](http://arxiv.org/abs/1801.00315v1),
12/2017

- ["Information Perspective to Probabilistic Modeling: Boltzmann Machines
  versus Born Machines"](
http://arxiv.org/abs/1712.04144v1
"We compare and contrast the statistical physics and quantum physics inspired
approaches for unsupervised generative modeling of classical data. The two
approaches represent probabilities of observed data using energy-based models
and quantum states respectively.Classical and quantum information patterns of
the target datasets therefore provide principled guidelines for structural
design and learning in these two approaches. Taking the restricted Boltzmann
machines (RBM) as an example, we analyze the information theoretical bounds of
the two approaches. We verify our reasonings by comparing the performance of
RBMs of various architectures on the standard MNIST datasets."),
Song Cheng, Jing Chen, Lei Wang,
arXiv: [1712.04144](http://arxiv.org/abs/1712.04144v1),
12/2017

- ["Stochastic gradient descent performs variational inference, converges to
  limit cycles for deep networks"](
http://arxiv.org/abs/1710.11029v2
"Stochastic gradient descent (SGD) is widely believed to perform implicit
regularization when used to train deep neural networks, but the precise manner
in which this occurs has thus far been elusive. We prove that SGD minimizes an
average potential over the posterior distribution of weights along with an
entropic regularization term. This potential is however not the original loss
function in general. So SGD does perform variational inference, but for a
different loss than the one used to compute the gradients. Even more
surprisingly, SGD does not even converge in the classical sense: we show that
the most likely trajectories of SGD for deep networks do not behave like
Brownian motion around critical points. Instead, they resemble closed loops
with deterministic components. We prove that such "out-of-equilibrium" behavior
is a consequence of highly non-isotropic gradient noise in SGD; the covariance
matrix of mini-batch gradients for deep networks has a rank as small as 1% of
its dimension. We provide extensive empirical validation of these claims,
proven in the appendix."),
Pratik Chaudhari, Stefano Soatto,
arXiv: [1710.11029](http://arxiv.org/abs/1710.11029v2),
10/2017

- ["A Correspondence Between Random Neural Networks and Statistical Field
  Theory"](
http://arxiv.org/abs/1710.06570v1
"A number of recent papers have provided evidence that practical design
questions about neural networks may be tackled theoretically by studying the
behavior of random networks. However, until now the tools available for
analyzing random neural networks have been relatively ad-hoc. In this work, we
show that the distribution of pre-activations in random neural networks can be
exactly mapped onto lattice models in statistical physics. We argue that
several previous investigations of stochastic networks actually studied a
particular factorial approximation to the full lattice model. For random linear
networks and random rectified linear networks we show that the corresponding
lattice models in the wide network limit may be systematically approximated by
a Gaussian distribution with covariance between the layers of the network. In
each case, the approximate distribution can be diagonalized by Fourier
transformation. We show that this approximation accurately describes the
results of numerical simulations of wide random neural networks. Finally, we
demonstrate that in each case the large scale behavior of the random networks
can be approximated by an effective field theory."),
Samuel S. Schoenholz, Jeffrey Pennington, Jascha Sohl-Dickstein,
arXiv: [1710.06570](http://arxiv.org/abs/1710.06570v1),
10/2017

- ["Entanglement Entropy of Target Functions for Image Classification and
  Convolutional Neural Network"](
http://arxiv.org/abs/1710.05520v1
"The success of deep convolutional neural network (CNN) in computer vision
especially image classification problems requests a new information theory for
function of image, instead of image itself. In this article, after establishing
a deep mathematical connection between image classification problem and quantum
spin model, we propose to use entanglement entropy, a generalization of
classical Boltzmann-Shannon entropy, as a powerful tool to characterize the
information needed for representation of general function of image. We prove
that there is a sub-volume-law bound for entanglement entropy of target
functions of reasonable image classification problems. Therefore target
functions of image classification only occupy a small subspace of the whole
Hilbert space. As a result, a neural network with polynomial number of
parameters is efficient for representation of such target functions of image.
The concept of entanglement entropy can also be useful to characterize the
expressive power of different neural networks. For example, we show that to
maintain the same expressive power, number of channels $D$ in a convolutional
neural network should scale with the number of convolution layers $n_c$ as
$D\sim D_0^{\frac{1}{n_c}}$. Therefore, deeper CNN with large $n_c$ is more
efficient than shallow ones."),
Ya-Hui Zhang,
arXiv: [1710.05520](http://arxiv.org/abs/1710.05520v1),
10/2017

- ["Machine Learning by Two-Dimensional Hierarchical Tensor Networks: A
  Quantum Information Theoretic Perspective on Deep Architectures"](
http://arxiv.org/abs/1710.04833v1
"The resemblance between the methods used in studying quantum-many body
physics and in machine learning has drawn considerable attention. In
particular, tensor networks (TNs) and deep learning architectures bear striking
similarities to the extent that TNs can be used for machine learning. Previous
results used one-dimensional TNs in image recognition, showing limited
scalability and a high bond dimension. In this work, we train two-dimensional
hierarchical TNs to solve image recognition problems, using a training
algorithm derived from the multipartite entanglement renormalization ansatz
(MERA). This approach overcomes scalability issues and implies novel
mathematical connections among quantum many-body physics, quantum information
theory, and machine learning. While keeping the TN unitary in the training
phase, TN states can be defined, which optimally encodes each class of the
images into a quantum many-body state. We study the quantum features of the TN
states, including quantum entanglement and fidelity. We suggest these
quantities could be novel properties that characterize the image classes, as
well as the machine learning tasks. Our work could be further applied to
identifying possible quantum properties of certain artificial intelligence
methods."),
Ding Liu, Shi-Ju Ran, Peter Wittek, Cheng Peng, Raul Blázquez García, Gang Su, Maciej Lewenstein,
arXiv: [1710.04833](http://arxiv.org/abs/1710.04833v1),
10/2017

- ["Neural Networks Quantum States, String-Bond States and chiral
  topological states"](
http://arxiv.org/abs/1710.04045v2
"Neural Networks Quantum States have been recently introduced as an Ansatz for
describing the wave function of quantum many-body systems. We show that there
are strong connections between Neural Networks Quantum States in the form of
Restricted Boltzmann Machines and some classes of Tensor Network states in
arbitrary dimension. In particular we demonstrate that short-range Restricted
Boltzmann Machines are Entangled Plaquette States, while fully connected
Restricted Boltzmann Machines are String-Bond States with a non-local geometry
and low bond dimension. These results shed light on the underlying architecture
of Restricted Boltzmann Machines and their efficiency at representing many-body
quantum states. String-Bond States also provide a generic way of enhancing the
power of Neural Networks Quantum States and a natural generalization to systems
with larger local Hilbert space. We compare the advantages and drawbacks of
these different classes of states and present a method to combine them
together. This allows us to benefit from both the entanglement structure of
Tensor Networks and the efficiency of Neural Network Quantum States into a
single Ansatz capable of targeting the wave function of strongly correlated
systems. While it remains a challenge to describe states with chiral
topological order using traditional Tensor Networks, we show that Neural
Networks Quantum States and their String-Bond States extension can describe a
lattice Fractional Quantum Hall state exactly. In addition, we provide
numerical evidence that Neural Networks Quantum States can approximate a chiral
spin liquid with better accuracy than Entangled Plaquette States and local
String-Bond States. Our results demonstrate the efficiency of neural networks
to describe complex quantum wave functions and pave the way towards the use of
String-Bond States as a tool in more traditional machine learning applications."),
Ivan Glasser, Nicola Pancotti, Moritz August, Ivan D. Rodriguez, J. Ignacio Cirac,
arXiv: [1710.04045](http://arxiv.org/abs/1710.04045v2),
10/2017

- ["Mean-field theory of input dimensionality reduction in unsupervised deep
  neural networks"](
http://arxiv.org/abs/1710.01467v2
"Deep neural networks as powerful tools are widely used in various domains.
However, the nature of computations at each layer of the deep networks is far
from being well understood. Increasing the interpretability of deep neural
networks is thus important. Here, we construct a mean-field framework to
understand how compact representations are developed across layers, not only in
deterministic random deep networks but also in generative deep networks where
network parameters are learned from input data. Our theory shows that the deep
computation implements a dimensionality reduction while maintaining a finite
level of weak correlations between neurons for possible feature extraction.
This work may pave the way for understanding how a sensory hierarchy works in
general."),
Haiping Huang,
arXiv: [1710.01467](http://arxiv.org/abs/1710.01467v2),
10/2017


- ["Machine Learning by Two-Dimensional Hierarchical Tensor Networks: A
  Quantum Information Theoretic Perspective on Deep Architectures"](
http://arxiv.org/abs/1710.04833v1
"The resemblance between the methods used in studying quantum-many body
physics and in machine learning has drawn considerable attention. In
particular, tensor networks (TNs) and deep learning architectures bear striking
similarities to the extent that TNs can be used for machine learning. Previous
results used one-dimensional TNs in image recognition, showing limited
scalability and a high bond dimension. In this work, we train two-dimensional
hierarchical TNs to solve image recognition problems, using a training
algorithm derived from the multipartite entanglement renormalization ansatz
(MERA). This approach overcomes scalability issues and implies novel
mathematical connections among quantum many-body physics, quantum information
theory, and machine learning. While keeping the TN unitary in the training
phase, TN states can be defined, which optimally encodes each class of the
images into a quantum many-body state. We study the quantum features of the TN
states, including quantum entanglement and fidelity. We suggest these
quantities could be novel properties that characterize the image classes, as
well as the machine learning tasks. Our work could be further applied to
identifying possible quantum properties of certain artificial intelligence
methods."),
Ding Liu, Shi-Ju Ran, Peter Wittek, Cheng Peng, Raul Blázquez García, Gang Su, Maciej Lewenstein,
arXiv: [1710.04833](http://arxiv.org/abs/1710.04833v1),
10/2017

- ["Unsupervised Generative Modeling Using Matrix Product States"](
http://arxiv.org/abs/1709.01662v2
"Generative modeling, which learns joint probability distribution from
training data and generates samples according to it, is an important task in
machine learning and artificial intelligence. Inspired by probabilistic
interpretation of quantum physics, we propose a generative model using matrix
product states, which is a tensor network originally proposed for describing
(particularly one-dimensional) entangled quantum states. Our model enjoys
efficient learning by utilizing the density matrix renormalization group method
which allows dynamic adjusting dimensions of the tensors, and offers an
efficient direct sampling approach, Zipper, for generative tasks. We apply our
method to generative modeling of several standard datasets including the
principled Bars and Stripes, random binary patterns and the MNIST handwritten
digits, to illustrate ability of our model, and discuss features as well as
drawbacks of our model over popular generative models such as Hopfield model,
Boltzmann machines and generative adversarial networks. Our work shed light on
many interesting directions for future exploration on the development of
quantum-inspired algorithms for unsupervised machine learning, which is of
possibility of being realized by a quantum device."),
Zhao-Yu Han, Jun Wang, Heng Fan, Lei Wang, Pan Zhang,
arXiv: [1709.01662](http://arxiv.org/abs/1709.01662v2),
9/2017

- ["Deep Learning and Quantum Entanglement: Fundamental Connections with
  Implications to Network Design"](
http://arxiv.org/abs/1704.01552v2
"Deep convolutional networks have witnessed unprecedented success in various
machine learning applications. Formal understanding on what makes these
networks so successful is gradually unfolding, but for the most part there are
still significant mysteries to unravel. The inductive bias, which reflects
prior knowledge embedded in the network architecture, is one of them. In this
work, we establish a fundamental connection between the fields of quantum
physics and deep learning. We use this connection for asserting novel
theoretical observations regarding the role that the number of channels in each
layer of the convolutional network fulfills in the overall inductive bias.
Specifically, we show an equivalence between the function realized by a deep
convolutional arithmetic circuit (ConvAC) and a quantum many-body wave
function, which relies on their common underlying tensorial structure. This
facilitates the use of quantum entanglement measures as well-defined
quantifiers of a deep network's expressive ability to model intricate
correlation structures of its inputs. Most importantly, the construction of a
deep ConvAC in terms of a Tensor Network is made available. This description
enables us to carry a graph-theoretic analysis of a convolutional network, with
which we demonstrate a direct control over the inductive bias of the deep
network via its channel numbers, that are related to the min-cut in the
underlying graph. This result is relevant to any practitioner designing a
network for a specific task. We theoretically analyze ConvACs, and empirically
validate our findings on more common ConvNets which involve ReLU activations
and max pooling. Beyond the results described above, the description of a deep
convolutional network in well-defined graph-theoretic tools and the formal
connection to quantum entanglement, are two interdisciplinary bridges that are
brought forth by this work."),
Yoav Levine, David Yakira, Nadav Cohen, Amnon Shashua,
arXiv: [1704.01552](http://arxiv.org/abs/1704.01552v2),
4/2017


- ["Opening the Black Box of Deep Neural Networks via Information"](
http://arxiv.org/abs/1703.00810v3
"Despite their great success, there is still no comprehensive theoretical
understanding of learning with Deep Neural Networks (DNNs) or their inner
organization. Previous work proposed to analyze DNNs in the \textit{Information
Plane}; i.e., the plane of the Mutual Information values that each layer
preserves on the input and output variables. They suggested that the goal of
the network is to optimize the Information Bottleneck (IB) tradeoff between
compression and prediction, successively, for each layer.
  In this work we follow up on this idea and demonstrate the effectiveness of
the Information-Plane visualization of DNNs. Our main results are: (i) most of
the training epochs in standard DL are spent on {\emph compression} of the
input to efficient representation and not on fitting the training labels. (ii)
The representation compression phase begins when the training errors becomes
small and the Stochastic Gradient Decent (SGD) epochs change from a fast drift
to smaller training error into a stochastic relaxation, or random diffusion,
constrained by the training error value. (iii) The converged layers lie on or
very close to the Information Bottleneck (IB) theoretical bound, and the maps
from the input to any hidden layer and from this hidden layer to the output
satisfy the IB self-consistent equations. This generalization through noise
mechanism is unique to Deep Neural Networks and absent in one layer networks.
(iv) The training time is dramatically reduced when adding more hidden layers.
Thus the main advantage of the hidden layers is computational. This can be
explained by the reduced relaxation time, as this it scales super-linearly
(exponentially for simple diffusion) with the information compression from the
previous layer."),
Ravid Shwartz-Ziv, Naftali Tishby,
arXiv: [1703.00810](http://arxiv.org/abs/1703.00810v3),
3/2017

- ["Reinforcement Learning Using Quantum Boltzmann Machines"](
http://arxiv.org/abs/1612.05695v2
"We investigate whether quantum annealers with select chip layouts can
outperform classical computers in reinforcement learning tasks. We associate a
transverse field Ising spin Hamiltonian with a layout of qubits similar to that
of a deep Boltzmann machine (DBM) and use simulated quantum annealing (SQA) to
numerically simulate quantum sampling from this system. We design a
reinforcement learning algorithm in which the set of visible nodes representing
the states and actions of an optimal policy are the first and last layers of
the deep network. In absence of a transverse field, our simulations show that
DBMs train more effectively than restricted Boltzmann machines (RBM) with the
same number of weights. Since sampling from Boltzmann distributions of a DBM is
not classically feasible, this is evidence of advantage of a non-Turing
sampling oracle. We then develop a framework for training the network as a
quantum Boltzmann machine (QBM) in the presence of a significant transverse
field for reinforcement learning. This further improves the reinforcement
learning method using DBMs."),
Daniel Crawford, Anna Levit, Navid Ghadermarzy, Jaspreet S. Oberoi, Pooya Ronagh,
arXiv: [1612.05695](http://arxiv.org/abs/1612.05695v2),
12/2016

- ["Low-Rank Tensor Networks for Dimensionality Reduction and Large-Scale
  Optimization Problems: Perspectives and Challenges PART 1"](
http://arxiv.org/abs/1609.00893v3
"Machine learning and data mining algorithms are becoming increasingly
important in analyzing large volume, multi-relational and multi--modal
datasets, which are often conveniently represented as multiway arrays or
tensors. It is therefore timely and valuable for the multidisciplinary research
community to review tensor decompositions and tensor networks as emerging tools
for large-scale data analysis and data mining. We provide the mathematical and
graphical representations and interpretation of tensor networks, with the main
focus on the Tucker and Tensor Train (TT) decompositions and their extensions
or generalizations.
  Keywords: Tensor networks, Function-related tensors, CP decomposition, Tucker
models, tensor train (TT) decompositions, matrix product states (MPS), matrix
product operators (MPO), basic tensor operations, multiway component analysis,
multilinear blind source separation, tensor completion, linear/multilinear
dimensionality reduction, large-scale optimization problems, symmetric
eigenvalue decomposition (EVD), PCA/SVD, huge systems of linear equations,
pseudo-inverse of very large matrices, Lasso and Canonical Correlation Analysis
(CCA) (This is Part 1)"),
A. Cichocki, N. Lee, I. V. Oseledets, A. -H. Phan, Q. Zhao, D. Mandic,
arXiv: [1609.00893](http://arxiv.org/abs/1609.00893v3),
9/2016

- ["Why does deep and cheap learning work so well?"](
http://arxiv.org/abs/1608.08225v4
"We show how the success of deep learning could depend not only on mathematics
but also on physics: although well-known mathematical theorems guarantee that
neural networks can approximate arbitrary functions well, the class of
functions of practical interest can frequently be approximated through "cheap
learning" with exponentially fewer parameters than generic ones. We explore how
properties frequently encountered in physics such as symmetry, locality,
compositionality, and polynomial log-probability translate into exceptionally
simple neural networks. We further argue that when the statistical process
generating the data is of a certain hierarchical form prevalent in physics and
machine-learning, a deep neural network can be more efficient than a shallow
one. We formalize these claims using information theory and discuss the
relation to the renormalization group. We prove various "no-flattening
theorems" showing when efficient linear deep networks cannot be accurately
approximated by shallow ones without efficiency loss, for example, we show that
$n$ variables cannot be multiplied using fewer than 2^n neurons in a single
hidden layer."),
Henry W. Lin, Max Tegmark, David Rolnick,
arXiv: [1608.08225](http://arxiv.org/abs/1608.08225v4),
8/2016

- ["Supervised Learning with Quantum-Inspired Tensor Networks"](
http://arxiv.org/abs/1605.05775v2
"Tensor networks are efficient representations of high-dimensional tensors
which have been very successful for physics and mathematics applications. We
demonstrate how algorithms for optimizing such networks can be adapted to
supervised learning tasks by using matrix product states (tensor trains) to
parameterize models for classifying images. For the MNIST data set we obtain
less than 1% test set classification error. We discuss how the tensor network
form imparts additional structure to the learned model and suggest a possible
generative interpretation."),
E. Miles Stoudenmire, David J. Schwab,
arXiv: [1605.05775](http://arxiv.org/abs/1605.05775v2),
5/2016

- ["Exponential Machines"](
http://arxiv.org/abs/1605.03795v3
"Modeling interactions between features improves the performance of machine
learning solutions in many domains (e.g. recommender systems or sentiment
analysis). In this paper, we introduce Exponential Machines (ExM), a predictor
that models all interactions of every order. The key idea is to represent an
exponentially large tensor of parameters in a factorized format called Tensor
Train (TT). The Tensor Train format regularizes the model and lets you control
the number of underlying parameters. To train the model, we develop a
stochastic Riemannian optimization procedure, which allows us to fit tensors
with 2^160 entries. We show that the model achieves state-of-the-art
performance on synthetic data with high-order interactions and that it works on
par with high-order factorization machines on a recommender system dataset
MovieLens 100K."),
Alexander Novikov, Mikhail Trofimov, Ivan Oseledets,
arXiv: [1605.03795](http://arxiv.org/abs/1605.03795v3),
5/2016

- ["Quantum Boltzmann Machine"](
http://arxiv.org/abs/1601.02036v1
"Inspired by the success of Boltzmann Machines based on classical Boltzmann
distribution, we propose a new machine learning approach based on quantum
Boltzmann distribution of a transverse-field Ising Hamiltonian. Due to the
non-commutative nature of quantum mechanics, the training process of the
Quantum Boltzmann Machine (QBM) can become nontrivial. We circumvent the
problem by introducing bounds on the quantum probabilities. This allows us to
train the QBM efficiently by sampling. We show examples of QBM training with
and without the bound, using exact diagonalization, and compare the results
with classical Boltzmann training. We also discuss the possibility of using
quantum annealing processors like D-Wave for QBM training and application."),
Mohammad H. Amin, Evgeny Andriyash, Jason Rolfe, Bohdan Kulchytskyy, Roger Melko,
arXiv: [1601.02036](http://arxiv.org/abs/1601.02036v1),
1/2016

- ["An exact mapping between the Variational Renormalization Group and Deep
  Learning"](
http://arxiv.org/abs/1410.3831v1
"Deep learning is a broad set of techniques that uses multiple layers of
representation to automatically learn relevant features directly from
structured data. Recently, such techniques have yielded record-breaking results
on a diverse set of difficult machine learning tasks in computer vision, speech
recognition, and natural language processing. Despite the enormous success of
deep learning, relatively little is understood theoretically about why these
techniques are so successful at feature learning and compression. Here, we show
that deep learning is intimately related to one of the most important and
successful techniques in theoretical physics, the renormalization group (RG).
RG is an iterative coarse-graining scheme that allows for the extraction of
relevant features (i.e. operators) as a physical system is examined at
different length scales. We construct an exact mapping from the variational
renormalization group, first introduced by Kadanoff, and deep learning
architectures based on Restricted Boltzmann Machines (RBMs). We illustrate
these ideas using the nearest-neighbor Ising Model in one and two-dimensions.
Our results suggests that deep learning algorithms may be employing a
generalized RG-like scheme to learn relevant features from data."),
Pankaj Mehta, David J. Schwab,
arXiv: [1410.3831](http://arxiv.org/abs/1410.3831v1),
10/2014

- ["Tensor Networks for Big Data Analytics and Large-Scale Optimization
  Problems"](
http://arxiv.org/abs/1407.3124v2
"In this paper we review basic and emerging models and associated algorithms
for large-scale tensor networks, especially Tensor Train (TT) decompositions
using novel mathematical and graphical representations. We discus the concept
of tensorization (i.e., creating very high-order tensors from lower-order
original data) and super compression of data achieved via quantized tensor
train (QTT) networks. The purpose of a tensorization and quantization is to
achieve, via low-rank tensor approximations "super" compression, and
meaningful, compact representation of structured data. The main objective of
this paper is to show how tensor networks can be used to solve a wide class of
big data optimization problems (that are far from tractable by classical
numerical methods) by applying tensorization and performing all operations
using relatively small size matrices and tensors and applying iteratively
optimized and approximative tensor contractions.
  Keywords: Tensor networks, tensor train (TT) decompositions, matrix product
states (MPS), matrix product operators (MPO), basic tensor operations,
tensorization, distributed representation od data optimization problems for
very large-scale problems: generalized eigenvalue decomposition (GEVD),
PCA/SVD, canonical correlation analysis (CCA)."),
Andrzej Cichocki,
arXiv: [1407.3124](http://arxiv.org/abs/1407.3124v2),
7/2014


## Quantum Computation and Quantum Algorithms for Machine Learning

- ["Quantum algorithm and quantum circuit for A-Optimal Projection:
  dimensionality reduction"](
http://arxiv.org/abs/1812.09782v1
"Learning low dimensional representation is a crucial issue for many machine
learning tasks such as pattern recognition and image retrieval. In this
article, we present a quantum algorithm and a quantum circuit to efficiently
perform A-Optimal Projection for dimensionality reduction. Compared with the
best-know classical algorithms, the quantum algorithm shows an exponential
speedup in both the number of training vectors $n$ and the reduced feature
space dimension $k$. We show that the space and time complexity of the QAOP
circuit are $O\left[ \log_2 \left( {nk} /{\epsilon} \right) \right]$ and
$O[ {\log_2(nk)} ploy\left(\log_2\epsilon^{-1} \right)]$ respectively,
with fidelity at least $1-\epsilon$. Firstly, a reformation of the original
QAOP algorithm is proposed to help omit the quantum-classical interactions
durning the QAOP algorithm. Then the quantum algorithm and quantum circuit with
performance guarantees are proposed. Specifically, the quantum circuit modules
for preparing the initial quantum state and implementing the controlled
rotation can be also used for other quantum machine learning algorithms."),
Bojia Duan, Jiabin Yuan,
arXiv: [1812.09782](http://arxiv.org/abs/1812.09782v1),
12/2018

- ["q-means: A quantum algorithm for unsupervised machine learning"](
http://arxiv.org/abs/1812.03584v2
"Quantum machine learning is one of the most promising applications of a
full-scale quantum computer. Over the past few years, many quantum machine
learning algorithms have been proposed that can potentially offer considerable
speedups over the corresponding classical algorithms. In this paper, we
introduce q-means, a new quantum algorithm for clustering which is a canonical
problem in unsupervised machine learning. The $q$-means algorithm has
convergence and precision guarantees similar to $k$-means, and it outputs with
high probability a good approximation of the $k$ cluster centroids like the
classical algorithm. Given a dataset of $N$ $d$-dimensional vectors $v_i$ (seen
as a matrix $V \in \mathbb{R}^{N \times d})$ stored in QRAM, the running time
of q-means is $\widetilde{O}\left( k d \frac{\eta}{\delta^2}\kappa(V)(\mu(V) +
k \frac{\eta}{\delta}) + k^2 \frac{\eta^{1.5}}{\delta^2} \kappa(V)\mu(V)
\right)$ per iteration, where $\kappa(V)$ is the condition number, $\mu(V)$ is
a parameter that appears in quantum linear algebra procedures and $\eta =
\max_{i} ||v_{i}||^{2}$. For a natural notion of well-clusterable datasets, the
running time becomes $\widetilde{O}\left( k^2 d \frac{\eta^{2.5}}{\delta^3} +
k^{2.5} \frac{\eta^2}{\delta^3} \right)$ per iteration, which is linear in the
number of features $d$, and polynomial in the rank $k$, the maximum square norm
$\eta$ and the error parameter $\delta$. Both running times are only
polylogarithmic in the number of datapoints $N$. Our algorithm provides
substantial savings compared to the classical $k$-means algorithm that runs in
time $O(kdN)$ per iteration, particularly for the case of large datasets."),
Iordanis Kerenidis, Jonas Landman, Alessandro Luongo, Anupam Prakash,
arXiv: [1812.03584](http://arxiv.org/abs/1812.03584v2),
12/2018

- ["Quantum algorithms for feedforward neural networks"](
http://arxiv.org/abs/1812.03089v1
"Quantum machine learning has the potential for broad industrial applications,
and the development of quantum algorithms for improving the performance of
neural networks is of particular interest given the central role they play in
machine learning today. In this paper we present quantum algorithms for
training and evaluating feedforward neural networks based on the canonical
classical feedforward and backpropagation algorithms. Our algorithms rely on an
efficient quantum subroutine for approximating the inner products between
vectors, and on storing intermediate values in quantum random access memory for
fast retrieval at later stages. The running times of our algorithms can be
quadratically faster than their classical counterparts, since they depend
linearly on the number of neurons in the network, as opposed to the number of
edges as in the classical case. This makes our algorithms suited for
large-scale, highly-connected networks where the number of edges in the network
dominates the classical algorithmic running time."),
Jonathan Allcock, Chang-Yu Hsieh, Iordanis Kerenidis, Shengyu Zhang,
arXiv: [1812.03089](http://arxiv.org/abs/1812.03089v1),
12/2018















- ["Quantum optical neural networks"](
http://arxiv.org/abs/1808.10047v2
"Physically motivated quantum algorithms for specific near-term quantum
hardware will likely be the next frontier in quantum information science. Here,
we show how many of the features of neural networks for machine learning can
naturally be mapped into the quantum optical domain by introducing the quantum
optical neural network (QONN). Through numerical simulation and analysis we
train the QONN to perform a range of quantum information processing tasks,
including newly developed protocols for quantum optical state compression,
reinforcement learning, and black-box quantum simulation. We consistently
demonstrate our system can generalize from only a small set of training data
onto states for which it has not been trained. Our results indicate QONNs are a
powerful design tool for quantum optical systems and, leveraging advances in
integrated quantum photonics, a promising architecture for next generation
quantum processors."),
Gregory R. Steinbrecher, Jonathan P. Olson, Dirk Englund, Jacques Carolan,
arXiv: [1808.10047](http://arxiv.org/abs/1808.10047v2),
8/2018

- ["A Quantum Model for Multilayer Perceptron"](
http://arxiv.org/abs/1808.10561v2
"Multilayer perceptron is the most common used class of feed-forward
artificial neural network. It contains many applications in diverse fields such
as speech recognition, image recognition, and machine translation software. To
cater for the fast development of quantum machine learning, in this paper, we
propose a new model to study multilayer perceptron in quantum computer. This
contains the tasks to prepare the quantum state of the output signal in each
layer and to establish the quantum version of learning algorithm about the
weights in each layer. We will show that the corresponding quantum versions can
achieve at least quadratic speedup or even exponential speedup over the
classical algorithms. This provide us an efficient method to study multilayer
perceptron and its applications in machine learning in quantum computer.
Finally, as an inspiration, an exponential fast learning algorithm (based on
Hebb's learning rule) of Hopfield network will be proposed."),
Changpeng Shao,
arXiv: [1808.10561](http://arxiv.org/abs/1808.10561v2),
8/2018

- ["Implementable Quantum Classifier for Nonlinear Data"](
http://arxiv.org/abs/1809.06056v1
"In this Letter, we propose a quantum machine learning scheme for the
classification of classical nonlinear data. The main ingredients of our method
are variational quantum perceptron (VQP) and a quantum generalization of
classical ensemble learning. Our VQP employs parameterized quantum circuits to
learn a Grover search (or amplitude amplification) operation with classical
optimization, and can achieve quadratic speedup in query complexity compared to
its classical counterparts. We show how the trained VQP can be used to predict
future data with $O(1)$ {query} complexity. Ultimately, a stronger nonlinear
classifier can be established, the so-called quantum ensemble learning (QEL),
by combining a set of weak VQPs produced using a subsampling method. The
subsampling method has two significant advantages. First, all $T$ weak VQPs
employed in QEL can be trained in parallel, therefore, the query complexity of
QEL is equal to that of each weak VQP multiplied by $T$. Second, it
dramatically reduce the {runtime} complexity of encoding circuits that map
classical data to a quantum state because this dataset can be significantly
smaller than the original dataset given to QEL. This arguably provides a most
satisfactory solution to one of the most criticized issues in quantum machine
learning proposals. To conclude, we perform two numerical experiments for our
VQP and QEL, implemented by Python and pyQuil library. Our experiments show
that excellent performance can be achieved using a very small quantum circuit
size that is implementable under current quantum hardware development.
Specifically, given a nonlinear synthetic dataset with $4$ features for each
example, the trained QEL can classify the test examples that are sampled away
from the decision boundaries using $146$ single and two qubits quantum gates
with $92\%$ accuracy."),
Yuxuan Du, Min-Hsiu Hsieh, Tongliang Liu, Dacheng Tao,
arXiv: [1809.06056](http://arxiv.org/abs/1809.06056v1),
9/2018

- ["A quantum autoencoder: the compression of qutrits via machine learning"](
http://arxiv.org/abs/1810.01637v1
"With quantum resources a precious commodity, their efficient use is highly
desirable. Quantum autoencoders have been proposed as a way to reduce quantum
memory requirements. Generally, an autoencoder is a device that uses machine
learning to compress inputs, that is, to represent the input data in a
lower-dimensional space. Here, we experimentally realize a quantum autoencoder,
which learns how to compress quantum data using a classical optimization
routine. We demonstrate that when the inherent structure of the data set allows
lossless compression, our autoencoder reduces qutrits to qubits with low error
levels. We also show that the device is able to perform with minimal prior
information about the quantum data or physical system and is robust to
perturbations during its optimization routine."),
Alex Pepper, Nora Tischler, Geoff J. Pryde,
arXiv: [1810.01637](http://arxiv.org/abs/1810.01637v1),
10/2018

- ["Quantum Convolutional Neural Networks"](
http://arxiv.org/abs/1810.03787v1
"We introduce and analyze a novel quantum machine learning model motivated by
convolutional neural networks (CNN). Our quantum convolutional neural network
(QCNN) makes use of only $O(\log(N))$ variational parameters for input sizes of
$N$ qubits, allowing for its efficient training and implementation on
realistic, near-term quantum devices. We show that QCNN circuits combine the
multi-scale entanglement renormalization ansatz and quantum error correction to
mimic renormalization-group flow, making them capable of recognizing different
quantum phases and associated phase transitions. As an example, we illustrate
the power of QCNNs in recognizing a 1D symmetry-protected topological phase,
and demonstrate that a QCNN trained on a set of exactly solvable points can
reproduce the phase diagram over the entire parameter regime. Finally,
generalizations and possible applications of QCNN are discussed."),
Iris Cong, Soonwon Choi, Mikhail D. Lukin,
arXiv: [1810.03787](http://arxiv.org/abs/1810.03787v1),
10/2018

- ["Quantum Neural Network and Soft Quantum Computing"](
http://arxiv.org/abs/1810.05025v1
"A new paradigm of quantum computing, namely, soft quantum computing, is
proposed for nonclassical computation using real world quantum systems with
naturally occurring environment-induced decoherence and dissipation. As a
specific example of soft quantum computing, we suggest a quantum neural
network, where the neurons connect pairwise via the "controlled Kraus
operations", hoping to pave an easier and more realistic way to quantum
artificial intelligence and even to better understanding certain functioning of
the human brain. Our quantum neuron model mimics as much as possible the
realistic neurons and meanwhile, uses quantum laws for processing information.
The quantum features of the noisy neural network are uncovered by the presence
of quantum discord and by non-commutability of quantum operations. We believe
that our model puts quantum computing into a wider context and inspires the
hope to build a soft quantum computer much earlier than the standard one."),
Zeng-Bing Chen,
arXiv: [1810.05025](http://arxiv.org/abs/1810.05025v1),
10/2018

- ["Quantum data compression by principal component analysis"](
http://arxiv.org/abs/1810.10710v1
"Data compression can be achieved by reducing the dimensionality of
high-dimensional but approximately low-rank datasets, which may in fact be
described by the variation of a much smaller number of parameters. It often
serves as a preprocessing step to surmount the curse of dimensionality and to
gain efficiency, and thus it plays an important role in machine learning and
data mining. In this paper, we present a quantum algorithm that compresses an
exponentially large high-dimensional but approximately low-rank dataset in
quantum parallel, by dimensionality reduction (DR) based on principal component
analysis (PCA), the most popular classical DR algorithm. We show that the
proposed algorithm achieves exponential speedup over the classical PCA
algorithm when the original dataset lies in a polylogarithmically
low-dimensional space. The compressed dataset can then be further processed to
implement other tasks of interest, with significantly less quantum resources.
As examples, we apply this algorithm to reduce data dimensionality for two
important quantum machine learning algorithms, quantum support vector machine
and quantum linear regression for prediction. This work demonstrates that
quantum machine learning can be released from the curse of dimensionality to
solve problems of practical importance."),
Chao-Hua Yu, Fei Gao, Song Lin, Jingbo Wang,
arXiv: [1810.10710](http://arxiv.org/abs/1810.10710v1),
10/2018

- ["Quantum advantage in training binary neural networks"](
http://arxiv.org/abs/1810.12948v1
"Neural networks have become a corner stone of artificial intelligence. Once a
task is defined, a neural network needs to undergo a training phase in order to
calibrate the network parameters. On a classical computer, the number of
training cycles is strongly correlated with the amount of parameters in the
neural network, making an optimization of the parameters computationally
expensive. Here, we propose the a fully quantum training protocol for quantum
binary neurons. We show that for special cases this protocol yields a quadratic
advantage over commonly used classical training methods, and numerics suggests
that this advantage is generic for most instances. The source of this advantage
is the possibility to run training cycles in a quantum superposition. Further,
we present an extension of the training of single quantum binary neurons to
feedforward binary neural networks."),
Yidong Liao, Oscar Dahlsten, Daniel Ebler, Feiyang Liu,
arXiv: [1810.12948](http://arxiv.org/abs/1810.12948v1),
10/2018

- ["Quantum-inspired classical algorithms for principal component analysis
  and supervised clustering"](
http://arxiv.org/abs/1811.00414v1
"We describe classical analogues to quantum algorithms for principal component
analysis and nearest-centroid clustering. Given sampling assumptions, our
classical algorithms run in time polylogarithmic in input, matching the runtime
of the quantum algorithms with only polynomial slowdown. These algorithms are
evidence that their corresponding problems do not yield exponential quantum
speedups. To build our classical algorithms, we use the same techniques as
applied in our previous work dequantizing a quantum recommendation systems
algorithm. Thus, we provide further evidence for the strength of classical
$\ell^2$-norm sampling assumptions when replacing quantum state preparation
assumptions, in the machine learning domain."),
Ewin Tang,
arXiv: [1811.00414](http://arxiv.org/abs/1811.00414v1),
10/2018

- ["An Artificial Neuron Implemented on an Actual Quantum Processor"](
http://arxiv.org/abs/1811.02266v1
"Artificial neural networks are the heart of machine learning algorithms and
artificial intelligence protocols. Historically, the simplest implementation of
an artificial neuron traces back to the classical Rosenblatt's `perceptron',
but its long term practical applications may be hindered by the fast scaling up
of computational complexity, especially relevant for the training of
multilayered perceptron networks. Here we introduce a quantum information-based
algorithm implementing the quantum computer version of a perceptron, which
shows exponential advantage in encoding resources over alternative
realizations. We experimentally test a few qubits version of this model on an
actual small-scale quantum processor, which gives remarkably good answers
against the expected results. We show that this quantum model of a perceptron
can be used as an elementary nonlinear classifier of simple patterns, as a
first step towards practical training of artificial quantum neural networks to
be efficiently implemented on near-term quantum processing hardware."),
Francesco Tacchino, Chiara Macchiavello, Dario Gerace, Daniele Bajoni,
arXiv: [1811.02266](http://arxiv.org/abs/1811.02266v1),
11/2018



- ["Quantum enhanced cross-validation for near-optimal neural networks
  architecture selection"](
http://arxiv.org/abs/1808.09058v1
"This paper proposes a quantum-classical algorithm to evaluate and select
classical artificial neural networks architectures. The proposed algorithm is
based on a probabilistic quantum memory and the possibility to train artificial
neural networks in superposition. We obtain an exponential quantum speedup in
the evaluation of neural networks. We also verify experimentally through a
reduced experimental analysis that the proposed algorithm can be used to select
near-optimal neural networks."),
Priscila G. M. dos Santos, Rodrigo S. Sousa, Ismael C. S. Araujo, Adenilton J. da Silva,
arXiv: [1808.09058](http://arxiv.org/abs/1808.09058v1),
8/2018

- ["Realizing quantum linear regression with auxiliary qumodes"](
http://arxiv.org/abs/1808.08888v1
"In order to exploit quantum advantages, quantum algorithms are indispensable
for operating machine learning with quantum computers. We here propose an
intriguing hybrid approach of quantum information processing for quantum linear
regression, which utilizes both discrete and continuous quantum variables, in
contrast to existing wisdoms based solely upon discrete qubits. In our
framework, data information is encoded in a qubit system, while information
processing is tackled using auxiliary continuous qumodes via qubit-qumode
interactions. Moreover, it is also elaborated that finite squeezing is quite
helpful for efficiently running the quantum algorithms in realistic setup.
Comparing with an all-qubit approach, the present hybrid approach is more
efficient and feasible for implementing quantum algorithms, still retaining
exponential quantum speed-up."),
Dan-Bo Zhang, Zheng-Yuan Xue, Shi-Liang Zhu, Z. D. Wang,
arXiv: [1808.08888](http://arxiv.org/abs/1808.08888v1),
8/2018

- ["Neural-network states for the classical simulation of quantum computing"](
http://arxiv.org/abs/1808.05232v1
"Simulating quantum algorithms with classical resources generally requires
exponential resources. However, heuristic classical approaches are often very
efficient in approximately simulating special circuit structures, for example
with limited entanglement, or based on one-dimensional geometries. Here we
introduce a classical approach to the simulation of general quantum circuits
based on neural-network quantum states (NQS) representations. Considering a set
of universal quantum gates, we derive rules for exactly applying single-qubit
and two-qubit Z rotations to NQS, whereas we provide a learning scheme to
approximate the action of Hadamard gates. Results are shown for the Hadamard
and Fourier transform of entangled initial states for systems sizes and total
circuit depths exceeding what can be currently simulated with state-of-the-art
brute-force techniques. The overall accuracy obtained by the neural-network
states based on Restricted Boltzmann machines is satisfactory, and offers a
classical route to simulating highly-entangled circuits. In the test cases
considered, we find that our classical simulations are comparable to quantum
simulations affected by an incoherent noise level in the hardware of about
$10^{-3}$ per gate."),
Bjarni Jónsson, Bela Bauer, Giuseppe Carleo,
arXiv: [1808.05232](http://arxiv.org/abs/1808.05232v1),
8/2018

- ["Learning and Inference on Generative Adversarial Quantum Circuits"](
http://arxiv.org/abs/1808.03425v1
"Quantum mechanics is inherently probabilistic in light of Born's rule. Using
quantum circuits as probabilistic generative models for classical data exploits
their superior expressibility and efficient direct sampling ability. However,
training of quantum circuits can be more challenging compared to classical
neural networks due to lack of efficient differentiable learning algorithm. We
devise an adversarial quantum-classical hybrid training scheme via coupling a
quantum circuit generator and a classical neural network discriminator
together. After training, the quantum circuit generative model can infer
missing data with quadratic speed up via amplitude amplification. We
numerically simulate the learning and inference of generative adversarial
quantum circuit using the prototypical Bars-and-Stripes dataset. Generative
adversarial quantum circuits is a fresh approach to machine learning which may
enjoy the practically useful quantum advantage on near-term quantum devices."),
Jinfeng Zeng, Yufeng Wu, Jin-Guo Liu, Lei Wang, Jiangping Hu,
arXiv: [1808.03425](http://arxiv.org/abs/1808.03425v1),
8/2018

- ["Quantum generative adversarial learning in a superconducting quantum
  circuit"](
http://arxiv.org/abs/1808.02893v1
"Generative adversarial learning is one of the most exciting recent
breakthroughs in machine learning---a subfield of artificial intelligence that
is currently driving a revolution in many aspects of modern society. It has
shown splendid performance in a variety of challenging tasks such as image and
video generations. More recently, a quantum version of generative adversarial
learning has been theoretically proposed and shown to possess the potential of
exhibiting an exponential advantage over its classical counterpart. Here, we
report the first proof-of-principle experimental demonstration of quantum
generative adversarial learning in a superconducting quantum circuit. We
demonstrate that, after several rounds of adversarial learning, a quantum state
generator can be trained to replicate the statistics of the quantum data output
from a digital qubit channel simulator, with a high fidelity ($98.8\%$ on
average) that the discriminator cannot distinguish between the true and the
generated data. Our results pave the way for experimentally exploring the
intriguing long-sought-after quantum advantages in machine learning tasks with
noisy intermediate-scale quantum devices."),
Ling Hu, Shu-Hao Wu, Weizhou Cai, Yuwei Ma, Xianghao Mu, Yuan Xu, Haiyan Wang, Yipu Song, Dong-Ling Deng, Chang-Ling Zou, Luyan Sun,
arXiv: [1808.02893](http://arxiv.org/abs/1808.02893v1),
8/2018

- ["Quantum Lyapunov control with machine learning"](
http://arxiv.org/abs/1808.02516v1
"Quantum state engineering is a central task in Lyapunov-based quantum
control. Given different initial states, better performance may be achieved if
the control parameters, such as the Lyapunov function, are individually
optimized for each initial state, however, at the expense of computing
resources. To tackle this issue, we propose an initial-state-adaptive Lyapunov
control strategy with machine learning, specifically, artificial neural
networks trained through supervised learning. Two designs are presented and
illustrated where the feedforward neural network and the general regression
neural network are used to select control schemes and design Lyapunov
functions, respectively. Since the sample generation and the training of neural
networks are carried out in advance, the initial-state-adaptive Lyapunov
control can be implemented without much increase of computational resources."),
S. C. Hou, X. X. Yi,
arXiv: [1808.02516](http://arxiv.org/abs/1808.02516v1),
8/2018

- ["Machine learning method for state preparation and gate synthesis on
  photonic quantum computers"](
http://arxiv.org/abs/1807.10781v1
"We show how techniques from machine learning and optimization can be used to
find circuits of photonic quantum computers that perform a desired
transformation between input and output states. In the simplest case of a
single input state, our method discovers circuits for preparing a desired
quantum state. In the more general case of several input and output relations,
our method obtains circuits that reproduce the action of a target unitary
transformation. We use a continuous-variable quantum neural network as the
circuit architecture. The network is composed of several layers of optical
gates with variable parameters that are optimized by applying automatic
differentiation using the TensorFlow backend of the Strawberry Fields photonic
quantum computer simulator. We demonstrate the power and versatility of our
methods by learning how to use short-depth circuits to synthesize single
photons, Gottesman-Kitaev-Preskill states, NOON states, cubic phase gates,
random unitaries, cross-Kerr interactions, as well as several other states and
gates. We routinely obtain high fidelities above 99\% using short-depth
circuits, typically consisting of a few hundred gates. The circuits are
obtained automatically by simply specifying the target state or gate and
running the optimization algorithm."),
Juan Miguel Arrazola, Thomas R. Bromley, Josh Izaac, Casey R. Myers, Kamil Brádler, Nathan Killoran,
arXiv: [1807.10781](http://arxiv.org/abs/1807.10781v1),
7/2018

- ["Quantized Hodgkin-Huxley Model for Quantum Neurons"](
http://arxiv.org/abs/1807.10698v1
"The Hodgkin-Huxley model describes the behavior of the membrane voltage in
neurons, treating each element of the cell membrane as an electric circuit
element, namely capacitors, memristors and voltage sources. We focus on the
activation channel of potassium ions, since it is simpler, while keeping the
majority of the features identified with the original model. This
simplification is physiologically meaningful, since it is related to some
neurodegenerative and autoimmune diseases, which are associated with a process
of demyelination in neurons. This model reduces to a memristor, a resistor
whose resistance depends on the history of charges crossing it, coupled to a
voltage source and a capacitor. Here, we use the recent quantization of the
memristor to glance at the Hodgkin-Huxley model in the quantum regime. We
compare the behavior of the potassium channel conductance in both the classical
and quantum realm. In the latter, we firstly introduce classical sources to
study the quantum-classical transition, and afterwards we switch to coherent
quantum sources in order to study the effects of entanglement. Numerical
simulations show an increment and adaptation depending on the history of
signals. Additionally, the response to AC sources showcases hysteretic behavior
in the I-V characteristic curve due to the presence of the memristor. We
investigate the memory capacitance represented by the area of the I-V loops,
which we call memory persistence. We find that it grows with entanglement,
which can be interpreted in terms of the fundamental relation between
information and thermodynamic entropies established by Landauer's principle.
These results pave the way for the construction of quantum neuron networks
inspired in the brain but capable of dealing with quantum information, a step
forward towards the design of neuromorphic quantum architectures with
implications in quantum machine learning."),
Xiao-Hang Cheng, Tasio Gonzalez-Raya, Xi Chen, Mikel Sanz, Enrique Solano,
arXiv: [1807.10698](http://arxiv.org/abs/1807.10698v1),
7/2018

- ["Experimental Implementation of a Quantum Autoencoder via Quantum Adders"](
http://arxiv.org/abs/1807.10643v1
"Quantum autoencoders allow for reducing the amount of resources in a quantum
computation by mapping the original Hilbert space onto a reduced space with the
relevant information. Recently, it was proposed to employ approximate quantum
adders to implement quantum autoencoders in quantum technologies. Here, we
carry out the experimental implementation of this proposal in the Rigetti cloud
quantum computer employing up to three qubits. The experimental fidelities are
in good agreement with the theoretical prediction, thus proving the feasibility
to realize quantum autoencoders via quantum adders in state-of-the-art
superconducting quantum technologies."),
Yongcheng Ding, Lucas Lamata, Mikel Sanz, Xi Chen, Enrique Solano,
arXiv: [1807.10643](http://arxiv.org/abs/1807.10643v1),
7/2018

- ["The fundamentals of quantum machine learning"](
http://arxiv.org/abs/1807.04259v2
"Within the past few years, we have witnessed the rising of quantum machine
learning (QML) models which infer electronic properties of molecules and
materials, rather than solving approximations to the electronic Schrodinger
equation. The increasing availability of large quantum mechanics reference data
sets have enabled these developments. We review the basic theories and key
ingredients of popular QML models such as choice of regressor, data of varying
trustworthiness, the role of the representation, and the effect of training set
selection. Throughout we emphasize the indispensable role of learning curves
when it comes to the comparative assessment of different QML models."),
Bing Huang, Nadine O. Symonds, O. Anatole von Lilienfeld,
arXiv: [1807.04259](http://arxiv.org/abs/1807.04259v2),
7/2018

- ["Recurrent neural networks running on quantum spins: memory accuracy and
  capacity"](
http://arxiv.org/abs/1807.03947v1
"Quantum computing and neural networks show great promise for the future of
information processing. In this paper we study a quantum reservoir computer, a
framework harnessing quantum dynamics and designed for fast and efficient
solving of temporal machine learning tasks such as speech recognition, time
series prediction and natural language processing. Specifically, we study
memory capacity and accuracy of a quantum reservoir computer based on the fully
connected transverse field Ising model by investigating different forms of
inter-spin interactions and computing timescales. We show that variation in
inter-spin interactions leads to a better memory capacity in general, by
engineering the type of interactions the capacity can be greatly enhanced and
there exists an optimal timescale at which the capacity is maximized. To
connect computational capabilities to physical properties of the underlaying
system, we also study the out-of-time-ordered correlator and find that its
faster decay implies a more accurate memory."),
Aki Kutvonen, Takahiro Sagawa, Keisuke Fujii,
arXiv: [1807.03947](http://arxiv.org/abs/1807.03947v1),
7/2018

- ["Benchmarking neural networks for quantum computation"](
http://arxiv.org/abs/1807.03253v2
"The power of quantum computers is still somewhat speculative. While they are
certainly faster than classical ones, the class of problems they can
efficiently solve has not been mapped definitively onto known classical
complexity theory, and there is a paucity of truly quantum algorithms. This is
partly because finding algorithms that take advantage of the quantum nature of
reality is very difficult. In previous work over the past three decades we have
proposed, and developed, the idea of using techniques of machine learning to
address this problem. Here we compare the performance of standard real- and
complex-valued classical neural networks with that of one of our models for a
quantum neural network, on both classical problems and on an archetypal quantum
problem: the computation of an entanglement witness. The quantum network is
shown to be considerably more powerful."),
N. H. Nguyen, E. C. Behrman, M. A. Moustafa, J. E. Steck,
arXiv: [1807.03253](http://arxiv.org/abs/1807.03253v2),
7/2018

- ["Adversarial training of quantum Born machine"](
http://arxiv.org/abs/1807.01235v2
"Generative adversarial network (GAN) is an effective machine learning
framework to train unsupervised generative models, and has drawn lots of
attention in recent years. In the meantime, there are some researches that use
parameterized quantum circuits to generate simple patterns. In this paper, we
present a quantum version of GAN, where parameterized quantum circuits are
trained by an adversarial discriminator, to generate new samples that follows
the probability distribution of a given training dataset. Two families of
quantum circuits, both composed of simple one-qubit rotation and two-qubit
controlled-phase gates, are considered. The parameters are learned through
classical gradient descent optimization. The results of a small-scale
proof-of-principle numerical experiment demonstrate that quantum circuits can
be trained in an adversarial way for generative tasks."),
Haozhen Situ, Zhimin He, Lvzhou Li, Shenggen Zheng,
arXiv: [1807.01235](http://arxiv.org/abs/1807.01235v2),
7/2018

- ["Optimization of neural networks via finite-value quantum fluctuations"](
http://arxiv.org/abs/1807.00414v1
"We numerically test an optimization method for deep neural networks (DNNs)
using quantum fluctuations inspired by quantum annealing. For efficient
optimization, our method utilizes the quantum tunneling effect beyond the
potential barriers. The path integral formulation of the DNN optimization
generates an attracting force to simulate the quantum tunneling effect. In the
standard quantum annealing method, the quantum fluctuations will vanish at the
last stage of optimization. In this study, we propose a learning protocol that
utilizes a finite value for quantum fluctuations strength to obtain higher
generalization performance, which is a type of robustness. We demonstrate the
performance of our method using two well-known open datasets: the MNIST dataset
and the Olivetti face dataset. Although computational costs prevent us from
testing our method on large datasets with high-dimensional data, results show
that our method can enhance generalization performance by induction of the
finite value for quantum fluctuations."),
Masayuki Ohzeki, Shuntaro Okada, Masayoshi Terabe, Shinichiro Taguchi,
arXiv: [1807.00414](http://arxiv.org/abs/1807.00414v1),
7/2018



- ["A Universal Training Algorithm for Quantum Deep Learning"](
http://arxiv.org/abs/1806.09729v1
"We introduce the Backwards Quantum Propagation of Phase errors (Baqprop)
principle, a central theme upon which we construct multiple universal
optimization heuristics for training both parametrized quantum circuits and
classical deep neural networks on a quantum computer. Baqprop encodes error
information in relative phases of a quantum wavefunction defined over the space
of network parameters; it can be thought of as the unification of the phase
kickback principle of quantum computation and of the backpropagation algorithm
from classical deep learning. We propose two core heuristics which leverage
Baqprop for quantum-enhanced optimization of network parameters: Quantum
Dynamical Descent (QDD) and Momentum Measurement Gradient Descent (MoMGrad).
QDD uses simulated quantum coherent dynamics for parameter optimization,
allowing for quantum tunneling through the hypothesis space landscape. MoMGrad
leverages Baqprop to estimate gradients and thereby perform gradient descent on
the parameter landscape; it can be thought of as the quantum-classical analogue
of QDD. In addition to these core optimization strategies, we propose various
methods for parallelization, regularization, and meta-learning as augmentations
to MoMGrad and QDD. We introduce several quantum-coherent adaptations of
canonical classical feedforward neural networks, and study how Baqprop can be
used to optimize such networks. We develop multiple applications of parametric
circuit learning for quantum data, and show how to perform Baqprop in each
case. One such application allows for the training of hybrid quantum-classical
neural-circuit networks, via the seamless integration of Baqprop with classical
backpropagation. Finally, for a representative subset of these proposed
applications, we demonstrate the training of these networks via numerical
simulations of implementations of QDD and MoMGrad."),
Guillaume Verdon, Jason Pye, Michael Broughton,
arXiv: [1806.09729](http://arxiv.org/abs/1806.09729v1),
6/2018

- ["Artificial Quantum Neural Network: quantum neurons, logical elements and
  tests of convolutional nets"](
http://arxiv.org/abs/1806.09664v1
"We consider a model of an artificial neural network that uses
quantum-mechanical particles in a two-humped potential as a neuron. To simulate
such a quantum-mechanical system the Monte-Carlo integration method is used. A
form of the self-potential of a particle and two potentials (exciting and
inhibiting) interaction are proposed. The possibility of implementing the
simplest logical elements, (such as AND, OR and NOT) based on introduced
quantum particles is shown. Further we show implementation of a simplest
convolutional network. Finally we construct a network that recognizes
handwritten symbols, which shows that in the case of simple architectures, it
is possible to transfer weights from a classical network to a quantum one."),
V. I. Dorozhinsky, O. V. Pavlovsky,
arXiv: [1806.09664](http://arxiv.org/abs/1806.09664v1),
6/2018

- ["Quantum Kitchen Sinks: An algorithm for machine learning on near-term
  quantum computers"](
http://arxiv.org/abs/1806.08321v1
"Noisy intermediate-scale quantum computing devices are an exciting platform
for the exploration of the power of near-term quantum applications. Performing
nontrivial tasks in such a framework requires a fundamentally different
approach than what would be used on an error-corrected quantum computer. One
such approach is to use hybrid algorithms, where problems are reduced to a
parameterized quantum circuit that is often optimized in a classical feedback
loop. Here we described one such hybrid algorithm for machine learning tasks by
building upon the classical algorithm known as random kitchen sinks. Our
technique, called quantum kitchen sinks, uses quantum circuits to nonlinearly
transform classical inputs into features that can then be used in a number of
machine learning algorithms. We demonstrate the power and flexibility of this
proposal by using it to solve binary classification problems for synthetic
datasets as well as handwritten digits from the MNIST database. We can show, in
particular, that small quantum circuits provide significant performance lift
over standard linear classical algorithms, reducing classification error rates
from $50\%$ to $<0.1\%$, and from $4.1\%$ to $1.4\%$ in these two examples,
respectively."),
C. M. Wilson, J. S. Otterbach, N. Tezak, R. S. Smith, G. E. Crooks, M. P. da Silva,
arXiv: [1806.08321](http://arxiv.org/abs/1806.08321v1),
6/2018

- ["Continuous-variable quantum neural networks"](
http://arxiv.org/abs/1806.06871v1
"We introduce a general method for building neural networks on quantum
computers. The quantum neural network is a variational quantum circuit built in
the continuous-variable (CV) architecture, which encodes quantum information in
continuous degrees of freedom such as the amplitudes of the electromagnetic
field. This circuit contains a layered structure of continuously parameterized
gates which is universal for CV quantum computation. Affine transformations and
nonlinear activation functions, two key elements in neural networks, are
enacted in the quantum network using Gaussian and non-Gaussian gates,
respectively. The non-Gaussian gates provide both the nonlinearity and the
universality of the model. Due to the structure of the CV model, the CV quantum
neural network can encode highly nonlinear transformations while remaining
completely unitary. We show how a classical network can be embedded into the
quantum formalism and propose quantum versions of various specialized model
such as convolutional, recurrent, and residual networks. Finally, we present
numerous modeling experiments built with the Strawberry Fields software
library. These experiments, including a classifier for fraud detection, a
network which generates Tetris images, and a hybrid classical-quantum
autoencoder, demonstrate the capability and adaptability of CV quantum neural
networks."),
Nathan Killoran, Thomas R. Bromley, Juan Miguel Arrazola, Maria Schuld, Nicolás Quesada, Seth Lloyd,
arXiv: [1806.06871](http://arxiv.org/abs/1806.06871v1),
6/2018

- ["Decoherence in a quantum neural network"](
http://arxiv.org/abs/1806.07251v1
"In this study, we propose a spin-star model for spin-(1/2) particles in order
to examine the coherence dynamics of a quantum neural network (QNN) unit. Since
quantum computing paradigm promises advantages over their classical
counterparts, quantum versions of neural networks can be examined in this
context. We focus on quantum coherence as a natural resource for quantum
computing and investigate the central spin coherence of a spin star model in
the time domain in a dissipative environment. More particularly, we investigate
the extend to which the central spin coherence time would be prolonged under
specific parameters and spin-coupling Hamiltonians in a Markov environment. We
show that Ising-type spin coupling is not desirable since it rapidly diminishes
the coherence time in a dissipative environment."),
Deniz Türkpençe, Tahir Çetin Akıncı, Serhat Şeker,
arXiv: [1806.07251](http://arxiv.org/abs/1806.07251v1),
6/2018

- ["Bayesian Quantum Circuit"](
http://arxiv.org/abs/1805.11089v1
"Parameterized quantum circuits (PQCs), as one of the most promising schemes
to realize quantum machine learning algorithms on near-term quantum computers,
have been designed to solve machine earning tasks with quantum advantages. In
this paper, we explain why PQCs with different structures can achieve
generative tasks in the discrete case from the perspective of probability
estimation. Although different kinds of PQCs are proposed for generative tasks,
the current methods often encounter the following three hurdles: (1) the mode
contraction problem; (2) unexpected data are often generated with a high
proportion; (3) target data cannot be sampled directly. For the purpose of
tackling the above hurdles, we devise Bayesian quantum circuit (BQC) through
introducing ancillary qubits to represent prior distributions. BQC advances
both generative and semi-supervised quantum circuit learning tasks, where its
effectiveness is validated by numerical simulations using the Rigetti Forest
platform."),
Yuxuan Du, Tongliang Liu, Dacheng Tao,
arXiv: [1805.11089](http://arxiv.org/abs/1805.11089v1),
5/2018

- ["Quantum classification of the MNIST dataset via Slow Feature Analysis"](
http://arxiv.org/abs/1805.08837v2
"Quantum machine learning carries the promise to revolutionize information and
communication technologies. While a number of quantum algorithms with potential
exponential speedups have been proposed already, it is quite difficult to
provide convincing evidence that quantum computers with quantum memories will
be in fact useful to solve real-world problems. Our work makes considerable
progress towards this goal.
  We design quantum techniques for Dimensionality Reduction and for
Classification, and combine them to provide an efficient and high accuracy
quantum classifier that we test on the MNIST dataset. More precisely, we
propose a quantum version of Slow Feature Analysis (QSFA), a dimensionality
reduction technique that maps the dataset in a lower dimensional space where we
can apply a novel quantum classification procedure, the Quantum Frobenius
Distance (QFD). We simulate the quantum classifier (including errors) and show
that it can provide classification of the MNIST handwritten digit dataset, a
widely used dataset for benchmarking classification algorithms, with $98.5\%$
accuracy, similar to the classical case. The running time of the quantum
classifier is polylogarithmic in the dimension and number of data points. We
also provide evidence that the other parameters on which the running time
depends (condition number, Frobenius norm, error threshold, etc.) scale
favorably in practice, thus ascertaining the efficiency of our algorithm."),
Iordanis Kerenidis, Alessandro Luongo,
arXiv: [1805.08837](http://arxiv.org/abs/1805.08837v2),
5/2018

- ["Universal discriminative quantum neural networks"](
http://arxiv.org/abs/1805.08654v1
"Quantum mechanics fundamentally forbids deterministic discrimination of
quantum states and processes. However, the ability to optimally distinguish
various classes of quantum data is an important primitive in quantum
information science. In this work, we train near-term quantum circuits to
classify data represented by non-orthogonal quantum probability distributions
using the Adam stochastic optimization algorithm. This is achieved by iterative
interactions of a classical device with a quantum processor to discover the
parameters of an unknown non-unitary quantum circuit. This circuit learns to
simulates the unknown structure of a generalized quantum measurement, or
Positive-Operator-Value-Measure (POVM), that is required to optimally
distinguish possible distributions of quantum inputs. Notably we use universal
circuit topologies, with a theoretically motivated circuit design, which
guarantees that our circuits can in principle learn to perform arbitrary
input-output mappings. Our numerical simulations show that shallow quantum
circuits could be trained to discriminate among various pure and mixed quantum
states exhibiting a trade-off between minimizing erroneous and inconclusive
outcomes with comparable performance to theoretically optimal POVMs. We train
the circuit on different classes of quantum data and evaluate the
generalization error on unseen mixed quantum states. This generalization power
hence distinguishes our work from standard circuit optimization and provides an
example of quantum machine learning for a task that has inherently no classical
analogue."),
Hongxiang Chen, Leonard Wossnig, Simone Severini, Hartmut Neven, Masoud Mohseni,
arXiv: [1805.08654](http://arxiv.org/abs/1805.08654v1),
5/2018



- ["Supervised learning with quantum enhanced feature spaces"](
http://arxiv.org/abs/1804.11326v1
"Machine learning and quantum computing are two technologies each with the
potential for altering how computation is performed to address previously
untenable problems. Kernel methods for machine learning are ubiquitous for
pattern recognition, with support vector machines (SVMs) being the most
well-known method for classification problems. However, there are limitations
to the successful solution to such problems when the feature space becomes
large, and the kernel functions become computationally expensive to estimate. A
core element to computational speed-ups afforded by quantum algorithms is the
exploitation of an exponentially large quantum state space through controllable
entanglement and interference. Here, we propose and use two novel methods which
represent the feature space of a classification problem by a quantum state,
taking advantage of the large dimensionality of quantum Hilbert space to obtain
an enhanced solution. One method, the quantum variational classifier builds on
[1,2] and operates through using a variational quantum circuit to classify a
training set in direct analogy to conventional SVMs. In the second, a quantum
kernel estimator, we estimate the kernel function and optimize the classifier
directly. The two methods present a new class of tools for exploring the
applications of noisy intermediate scale quantum computers to machine learning."),
Vojtech Havlicek, Antonio D. Córcoles, Kristan Temme, Aram W. Harrow, Jerry M. Chow, Jay M. Gambetta,
arXiv: [1804.11326](http://arxiv.org/abs/1804.11326v1),
4/2018

- ["Quantum generative adversarial learning"](
http://arxiv.org/abs/1804.09139v1
"Generative adversarial networks (GANs) represent a powerful tool for
classical machine learning: a generator tries to create statistics for data
that mimics those of a true data set, while a discriminator tries to
discriminate between the true and fake data. The learning process for generator
and discriminator can be thought of as an adversarial game, and under
reasonable assumptions, the game converges to the point where the generator
generates the same statistics as the true data and the discriminator is unable
to discriminate between the true and the generated data. This paper introduces
the notion of quantum generative adversarial networks (QuGANs), where the data
consists either of quantum states, or of classical data, and the generator and
discriminator are equipped with quantum information processors. We show that
the unique fixed point of the quantum adversarial game also occurs when the
generator produces the same statistics as the data. Since quantum systems are
intrinsically probabilistic the proof of the quantum case is different from -
and simpler than - the classical case. We show that when the data consists of
samples of measurements made on high-dimensional spaces, quantum adversarial
networks may exhibit an exponential advantage over classical adversarial
networks."),
Seth Lloyd, Christian Weedbrook,
arXiv: [1804.09139](http://arxiv.org/abs/1804.09139v1),
4/2018

- ["Quantum generative adversarial networks"](
http://arxiv.org/abs/1804.08641v2
"Quantum machine learning is expected to be one of the first potential
general-purpose applications of near-term quantum devices. A major recent
breakthrough in classical machine learning is the notion of generative
adversarial training, where the gradients of a discriminator model are used to
train a separate generative model. In this work and a companion paper, we
extend adversarial training to the quantum domain and show how to construct
generative adversarial networks using quantum circuits. Furthermore, we also
show how to compute gradients -- a key element in generative adversarial
network training -- using another quantum circuit. We give an example of a
simple practical circuit ansatz to parametrize quantum machine learning models
and perform a simple numerical experiment to demonstrate that quantum
generative adversarial networks can be trained successfully."),
Pierre-Luc Dallaire-Demers, Nathan Killoran,
arXiv: [1804.08641](http://arxiv.org/abs/1804.08641v2),
4/2018

- ["Machine learning assisted readout of trapped-ion qubits"](
http://arxiv.org/abs/1804.07718v2
"We reduce measurement errors in a quantum computer using machine learning
techniques. We exploit a simple yet versatile neural network to classify
multi-qubit quantum states, which is trained using experimental data. This
flexible approach allows the incorporation of any number of features of the
data with minimal modifications to the underlying network architecture. We
experimentally illustrate this approach in the readout of trapped-ion qubits
using additional spatial and temporal features in the data. Using this neural
network classifier, we efficiently treat qubit readout crosstalk, resulting in
a 30\% improvement in detection error over the conventional threshold method.
Our approach does not depend on the specific details of the system and can be
readily generalized to other quantum computing platforms."),
Alireza Seif, Kevin A. Landsman, Norbert M. Linke, Caroline Figgatt, C. Monroe, Mohammad Hafezi,
arXiv: [1804.07718](http://arxiv.org/abs/1804.07718v2),
4/2018

- ["Quantum codes from classical graphical models"](
http://arxiv.org/abs/1804.07653v1
"We introduce a new graphical framework for designing quantum error correction
codes based on classical principles. A key feature of this graphical language,
over previous approaches, is that it is closely related to that of factor
graphs or graphical models in classical information theory and machine
learning. It enables us to formulate the description of recently-introduced
`coherent parity check' quantum error correction codes entirely within the
language of classical information theory. This makes our construction
accessible without requiring background in quantum error correction or even
quantum mechanics in general. More importantly, this allows for a collaborative
interplay where one can design new quantum error correction codes derived from
classical codes."),
Joschka Roffe, Stefan Zohren, Dominic Horsman, Nicholas Chancellor,
arXiv: [1804.07653](http://arxiv.org/abs/1804.07653v1),
4/2018

- ["A Simple Quantum Neural Net with a Periodic Activation Function"](
http://arxiv.org/abs/1804.07633v2
"In this paper, we propose a simple neural net that requires only $O(nlog_2k)$
number of qubits and $O(nk)$ quantum gates: Here, $n$ is the number of input
parameters, and $k$ is the number of weights applied to these parameters in the
proposed neural net. We describe the network in terms of a quantum circuit, and
then draw its equivalent classical neural net which involves $O(k^n)$ nodes in
the hidden layer. Then, we show that the network uses a periodic activation
function of cosine values of the linear combinations of the inputs and weights.
The backpropagation is described through the gradient descent, and then iris
and breast cancer datasets are used for the simulations. The numerical results
indicate the network can be used in machine learning problems and it may
provide exponential speedup over the same structured classical neural net."),
Ammar Daskin,
arXiv: [1804.07633](http://arxiv.org/abs/1804.07633v2),
4/2018



- ["Optimizing a Polynomial Function on a Quantum Simulator"](
http://arxiv.org/abs/1804.05231v1
"Gradient descent method, as one of the major methods in numerical
optimization, is the key ingredient in many machine learning algorithms. As one
of the most fundamental way to solve the optimization problems, it promises the
function value to move along the direction of steepest descent. For the vast
resource consumption when dealing with high-dimensional problems, a quantum
version of this iterative optimization algorithm has been proposed
recently[arXiv:1612.01789]. Here, we develop this protocol and implement it on
a quantum simulator with limited resource. Moreover, a prototypical experiment
was shown with a 4-qubit Nuclear Magnetic Resonance quantum processor,
demonstrating a optimization process of polynomial function iteratively. In
each iteration, we achieved an average fidelity of 94\% compared with
theoretical calculation via full-state tomography. In particular, the iterative
point gradually converged to the local minimum. We apply our method to
multidimensional scaling problem, further showing the potentially capability to
yields an exponentially improvement compared with classical counterparts. With
the onrushing tendency of quantum information, our work could provide a
subroutine for the application of future practical quantum computers."),
Keren Li, Shijie Wei, Feihao Zhang, Pan Gao, Zengrong Zhou, Tao Xin, Xiaoting Wang, Guilu Long,
arXiv: [1804.05231](http://arxiv.org/abs/1804.05231v1),
4/2018

- ["Differentiable Learning of Quantum Circuit Born Machine"](
http://arxiv.org/abs/1804.04168v1
"Quantum circuit Born machines are generative models which represent the
probability distribution of classical dataset as quantum pure states.
Computational complexity considerations of the quantum sampling problem suggest
that the quantum circuits exhibit stronger expressibility compared to classical
neural networks. One can efficiently draw samples from the quantum circuits via
projective measurements on qubits. However, similar to the leading implicit
generative models in deep learning, such as the generative adversarial
networks, the quantum circuits cannot provide the likelihood of the generated
samples, which poses a challenge to the training. We devise an efficient
gradient-based learning algorithm for the quantum circuit Born machine by
minimizing the kerneled maximum mean discrepancy loss. We simulated generative
modeling of the Bars-and-Stripes dataset and Gaussian mixture distributions
using deep quantum circuits. Our experiments show the importance of circuit
depth and gradient-based optimization algorithm. The proposed learning
algorithm is runnable on near-term quantum device and can exhibit quantum
advantages for generative modeling."),
Jin-Guo Liu, Lei Wang,
arXiv: [1804.04168](http://arxiv.org/abs/1804.04168v1),
4/2018

- ["Hierarchical quantum classifiers"](
http://arxiv.org/abs/1804.03680v1
"Hierarchical quantum circuits have been shown to perform binary
classification of classical data encoded in a quantum state. We demonstrate
that more expressive circuits in the same family achieve better accuracy and
can be used to classify highly entangled quantum states, for which there is no
known efficient classical method. We compare performance for several different
parameterizations on two classical machine learning datasets, Iris and MNIST,
and on a synthetic dataset of quantum states. Finally, we demonstrate that
performance is robust to noise and deploy an Iris dataset classifier on the
ibmqx4 quantum computer."),
Edward Grant, Marcello Benedetti, Shuxiang Cao, Andrew Hallam, Joshua Lockhart, Vid Stojevic, Andrew G. Green, Simone Severini,
arXiv: [1804.03680](http://arxiv.org/abs/1804.03680v1),
4/2018

- ["Strawberry Fields: A Software Platform for Photonic Quantum Computing"](
http://arxiv.org/abs/1804.03159v1
"We introduce Strawberry Fields, an open-source quantum programming
architecture for light-based quantum computers. Built in Python, Strawberry
Fields is a full-stack library for design, simulation, optimization, and
quantum machine learning of continuous-variable circuits. The platform consists
of three main components: (i) an API for quantum programming based on an
easy-to-use language named Blackbird; (ii) a suite of three virtual quantum
computer backends, built in NumPy and Tensorflow, each targeting specialized
uses; and (iii) an engine which can compile Blackbird programs on various
backends, including the three built-in simulators, and -- in the near future --
photonic quantum information processors. The library also contains examples of
several paradigmatic algorithms, including teleportation, (Gaussian) boson
sampling, instantaneous quantum polynomial, Hamiltonian simulation, and
variational quantum circuit optimization."),
Nathan Killoran, Josh Izaac, Nicolás Quesada, Ville Bergholm, Matthew Amy, Christian Weedbrook,
arXiv: [1804.03159](http://arxiv.org/abs/1804.03159v1),
4/2018

- ["Variational quantum simulation of imaginary time evolution with
  applications in chemistry and beyond"](
http://arxiv.org/abs/1804.03023v1
"Imaginary time evolution is a powerful tool in the study of many-body quantum
systems. While it is conceptually simple to simulate such evolution with a
classical computer, the time and memory requirements scale exponentially with
the system size. Conversely, quantum computers can efficiently simulate
many-body quantum systems, but the non-unitary nature of imaginary time
evolution is incompatible with canonical unitary quantum circuits. Here we
propose a variational method for simulating imaginary time evolution on a
quantum computer, using a hybrid algorithm that combines quantum and classical
resources. We apply this technique to the problem of finding the ground state
energy of many-particle Hamiltonians. We numerically test our algorithm on
problems in quantum computational chemistry; specifically, finding the ground
state energy of the Hydrogen molecule and Lithium Hydride. Our algorithm
successfully finds the global ground state with high probability, outperforming
gradient descent optimisation which commonly becomes trapped in local minima.
Our method can also be applied to general optimisation problems, Gibbs state
preparation, and quantum machine learning. As our algorithm is hybrid, suitable
for error mitigation methods, and can exploit shallow quantum circuits, it can
be implemented with current and near-term quantum computers."),
Sam McArdle, Suguru Endo, Ying Li, Simon Benjamin, Xiao Yuan,
arXiv: [1804.03023](http://arxiv.org/abs/1804.03023v1),
4/2018

- ["Neural network decoder for topological color codes with circuit level
  noise"](
http://arxiv.org/abs/1804.02926v1
"A quantum computer needs the assistance of a classical algorithm to detect
and identify errors that affect encoded quantum information. At this interface
of classical and quantum computing the technique of machine learning has
appeared as a way to tailor such an algorithm to the specific error processes
of an experiment --- without the need for a priori knowledge of the error
model. Here, we apply this technique to topological color codes. We demonstrate
that a recurrent neural network with long short-term memory cells can be
trained to reduce the error rate $\epsilon_{\rm L}$ of the encoded logical
qubit to values much below the error rate $\epsilon_{\rm phys}$ of the physical
qubits --- fitting the expected power law scaling $\epsilon_{\rm L} \propto
\epsilon_{\rm phys}^{(d+1)/2}$, with $d$ the code distance. The neural network
incorporates the information from "flag qubits" to avoid reduction in the
effective code distance caused by the circuit. As a test, we apply the neural
network decoder to a density-matrix based simulation of a superconducting
quantum computer, demonstrating that the logical qubit has a longer life-time
than the constituting physical qubits with near-term experimental parameters."),
P. Baireuther, M. D. Caio, B. Criger, C. W. J. Beenakker, T. E. O'Brien,
arXiv: [1804.02926](http://arxiv.org/abs/1804.02926v1),
4/2018

- ["Quantum Machine Learning Matrix Product States"](
http://arxiv.org/abs/1804.02398v1
"Matrix product states minimize bipartite correlations to compress the
classical data representing quantum states. Matrix product state algorithms and
similar tools---called tensor network methods---form the backbone of modern
numerical methods used to simulate many-body physics. Matrix product states
have a further range of applications in machine learning. Finding matrix
product states is in general a computationally challenging task, a
computational task which we show quantum computers can accelerate. We present a
quantum algorithm which returns a classical description of a $k$-rank matrix
product state approximating an eigenvector given black-box access to a unitary
matrix. Each iteration of the optimization requires $O(n\cdot k^2)$ quantum
gates, yielding sufficient conditions for our quantum variational algorithm to
terminate in polynomial-time."),
Jacob Biamonte,
arXiv: [1804.02398](http://arxiv.org/abs/1804.02398v1),
4/2018

- ["Classical Verification of Quantum Computations"](
http://arxiv.org/abs/1804.01082v1
"We present the first protocol allowing a classical computer to interactively
verify the result of an efficient quantum computation. We achieve this by
constructing a measurement protocol, which enables a classical verifier to
ensure that the quantum prover holds an n qubit quantum state, and correctly
reports the results of measuring it in a basis of the verifier's choice. This
is enforced based on the assumption that the learning with errors problem is
computationally intractable for efficient quantum machines."),
Urmila Mahadev,
arXiv: [1804.01082](http://arxiv.org/abs/1804.01082v1),
4/2018

- ["Circuit-centric quantum classifiers"](
http://arxiv.org/abs/1804.00633v1
"The current generation of quantum computing technologies call for quantum
algorithms that require a limited number of qubits and quantum gates, and which
are robust against errors. A suitable design approach are variational circuits
where the parameters of gates are learnt, an approach that is particularly
fruitful for applications in machine learning. In this paper, we propose a
low-depth variational quantum algorithm for supervised learning. The input
feature vectors are encoded into the amplitudes of a quantum system, and a
quantum circuit of parametrised single and two-qubit gates together with a
single-qubit measurement is used to classify the inputs. This circuit
architecture ensures that the number of learnable parameters is
poly-logarithmic in the input dimension. We propose a quantum-classical
training scheme where the analytical gradients of the model can be estimated by
running several slightly adapted versions of the variational circuit. We show
with simulations that the circuit-centric quantum classifier performs well on
standard classical benchmark datasets while requiring dramatically fewer
parameters than other methods. We also evaluate sensitivity of the
classification to state preparation and parameter noise, introduce a quantum
version of dropout regularisation and provide a graphical representation of
quantum gates as highly symmetric linear layers of a neural network."),
Maria Schuld, Alex Bocharov, Krysta Svore, Nathan Wiebe,
arXiv: [1804.00633](http://arxiv.org/abs/1804.00633v1),
4/2018

- ["A note on state preparation for quantum machine learning"](
http://arxiv.org/abs/1804.00281v1
"The intersection between the fields of machine learning and quantum
information processing is proving to be a fruitful field for the discovery of
new quantum algorithms, which potentially offer an exponential speed-up over
their classical counterparts. However, many such algorithms require the ability
to produce states proportional to vectors stored in quantum memory. Even given
access to quantum databases which store exponentially long vectors, the
construction of which is considered a one-off overhead, it has been argued that
the cost of preparing such amplitude-encoded states may offset any exponential
quantum advantage. Here we argue that specifically in the context of machine
learning applications it suffices to prepare a state close to the ideal state
only in the $\infty$-norm, and that this can be achieved with only a constant
number of memory queries."),
Zhikuan Zhao, Vedran Dunjko, Jack K. Fitzsimons, Patrick Rebentrost, Joseph F. Fitzsimons,
arXiv: [1804.00281](http://arxiv.org/abs/1804.00281v1),
4/2018




- ["Towards Quantum Machine Learning with Tensor Networks"](
http://arxiv.org/abs/1803.11537v1
"Machine learning is a promising application of quantum computing, but
challenges remain as near-term devices will have a limited number of physical
qubits and high error rates. Motivated by the usefulness of tensor networks for
machine learning in the classical context, we propose quantum computing
approaches to both discriminative and generative learning, with circuits based
on tree and matrix product state tensor networks that could have benefits for
near-term devices. The result is a unified framework where classical and
quantum computing can benefit from the same theoretical and algorithmic
developments, and the same model can be trained classically then transferred to
the quantum setting for additional optimization. Tensor network circuits can
also provide qubit-efficient schemes where, depending on the architecture, the
number of physical qubits required scales only logarithmically with, or
independently of the input or output data sizes. We demonstrate our proposals
with numerical experiments, training a discriminative model to perform
handwriting recognition using a optimization procedure that could be carried
out on quantum hardware, and testing the noise resilience of the trained model."),
William Huggins, Piyush Patel, K. Birgitta Whaley, E. Miles Stoudenmire,
arXiv: [1803.11537](http://arxiv.org/abs/1803.11537v1),
3/2018

- ["Barren plateaus in quantum neural network training landscapes"](
http://arxiv.org/abs/1803.11173v1
"Many experimental proposals for noisy intermediate scale quantum devices
involve training a parameterized quantum circuit with a classical optimization
loop. Such hybrid quantum-classical algorithms are popular for applications in
quantum simulation, optimization, and machine learning. Due to its simplicity
and hardware efficiency, random circuits are often proposed as initial guesses
for exploring the space of quantum states. We show that the exponential
dimension of Hilbert space and the gradient estimation complexity make this
choice unsuitable for hybrid quantum-classical algorithms run on more than a
few qubits. Specifically, we show that for a wide class of reasonable
parameterized quantum circuits, the probability that the gradient along any
reasonable direction is non-zero to some fixed precision is exponentially small
as a function of the number of qubits. We argue that this is related to the
2-design characteristic of random circuits, and that solutions to this problem
must be studied."),
Jarrod R. McClean, Sergio Boixo, Vadim N. Smelyanskiy, Ryan Babbush, Hartmut Neven,
arXiv: [1803.11173](http://arxiv.org/abs/1803.11173v1),
3/2018

- ["Quantum algorithms for training Gaussian Processes"](
http://arxiv.org/abs/1803.10520v1
"Gaussian processes (GPs) are important models in supervised machine learning.
Training in Gaussian processes refers to selecting the covariance functions and
the associated parameters in order to improve the outcome of predictions, the
core of which amounts to evaluating the logarithm of the marginal likelihood
(LML) of a given model. LML gives a concrete measure of the quality of
prediction that a GP model is expected to achieve. The classical computation of
LML typically carries a polynomial time overhead with respect to the input
size. We propose a quantum algorithm that computes the logarithm of the
determinant of a Hermitian matrix, which runs in logarithmic time for sparse
matrices. This is applied in conjunction with a variant of the quantum linear
system algorithm that allows for logarithmic time computation of the form
$\mathbf{y}^TA^{-1}\mathbf{y}$, where $\mathbf{y}$ is a dense vector and $A$ is
the covariance matrix. We hence show that quantum computing can be used to
estimate the LML of a GP with exponentially improved efficiency under certain
conditions."),
Zhikuan Zhao, Jack K. Fitzsimons, Michael A. Osborne, Stephen J. Roberts, Joseph F. Fitzsimons,
arXiv: [1803.10520](http://arxiv.org/abs/1803.10520v1),
3/2018



- ["Measurement-based adaptation protocol with quantum reinforcement
  learning"](
http://arxiv.org/abs/1803.05340v1
"Machine learning employs dynamical algorithms that mimic the human capacity
to learn, where the reinforcement learning ones are among the most similar to
humans in this respect. On the other hand, adaptability is an essential aspect
to perform any task efficiently in a changing environment, and it is
fundamental for many purposes, such as natural selection. Here, we propose an
algorithm based on successive measurements to adapt one quantum state to a
reference unknown state, in the sense of achieving maximum overlap. The
protocol naturally provides many identical copies of the reference state, such
that in each measurement iteration more information about it is obtained. In
our protocol, we consider a system composed of three parts, the "environment"
system, which provides the reference state copies; the register, which is an
auxiliary subsystem that interacts with the environment to acquire information
from it; and the agent, which corresponds to the quantum state that is adapted
by digital feedback with input corresponding to the outcome of the measurements
on the register. With this proposal we can achieve an average fidelity between
the environment and the agent of more than $90\% $ with less than $30$
iterations of the protocol. In addition, we extend the formalism to $ d
$-dimensional states, reaching an average fidelity of around $80\% $ in less
than $400$ iterations for $d=$ 11, for a variety of genuinely quantum as well
as semiclassical states. This work paves the way for the development of quantum
reinforcement learning protocols using quantum data, and the future deployment
of semi-autonomous quantum systems."),
F. Albarrán-Arriagada, J. C. Retamal, E. Solano, L. Lamata,
arXiv: [1803.05340](http://arxiv.org/abs/1803.05340v1),
3/2018



- ["Quantum Variational Autoencoder"](
http://arxiv.org/abs/1802.05779v1
"Variational autoencoders (VAEs) are powerful generative models with the
salient ability to perform inference. Here, we introduce a \emph{quantum
variational autoencoder} (QVAE): a VAE whose latent generative process is
implemented as a quantum Boltzmann machine (QBM). We show that our model can be
trained end-to-end by maximizing a well-defined loss-function: a "quantum"
lower-bound to a variational approximation of the log-likelihood. We use
quantum Monte Carlo (QMC) simulations to train and evaluate the performance of
QVAEs. To achieve the best performance, we first create a VAE platform with
discrete latent space generated by a restricted Boltzmann machine (RBM). Our
model achieves state-of-the-art performance on the MNIST dataset when compared
against similar approaches that only involve discrete variables in the
generative process. We consider QVAEs with a smaller number of latent units to
be able to perform QMC simulations, which are computationally expensive. We
show that QVAEs can be trained effectively in regimes where quantum effects are
relevant despite training via the quantum bound. Our findings open the way to
the use of quantum computers to train QVAEs to achieve competitive performance
for generative models. Placing a QBM in the latent space of a VAE leverages the
full potential of current and next-generation quantum computers as sampling
devices."),
Amir Khoshaman, Walter Vinci, Brandon Denis, Evgeny Andriyash, Mohammad H. Amin,
arXiv: [1802.05779](http://arxiv.org/abs/1802.05779v1),
2/2018

- ["Learning DNFs under product distributions via μ-biased quantum
  Fourier sampling"](
http://arxiv.org/abs/1802.05690v1
"We show that DNF formulae can be quantum PAC-learned in polynomial time under
product distributions using a quantum example oracle. The best classical
algorithm (without access to membership queries) runs in superpolynomial time.
Our result extends the work by Bshouty and Jackson (1998) that proved that DNF
formulae are efficiently learnable under the uniform distribution using a
quantum example oracle. Our proof is based on a new quantum algorithm that
efficiently samples the coefficients of a {\mu}-biased Fourier transform."),
Varun Kanade, Andrea Rocchetto, Simone Severini,
arXiv: [1802.05690](http://arxiv.org/abs/1802.05690v1),
2/2018

- ["Taking gradients through experiments: LSTMs and memory proximal policy
  optimization for black-box quantum control"](
http://arxiv.org/abs/1802.04063v1
"In this work we introduce the application of black-box quantum control as an
interesting rein- forcement learning problem to the machine learning community.
We analyze the structure of the reinforcement learning problems arising in
quantum physics and argue that agents parameterized by long short-term memory
(LSTM) networks trained via stochastic policy gradients yield a general method
to solving them. In this context we introduce a variant of the proximal policy
optimization (PPO) algorithm called the memory proximal policy optimization
(MPPO) which is based on this analysis. We then show how it can be applied to
specific learning tasks and present results of nu- merical experiments showing
that our method achieves state-of-the-art results for several learning tasks in
quantum control with discrete and continouous control parameters."),
Moritz August, José Miguel Hernández-Lobato,
arXiv: [1802.04063](http://arxiv.org/abs/1802.04063v1),
2/2018

- ["Leveraging Adiabatic Quantum Computation for Election Forecasting"](
http://arxiv.org/abs/1802.00069v1
"Accurate, reliable sampling from fully-connected graphs with arbitrary
correlations is a difficult problem. Such sampling requires knowledge of the
probabilities of observing every possible state of a graph. As graph size
grows, the number of model states becomes intractably large and efficient
computation requires full sampling be replaced with heuristics and algorithms
that are only approximations of full sampling. This work investigates the
potential impact of adiabatic quantum computation for sampling purposes,
building on recent successes training Boltzmann machines using a quantum
device. We investigate the use case of quantum computation to train Boltzmann
machines for predicting the 2016 Presidential election."),
Maxwell Henderson, John Novak, Tristan Cook,
arXiv: [1802.00069](http://arxiv.org/abs/1802.00069v1),
1/2018

- ["A Quantum Extension of Variational Bayes Inference"](
http://arxiv.org/abs/1712.04709v1
"Variational Bayes (VB) inference is one of the most important algorithms in
machine learning and widely used in engineering and industry. However, VB is
known to suffer from the problem of local optima. In this Letter, we generalize
VB by using quantum mechanics, and propose a new algorithm, which we call
quantum annealing variational Bayes (QAVB) inference. We then show that QAVB
drastically improve the performance of VB by applying them to a clustering
problem described by a Gaussian mixture model. Finally, we discuss an intuitive
understanding on how QAVB works well."),
Hideyuki Miyahara, Yuki Sughiyama,
arXiv: [1712.04709](http://arxiv.org/abs/1712.04709v1),
12/2017

- ["A quantum algorithm to train neural networks using low-depth circuits"](
http://arxiv.org/abs/1712.05304v1
"The question has remained open if near-term gate model quantum computers will
offer a quantum advantage for practical applications in the pre-fault tolerance
noise regime. A class of algorithms which have shown some promise in this
regard are the so-called classical-quantum hybrid variational algorithms. Here
we develop a low-depth quantum algorithm to train quantum Boltzmann machine
neural networks using such variational methods. We introduce a method which
employs the quantum approximate optimization algorithm as a subroutine in order
to approximately sample from Gibbs states of Ising Hamiltonians. We use this
approximate Gibbs sampling to train neural networks for which we demonstrate
training convergence for numerically simulated noisy circuits with depolarizing
errors of rates of up to 4%."),
Guillaume Verdon, Michael Broughton, Jacob Biamonte,
arXiv: [1712.05304](http://arxiv.org/abs/1712.05304v1),
12/2017

- ["Hardening Quantum Machine Learning Against Adversaries"](
http://arxiv.org/abs/1711.06652v1
"Security for machine learning has begun to become a serious issue for present
day applications. An important question remaining is whether emerging quantum
technologies will help or hinder the security of machine learning. Here we
discuss a number of ways that quantum information can be used to help make
quantum classifiers more secure or private. In particular, we demonstrate a
form of robust principal component analysis that, under some circumstances, can
provide an exponential speedup relative to robust methods used at present. To
demonstrate this approach we introduce a linear combinations of unitaries
Hamiltonian simulation method that we show functions when given an imprecise
Hamiltonian oracle, which may be of independent interest. We also introduce a
new quantum approach for bagging and boosting that can use quantum
superposition over the classifiers or splits of the training set to aggregate
over many more models than would be possible classically. Finally, we provide a
private form of $k$--means clustering that can be used to prevent an all
powerful adversary from learning more than a small fraction of a bit from any
user. These examples show the role that quantum technologies can play in the
security of ML and vice versa. This illustrates that quantum computing can
provide useful advantages to machine learning apart from speedups."),
Nathan Wiebe, Ram Shankar Siva Kumar,
arXiv: [1711.06652](http://arxiv.org/abs/1711.06652v1),
11/2017

- ["An efficient quantum algorithm for generative machine learning"](
http://arxiv.org/abs/1711.02038v1
"A central task in the field of quantum computing is to find applications
where quantum computer could provide exponential speedup over any classical
computer. Machine learning represents an important field with broad
applications where quantum computer may offer significant speedup. Several
quantum algorithms for discriminative machine learning have been found based on
efficient solving of linear algebraic problems, with potential exponential
speedup in runtime under the assumption of effective input from a quantum
random access memory. In machine learning, generative models represent another
large class which is widely used for both supervised and unsupervised learning.
Here, we propose an efficient quantum algorithm for machine learning based on a
quantum generative model. We prove that our proposed model is exponentially
more powerful to represent probability distributions compared with classical
generative models and has exponential speedup in training and inference at
least for some instances under a reasonable assumption in computational
complexity theory. Our result opens a new direction for quantum machine
learning and offers a remarkable example in which a quantum algorithm shows
exponential improvement over any classical algorithm in an important
application field."),
Xun Gao, Zhengyu Zhang, Luming Duan,
arXiv: [1711.02038](http://arxiv.org/abs/1711.02038v1),
11/2017

- ["Learning Hidden Quantum Markov Models"](
http://arxiv.org/abs/1710.09016v1
"Hidden Quantum Markov Models (HQMMs) can be thought of as quantum
probabilistic graphical models that can model sequential data. We extend
previous work on HQMMs with three contributions: (1) we show how classical
hidden Markov models (HMMs) can be simulated on a quantum circuit, (2) we
reformulate HQMMs by relaxing the constraints for modeling HMMs on quantum
circuits, and (3) we present a learning algorithm to estimate the parameters of
an HQMM from data. While our algorithm requires further optimization to handle
larger datasets, we are able to evaluate our algorithm using several synthetic
datasets. We show that on HQMM generated data, our algorithm learns HQMMs with
the same number of hidden states and predictive accuracy as the true HQMMs,
while HMMs learned with the Baum-Welch algorithm require more states to match
the predictive accuracy."),
Siddarth Srinivasan, Geoff Gordon, Byron Boots,
arXiv: [1710.09016](http://arxiv.org/abs/1710.09016v1),
10/2017

- ["Enhanced Quantum Synchronization via Quantum Machine Learning"](
http://arxiv.org/abs/1709.08519v1
"We study the quantum synchronization between a pair of two-level systems
inside two coupledcavities. Using a digital-analog decomposition of the master
equation that rules the system dynamics, we show that this approach leads to
quantum synchronization between both two-level systems. Moreover, we can
identify in this digital-analog block decomposition the fundamental elements of
a quantum machine learning protocol, in which the agent and the environment
(learning units) interact through a mediating system, namely, the register. If
we can additionally equip this algorithm with a classical feedback mechanism,
which consists of projective measurements in the register, reinitialization of
the register state and local conditional operations on the agent and register
subspace, a powerful and flexible quantum machine learning protocol emerges.
Indeed, numerical simulations show that this protocol enhances the
synchronization process, even when every subsystem experience different
loss/decoherence mechanisms, and give us flexibility to choose the
synchronization state. Finally, we propose an implementation based on current
technologies in superconducting circuits."),
F. A. Cárdenas-López, M. Sanz, J. C. Retamal, E. Solano,
arXiv: [1709.08519](http://arxiv.org/abs/1709.08519v1),
9/2017

- ["Generalized Quantum Reinforcement Learning with Quantum Technologies"](
http://arxiv.org/abs/1709.07848v1
"We propose a protocol to perform generalized quantum reinforcement learning
with quantum technologies. At variance with recent results on quantum
reinforcement learning with superconducting circuits [L. Lamata, Sci. Rep. 7,
1609 (2017)], in our current protocol coherent feedback during the learning
process is not required, enabling its implementation in a wide variety of
quantum systems. We consider diverse possible scenarios for an agent, an
environment, and a register that connects them, involving multiqubit and
multilevel systems, as well as open-system dynamics. We finally propose
possible implementations of this protocol in trapped ions and superconducting
circuits. The field of quantum reinforcement learning with quantum technologies
will enable enhanced quantum control, as well as more efficient machine
learning calculations."),
F. A. Cárdenas-López, L. Lamata, J. C. Retamal, E. Solano,
arXiv: [1709.07848](http://arxiv.org/abs/1709.07848v1),
9/2017

- ["Quantum Autoencoders via Quantum Adders with Genetic Algorithms"](
http://arxiv.org/abs/1709.07409v1
"The quantum autoencoder is a recent paradigm in the field of quantum machine
learning, which may enable an enhanced use of resources in quantum
technologies. To this end, quantum neural networks with less nodes in the inner
than in the outer layers were considered. Here, we propose a useful connection
between approximate quantum adders and quantum autoencoders. Specifically, this
link allows us to employ optimized approximate quantum adders, obtained with
genetic algorithms, for the implementation of quantum autoencoders for a
variety of initial states. Furthermore, we can also directly optimize the
quantum autoencoders via genetic algorithms. Our approach opens a different
path for the design of quantum autoencoders in controllable quantum platforms."),
L. Lamata, U. Alvarez-Rodriguez, J. D. Martín-Guerrero, M. Sanz, E. Solano,
arXiv: [1709.07409](http://arxiv.org/abs/1709.07409v1),
9/2017

- ["Quantum machine learning: a classical perspective"](
http://arxiv.org/abs/1707.08561v3
"Recently, increased computational power and data availability, as well as
algorithmic advances, have led machine learning techniques to impressive
results in regression, classification, data-generation and reinforcement
learning tasks. Despite these successes, the proximity to the physical limits
of chip fabrication alongside the increasing size of datasets are motivating a
growing number of researchers to explore the possibility of harnessing the
power of quantum computation to speed-up classical machine learning algorithms.
Here we review the literature in quantum machine learning and discuss
perspectives for a mixed readership of classical machine learning and quantum
computation experts. Particular emphasis will be placed on clarifying the
limitations of quantum algorithms, how they compare with their best classical
counterparts and why quantum resources are expected to provide advantages for
learning problems. Learning in the presence of noise and certain
computationally hard problems in machine learning are identified as promising
directions for the field. Practical questions, like how to upload classical
data into quantum form, will also be addressed."),
Carlo Ciliberto, Mark Herbster, Alessandro Davide Ialongo, Massimiliano Pontil, Andrea Rocchetto, Simone Severini, Leonard Wossnig,
arXiv: [1707.08561](http://arxiv.org/abs/1707.08561v3),
7/2017



- ["Experimental Quantum Hamiltonian Learning"](
http://arxiv.org/abs/1703.05402v1
"Efficiently characterising quantum systems, verifying operations of quantum
devices and validating underpinning physical models, are central challenges for
the development of quantum technologies and for our continued understanding of
foundational physics. Machine-learning enhanced by quantum simulators has been
proposed as a route to improve the computational cost of performing these
studies. Here we interface two different quantum systems through a classical
channel - a silicon-photonics quantum simulator and an electron spin in a
diamond nitrogen-vacancy centre - and use the former to learn the latter's
Hamiltonian via Bayesian inference. We learn the salient Hamiltonian parameter
with an uncertainty of approximately $10^{-5}$. Furthermore, an observed
saturation in the learning algorithm suggests deficiencies in the underlying
Hamiltonian model, which we exploit to further improve the model itself. We go
on to implement an interactive version of the protocol and experimentally show
its ability to characterise the operation of the quantum photonic device. This
work demonstrates powerful new quantum-enhanced techniques for investigating
foundational physical models and characterising quantum technologies."),
Jianwei Wang, Stefano Paesani, Raffaele Santagati, Sebastian Knauer, Antonio A. Gentile, Nathan Wiebe, Maurangelo Petruzzella, Jeremy L. O'Brien, John G. Rarity, Anthony Laing, Mark G. Thompson,
arXiv: [1703.05402](http://arxiv.org/abs/1703.05402v1),
3/2017

- ["Tomography and Generative Data Modeling via Quantum Boltzmann Training"](
http://arxiv.org/abs/1612.05204v1
"The promise of quantum neural nets, which utilize quantum effects to model
complex data sets, has made their development an aspirational goal for quantum
machine learning and quantum computing in general. Here we provide new methods
of training quantum Boltzmann machines, which are a class of recurrent quantum
neural network. Our work generalizes existing methods and provides new
approaches for training quantum neural networks that compare favorably to
existing methods. We further demonstrate that quantum Boltzmann machines enable
a form of quantum state tomography that not only estimates a state but provides
a perscription for generating copies of the reconstructed state. Classical
Boltzmann machines are incapable of this. Finally we compare small
non-stoquastic quantum Boltzmann machines to traditional Boltzmann machines for
generative tasks and observe evidence that quantum models outperform their
classical counterparts."),
Maria Kieferova, Nathan Wiebe,
arXiv: [1612.05204](http://arxiv.org/abs/1612.05204v1),
12/2016

- ["Quantum Machine Learning"](
http://arxiv.org/abs/1611.09347v1
"Recent progress implies that a crossover between machine learning and quantum
information processing benefits both fields. Traditional machine learning has
dramatically improved the benchmarking and control of experimental quantum
computing systems, including adaptive quantum phase estimation and designing
quantum computing gates. On the other hand, quantum mechanics offers
tantalizing prospects to enhance machine learning, ranging from reduced
computational complexity to improved generalization performance. The most
notable examples include quantum enhanced algorithms for principal component
analysis, quantum support vector machines, and quantum Boltzmann machines.
Progress has been rapid, fostered by demonstrations of midsized quantum
optimizers which are predicted to soon outperform their classical counterparts.
Further, we are witnessing the emergence of a physical theory pinpointing the
fundamental and natural limitations of learning. Here we survey the cutting
edge of this merger and list several open problems."),
Jacob Biamonte, Peter Wittek, Nicola Pancotti, Patrick Rebentrost, Nathan Wiebe, Seth Lloyd,
arXiv: [1611.09347](http://arxiv.org/abs/1611.09347v1),
11/2016

- ["Quantum algorithms for supervised and unsupervised machine learning"](
http://arxiv.org/abs/1307.0411v2
"Machine-learning tasks frequently involve problems of manipulating and
classifying large numbers of vectors in high-dimensional spaces. Classical
algorithms for solving such problems typically take time polynomial in the
number of vectors and the dimension of the space. Quantum computers are good at
manipulating high-dimensional vectors in large tensor product spaces. This
paper provides supervised and unsupervised quantum machine learning algorithms
for cluster assignment and cluster finding. Quantum machine learning can take
time logarithmic in both the number of vectors and their dimension, an
exponential speed-up over classical algorithms."),
Seth Lloyd, Masoud Mohseni, Patrick Rebentrost,
arXiv: [1307.0411](http://arxiv.org/abs/1307.0411v2),
7/2013

- ["Improved Bounds on Quantum Learning Algorithms"](
http://arxiv.org/abs/quant-ph/0411140v2
"In this article we give several new results on the complexity of algorithms
that learn Boolean functions from quantum queries and quantum examples.
  Hunziker et al. conjectured that for any class C of Boolean functions, the
number of quantum black-box queries which are required to exactly identify an
unknown function from C is $O(\frac{\log |C|}{\sqrt{{\hat{\gamma}}^{C}}})$,
where $\hat{\gamma}^{C}$ is a combinatorial parameter of the class C. We
essentially resolve this conjecture in the affirmative by giving a quantum
algorithm that, for any class C, identifies any unknown function from C using
$O(\frac{\log |C| \log \log |C|}{\sqrt{{\hat{\gamma}}^{C}}})$ quantum black-box
queries.
  We consider a range of natural problems intermediate between the exact
learning problem (in which the learner must obtain all bits of information
about the black-box function) and the usual problem of computing a predicate
(in which the learner must obtain only one bit of information about the
black-box function). We give positive and negative results on when the quantum
and classical query complexities of these intermediate problems are
polynomially related to each other.
  Finally, we improve the known lower bounds on the number of quantum examples
(as opposed to quantum black-box queries) required for $(\epsilon,\delta)$-PAC
learning any concept class of Vapnik-Chervonenkis dimension d over the domain
$\{0,1\}^n$ from $\Omega(\frac{d}{n})$ to $\Omega(\frac{1}{\epsilon}\log
\frac{1}{\delta}+d+\frac{\sqrt{d}}{\epsilon})$. This new lower bound comes
closer to matching known upper bounds for classical PAC learning."),
Alp Atici, Rocco A. Servedio,
arXiv: [quant-ph/0411140](http://arxiv.org/abs/quant-ph/0411140v2),
11/2004

- ["The geometry of quantum learning"](
http://arxiv.org/abs/quant-ph/0309059v1
"Concept learning provides a natural framework in which to place the problems
solved by the quantum algorithms of Bernstein-Vazirani and Grover. By combining
the tools used in these algorithms--quantum fast transforms and amplitude
amplification--with a novel (in this context) tool--a solution method for
geometrical optimization problems--we derive a general technique for quantum
concept learning. We name this technique "Amplified Impatient Learning" and
apply it to construct quantum algorithms solving two new problems: BATTLESHIP
and MAJORITY, more efficiently than is possible classically."),
Markus Hunziker, David A. Meyer, Jihun Park, James Pommersheim, Mitch Rothstein,
arXiv: [quant-ph/0309059](http://arxiv.org/abs/quant-ph/0309059v1),
9/2003

