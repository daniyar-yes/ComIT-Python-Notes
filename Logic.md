Logic is the study of reasoning.

Not all thoughts are linked to reasoning
Invications (max speed, insert card, etc.);
interrogations
exclamations (
lament (what a pity, what joy etc.)

Thoughts are linked to reasoning:
express information about something or someone;
Today is 15 degress C.
John is taller that Peter.
The moon is made of cheese.
The order of the factors doesn't alter the product.
These all can be TRUE or FALSE.

Reasoning is evaluating the THRUTH or FALSE.

There can be Incorrect and Correcct Reasoning
Take 2 bits of information and generate something new.

<b>PROPOSITIONAL LOGIC</b>
<ul>
  <li>Propositions
  <li>Atomic
<li>Molecular
<li>Link terms to connectives
</ul>


Proposition:
Sentence that describe some property about someone or something.
It has precise words and a clear sense.
Can be evaluated to true or false.


Type of propositions:
<b>Atomic</b>
is the simplest proposition.
Very short sentences that you can evaluate to T or F instantly.

<b> Molecular</b>
Composed of atomic propositions joined by link terms (or connectives).

<b>Link Terms (or connectives):</b> they link 2 propositions.
  <ul>
  <li>Conjunctions 'AND'. E.g. John goes to the movies <b>and</b> Maria makes supper.
  <li>Disjunction 'OR': E.g. John goes to the movies <b>OR</b> Maria makes supper.
  <li>Negation 'NOT', ~ It does not 'connect' two propositions, but applies to one. Denies it.
    E.g. Maria <b>does not</b> make supper. I <b>do not</b> live in Uruguay.
  </ul>
  
  <b>Formalization</b>
  The structure is "exctracted" from normal language via a formalization process.
  <ul>Process of formalization:
  <li> Understand the meaning of the the sentence.
  <li> Indetify <b>Atomic Propositions</b>
  <li> Identify <b>Connectives</b>
    <li> Group into <b>Molecular Propositions</b> 
      </ul>

<b> Formalization </b> is the process of breaking down molecules to atoms in logic.

<b> INTERPRETATION </b>

If today rains, I won't take the bus.
If I don't get paid, I won't go to work.

Two different things, but the same logical structure.
P -> Q
-> represents if: if P then Q
P and Q are variables.

<b> AMBIGUITIES (Двусмысленность)</b>
Today it is a sunny day.
Today is sunny.
It's a sunny day today

Formalizing - giving structure. Turning phrases into symbols.
Interpretation - giving it a meaning. Turnins sybmols into phrases.

<b> Truth Tables </b>
Atomic propositions can be T or F. We derive the T or F by comparing Atomic propositions with reality.

For moleculars, they also can be T or F. We determine it by using truth tables of their molecular propositions.

Consider a proposition <b>P</b> taht can take T or F:
| Not p | P |
|---|---|
|F|T|
|T|F|

Let's consider to propositions, <b>P</b> and <b>Q</b>

Both true p=T, q=T
Both False p=F, q=F
P is true and q False p=T, q=F
Q is true and q false p=F, q=T.

Conjunction "^" (and)

|p|q|p^q|
|---|---|---|
|T|T|T|
|T|F|F|
|F|T|F|
|F|F|F|

Disjunction "v" (or)

|p|q|p v q|
|---|---|---|
|T|T|T|
|T|F|T|
|F|T|T|
|F|F|F|
