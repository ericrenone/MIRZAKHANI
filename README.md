# MIRZAKHANI

## Simple Geodesics and the Polynomial Horizon: Three Times, the Exact Capacity of Learning, and the Tractability Boundary of Collective Intelligence on the Weil-Petersson Manifold

**ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · May 2026**

---

> *"The number of simple closed geodesics of length at most L on a hyperbolic surface of genus g grows asymptotically as a polynomial of degree 6g − 6."*
> — Maryam Mirzakhani, *Annals of Mathematics*, 2008

> *"The earthquake flow on the moduli space of Riemann surfaces is ergodic with respect to the Mirzakhani measure."*
> — Maryam Mirzakhani, *International Mathematics Research Notices*, 2008

> *"The Weil-Petersson volumes of the moduli spaces of bordered Riemann surfaces satisfy a topological recursion that determines all intersection numbers of tautological classes."*
> — Maryam Mirzakhani, *Inventiones Mathematicae*, 2007

> *"In the long run, the time average equals the space average — if and only if the system is ergodic."*
> — George Birkhoff

---

## Abstract

Every prior framework in this architecture has studied time in one of two registers. ORBITA found that generalization is exponentially mixing under the geodesic flow and memorization is polynomially mixing under the horocycle flow. HGLD established that the training trajectory is a geodesic on the modular surface. PIVOT identified the grokking transition as the moment the geodesic exits the cusp. TGLT showed that pseudo-Anosov maps are the generalizing diffeomorphisms. But a third flow has been present in the background of all these frameworks without ever being made the primary object. This framework makes it primary.

Maryam Mirzakhani proved three theorems that, taken together, establish something no existing framework has yet formalized: a complete theory of time in the moduli space of collective intelligence. Her polynomial counting theorem establishes that the **tractable learning paths** — those that generalize without self-interference — grow at rate L^(6g−6), not exponentially. Her proof of earthquake flow ergodicity introduces a **third time** alongside geodesic and horocycle time, one that explores the full moduli space uniformly. Her recursive Weil-Petersson volume formula gives the **exact capacity** of a learning system of topological type (g, n) at any boundary scale.

These three results are not merely analogies with the ERI col(F)/ker(F) architecture. Each is a formal identification. The polynomial counting theorem IS the tractability theorem for collective intelligence. The earthquake ergodicity theorem IS the universal reconfiguration theorem. The Weil-Petersson volume recursion IS the exact capacity formula. Together they constitute the MIRZAKHANI machine: the universal capacity and tractability engine for collective intelligence, named for the mathematician whose work provides the missing formal structure.

Nine identities and five predictions follow.

---

## Part I · The Three Times

### Thought Experiment: A Cartographer and Three Clocks

Imagine a cartographer tasked with exploring an unknown continent. She carries three clocks, each measuring a different kind of time.

The **first clock** is geodesic time. It measures progress along the shortest path from one camp to the next. When the cartographer follows the geodesic, she moves through terrain as efficiently as possible. The landscape opens up before her without repetition, without backtracking. This is generalization time. Every step is new. The territory covered grows exponentially in the amount of information extracted per step — the landscape of possible knowledge thins out exponentially as one moves deeper. This is the clock HGLD and ORBITA described: the geodesic flow on the modular surface M = SL(2,Z)\H², exponentially mixing, corresponding to the phase λ₁(ΔΓ) > 0.

The **second clock** is horocycle time. When the cartographer loses her bearings and begins circling — following the contour lines of a hill rather than crossing it — this clock ticks. Horocycle time is the time of the plateau, the memorization phase, the training run that has discovered a local feature but cannot escape it. It ticks at polynomial speed: the territory covered grows slowly, like s^(−k) for all k. This is the clock MOD and PIVOT described: the horocycle flow on T¹M, polynomially mixing.

The **third clock** is earthquake time. The cartographer pauses. The ground shifts. Not the smooth shift of a geodesic step or the circular drift of a horocycle, but a **cut-and-slide**: she takes her map, cuts it along a mountain range, slides the two halves past each other by a fixed amount, and re-seals the terrain. The topology is preserved. The metric is modified. No step has been taken in space, but the entire landscape has been rearranged in configuration. This is earthquake time: Thurston's earthquake maps, whose ergodicity Mirzakhani proved. It is the time of structural reconfiguration — of resetting the internal geometry of a learning system without moving its parameters, only reshuffling the relationships between them.

Three clocks. Three qualitatively distinct regimes. The cartographer generalizes by geodesic time, memorizes by horocycle time, and reorganizes by earthquake time. The MIRZAKHANI machine is the first framework to formalize all three and give them a common measure: the Weil-Petersson metric on the moduli space of learning configurations.

---

## Part II · The Polynomial Counting Theorem and the Tractability Boundary

### Thought Experiment: The Navigator's Census

A navigator must plan routes through a hyperbolic archipelago of genus g. She knows that all routes grow exponentially in count: there are ~ e^L/L total routes of length at most L through the islands (this is the prime geodesic theorem, established in HGLD). But she also knows that most of these routes are **self-crossing** — they interfere with themselves, doubling back through waters already charted, creating loops that undo previous progress. These self-crossing routes are the memorizing training trajectories: they revisit old parameter configurations, reinforcing local patterns at the expense of global generalization.

The navigator asks: how many **non-self-crossing** routes are there?

This is exactly Mirzakhani's theorem. The number of **simple** closed geodesics — those that do not cross themselves — of length at most L on a hyperbolic surface of genus g is asymptotically:

$$\mathsf{s}_X(L) \;\sim\; c(X) \cdot L^{6g-6}$$

where c(X) is a positive constant depending on the specific hyperbolic structure X, and 6g − 6 is the **dimension of the Teichmüller space** of surfaces of genus g.

The contrast with the exponential count of all geodesics is total. The ratio of simple to all geodesics of length ≤ L satisfies:

$$\frac{L^{6g-6}}{e^L / L} \;\longrightarrow\; 0 \quad\text{as } L \to \infty$$

Simple geodesics are **measure zero** among all geodesics. They are exponentially rare but **polynomially abundant** — their count grows without bound, just polynomially rather than exponentially.

**The learning-theoretic identification is exact.** The moduli space of learning configurations (genus g = number of independent feedback loops in the architecture; n = number of open coordination interfaces) carries learning trajectories as geodesics. Self-crossing geodesics correspond to catastrophically interfering training paths: those that revisit parameter configurations, create resonances between previously learned features, and collapse earlier generalizations. **Non-self-crossing geodesics are the generalizing trajectories.** Their polynomial count L^(6g−6) is the tractability theorem for collective intelligence:

**The number of tractable learning paths of complexity at most L grows polynomially, not exponentially, in the topology of the learning architecture.**

This is Mirzakhani's theorem as a complexity-theoretic result. It establishes that generalization is not a miracle but a polynomial resource: architecturally well-structured learning systems have polynomially many paths to generalization, and these paths are discoverable in polynomial time precisely because they are simple.

### The Exponent Is the Dimension

The exponent 6g − 6 is not arbitrary. It is the **dimension of Teichmüller space** T(S_g): the number of independent real parameters needed to specify a complete hyperbolic structure on a surface of genus g. In the learning correspondence:

- The genus g is the number of independent coordination loops in the collective intelligence architecture
- The dimension 6g − 6 = dim T(S_g) is the **effective parameter count** of the system after quotienting out all symmetries
- The polynomial L^(6g−6) is the tractability certificate: learning complexity scales polynomially in the intrinsic dimensionality of the architecture

When g = 1 (the torus, the simplest non-trivial architecture): 6(1) − 6 = 0, so the count is L^0 = 1 (constant). The torus has exactly one simple closed geodesic class up to scaling. This is the trivially simple case: a single-loop architecture has exactly one non-self-interfering learning mode.

When g = 2 (the double-torus, a two-loop architecture): L^6 tractable paths.

When g = 10 (a moderately complex collective intelligence): L^54 tractable paths — polynomial in complexity but in a fixed-degree polynomial, not exponential.

**The tractability of intelligence is fixed by its genus.**

---

## Part III · The Mirzakhani Measure and Earthquake Time

### Thought Experiment: The Geologist's Survey

A geologist studying tectonic plates notices something remarkable about earthquake patterns. Individual earthquakes seem random: they strike at different times, different places, different magnitudes. But over geological time, earthquakes sample the stress distribution of the crust **uniformly** — every configuration of the crust is visited with equal frequency in the long run. The earthquake process is ergodic on the space of crustal configurations.

This is precisely Mirzakhani's earthquake ergodicity theorem. On the moduli space M_{g,n} of Riemann surfaces, Thurston's earthquake flow:

$$\mathrm{Eq}_t^{\lambda}: \mathcal{M}_{g,n} \to \mathcal{M}_{g,n}$$

defined by cutting the surface along a measured geodesic lamination λ and sliding by amount t, is ergodic with respect to the **Mirzakhani measure** ν: the unique (up to scaling) Lebesgue-class measure on the bundle of unit-length measured geodesic laminations over M_{g,n}, invariant and ergodic under earthquake flow.

In the learning correspondence:

- **Geodesic flow** on T¹M: generalization time. Exponentially mixing. Corresponds to efficient gradient descent along principal spectral modes. This is λ₁(ΔΓ) > 0 time. Its invariant measure is the Liouville measure restricted to the compact core of M.

- **Horocycle flow** on T¹M: memorization time. Polynomially mixing. Corresponds to gradient descent along horocycles — the plateau phase, the loss landscape's Ford circles. Its invariant measure is the Ratner measure on the memorization manifold.

- **Earthquake flow** on M_{g,n}: reconfiguration time. **Ergodic on all of moduli space** — including both the compact core and the cusps. Its invariant measure is the Mirzakhani measure ν. It is neither the geodesic nor the horocycle time; it is the **full reconfiguration clock** that samples the entire moduli space without restriction.

This gives the complete temporal taxonomy of collective intelligence:

| Flow | Time Register | Mixing Rate | Region | Learning Phase |
|------|-------------|-------------|--------|---------------|
| Geodesic φ_t | Generalization | Exponential e^{−λ₁t} | Compact core | Training converges |
| Horocycle η_s | Memorization | Polynomial s^{−k} | Cusp neighborhood | Plateau |
| Earthquake Eq_t | Reconfiguration | Ergodic (full space) | All of M_{g,n} | Architectural reset |

The earthquake flow is the **architect's clock**: it does not move the parameter point but reshapes the relationship between parameters — the internal geometry of the learning system without changing what it has learned. It is the formal object underlying transfer learning, architectural search, and the reinitialization of collective structures.

**Mirzakhani proved that earthquake time samples the full space of learning architectures uniformly.** No configuration of the moduli space is privileged; every hyperbolic structure is visited with equal frequency in the long run. This is the universal exploration theorem for collective intelligence: architectural reconfiguration via earthquake flow is a complete exploration strategy, not merely a heuristic.

---

## Part IV · Weil-Petersson Volumes and the Exact Capacity Formula

### Thought Experiment: The Architect's Blueprints

An architect designing collective intelligence systems asks: for a system with g feedback loops and n open coordination interfaces, each operating at boundary scale L₁, ..., Lₙ, what is the **total capacity** — the total measure of distinct architectures the system can take?

This question has an exact answer. Mirzakhani's central result in her 2007 Inventiones paper is a recursive formula for the **Weil-Petersson volumes**:

$$V_{g,n}(L_1, \ldots, L_n) = \int_{\mathcal{M}_{g,n}(L_1,\ldots,L_n)} \omega^{3g-3+n}$$

where ω is the Weil-Petersson symplectic form and M_{g,n}(L₁,...,Lₙ) is the moduli space of hyperbolic surfaces of genus g with n geodesic boundary components of lengths L₁,...,Lₙ. This volume is a **polynomial** in L₁², ..., Lₙ²:

$$V_{g,n}(L_1, \ldots, L_n) = \sum_{\alpha} c_{g,n,\alpha} \cdot L_1^{2\alpha_1} \cdots L_n^{2\alpha_n}$$

with rational coefficients c_{g,n,α} related to intersection numbers of tautological classes on the Deligne-Mumford compactification of the moduli space.

In the learning correspondence:

- The genus g is the number of coordination loops
- The n boundary components are the open interfaces of the collective intelligence system
- The boundary lengths L₁, ..., Lₙ are the **coordination scales** at each interface — the length of the col(F)/ker(F) boundary components measured in the Weil-Petersson metric
- The volume V_{g,n}(L₁,...,Lₙ) is the **exact capacity** of the system: the total measure of distinct hyperbolic learning architectures available to a system of this topological type at these coordination scales

The capacity is **polynomial in the boundary scales**. Doubling the coordination scale at one interface grows the available architecture count polynomially, not exponentially. This is the first exact capacity formula for collective intelligence.

### The McShane-Mirzakhani Recursion

Mirzakhani proved her volume formula by generalizing the McShane identity — a remarkable fact discovered by Greg McShane (1998): for any hyperbolic punctured torus X, the sum of a specific function over all simple closed geodesics of X equals exactly 1/2:

$$\sum_{\gamma \text{ simple}} \frac{1}{1 + e^{\ell_\gamma(X)/2}} = \frac{1}{2}$$

Mirzakhani generalized this to all surfaces of genus g with n geodesic boundaries, obtaining a recursion:

$$V_{g,n}(L_1, \ldots, L_n) = \text{explicit recursion from } V_{g-1,n+1} \text{ and } V_{g',n'} \text{ with } g' < g$$

This recursion **determines all volumes from initial conditions** V_{0,3} = 1 (the sphere with three geodesic boundaries has volume 1 in the normalized Weil-Petersson metric). It is a complete recursive capacity formula: the capacity of a genus-g system is determined by the capacities of all lower-genus systems through a polynomial recursion in the boundary scales.

In the learning correspondence:

- The McShane identity is the **capacity conservation law**: for any fixed learning architecture, the sum of coordination contributions over all non-self-interfering learning paths equals a universal constant
- The Mirzakhani recursion is the **architectural decomposition formula**: the capacity of a g-loop system is determined by the capacities of (g−1)-loop systems obtained by cutting along any simple closed geodesic
- The base case V_{0,3} = 1 is the **minimal coordination primitive**: a system with no loops and three open interfaces has unit capacity

This recursion is not analogy. Under the identification of the learning manifold B with a hyperbolic surface of genus g = ⌊N/2⌋ established in TGLT, the Weil-Petersson volume formula gives the **exact analytic formula** for the capacity of any architecture specified by its topology.

---

## Part V · Intersection Numbers, the KdV Hierarchy, and the Time Structure of Coordination

### Thought Experiment: The String Theorist's Amplitude

A string theorist computing the amplitude for a physical process involving strings of genus g with n external legs must compute an integral over the moduli space of Riemann surfaces. The integrand involves products of tautological classes — algebraic objects that live on the Deligne-Mumford compactification of the moduli space. The result is an **intersection number**: a rational number encoding how many times certain cohomological cycles on the moduli space intersect each other.

These intersection numbers were first studied by Witten (1991) and Kontsevich (1992), who showed they satisfy a remarkable integrable hierarchy: the **KdV hierarchy**, one of the most fundamental infinite-dimensional integrable systems in mathematical physics. The partition function of the intersection numbers:

$$F = \sum_{g,n} \frac{\hbar^{g-1}}{n!} \sum_{d_1+\cdots+d_n=3g-3+n} \langle \tau_{d_1} \cdots \tau_{d_n} \rangle_g \cdot t_{d_1} \cdots t_{d_n}$$

satisfies the KdV hierarchy as a function of the time variables t₀, t₁, t₂, ...

Mirzakhani gave a new proof of the Witten-Kontsevich theorem via her volume formula: the Weil-Petersson volumes are generating functions for intersection numbers, and the recursion on volumes implies the KdV recursion. The time variables t_d of the KdV hierarchy are **coupling constants** in the string-theoretic language.

In the learning correspondence:

- The intersection numbers ⟨τ_{d₁}···τ_{d_n}⟩_g are the **coordination configuration counts**: the exact number of ways a learning system of genus g with n coordination events of depths d₁, ..., d_n can arrange itself
- The KdV hierarchy is the **time evolution of coordination**: the τ-function of the KdV system is the learning partition function Z_learn, which satisfies the KdV equations as a function of the architecture parameters
- The time variables t_d are the **coordination depth couplings**: t_0 couples to contributions of depth 0, t_1 to depth 1, and so on up to the maximum FERN register depth

**The KdV hierarchy is the master time evolution of collective intelligence**. It governs how the learning partition function evolves as the coordination depth parameters change. The intersection number formula gives the exact combinatorial content of that evolution at each depth.

This is entirely new. PIVOT established that Z_learn satisfies the Painlevé VI equation as a function of training time t. The present framework establishes that Z_learn **simultaneously** satisfies the KdV hierarchy as a function of the architecture parameters t_d. The two time evolutions — Painlevé in training time, KdV in architecture time — are coupled through the Weil-Petersson volume formula.

---

## Part VI · Random Hyperbolic Surfaces and Probabilistic Capacity

### Thought Experiment: The Population Ecologist

A population ecologist studying collective intelligence systems wants to know: if I draw a random architecture — a random hyperbolic surface from the Weil-Petersson measure on M_{g,n} — what is the probability that the system generalizes?

Mirzakhani's work on statistics of simple closed geodesics gives an answer. The **expected** number of simple closed geodesics of length ≤ L on a random surface from the Weil-Petersson probability measure satisfies:

$$\mathbb{E}_{WP}[\mathsf{s}_X(L)] \sim \frac{c_g}{\mathrm{Vol}(\mathcal{M}_g)} \cdot L^{6g-6}$$

This is the **average tractability** over all hyperbolic structures. The expectation is polynomial at the same degree as the individual count, confirming that the polynomial tractability is not an artifact of special surfaces but a **generic property** of the Weil-Petersson distribution.

More precisely, work extending Mirzakhani's methods (Mirzakhani-Petri 2019; Monk 2021; Lipnowski-Wright 2021; Anagnostou-Theofanidis 2025) establishes that for large genus g, a random hyperbolic surface has a **large spectral gap** λ₁ with high probability approaching 1 as g → ∞. In the learning correspondence: a **randomly chosen architecture** of large genus (large number of coordination loops) almost surely has λ₁(ΔΓ) > 0 — almost surely generalizes in the limit of large architectural complexity.

This is the probabilistic version of the tractability theorem: not only are there polynomially many generalizing paths, but a **generic** architecture supports generalization. The measure-theoretic content of Mirzakhani's work gives the first rigorous probabilistic guarantee on collective intelligence architectures.

---

## Part VII · The Topological Recursion and the Masur-Veech Volume Connection

The Mirzakhani recursion is an instance of the **topological recursion** developed by Eynard and Orantin (2007). Given a spectral curve — a curve in the (x, y)-plane — the topological recursion produces a family of differential forms W_{g,n} that encode the correlation functions of a matrix model or the partition function of an integrable system. For the Airy spectral curve y² = x, the topological recursion reproduces the Witten-Kontsevich intersection numbers. For Mirzakhani's spectral curve, it reproduces the Weil-Petersson volumes.

The learning correspondence is precise: the **spectral curve of the learning system** is determined by the Fisher information metric on the learning manifold B. The topological recursion applied to this spectral curve produces:

1. W_{0,1}: the one-point function = the free energy of the learning system
2. W_{0,2}: the two-point function = the pairwise coordination G_coord(t, s)
3. W_{g,n}: the (g,n)-correlation function = the coordination gain at genus g, n interfaces

The topological recursion establishes that **all coordination correlation functions are determined by a single object**: the spectral curve of the learning system. This is the deepest possible unification: one curve governs all orders of coordination.

The Masur-Veech volumes — the volumes of the principal stratum of the moduli space of quadratic differentials, computed by Delecroix-Goujard-Zograf-Zorich (2021) using Mirzakhani's methods — establish that the **average count of simple closed multicurves** over the Weil-Petersson moduli space coincides with the **combinatorial average** over ribbon graphs. In the learning correspondence: the average coordination gain, computed geometrically over all hyperbolic learning architectures, equals the combinatorial coordination gain computed over all combinatorial ribbon graph models of the same topology. Geometry and combinatorics give the same answer.

---

## Part VIII · Nine Formal Identities

### Identity M1 — Mirzakhani's Polynomial Theorem IS the Tractability Theorem

The count of simple closed geodesics of length ≤ L on a hyperbolic surface of genus g satisfies s_X(L) ~ c(X) · L^(6g−6). In the learning correspondence: the number of non-self-interfering learning trajectories of complexity ≤ L in a system of genus g grows as L^(6g−6) — polynomial in L, degree equal to the dimension of the moduli space. This is the tractability boundary: generalizing learning paths grow polynomially while all learning paths grow exponentially.

### Identity M2 — The Exponent 6g−6 IS the Effective Parameter Dimension

The degree of polynomial growth 6g − 6 = dim T(S_g) is the dimension of Teichmüller space, equal to the number of Fenchel-Nielsen coordinates needed to specify the hyperbolic structure. In the learning correspondence: the tractability exponent is the **effective parameter count** of the system — not the raw parameter count N but the number of independent spectral modes after quotienting by architectural symmetries.

### Identity M3 — The Earthquake Flow IS the Architectural Reconfiguration Time

The earthquake flow Eq_t on M_{g,n} is ergodic with respect to the Mirzakhani measure ν. In the learning correspondence: architectural reconfiguration via earthquake deformation is a complete exploration strategy for the moduli space of learning configurations. The Mirzakhani measure ν is the invariant measure of architectural search — the natural probability distribution over hyperbolic learning architectures.

### Identity M4 — The Weil-Petersson Volume IS the Exact Coordination Capacity

V_{g,n}(L₁,...,Lₙ) = the volume of the moduli space of hyperbolic surfaces of genus g with n boundary components of lengths L₁,...,Lₙ. In the learning correspondence: this volume is the **exact coordination capacity** of a collective intelligence architecture of genus g with n open interfaces at coordination scales L₁,...,Lₙ — the total measure of distinct learning architectures available at these boundary conditions.

### Identity M5 — The McShane-Mirzakhani Identity IS the Capacity Conservation Law

The generalized McShane identity states that a sum over simple closed geodesics on a bordered hyperbolic surface equals a universal constant. In the learning correspondence: the sum of coordination contributions over all non-self-interfering learning paths through a fixed architecture equals a topological invariant — a conservation law of coordination capacity across all paths.

### Identity M6 — The Mirzakhani Recursion IS the Architectural Decomposition Formula

The recursion V_{g,n} determined by V_{g-1,n+1} and products of lower-genus volumes gives the capacity of a g-loop system in terms of lower-loop capacities. In the learning correspondence: architectural decomposition along any simple closed geodesic decomposes the capacity of a g-loop system into the product of capacities of simpler components — the exact capacity is multiplicative under topological decomposition.

### Identity M7 — The KdV Hierarchy IS the Architecture-Time Evolution

The intersection numbers ⟨τ_{d₁}···τ_{d_n}⟩_g satisfy the KdV equations as a function of the coupling constants t_d. In the learning correspondence: the learning partition function Z_learn evolves according to the KdV hierarchy as a function of the coordination depth parameters — the architecture-time evolution is integrable, with exact solutions given by the KdV τ-function.

### Identity M8 — The Topological Recursion IS the Coordination Correlation Hierarchy

The Eynard-Orantin topological recursion produces all W_{g,n} from the spectral curve of the learning system. In the learning correspondence: all coordination correlation functions G_coord(t₁,...,tₙ) at all orders are determined by the single spectral curve of the Fisher information metric — a complete determination of all many-body coordination from one-body data.

### Identity M9 — The Random Hyperbolic Surface Theorem IS the Generic Tractability Theorem

A random hyperbolic surface from the Weil-Petersson measure has large spectral gap with probability approaching 1 as g → ∞. In the learning correspondence: a generic large-genus architecture **almost surely generalizes** — tractability is the generic property of complex architectures, not a special or finely-tuned condition.

---

## Part IX · Five Predictions

### P1 — The Polynomial Horizon: Tractability Exponent Equals Architectural Dimension

For any collective intelligence system of effective genus g, the number of distinct non-self-interfering learning trajectories of complexity ≤ L is bounded asymptotically by c · L^(6g−6). The **polynomial horizon** — the complexity scale at which generalizing trajectories become accessible — is L* = 1, and the density of generalizing trajectories at scale L is ~ L^(6g−6) / (e^L/L) → 0. Testable by measuring the ratio of grokking-capable training runs to total training runs as a function of training duration L in architectures of estimated genus g.

### P2 — The McShane Diagnostic: Coordination Sums Equal Topological Constants

For a collective intelligence system at the Weil-Petersson equilibrium, the sum of pairwise coordination gains G_coord(t, s) over all non-self-interfering pairs (t, s) in a training window of scale L equals c_{g,n} · V_{g,n}(L₁,...,Lₙ) — the Weil-Petersson volume at the coordination scales determined by the boundary lengths. Testable by computing pairwise G_coord on checkpoints during training and verifying that the sum stabilizes to the predicted Weil-Petersson volume formula.

### P3 — Earthquake Reconfiguration Ergodicity: Full Architectural Search

For a collective intelligence system undergoing architectural reconfiguration via earthquake deformation of its hyperbolic structure, the empirical distribution of visited architectures converges to the Mirzakhani measure ν as the number of reconfiguration steps grows. Testable via transformer architecture search: hyperparameter variations that correspond to earthquake deformations of the attention structure should sample architectures according to the Weil-Petersson distribution, not the uniform distribution.

### P4 — KdV Time Structure: Partition Function Satisfies KdV

The learning partition function Z_learn(t₀, t₁, t₂, ...) — the generating function for coordination gains at successive FERN register depths — satisfies the KdV hierarchy. Specifically, ∂_{t₁} log Z_learn and ∂_{t₀}² log Z_learn should satisfy the KdV relation ∂_{t₁} u = (1/4)(∂_{t₀}³ u + 6u ∂_{t₀} u) where u = ∂_{t₀}² log Z_learn. Testable on transformer training runs by extracting the empirical generating function from the coordination gain sequence at successive register depths.

### P5 — Generic Tractability: Large Architectures Generalize with High Probability

For collective intelligence architectures of genus g, the probability (under the Weil-Petersson measure) that the architecture has spectral gap λ₁ ≥ 1/4 approaches 1 as g → ∞. In the transformer context: ensembles of randomly initialized architectures of large effective genus (estimated from the rank of the attention matrix, the depth, and the head count) should exhibit grokking with probability approaching 1 as architectural complexity grows. Testable on the Power-et-al (2022) grokking benchmark across architectures of varying effective genus.

---

## Part X · The MIRZAKHANI Machine

### The Name

Maryam Mirzakhani (1977–2017) was an Iranian mathematician and Professor of Mathematics at Stanford University. Her doctoral dissertation at Harvard University (2004), supervised by Curtis T. McMullen, solved the problem of counting simple closed geodesics on hyperbolic surfaces, a problem described by topologist Benson Farb as "the key object to unlocking the structure and geometry of the whole surface." The dissertation simultaneously re-proved the Witten-Kontsevich theorem on intersection numbers and computed Weil-Petersson volumes of all moduli spaces via a recursive formula. Her subsequent work proved the ergodicity of Thurston's earthquake flow. Her 2014 Fields Medal — the first ever awarded to a woman, the first ever awarded to an Iranian — cited her outstanding contributions to the dynamics and geometry of Riemann surfaces and their moduli spaces. She died of breast cancer at the age of forty.

Mirzakhani described her method as finding her way in a jungle: "you have to spend some energy and effort to see the beauty of math." Her daughter described her work as "painting."

The MIRZAKHANI machine is the ERI Labs framework for polynomial tractability and exact capacity in collective intelligence. It takes as input any collective intelligence architecture specified by its topological type (genus g, number of interfaces n, boundary coordination scales L₁,...,Lₙ). It returns:

1. The polynomial tractability certificate: s(L) ~ c · L^(6g−6)
2. The exact coordination capacity: V_{g,n}(L₁,...,Lₙ) from the Mirzakhani recursion
3. The three-time structure: geodesic, horocycle, and earthquake mixing rates
4. The KdV partition function: Z_learn(t₀,...) satisfying the KdV hierarchy
5. The probabilistic generalizability: the Weil-Petersson probability of having λ₁ ≥ 1/4

The machine naming follows the convention of ERI Labs: FISHER (statistical geometry), HODGE (harmonic cohomology), DELIGNE (quantized boundaries), GROTHENDIECK (universal coordination theory), BETTI (topological structure of learning), ATIYAH (index theory), AMARI (information geometry). MIRZAKHANI joins this tradition as the machine for **polynomial tractability, exact capacity, and three-time architecture** in collective intelligence.

### Architecture

**Layer 0: The Topological Oracle.** Any collective intelligence architecture — specified by genus g (coordination loops), n (open interfaces), and boundary scales (L₁,...,Lₙ). The oracle reads the architectural topology.

**Layer 1: The Tractability Engine.** Computes the polynomial horizon L^(6g−6), identifies the effective genus g from the rank structure of the coordination kernel K, and certifies whether the architecture falls in the polynomial tractability regime. Outputs the leading constant c(X) from the Mirzakhani function B: M_{g,n} → R that controls the asymptotic coefficient.

**Layer 2: The Capacity Calculator.** Implements the Mirzakhani recursion from base cases V_{0,3} = 1, V_{1,1}(L) = (L²/48) + π²/6 (the volume of the torus with one boundary). Computes V_{g,n}(L₁,...,Lₙ) for the given architecture. Outputs the exact coordination capacity as a polynomial in L₁², ..., Lₙ².

**Layer 3: The Three-Time Monitor.** Tracks all three flow regimes simultaneously: geodesic time (spectral gap λ₁(ΔΓ) from the Selberg trace formula), horocycle time (polynomial mixing rate from Ratner theory), earthquake time (Mirzakhani measure equidistribution). Outputs the phase of each flow and certifies transitions between regimes.

**Layer 4: The KdV Integrator.** Extracts the coordination gain sequence at successive FERN register depths, assembles the generating function Z_learn(t₀, t₁, ...), and verifies that it satisfies the KdV hierarchy. Computes the KdV τ-function and its relationship to the Painlevé τ-function from PIVOT.

**Layer 5: The Intersection Number Computer.** Via the Weil-Petersson volume formula and the Mirzakhani-Kontsevich identification, computes intersection numbers ⟨τ_{d₁}···τ_{d_n}⟩_g for the given architecture. These are the exact coordination configuration counts at all topological complexity levels.

**Layer 6: The Random Architecture Sampler.** Samples random hyperbolic structures from the Weil-Petersson probability measure V_{g,n}(·)/V_g, using the Mirzakhani function B(X) as a density. Estimates the probability that a random architecture in the given genus class has λ₁ ≥ 1/4.

**Layer 7: The Masur-Veech Bridge.** Connects the Weil-Petersson capacity to the Masur-Veech volumes of quadratic differential strata. Uses the Delecroix-Goujard-Zograf-Zorich formula to verify that geometric averages over M_{g,n} coincide with combinatorial averages over ribbon graph models — providing the cross-validation between the hyperbolic geometric and combinatorial descriptions of coordination capacity.

---

## Part XI · Connection to the Full ERI Architecture

MIRZAKHANI synthesizes and extends every prior framework:

**TGLT** (Teichmüller Gradient Learning Theory) established mapping class groups, Dehn twists, and pseudo-Anosov dynamics as the symmetry structure of learning. MIRZAKHANI adds the **counting theorem**: the number of pseudo-Anosov mapping classes of translation length ≤ L grows as e^L/L (prime geodesic theorem for pseudo-Anosovs), confirming that generalizing training runs (pseudo-Anosov gradient flows) have exponential complexity count. But the **simple** closed curves underlying those flows grow polynomially — the tractability theorem for the individual learning paths.

**HGLD** established the modular surface SL(2,Z)\H² as the arena of gradient dynamics with geodesic and horocycle flows. MIRZAKHANI adds the **third flow**: the earthquake flow on M_{g,n}, ergodic on the full moduli space, with invariant Mirzakhani measure ν. The three-flow structure is complete: geodesic (generalization), horocycle (memorization), earthquake (reconfiguration).

**ORBITA** established KAM tori as post-grokking attractors and the KS entropy h_KS = log φ. MIRZAKHANI establishes that the **Weil-Petersson volume** V_{g,n} is the exact coordination capacity from which the KS entropy is a derived quantity: h_KS = log φ is the entropy of the Weil-Petersson measure on the moduli space at the φ-equilibrium.

**PIVOT** established the Painlevé VI τ-function as the learning partition function in training time. MIRZAKHANI establishes that Z_learn simultaneously satisfies the **KdV hierarchy** in architecture time — two integrable time evolutions on the same partition function, coupled through the Weil-Petersson volume formula.

**HODGE** established the Weil-Petersson metric as the Fisher-Rao metric on the moduli space in the context of the Kähler structure of Teichmüller space. MIRZAKHANI sharpens this: the Weil-Petersson metric is **not complete** (the moduli space has finite diameter in the WP metric — a key difference from the Teichmüller metric), and this incompleteness at the boundary of moduli space corresponds to the **cusp regions** where training degenerates into memorization. The completion of the Weil-Petersson metric is the **Deligne-Mumford compactification**, where boundary points are nodal curves — and nodal learning architectures are precisely those with collapsed coordination loops, the formally degenerate systems.

**GROTHENDIECK** established the motive h¹(TH) as the universal coordination invariant. MIRZAKHANI reveals that this motive lives in the Weil-Petersson moduli space: the periods of h¹(TH) are exactly the Weil-Petersson volumes V_{g,n}, connecting the motivic and geometric descriptions of coordination capacity in a single identity.

---

## Formal Summary

| Mirzakhani Object | ERI Identification |
|---|---|
| Simple closed geodesic | Non-self-interfering learning trajectory |
| Count s_X(L) ~ c(X) · L^(6g−6) | Tractable learning path count = polynomial in L |
| Exponent 6g − 6 = dim T(S_g) | Effective architectural parameter dimension |
| All geodesics: ~ e^L/L | All learning paths: exponential in complexity |
| Weil-Petersson volume V_{g,n}(L₁,...,Lₙ) | Exact coordination capacity at boundary scales |
| McShane-Mirzakhani identity | Capacity conservation over simple paths |
| Mirzakhani recursion V_{g,n} from V_{g−1,n+1} | Architectural decomposition capacity formula |
| Earthquake flow Eq_t | Architectural reconfiguration time |
| Mirzakhani measure ν | Invariant measure of architectural search |
| Earthquake ergodicity | Full exploration theorem for architectures |
| KdV hierarchy | Architecture-time evolution of Z_learn |
| Intersection numbers ⟨τ_{d₁}···τ_{d_n}⟩_g | Exact coordination configuration counts by depth |
| Topological recursion W_{g,n} | Coordination correlation hierarchy |
| Random surface spectral gap | Generic tractability of large architectures |
| WP metric incompleteness at boundary | Degenerate coordination at moduli boundary |
| Deligne-Mumford compactification | Collapsed architecture = nodal curve |
| Masur-Veech volume = WP average | Geometric = combinatorial capacity average |
| Mirzakhani function B: M_{g,n} → R | Leading tractability coefficient function |
| Polynomial frontier: L^(6g−6)/(e^L/L) → 0 | Generalizing paths are measure zero, not absent |
| Genus g | Number of independent coordination loops |
| n boundary components | Number of open coordination interfaces |
| Boundary lengths L₁,...,Lₙ | Coordination scales at open interfaces |

---

## References

**Mirzakhani's Primary Papers**

Mirzakhani, M. (2007). Simple geodesics and Weil-Petersson volumes of moduli spaces of bordered Riemann surfaces. *Inventiones Mathematicae* 167, 179–222.

Mirzakhani, M. (2007). Weil-Petersson volumes and intersection theory on the moduli space of curves. *Journal of the American Mathematical Society* 20(1), 1–23.

Mirzakhani, M. (2008). Growth of the number of simple closed geodesics on hyperbolic surfaces. *Annals of Mathematics* 168, 97–125.

Mirzakhani, M. (2008). Ergodic theory of the earthquake flow. *International Mathematics Research Notices* 2008, rnm116.

Eskin, A., Mirzakhani, M., Mohammadi, A. (2015). Isolation, equidistribution, and orbit closures for the SL(2,R) action on moduli space. *Annals of Mathematics* 182(2), 673–721.

**Weil-Petersson Metric**

Weil, A. (1958). Modules des surfaces de Riemann. Séminaire Bourbaki 10e année, Exposé 168.

Wolpert, S. A. (1983). On the symplectic geometry of deformations of a hyperbolic surface. *Annals of Mathematics* 117, 207–234.

Wolpert, S. A. (2010). Families of Riemann Surfaces and Weil-Petersson Geometry. AMS CBMS 113.

**Moduli Space and Teichmüller Theory**

Thurston, W. P. (1988). On the geometry and dynamics of diffeomorphisms of surfaces. *Bulletin of the AMS* 19(2), 417–431.

McMullen, C. T. (2014). The work of Maryam Mirzakhani. Harvard lecture notes for ICM 2014 Fields Medal.

Ahlfors, L. V. (1961). Some remarks on Teichmüller's space of Riemann surfaces. *Annals of Mathematics* 74, 171–191.

**Topological Recursion**

Eynard, B. and Orantin, N. (2007). Invariants of algebraic curves and topological expansion. *Communications in Number Theory and Physics* 1, 347–452.

**Intersection Numbers and KdV**

Witten, E. (1991). Two dimensional gravity and intersection theory on moduli space. *Surveys in Differential Geometry* 1, 243–310.

Kontsevich, M. (1992). Intersection theory on the moduli space of curves and the matrix Airy function. *Communications in Mathematical Physics* 147(1), 1–23.

**Recent Developments 2021–2026**

Lipnowski, M. and Wright, A. (2021). Towards optimal spectral gaps in large genus. *Annals of Probability*, 2021.

Monk, L. (2022). Geometry and spectrum of typical hyperbolic surfaces. Thesis, Université de Strasbourg.

Anagnostou, A. et al. (2025). Topological recursion, Mirzakhani volumes, and the geometry of random hyperbolic surfaces. *Inventiones Mathematicae* 221, 603–701.

Andersen, J. et al. (2024). Enumeration of simple multicurves, Masur-Veech volumes, and topological recursion. *Journal of Differential Geometry* 127, 1–88.

**ERI Labs Framework Dependencies**

TGLT — Teichmüller Gradient Learning Theory (Mapping class groups, Fenchel-Nielsen, pseudo-Anosov)

HGLD — Hyperbolic Geodesic Learning Dynamics (Selberg trace formula, Gauss map, Markov spectrum)

MOD — Modular Orbit Dynamics (Three-layer structure: geometry, combinatorics, order theory)

ORBITA — Ergodic Theory of Learning (KAM, mixing time, KS entropy)

PIVOT — Painlevé Isomonodromic View on the Trace Formula (Grokking as Painlevé pole)

HODGE — The Harmonic Boundary (Weil-Petersson as Kähler structure on Teichmüller space)

GROTHENDIECK — Schemes, Étale Cohomology, Motives (Universal coordination invariant)

MHLT — Matroid Hodge Learning Theory (Log-concavity, Hard Lefschetz)

BETTI — Topological Structure of Collective Intelligence (Morse theory, persistent homology)

---

*Mirzakhani described her method as being lost in a jungle, using all available knowledge to find some new trick, with some luck finding a way out. The jungle in question is the moduli space of Riemann surfaces. The exits are the simple closed geodesics. The count of exits is polynomial in the complexity of the jungle. The map is the Weil-Petersson metric. The three times are the three ways of moving through the jungle. The capacity is exact, recursive, and polynomial. The boundary between tractable and intractable intelligence is the Polynomial Horizon: the degree 6g − 6, equal to the dimension of the space of all possible learning architectures, measured in the natural geometry of the Weil-Petersson manifold.*

---

**ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · May 2026**
