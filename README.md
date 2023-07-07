# Falsehoods Programmers Believe About Quantum Technology

Common misconceptions about quantum technology and computers.

1. Quantum computers will destroy the internet.

   No, even if Shor's algorithm poses a potential threat, several institutions like the american NIST are working on successors of the current cryptography standards (see https://csrc.nist.gov/Projects/post-quantum-cryptography). And besides this, quantum technology offers new methods to secure communication, like QKD (quantum key distribution) or other approaches (see also https://kjoo.be/application-scenarios-for-the-quantum-internet/)
   
2. All cryptography algorithms are since Shor broken.

   Actually they are not broken as long we don't have quantum computers with sufficient power. So far quantum computers have neither the number of qubits necessary nor the neededstability (see NISQ) of them. 
   
3. I need to have a PhD in Physics to work with quantum computers.

   Don't worry. You only need some interest. Quantum computing is an interdisciplinary field that combines concepts from physics, computer science, mathematics, and engineering. While a Ph.D. in Physics can certainly be advantageous and provide a strong foundation in the underlying principles of quantum mechanics, there are various roles within the field of quantum computing that don't require such an advanced degree.
   
4. Quantum computers are to only application of quantum technology.

   No, quantum computers are definitely not the only application of quantum technology. While quantum computers are a prominent and exciting application, there are several other areas where quantum technology finds utility. Here are a few examples:
      * Quantum Communication: Quantum technology enables secure communication by leveraging the principles of quantum mechanics to ensure the confidentiality and integrity of transmitted information.
      * Quantum Sensing: Quantum sensors can provide enhanced precision and sensitivity in various fields, such as navigation, imaging, and metrology.
      * Quantum Metrology: Quantum metrology exploits quantum properties to achieve higher precision in measurements, offering advancements in fields like timekeeping, electrical standards, and fundamental constants.
      * Quantum Simulation: Quantum simulators use quantum systems to simulate and study complex phenomena in fields such as chemistry, material science, and condensed matter physics. They can provide insights into the behavior of quantum systems that are challenging to study using classical computers.
      * Quantum Cryptography: Quantum technology enables the development of secure cryptographic protocols that leverage the principles of quantum mechanics, such as quantum key distribution. These protocols offer information security based on fundamental quantum properties, providing protection against certain types of attacks.

   These are just a few examples of the diverse applications of quantum technology beyond quantum computers. As the field continues to advance, we can expect further discoveries and applications that harness the unique properties of quantum mechanics.

5. Quantum computers should be cooled in space, because it is already cold out there.
6. Quantum computers are not solving for real applications.
7. Quantum computers will replace all classical computers.

   Quantum computers have the potential to revolutionize certain areas of computing by solving certain problems more efficiently than classical computers. However, it is unlikely that quantum computers will completely replace classical computers soon. It is more likely to see quantum computing to be complementary to classical computers. Quantum computers alone won't be very useful for most problems. They will work alongside classical CPUs, GPUs, TPUs and other and together the advantage of quantum computing can be leveraged. Quantum computers may be used for specialized applications that benefit from their unique capabilities, while classical computers continue to handle general-purpose computing tasks.
   
8. Quantum computers can used to solve all existing problems.
9. There will always be errors that prevent quantum computers to be useful.
10. Quantum computers kills blockchains like Bitcoin or Ethereum.
11. We have already reached Quantum Supremacy.
12. Access to quantum computers is limited to rich people.

13. Similar: access to quantum computers is limited to scientists.

14. Quantum computers best use is for large data.

    Quantum computers have the potential to provide significant advantages for certain types of problems, including those involving large data sets. However, it's important to note that quantum computers are not inherently better at handling large data compared to classical computers.

15. Qubits are in state 0 and 1 at the same time.

16. With entangled qubits you can send information faster than speed of light.

17. The cat in Schrödinger's thought experiment really died.

    Thankfully no cat was harmed in this thought experiment of Erwin Schrödinger to illustrate some of the counterintuitive aspects of quantum mechanics. 😽

18. Quantum computer promises infinite speedup for any computation.
19. A qubit can be stored in a hard disk or USB stick like a normal bit.
20. Eight qubits grouped together are a qubyte.

    No, eight qubits grouped together is not called a "qubyte". “Qubyte” is not a standard term in quantum computing. For example, a system of eight qubits is often referred to as an eight-qubit quantum register or an eight-qubit quantum state. In classical computing, the fundamental unit is a bit and eight bits grouped together are called a “byte” and 1024 bytes are called a “kilobyte”. But there is no analogous to this in quantum computing.
   
21. An enterprise architect will tell me, when I have to use it. 
22. Business will tell me, when I have to use it.

23. I have to learn strange and new programming languages before I can use quantum computers.

    You can, if you want, but you don't have to. You can learn new languages that are specialized and developed by a certain vendor (like [Q#](https://azure.microsoft.com/en-us/resources/development-kit/quantum-computing/) by Microsoft or [Silq](https://silq.ethz.ch/) ). Additionally, you have the option to use languages like [OpenQASM](https://github.com/openqasm/) for describing quantum circuits. OpenQASM is an open-source quantum assembly language that allows you to define quantum operations and compose them into circuits.

    However, languages like Python can be used to interact with qubits. A good list of resources can befound at [awesome-quantum-software](https://github.com/qosf/awesome-quantum-software) and you will find many familiar languages.

24. My SHA256, MD5,... is safe enough for the next decade 

    
25. I don't need quantum computers, I am in the cloud and already using kubernetes.
26. More qubits is all you need. 
27. Quantum computers need a lots of energy to cool down the qubits to near absolut zero.
28. There is nothing else then quantum circuits.
29. As a developer I have to understand the full stack, from endusers UI down to cryogenic for how cool a qubit.
30. Quantum computers are inexact and I don't can calculate Pi to last decimal.
31. I will have a quantum computer at home.
32. Quantum computing is a hoax, it does actually not exist. 
33. Quantum computer will destroy the world since you can create wormwholes with it.

    No, actually not. Actually it was just a hype by media and only a simplification of what happened. See https://scottaaronson.blog/?p=6871 for detailed explaination.

34. I have to use Python to program quantum computers.
    
      No, see quantum falsehood #23.



Licensed under [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
