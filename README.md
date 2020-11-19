# Southampton-Masters-dissertation

**TITLE:**
Policy-adaptable methods for resolving normative conflicts through argumentation and graph colouring

**ABSTRACT:**
In a multi-agent system, one may choose to govern the behaviour of an agent by imposing norms, which act as guidelines for how agents should act either all of the time or in given situations. However, imposing multiple norms on one or more agents may result in situations where these norms conflict over how the agent should behave. In any system with normative conflicts (such as safe reinforcement models or systems which monitor safety protocols), one must decide which norms should be followed such that the most important and most relevant norms are maintained. We introduce a new method for resolving normative conflicts through argumentation and graph colouring which is compatible with a variety of normative conflict resolution policies. We prove that this method always creates an admissible set of arguments under argumentation semantics, meaning that it produces coherent outputs. We also introduce more robust variants of this method, each building upon their predecessor to create a superior output, and we include further mathematical proof of their coherence. Our most advanced variant uses the existing concept of curtailment, where one norm may supersede another without fully eliminating it. The methods we introduce are all compatible with various pre-existing policies for resolving normative conflicts. Empirical evaluations are also performed to compare our algorithms to each other and to others in existing literature

**Description**
Some of the results of this paper have been implemented in "ColourResolve.ipynb" (Jupyter notebook file) and "ColourResolveComplete.ipynb". 
"ColourResolve weak ordering comparison.ipynb" provides the source code for an empirical comparison performed in Section 5 of the dissertation.
