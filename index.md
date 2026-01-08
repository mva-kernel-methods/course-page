---
layout: home
---

## Course materials: **[(Slides)](/static_files/materials/slides.pdf)**  

The slides for all lectures are available in pdf format. Slides are frequently updated. 
Please let us know if you spot typos! Each lecture corresponds to a range of slides. 

Please go to **[the lectures' page](lectures/)** to find more details about each lecture.

The schedule for the course is available **[here](schedule/)**.  




## Course description

Many problems in real-world applications of machine learning can be formalized as classical statistical problems, e.g., pattern recognition, regression or dimension reduction, with the caveat that the data are often not vectors of numbers. For example, protein sequences and structures in computational biology, text and XML documents in web mining, segmented pictures in image processing, or time series in speech recognition and finance, have particular structures which contain relevant information for the statistical problem but can hardly be encoded into finite-dimensional vector representations.

Kernel methods are a class of algorithms well suited for such problems. Indeed they extend the applicability of many statistical methods initially designed for vectors to virtually any type of data, without the need for explicit vectorization of the data. The price to pay for this extension to non-vectors is the need to define a so-called positive definite kernel function between the objects, formally equivalent to an implicit vectorization of the data. The "art" of kernel design for various objects have witnessed important advances in recent years, resulting in many state-of-the-art algorithms and successful applications in many domains.

The goal of this course is to present the mathematical foundations of kernel methods, as well as the main approaches that have emerged so far in kernel design. We will start with a presentation of the theory of positive definite kernels and reproducing kernel Hilbert spaces, which will allow us to introduce several kernel methods including kernel principal component analysis and support vector machines. Then we will come back to the problem of defining the kernel. We will present the main results about Mercer kernels and semigroup kernels, as well as a few examples of kernel for strings and graphs, taken from applications in computational biology, text processing and image analysis. Finally we will touch upon topics of active research, such as large-scale kernel methods and deep kernel machines.

## Schedule and organization

- The class on kernel methods, jointly organized for IASD, MVA, and MASH M2 programs, will take place on **Wednesdays** from **1:30pm** to **4:30pm**, starting on January 07th, at 16bis rue de l'Estrapade, 75005 Paris. See the **[full schedule](schedule/)**. There will be 9 sessions in total.
- The grading of the class will be done with (i) one final exam, (ii) a data challenge, (iii) regular (short) exercises to do online. 

## Evaluation
 The final note will be a weighted average of a data challenge (40%), a final exam (40%) and regular homeworks (20%).
