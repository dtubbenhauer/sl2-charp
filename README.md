# Code, additonal material and Erratum for *Fractal behavior of tensor powers of the two dimensional space in prime characteristic*

I collected a bit of Mathematica code relevant for the paper *Fractal behavior of tensor powers of the two dimensional space in prime characteristic*
<a href="TBA">TBA</a> on this page.

The code is in a **.n** file that can be downloaded from this site and you can run it with Mathematica. 

After the Mathematica code we explain a Google Colab file **. ipynb** where we explain (or rather sektch) how machine learning and deep learning can be used to tackle the main problem recalled in the background below.

An Erratum for the paper *Fractal behavior of tensor powers of the two dimensional space in prime characteristic* can be found at the bottom of the page.

# Contact

If you find any errors in the paper *Fractal behavior of tensor powers of the two dimensional space in prime characteristic* **please email me**:

[dtubbenhauer@gmail.com](mailto:dtubbenhauer@gmail.com?subject=[GitHub]%web-reps)

Same goes for any errors related to this page.

# Background

Let $\mathbf{k}$ be a field and let $\Gamma$ be a group, possibly an algebraic group or affine group scheme over $\mathbf{k}$. For any finite dimensional $\Gamma$-representation $W$ 
over $\mathbf{k}$ let $\nu(W)\in\mathbb{Z_{\geq\text{0}}}$ be an integer $\nu$ such that
$W\cong\oplus_{i=1}^{\nu}W_{i}$,
where $W_{i}$ are indecomposable $\Gamma$-representations. This number is well-defined
by the Krull&ndash;Schmidt theorem. Now let $V$ be a finite dimensional $\Gamma$-representation and define
the integer sequence
$$b_{n}(V):=\nu(V^{\otimes n}),n\in\mathbb{Z_{\geq\text{0}}}.$$
To study the growth of $b_{n}=b_{n}(V)$ is the main task of this paper.

We write $\sim$ for `asymptotically equal'. One could hope that
$$b_{n}\sim h(n)\cdot n^{\alpha}\cdot\lambda^{n},$$
for a bounded function $h(n)$, the subexponential factor $n^{\alpha}$ and the dominating growth rate $\lambda^{n}$.

We do not know in what generality this expression holds, 
but expressions of this form are very common in the theory of asymptotics of generating functions. What we know is:

- In general, $\lambda=\dim V$ but we do not know whether the asymtotic formula holds.
- When $\Gamma$ is a finite group, then $b_{n}\sim h(n)\cdot n^{0}\cdot(\dim V)^{n}$. This is independent of the characteristic of the underlying field.
- When $\Gamma=SL_{2}(\mathbb{C})$ and $V$ is the vector representation with $\dim V=2$, then $b_{n}\sim\sqrt{2/\pi}\cdot n^{-1/2}\cdot 2^{n}$.
- More generally, when $\Gamma$ is a reductive group in characterictic zero and $V$ is any finite dimensional $\Gamma$-representation, then we have a formula of the form $b_{n}\sim h(n)\cdot n^{\alpha}\cdot(\dim V)^{n}$ with explicitly computable $h(n)$ and $\alpha$. Moreover, $\alpha$ is in $1/2\mathbb{Z}$.

Let $V$ be a two dimensional vector space over an infinite field. Let $\Gamma$ be the algebraic group $SL(V)\simeq SL_{2}(\mathbf{k})$. Let 
$b_{n}=b_{n}(V)$ be the sequence as above. As a matter of fact, the sequence $b_{n}$ depends only on the characteristic of $\mathbf{k}$ (which is only implicit in our notation), so we only need to study it for one infinite field for each $p\geq 0$. The case $p=0$ is easy, see above, so let $p>0$.

Let us define the following transcendental number:
$$\alpha_{p}:=-\frac{1}{2}\log_{p}\frac{2p^{2}}{p+1}=
-1+\frac{\ln\tfrac{p+1}{2}}{\ln p}.$$

**Theorem**

>For any $p>0$ there exist positive constants $C_{1}=C_{1}(p)$ and $C_{2}=C_{2}(p)$
>such that we have
$$C_{1}\cdot n^{\alpha_{p}}\cdot 2^{n}\leq b_{n}\leq C_{2}\cdot n^{\alpha_{p}}\cdot 2^{n},\qquad n\geq 1.$$

The aim of the code on this page is to illustrate this theorem in examples.

# Mathematica code

Growth rates of the vector representation of SL2 in positive characteristic

<https://www.wolframcloud.com/obj/02e25415-5c98-4dd9-84cf-8925156aeda9?_embed=iframe>

<https://www.wolframcloud.com/obj/de16c88e-6b99-42e3-8bb3-9fb6fb8d7d90?_embed=iframe>

To do

# Google Colab and machine learning

To do


# Erratum

Empty so far.
