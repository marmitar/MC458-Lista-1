# Analysis of Algorithms I (MC458) - Test 1

- [Questions](./Enunciado.pdf)
- [Answers](./Resposta.pdf)
- [Turn in](./Entrega.pdf)

## Function Growth and Recurrence

*In the questions below, assume every function has domain ℕ, is positive, and is monotonically increasing.*

---

### Question 1

- **(a)** Chorãozinho claims that, for any integer $k \ge 1$, if $g(n) \in o\!\bigl(n^{k}\bigr)$ then necessarily $g(n) \in O\!\bigl(n^{\,k-\varepsilon}\bigr)$ for some $\varepsilon>0$. Prove that Chorãozinho is **wrong**.

- **(b)** Xitoró claims that, for any integer $k \ge 1$, if $g(n) \in O\!\bigl(n^{\,k-\varepsilon}\bigr)$ for some $\varepsilon>0$, then $g(n) \in o\!\bigl(n^{k}\bigr)$. Prove that Xitoró is **correct**.

---

### Question 2

Find a closed-form expression for the recurrence

$$
    T(1)=1,\quad\text{and for } n\ge 2,\; T(n)=T(n-1)+2n-1,
$$

and prove your formula using the substitution method.

---

### Question 3

A certain problem has two algorithms, **A** and **B**, whose running times on the RAM model are

$$
    T_A(n)=8\,T_A\!\bigl(n/2\bigr)+n^{2}
    \quad\text{and}\quad
    T_B(n)=\alpha\,T_B\!\bigl(n/3\bigr)+n^{2}.
$$

Determine the largest integer value of $\alpha$ such that $T_B(n)=o\!\bigl(T_A(n)\bigr)$-that is, algorithm B is asymptotically faster than A. Give a careful justification for your answer.
