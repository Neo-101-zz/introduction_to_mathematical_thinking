## ASSIGMENT 4(for Lecture 4)

1.<br/>

φ	ψ	φ ⇒ ψ	ψ ⇒ φ	φ ⇔ ψ<br/>

T	T	T		T		T<br/>

T	F	F		T		F<br/>

F	T	T		F		F<br/>

F	F	T		T		T<br/>

2.<br/>

φ	ψ	¬φ	φ ⇒ ψ	¬φ ∨ ψ<br/>

T	T	F	T		T<br/>

T	F	F	F		F<br/>

F	T	T	T		T<br/>

F	F	T	T		T<br/>

3.<br/>

φ	ψ	¬ψ	!(φ ⇒ ψ)	φ ∧ ¬ψ<br/>

T	T	F	F		F<br/>

T	F	T	T		T<br/>

F	T	F	F		F<br/>

F	F	T	F		F<br/>

4.<br/>

(a)<br/>

φ	ψ	φ ⇒ ψ	φ ∧ (φ ⇒ ψ)	[φ ∧ (φ ⇒ ψ)] ⇒ ψ<br/>

T	T	T		T			T<br/>

T	F	F		F			T<br/>

F	T	T		F			T<br/>

F	F	T		F			T<br/>

(b)<br/>

The logic statement in (a) is about _modus ponens_. <br/>

And it only depends on the truth of φ and ψ.<br/>

In all possible combinations of the truth of φ and ψ, "[φ ∧ (φ ⇒ ψ)] ⇒ ψ" is true.<br/>

So it proves that _modus ponens_ is a valid rule of inference.<br/>

5.<br/>

(1) φ ∨ ψ means at least one of φ and ψ is true.<br/>

(2) Thus ¬(φ ∨ ψ) means it is not the case that at least one of φ and ψ is true.<br/>

(3) If not the case that at least one of φ and ψ is true, then they are both false.<br/>

(4) This is clearly the same as saying that both ¬φ and ¬ψ are true. <br/>

(5) By the meaning of _and_, this can be expressed as (¬φ) ∧ (¬ψ).<br/>

6.<br/>

(a) 34,159 is not a prime number.<br/>

(b) Roses are not red or violets are not blue.<br/>

(c) If there are hamburgers, I will not have a hot dog.<br/>

(d) Fred will not go or he will not play.<br/>

(e) The number x is not negative and not greater than 10.<br/>

(f) We will lose both the first game and the second.<br/>

7.<br/>

​						*										*<br/>

φ	ψ	φ ⇒ ψ	ψ ⇒ φ	φ ⇔ ψ	¬φ	¬ψ	¬φ ⇒ ¬ψ		¬φ ⇒ ¬ψ		¬φ ⇔¬ ψ<br/>

T	T	T		T		T		F	F	T			T			T<br/>

T	F	F		T		F		F	T	T			F			F<br/>

F	T	T		F		F		T	F	F			T			F<br/>

F	F	T		T		T		T	T	T			T			T<br/>

Since the two columns marked * are identical, we know that the two expressions are equivalent.<br/>

8.<br/>

(a)<br/>

φ	ψ	φ ⇒ ψ	ψ ⇒ φ	φ ⇔ ψ<br/>

T	T	T		T		T<br/>

T	F	F		T		F<br/>

F	T	T		F		F<br/>

F	F	T		T		T<br/>

(b)<br/>

φ	ψ	θ	ψ ∨ θ	φ ⇒ (ψ ∨ θ)<br/>

T	T	T	T		T<br/>

T	T	F	T		T<br/>

T	F	T	T		T<br/>

T	F	F	F		F<br/>

F	T	T	T		T<br/>

F	T	F	T		T<br/>

F	F	T	T		T<br/>

F	F	F	F		T<br/>

9.<br/>

​					*							*<br/>

φ	ψ	θ	ψ ∧ θ	φ ⇒ (ψ ∧ θ)	φ ⇒ ψ	φ ⇒ θ	 (φ ⇒ ψ) ∧ (φ ⇒ θ)<br/>

T	T	T	T		T			T		T		T<br/>

T	T	F	F		F			T		F		F<br/>

T	F	T	F		F			F		T		F<br/>

T	F	F	F		F			F		F		F<br/>

F	T	T	T		T			T		T		T<br/>

F	T	F	F		T			T		T		T<br/>

F	F	T	F		T			T		T		T<br/>

F	F	F	F		T			T		T		T<br/>

Since the two columns marked * are identical, we know that the two expressions are equivalent.<br/>

10.<br/>

[φ ⇒ (ψ ∧ θ)] ⇔ [¬φ ∨ (ψ ∧ θ)] ⇔ [(¬φ ∨ ψ) ∧ (¬φ ∨ θ)] ⇔  [(φ ⇒ ψ) ∧ (φ ⇒ θ)]<br/>

11.<br/>

​		*				*<br/>

φ	ψ	φ ⇒ ψ	¬ψ	¬φ	¬ψ ⇒ ¬φ	<br/>

T	T	T		F	F	T<br/>

T	F	F		T	F	F<br/>

F	T	T		F	T	T<br/>

F	F	T		T	T	T<br/>

Since the two columns marked * are identical, we know that the two expressions are equivalent.<br/>

12.<br/>

(a) If two rectangles have different area, they are not congruent.<br/>

(b) If a triangle with sides a, b, c (c largest) does not have the relation a^2 + b^2 = c^2, then it is not right-angled.<br/>

(c) If n is not prime, then 2^n - 1 is not prime.<br/>

(d) If the Dollar rises, the Yuan will fall.<br/>

13.<br/>

​		*		*<br/>

φ	ψ	φ ⇒ ψ	ψ ⇒ φ<br/>

T	T	T		T<br/>

T	F	F		T<br/>

F	T	T		F<br/>

F	F	T		T<br/>

Since the two columns marked * are not identical, we know that the two expressions are not equivalent.<br/>

14.<br/>

(a) If two rectangles have the same area, they are congruent.<br/>

(b) If a triangle with sides a, b, c (c largest) has the relation a^2 + b^2 = c^2, then it is right-angled.<br/>

(c) If n is prime, then 2^n - 1 is prime.<br/>

(d) If the Dollar falls, the Yuan will rise.<br/>

#### OPTIONAL PROBLEMS

1.<br/>

(¬φ) ∨ ψ<br/>

2.<br/>

φ	ψ	φ .∨ ψ<br/>

T	T	F<br/>

T	F	T<br/>

F	T	T<br/>

F	F	F<br/>

3.<br/>

(φ ∨ ψ) - (φ ∧ ψ)<br/>

4.<br/>

(a) 0 is not equal to 0<br/>

(b) 0 is equal to 0<br/>

(c) 0 is equal to 0<br/>

(d) 0 is not equal to 0<br/>

5.<br/>

M	N	M × N	M + N<br/>

1	1	1		0<br/>

1	0	0		1<br/>

0	1	0		1<br/>

0	0	0		0<br/>

6.<br/>

M	N	M × N	M + N<br/>

T	T	T		F<br/>

T	F	F		T<br/>

F	T	F		T<br/>

F	F	F		F<br/>

(a) ∧<br/>

(b) .∨<br/>

(c) I am not sure. Because minus has not been defined. If it is defined that - 1 = 0 and - 0 = 1, then the answer is "Yes".<br/>

7.<br/>

M	N	M × N	M + N<br/>

F	F	F		T<br/>

F	T	T		F<br/>

T	F	T		F<br/>

T	T	T		T<br/>

 (M × N)  ⇔ (M ∨ N)<br/>

 (M + N)  ⇔ ¬(M .∨ N)<br/>

8.<br/>

Two. The "E" card and the "4" card.<br/>

φ: the letter on the card is vowel.<br/>

ψ: the number on the other side is odd.<br/>

φ	ψ	φ ⇒ ψ<br/>

T	T	T<br/>

T	F	F<br/>

F	T	T<br/>

F	F	T<br/>

Whatever the consequent, the conditional is true if the antecedent is false So we need not to check "B" card.<br/>

Whatever the antecedent , the conditional is true if the consequent is true. So we need not to check "7" card.<br/>

So we have "E" card and "4" card left. Only if the number of "E" card is odd and the letter of "4" card is not vowel, the rule is true. Otherwise, it is false.<br/>

9.<br/>

T: odd<br/>

F: even<br/>

m	n	mn<br/>

T	T	T<br/>

T	F	F<br/>

F	T	F<br/>

F	F	F<br/>

10.<br/>

No, it is not true.

T: even<br/>

F: odd<br/>

m	n	mn<br/>

T	T	T<br/>

T	F	T<br/>

F	T	T<br/>

F	F	F<br/>

11.<br/>

It is the same as question 10. Check the person's ID h who has a beer and the person's drink who is under the drinking age.<br/>

12.<br/>

The logical structure of two questions are the same. My answer to them is according to the same logical rule. So they are the same easy, or the same difficult. Specific logical rule is in the answer to Optional Problem 8 above.



