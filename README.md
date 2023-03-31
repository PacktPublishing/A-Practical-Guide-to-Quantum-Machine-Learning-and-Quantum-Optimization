# A Practical Guide to Quantum Machine Learning and Quantum Optimisation 

<a href="https://www.packtpub.com/product/a-practical-guide-to-quantum-machine-learning-and-quantum-optimisation/9781804613832?utm_source=github&utm_medium=repository&utm_campaign="><img src="https://content.packt.com/B19003/cover_image_small.jpg" alt="A Practical Guide to Quantum Machine Learning and Quantum Optimisation " height="256px" align="right"></a>

This is the code repository for [A Practical Guide to Quantum Machine Learning and Quantum Optimisation ](https://www.packtpub.com/product/a-practical-guide-to-quantum-machine-learning-and-quantum-optimisation/9781804613832?utm_source=github&utm_medium=repository&utm_campaign=), published by Packt.

**Hands-on Approach to Modern Quantum Algorithms**

## What is this book about?
This book introduces the main quantum algorithms that are currently used in optimization and machine learning. The approach is hands-on, with examples that can be run on simulators and actual quantum computers. The algorithms are explained in full detail, without sacrificing rigor, but, at the same time, keeping mathematical prerequisites to a minimum.

This book covers the following exciting features:
* Review the basics of quantum computing
* Gain a solid understanding of modern quantum algorithms
* Understand how to formulate optimization problems with QUBO
* Solve optimization problems with quantum annealing, QAOA, GAS, and VQE
* Find out how to create quantum machine learning models
* Explore how quantum support vector machines and quantum neural networks work using Qiskit and PennyLane
* Discover how to implement hybrid architectures using Qiskit and PennyLane and its PyTorch interface

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1804613835) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
import dimod
J = {(0,1):1, (0,2):1}
h = {}
problem = dimod.BinaryQuadraticModel(h, J, 0.0, dimod.SPIN)
print("The problem we are going to solve is:")
print(problem)
```

**Following is what you need for this book:**
This book is for professionals from a wide variety of backgrounds, including computer scientists and programmers, engineers, physicists, chemists, and mathematicians. Basic knowledge of linear algebra and some programming skills (for instance, in Python) are assumed, although all mathematical prerequisites will be covered in the appendices.

With the following software and hardware list you can run all code files present in the book (Chapter 1-18).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 2-12 | Anaconda | Windows, Mac OS X, and Linux (Any) |
| 2-12 | Google Colab | Windows, Mac OS X, and Linux (Any) |


We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://packt.link/FtU9t).

### Related products
* Quantum Computing Experimentation with Amazon Braket  [[Packt]](https://www.packtpub.com/product/quantum-computing-experimentation-with-amazon-braket/9781800565265?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/1800565267)

* Essential Mathematics for Quantum Computing  [[Packt]](https://www.packtpub.com/product/essential-mathematics-for-quantum-computing/9781801073141#_ga=2.165177852.2122294857.1679392398-1305371096.1644413090?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/1801073147)



## Get to Know the Authors
**Elías F. Combarro**
 holds degrees from the University of Oviedo (Spain) in both Mathematics (1997, award for second highest grades in the country) and Computer Science (2002, award for highest grades in the country). After some research stays at the Novosibirsk State University (Russia), he obtained a Ph.D. in Mathematics (Oviedo, 2001) with a dissertation on the properties of some computable predicates under the supervision of Prof. Andrey Morozov and Prof. Consuelo Martínez.
Since 2009, Elías F. Combarro has been an associate professor at the Computer Science Department of the University of Oviedo. He has published more than 50 research papers in international journals on topics such as Computability Theory, Machine Learning, Fuzzy Measures and Computational Algebra. His current research focuses on the application Quantum Computing to algebraic, optimisation and machine learning problems.
From July 2020 to January 2021, he was a Cooperation Associate at CERN openlab. Currently, he is the Spain representative in the Advisory Board of CERN Quantum Technology Initiative, a member of the Advisory Board of SheQuantum and one of the founders of the QSpain, a quantum computing think tank based in Spain.

**Samuel González-Castillo**
 holds degrees from the University of Oviedo (Spain) in both Mathematics and Physics (2021). He is currently a mathematics research student at the National University of Ireland, Maynooth, where he works as a graduate teaching assistant.He completed his physics bachelor thesis under the supervision of Prof. Elías F. Combarro and Prof. Ignacio F. Rúa (University of Oviedo), and Dr. Sofia Vallecorsa (CERN). In it, he worked alongside other researchers from ETH Zürich on the application of Quantum Machine Learning to classification problems in High Energy Physis. In 2021, he was a summer student at CERN developing a benchmarking framework for quantum simulators. He has contributed to several conferences on quantum computing.



### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781804613832">https://packt.link/free-ebook/9781804613832 </a> </p>