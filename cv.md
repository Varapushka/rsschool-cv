## [rsschool-cv](https://varapushka.github.io/rsschool-cv/cv)

# **Sergei Voropaev**

---

## **Contact information:**

**Discord:** Sergei Voropaev#1950

**E-mail:** nifelim96@gmail.com

**Telegram:** @varapushka

---

## **Brifelly About Myself**

I work at a chemical plant and decided to develop a new profession for myself.

I’m interested in Web Development and I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

---

## **Skills and Proficiency**

- HTML5
- Git, GitHub
- Vs Code
- JavaScript Basics

---

## **Code example:**

**KATA from CODEWARS:** Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p. We want to find a positive integer k, if it exists, such that the sum of the digits of n taken to the successive powers of p is equal to k \* n.

```
function digPow(n, p) {
  let arr = [...('' + n)];
  let arrInt = arr.map(Number);
  let sumArr = 0;
for (i = 0; i < arrInt.length; i++, p++) {
  sumArr += Math.pow(arrInt[i], p);
}
 let k = sumArr/n;
  return (k >= 1 && Number.isInteger(k)) ? k : -1;
}
```

---

## **Courses:**

- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
- JavaScript [https://learn.javascript.ru/](https://learn.javascript.ru/)

---

## **Languagies:**

- Russian - Native
- English - A2
