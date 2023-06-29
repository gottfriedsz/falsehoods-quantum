# Falsehoods Programmers Believe About Quantum Technology

Common misconceptions about quantum technology and computers.

1. Quantum computers will destroy the internet.

   No, even if Shor's algorithm poses a potential threat, several institutions like the
   american NIST are working on successors of the current cryptography standards (see 
   https://csrc.nist.gov/Projects/post-quantum-cryptography). And besides this, quantum 
   technology offers new methods to secure communication, like QKD (quantum key distribution)
   or other approaches (see also https://kjoo.be/application-scenarios-for-the-quantum-internet/)
   
2. All cryptography algorithms are since Shor broken.

   Actually they are not broken as long we don't have quantum computers with sufficient
   power. So far quantum computers have neither the number of qubits necessary nor the needed
   stability (see NISQ) of them. 
   
3. I need to have a PhD in Physics to work with quantum computers.

   Don't worry. You only need some interest. Quantum computing is an interdisciplinary
   field that combines concepts from physics, computer science, mathematics, and engineering. While
   a Ph.D. in Physics can certainly be advantageous and provide a strong foundation in the underlying
   principles of quantum mechanics, there are various roles within the field of quantum
   computing that don't require such an advanced degree.
   
5. Quantum computers are to only application of quantum technology.
6. Quantum computers should be cooled in space, because it is already cold out there.
7. Quantum computers are not solving for real applications.
8. Quantum computers will replace all classical computers.
9. Quantum computers can used to solve all existing problems.
10. There will always be errors that prevent quantum computers to be useful.
11. Quantum computers kills blockchains like Bitcoin or Ethereum.
12. We have already reached Quantum Supremacy.
13. Access to quantum computers is limited to rich people.

14. Similar: access to quantum computers is limited to scientists.

15. Quantum computers best use is for large data.

    Quantum computers have the potential to provide significant advantages for certain
    types of problems, including those involving large data sets. However, it's important
    to note that quantum computers are not inherently better at handling large
    data compared to classical computers.

17. Qubits are in state 0 and 1 at the same time.

18. With entangled qubits you can send information faster than speed of light.

19. The cat in Schrödinger's thought experiment really died.

    Thankfully no cat was harmed in this thought experiment of Erwin Schrödinger to
    illustrate some of the counterintuitive aspects of quantum mechanics. 😽

21. Quantum computer promises infinite speedup for any computation.
22. A qubit can be stored in a hard disk or USB stick like a normal bit.
23. Eight qubits grouped together are a qubyte. 
24. An enterprise architect will tell me, when I have to use it. 
25. Business will tell me, when I have to use it.

26. I have to learn strange and new programming languages before I can use quantum computers.

    You can, if you want, but you don't have to. You can learn new languages that are specialized
    and developed by a certain vendor (like [Q#](https://azure.microsoft.com/en-us/resources/development-kit/quantum-computing/) by Microsoft or
    [Silq](https://silq.ethz.ch/) ). Additionally, you have the option to use languages like [OpenQASM](https://github.com/openqasm/)
    for describing quantum circuits. OpenQASM is an open-source quantum assembly language that allows you to define quantum
    operations and compose them into circuits.

    However, languages like Python can be used to interact with qubits. A good list of resources can be
    found at [awesome-quantum-software](https://github.com/qosf/awesome-quantum-software) and you will find
    many familiar languages.

28. My SHA256, MD5,... is safe enough for the next decade 

    
29. I don't need quantum computers, I am in the cloud and already using kubernetes.
30. More qubits is all you need. 
31. Quantum computers need a lots of energy to cool down the qubits to near absolut zero.
32. There is nothing else then quantum circuits.
33. As a developer I have to understand the full stack, from endusers UI down to cryogenic for how cool a qubit.
34. Quantum computers are inexact and I don't can calculate Pi to last decimal.
35. I will have a quantum computer at home.
36. Quantum computing is a hoax, it does actually not exist. 
37. Quantum computer will destroy the world since you can create wormwholes with it.

    No, actually not. Actually it was just a hype by media and only a simplification of what happened. See 
    https://scottaaronson.blog/?p=6871 for detailed explaination.

Licensed under [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
