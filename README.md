## 18.336J/6.335J: Fast Methods for Partial Differential and Integral Equations 

A unified introduction to the theory and practice of modern, near linear-time, numerical methods for large-scale partial differential and integral equations. 
Topics include: preconditioned iterative methods; generalized Fast Fourier Transform and other butterfly-based methods; multiresolution approaches including multigrid algorithms, hierarchical low-rank matrix decompositions, and low and high frequency Fast Multipole Methods. 
Example applications include: aircraft design, cardiovascular system modeling, electronic structure computation, and tomographic imaging.

## Syllabus

**Lectures**: Tuesday/Thursday 9:30-11:00 am (2-136).  

**Office Hours**: TBD.

**Prerequisites**: This course covers advanced techniques for discretizing and solving PDEs. 
Some familiarity with ordinary differential equations, partial differential equaitons, Fourier transforms, linear algebra, and basic numerical methods for PDEs is assumed. 
It is strongly recommended that you have taken a previous course on basic numerical methods, such as [2.096/6.336/16.910](http://student.mit.edu/catalog/m6b.html#6.336), [2.097/6.339/16.920](http://student.mit.edu/catalog/m16b.html#16.920), [18.085](http://student.mit.edu/catalog/m18a.html#18.085), or [6.337/18.335](http://student.mit.edu/catalog/m18a.html#18.335).
Problem sets will involve extensive coding and are required to be completed in **Python** or **Julia** notebooks.

**Textbooks & Other Reading**: Recommended reading will be posted as the class progresses. There is no textbook for the course, but the following books may be useful:
* Strauss "Partial Differential Equations: An Introduction". An advanced undergrad intrdouction to PDEs.
* Boyd "Chebyshev and Fourier Spectral Methods". Very readable and [available online](http://depts.washington.edu/ph506/Boyd.pdf).
* LeVeque "Finite difference methods for ordinary and partial differential equations".
* LeVeque "Finite volume methods for hyperbolic problems".

**Grading**: 50% problem sets (approximately biweekly), 50% final project report and presentation.

**Collaboration Policy**: Make a strong effort to solve problems on your own before discussing with any classmates.  You must write up your own solutions.  Sharing code is not allowed.

## Lecture Material and Summaries

### Lecture 1: Introduction to Fast Methods, PDEs, IEs

**Summary**
* Course policies
* Steven Johnson's Julia tutorial: 09/06/2019 5-7pm (32-141)
* Why fast algorithms? History of algorithms for the Fourier transform.
* Why PDEs? Models for physical systems. Classes of PDEs. Elliptic regularity theorem.
* Why integral equations? Better conditioning from using exact solution formulae.
* [Top ten algorithms of the 20th century](https://archive.siam.org/pdf/news/637.pdf)
