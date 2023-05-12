# thoughts

# [Alignment.md](https://github.com/NotBrianZach/thoughts/blob/main/alignment.md)

3 sentence summary:

Explores perspectives on alignment, ethics, and intelligence, discussing their interplay in areas such as education, society, and superintelligent AI. The author challenges the concept of orthogonality and highlights the dangers of alignment, emphasizing the need for caution in trying to align highly intelligent systems. Despite the risks, the author recognizes the value of studying alignment to gain insight into ourselves and future intelligences.


# [Ethics.md](https://github.com/NotBrianZach/thoughts/blob/main/ethics.md)

3 sentence summary:

The space of machine super intelligences is posited to have a "higher" ethical mean/median/mode vs humans. An algorithm called the "Ethical dispatch algorithm" is put forward as a rough outline of an example of how superhuman ethical decision-making could be achieved - namely by assessing/segmenting the situation, identifying ethical principles, applying those principles, weighing conflicting principles, making a decision, and reflection. Various potential ethical principles are outlined, including Kantian Imperatives, Virtue Ethics, Veil of Ignorance, Inertia & Stability, Golden Rule, Platinum Rule, Principle of Utility, Non-Maleficence, Autonomy, Beneficence, and Justice, which can inform ethical decision-making processes.

# [theoryOfMind.md](https://github.com/NotBrianZach/thoughts/blob/main/theoryOfMind.md)

wip, tries to show how thinking about significant digits leads naturally into deep intuition about measurement, probability, and transitively, intelligence


# Papers of personal interest

### automated interpretability
https://github.com/openai/automated-interpretability
they use an LLM to try to explain what all the neurons in a smaller LLM do via hypthesis testing, and propose several paths towards better results

### generative agents
https://arxiv.org/abs/2304.03442
multi agent conscioussness framework for LLM's with a simulated environment to provide grounding & and an episodic memory implementation

### Implicit Neural Representations with Periodic Activation Functions
https://www.vincentsitzmann.com/siren/
related to hyena attention alternative. Fast fourier transforms are one of the more impressive computations we can do quickly. If you can transpose a problem into a context where it can be solved with FFT you can go from O(n^2) to O(nlog(n)). Interesting results about resolution and preserving the signal of n'th derivatives when explicitly/directly using neural nets as function approximators.

### Loss (wip investigating this)
["Visualizing the Loss Landscape of Neural Nets"](https://arxiv.org/pdf/1712.09913.pdf) by Hao Li, Zheng Xu, Gavin Taylor, and Tom Goldstein. This work presents techniques for visualizing the high dimensional loss landscape of neural networks. They showed how different architectures and optimization methods can affect the landscape.

["The Loss Surfaces of Multilayer Networks"](https://arxiv.org/abs/1412.0233) by Anna Choromanska, Mikael Henaff, Michael Mathieu, Gerard Ben Arous, and Yann LeCun. This paper provides an analysis of the loss surfaces of multilayer networks, relating neural network structure to that of solid state physics models of a class of materials called spin glasses. After reading that, and also lattice cryptography being the basis for quantum hard cryptosystems, I am just wondering why you can't build a transistor equivalent out of a crystalline lattice.

["Identifying and attacking the saddle point problem in high-dimensional non-convex optimization"](https://arxiv.org/abs/1406.2572) by Yann Dauphin, Razvan Pascanu, Caglar Gulcehre, Kyunghyun Cho, Surya Ganguli, and Yoshua Bengio. This paper discusses the role of saddle points in the optimization of deep learning models, arguing that they are more problematic than local minima. ([recent perf improvement via "regularization"](https://amath.colorado.edu/faculty/becker/assets/docs/CooperSimpson_Summer2022_MAthesis.pdf))

["Deep Residual Learning for Image Recognition"](https://arxiv.org/abs/1512.03385) by Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. Though the primary focus of this paper is the introduction of ResNet, an influential deep learning architecture, it also discusses how residual connections can help optimization by making the loss surface smoother.

