## `./3/3_AD_ex.tex`

Example: p-exp metric family (p-exp-metric-family) ~> proof
  Part 1: positivity, symmetry: basics
    define | | as absolute value

  Thm: Mulholland statement ~> todo

  Part 2:
    continuity of functions & composition
    monotonicity & composition
    convexity & composition

    Convexity of $F(e^t)$:
Logarithmic properties
      characterization of convexity: second derivative positive
      lim x-> inf f(x) = 1 & f(x) strictly increasing -> f(x) > 1
        increasing = f' > 0
        limit properties


Rem: Minkowski is in p-exp family ~> proof
  Limit of functions x -> inf
  Continuity = limit in function
  L Hospital rule


## ./4/1_seg_add_metrics.tex


Thm: Representation Theorem for Segmentally Additive Proximity Structures ~> cite?

Metric stuff: missing defs metric, continuous, closed, open interval, supremum, finite sequences

Remark: continuity & monotonicity of sub length ~> cite Busemann


## ./4/2_seg_add_PS.tex

Missing representation theorem?

## ./4/3_seg_add_metrics_ex.tex

Ex: segmental additivity of the minkowski metric ~> proof
  basic arithmetic


## ./5/1_neccesary_and_suff_conds.tex


Thm: Necessary and sufficient conditions for additive difference metrics ~> proof
  Representation by G: metric induces ordinal scale ~> todo
  Form of H_i: Basic argumentation, linear function definition ~> todo check if only linear functions satisfy this
  Form of F_i: Basic argumentation

  Inequality 1: ~> proof, todo add name
    triangle inequality, basic argumentation

  F continuous ~> proof
    increasing -> discontinuities are gaps ~> ref?
    real analysis ~> countable many gaps
    epsilon-delta continuity

  Characterization of convexity ~> proof
    Part 1
      basic args
    Part 2
      basic args
      characterization of convexity ~> ref
  

Rem: form of metric, G = F^-1 ~> proof
  increasing functions has inverse



## ./5/2_lp_repr_theorem.tex

Thm: unique representation theorem ~> proof
  Part 0: establishing basics and applying lemma ~> todo formulate part and apply lemma

  Part 1: extending the bounds of F:
    basic argumentation
    repeatedly applying the argument

  Part2: Deriving functional equation
    basic args
    Hardy ~> ref
    Aczel ~> ref

  Part3: proving equality for positive reals
    basics args
    Theorem add diff prox struct ~> todo smth



## ./5/2-0_lemma.tex

Notation and definitions at start ~> todo check where to add

Rem: translation invariance and domain ~> proof
  i) translation invariance:
    basic args
  ii) domain:
    basic args
  iii) greatest possible difference
    basic args, cartesian product
  iv) continuity
    composition of continuous


Lem: distance between open and compact set ~> proof, todo add name
  compactness, convergent subsequence ~> todo ref?
  limit points, convergence in closed sets


Lem: arbitrary small delta balls ~> proof
  continuity of partial functions ~> todo check
  basic args

Lem: main lemma ~> proof, todo add name
  Part0:
    topology open&closed
    continuous images of compact sets ~> todo check
    boundedness with respect to metrics ~> todo check

  Part 1:
    basic args

  Part2:
    basic args
    convex combinatoin ~> todo
    convexity of spheres ~> proof
    basic args

  Part3:
    basic args
    repeating argument ~> todo check

  Part4:
    continuity
    basic args


## ./5/2-1_convex_spheres.tex

defs convex combination (strict), convex hull

Thm: conv hull = set of all conv combs ~> todo ref
Thm: compact -> conv hull compact ~> todo ref

def extreme point
Thm: Minkowski Theorem ~> todo ref

Lem: open/closedness of delta balls ~> proof
  continuity, partial function continuity
  topological continuity closed sets ~> todo ref

Lem: compressing extreme points ~> proof
  basic args

Lem: convexity of balls ~> proof
  basic args
  density and limits for Q and R ~> todo ref
