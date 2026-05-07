# God-Complex
Ongoing research into a neural network which morphs the underlying rules of the universe in which it exists within.


Current machine learning is gated by the very properties that made its inception possible: the underlying rules of our universe. I propose that, rather than embedding neural networks into simulated versions of our own mathematical universe, we instead allow the network to bend the very rules we find crutial to our existance to its own will; essentially, creating a neural network which, rather than updating weights, could instead fold the very reality of its mathematical existence to best fit the task. For example, if the task requires, the network could bend the fundamental law of distrubution, or perhaps integrate subtraction into multiplication. Additonally, the network would have full control over the very space in which its neurons are contained within; one task could yeild standard 3-dimensional geometry, while another optimized by stretching and curving the distance between neurons continuously, or perhaps something more novel.


# Baseline Vaccum (Axiom 0)
To allow a network to control the very mathematical existence it is contained within, one must first define the scope of its most basic existence. Such an existence follows standard mathematics and would consist of:
* N-dimensional Euclidean space with a flat metric tensor
* Standard field axioms (Commutativity, Associativity, Distributivity, Identity, Inverse)
* Standard chain rule
* Standard linear accumulation, geometric scaling, symmetry, and inversion

# The Differential Substrate (Axiom 1)
Our mathematics prevent the path which inputs take from effecting the output; addition is cummutative, and multiplication associative. We must in essence make the trajectory of the operation an additional input.

Each arithmatic operation will be expressed as a continuous flow over a progress variablt $t$:
$$ H(A, B; \theta) = I(\theta) + \int_0^B \mathcal{K}(A, t, \theta)dt $$
Where $\mathcal{K}(A, t, \theta)$ is the interaction kernel, or the instantaneous step size at each moment of the operations unfolding. Unlike standard arithmatic, where $\mathcal{K}$ is constant or linear in $A$, and $t$ plays no role, this dynamic case makes $\mathcal{K}$ a full function of $t$; the step size changes as the operation progresses. When $\mathcal{K}$ varies with $t$, arithmatic becomes path-dependent. The result of $A \oplus B$ is not determined soley by $A$ and $B$; the trajectory the operation takes from $t = 0$ to $t = B$ is just as important.

To comprehend this, imagine oneself driving from point X to point Y. In standard arithmatic, whether or not you speed on the highway or navigate through city streets and country roads does not change the fact that your final destination is point Y. God-Complex breaks the asumption that the final destination is the ultimate goal; the roads taken, and subsequent time delay or fuel mileage, are differentially important. While standard arithmatic focuses on a consistent, predictable output, God-Complex can determine which road combination is most efficient for trip X to Y, and does so by integrating the path taken into the actual output.

Additionally, a dynamic step size does not in fact break backpropagation. By Leibniz's integral rule, as long as $\mathcal{K}$ is differential in $\theta$:

$$ \frac{ \partial}{ \partial \theta} \int_0^B \mathcal{K}(A, t, \theta) dt = \int_0^B \frac{ \partial \mathcal{K}}{ \partial \theta}(A, t, \theta) dt $$


# Constraints
Although extreme complexity is the basis of this supposed "God Complex", this complexity comes at a cost. As complexity scales, the neccessity for guardrails does so equally; A network with infinite freedom will experience catastrophic collapse. To prevent the divergence onto a "trivial solution", adequate guardrails must be implemented. Examples of potential guardrails include, but are not limited to:
* The Principle Of Minimum Action
* Information Persistence

These guardrails, however, come at a cost. A metabolic tax which drains the network anytime it attempts to break the laws of our universe could inadvertently punish the network for attempting to bend said rules in the first place, limiting exploration potential. Furthermore, although potentially detrimental to network stability, homeomorphic transformations could act as information bottlenecks, or potentially even expanders (as strange as that sounds), which could mathemetaically force specific functionalities onto the network fluidly. Enforcing a homeomorphic regime within the simulated universe would reduce network expression, and, in turn, could prune novel solutions to datasets.

Before diving into this, it is neccessary to adress the deep psychological divide between emergence and pre-existence:
* Are fundamental laws the ground for universal complexity?
* Are fundamental laws an inate property of all universes, regardless of complexity?
* Do universes act as rulesets for the emergence of fundamental laws?
* Or are fundamental laws merely an interpretation of the rules of a universe?


# Potential Modes of Failure
It is also important to list potential areas of failure, such as:
* The Trivial Void: the network redefines the correct answer entirely to whatever it is outputting.
* Axiomic Heat Death: The rules of the universe become too complex; signal to output ratio drops to zero, as the physics are too turbulent.
* The Brittle Universe: The network converges onto a set of rules that are too hyperspecific to the training data. Upon a new data point being introduced, they "shatter". The universe lacks general stability.
* Dimensional Fragmentation: Rather than remaining a smooth manifold, the network tears space into isolated pockets, preventing neurons from communicating. Failure of the homeomorphic constraint.
* The Zero Energy Stasis: If metabolic tax is too high, the network will freeze in place, as learning is too expensive.

