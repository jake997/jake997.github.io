---
layout: default
title: Home
---

# Yacoub Hendi

Ph.D. Student in Mathematics  
Uppsala University, Sweden  

📧 [Email: yacoub.hendi@math.uu.se](mailto:yacoub.hendi@math.uu.se)  
📄 [Download CV](/assets/pdfs/cv.pdf)

---

## Research Interests

My research explores the intersection of machine learning and geometry. On one hand, I apply machine learning techniques to compute numerical approximations on manifolds such as Ricci-flat metrics on Calabi–Yau manifolds. On the other hand, I study the geometric properties of neural networks to better understand their efficiency.

---

## Education

**Ph.D. in Mathematics (2023– )**  
Uppsala University  
Advisor: Prof. Magdalena Larfors  

**Master of Mathematics (2021–2023)**  
Thesis: Computation of the superpotential for monotone Lagrangian submanifolds in products of complex projective lines  
Advisor: Assoc. Prof. Luis Diogo  

**Bachelor of Mathematics (2018–2021)**  
Thesis: On The Prime Number Theorem  
Advisor: Prof. Andreas Strömbergsson  

**Bachelor of Computer Science (2018–2021)**  
Thesis: Parameterized Verification under The Total Store Order Memory Model is EXPTIME-Complete  
Advisor: Prof. Parosh Abdulla  

---

## Activities

{% assign sorted_activities = site.data.activities | sort: "year" | reverse %}
{% for activity in sorted_activities %}
{% include activity.html activity=activity %}
{% endfor %}

---

## Talks

{% assign sorted_talks = site.data.talks | sort: "year" | reverse %}
{% for talk in sorted_talks %}
{% include talk.html talk=talk %}
{% endfor %}

---

## Publications & Papers

{% for pub in site.data.publications %}
{% include publication.html %}
{% endfor %}