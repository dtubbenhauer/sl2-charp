# Code, additonal material and Erratum for *Fractal behavior of tensor powers of the two dimensional space in prime characteristic*

I collected a bit of Mathematica code relevant for the paper *Fractal behavior of tensor powers of the two dimensional space in prime characteristic*
<a href="https://arxiv.org/abs/2307.03044">https://arxiv.org/abs/2307.03044</a> on this page.

The code is in a **.n** file that can be downloaded from this site and you can run it with Mathematica.

You can also download a **.pdf** file where additional material for the paper can be found, e.g. more details for some of the calculations.

An Erratum for the paper *Asymptotics in finite monoidal categories* can be found at the bottom of the page.

# Contact

If you find any errors in the paper *Fractal behavior of tensor powers of the two dimensional space in prime characteristic* **please email me**:

[dtubbenhauer@gmail.com](mailto:dtubbenhauer@gmail.com?subject=[GitHub]%web-reps)

Same goes for any errors related to this page.

# Background

Let $\mathbf{k}$ be a field and let $\Gamma$ be a group, possibly an algebraic group or affine group scheme over $\mathbf{k}$. For any finite dimensional $\Gamma$-representation $W$ 
over $\mathbf{k}$ let $\nu(W)\in\mathbb{Z}_{\geq 0}$ be an integer $\nu$ such that
$W\cong\oplus_{i=1}^{\nu}W_{i}$,
where $W_{i}$ are indecomposable $\Gamma$-representations. This number is well-defined
by the Krull--Schmidt theorem. Now let $V$ be a finite dimensional $\Gamma$-representation and define
the integer sequence
$$
b_{n}(V):=\nu(V^{\otimes n}),\; n\in\mathbb{Z}_{\geq 0}.
$$
To study the growth of $b_{n}$ is the main task of this paper.

Let $V$ be a two dimensional vector space over an infinite field. Let $\Gamma$ be the algebraic group $SL(V)\simeq SL_{2}(\mathbf{k})$. Let 
$b_{n}=b_{n}(V)$ be the sequence as above. As a matter of fact, the sequence $b_{n}$ depends only on the characteristic of $\mathbf{k}$ (which is only implicit in our notation), so we only need to study it for one infinite field for each $p\geq 0$. The case $p=0$ is easy, sp let $p>0$.

**Theorem**

>For any $p>0$ there exist positive constants $C_{1}=C_{1}(p)$ and $C_{2}=C_{2}(p)$
>such that we have
$$C_{1}\cdot n^{\alpha_{p}}\cdot 2^{n}\leq b_{n}\leq C_{2}\cdot n^{\alpha_{p}}\cdot 2^{n},\qquad n\geq 1.$$

The aim of the code on this page is to illustrate this theorem in examples.

# Online illustrations

Growth rates of the vector representation of SL2 in positive characteristic

<https://www.wolframcloud.com/obj/02e25415-5c98-4dd9-84cf-8925156aeda9?_embed=iframe>

<https://www.wolframcloud.com/obj/de16c88e-6b99-42e3-8bb3-9fb6fb8d7d90?_embed=iframe>

To do

# Extra material

To do


# Erratum

Empty so far.
