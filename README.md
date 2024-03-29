# Falsehoods Programmers Believe About Quantum Technology

Common misconceptions about quantum technology and computers.

FQ01. Quantum computers will destroy the internet.

   No, even if Shor's algorithm poses a potential threat, several institutions like the american NIST are working on successors of the current cryptography standards (see https://csrc.nist.gov/Projects/post-quantum-cryptography). And besides this, quantum technology offers new methods to secure communication, like QKD (quantum key distribution) or other approaches (see also https://kjoo.be/application-scenarios-for-the-quantum-internet/)
   
FQ02. All cryptography algorithms are since Shor broken.

   Actually they are not broken as long we don't have quantum computers with sufficient power. So far quantum computers have neither the number of qubits necessary nor the neededstability (see NISQ) of them. 
   
FQ03. I need to have a PhD in Physics to work with quantum computers.

   Don't worry. You only need some interest. Quantum computing is an interdisciplinary field that combines concepts from physics, computer science, mathematics, and engineering. While a Ph.D. in Physics can certainly be advantageous and provide a strong foundation in the underlying principles of quantum mechanics, there are various roles within the field of quantum computing that don't require such an advanced degree.
   
FQ04. Quantum computers are the only application of quantum technology.

   No, quantum computers are definitely not the only application of quantum technology. While quantum computers are a prominent and exciting application, there are several other areas where quantum technology finds utility. Here are a few examples:
      * Quantum Communication: Quantum technology enables secure communication by leveraging the principles of quantum mechanics to ensure the confidentiality and integrity of transmitted information.
      * Quantum Sensing: Quantum sensors can provide enhanced precision and sensitivity in various fields, such as navigation, imaging, and metrology.
      * Quantum Metrology: Quantum metrology exploits quantum properties to achieve higher precision in measurements, offering advancements in fields like timekeeping, electrical standards, and fundamental constants.
      * Quantum Simulation: Quantum simulators use quantum systems to simulate and study complex phenomena in fields such as chemistry, material science, and condensed matter physics. They can provide insights into the behavior of quantum systems that are challenging to study using classical computers.
      * Quantum Cryptography: Quantum technology enables the development of secure cryptographic protocols that leverage the principles of quantum mechanics, such as quantum key distribution. These protocols offer information security based on fundamental quantum properties, providing protection against certain types of attacks.

   These are just a few examples of the diverse applications of quantum technology beyond quantum computers. As the field continues to advance, we can expect further discoveries and applications that harness the unique properties of quantum mechanics.

FQ05. Quantum computers should be cooled in space, because it is already cold out there.

FQ06. Quantum computers are not solving for real applications.

FQ07. Quantum computers will replace all classical computers.

   Quantum computers have the potential to revolutionize certain areas of computing by solving certain problems more efficiently than classical computers. However, it is unlikely that quantum computers will completely replace classical computers soon. It is more likely to see quantum computing to be complementary to classical computers. Quantum computers alone won't be very useful for most problems. They will work alongside classical CPUs, GPUs, TPUs and other and together the advantage of quantum computing can be leveraged. Quantum computers may be used for specialized applications that benefit from their unique capabilities, while classical computers continue to handle general-purpose computing tasks.
   
FQ08. Quantum computers can used to solve all existing problems.

FQ09. There will always be errors that prevent quantum computers to be useful.

FQ10. Quantum computers kills blockchains like Bitcoin or Ethereum.

FQ11. We have already reached Quantum Supremacy.

FQ12. Access to quantum computers is limited to rich people.

FQ13. Similar: access to quantum computers is limited to scientists.

FQ14. Quantum computers best used is for large data.

   Quantum computers have the potential to provide significant advantages for certain types of problems, including those involving large data sets. However, it's important to note that quantum computers are not inherently better at handling large data compared to classical computers.

FQ15. Qubits are in state 0 and 1 at the same time.

   Yes, in quantum computing, qubits can exist in a superposition of states, which means they can be in a combination of both 0 and 1 simultaneously. This is one of the fundamental properties of quantum mechanics that distinguishes it from classical computing. A classical bit can represent either a 0 or a 1, but not both at the same time. However, a qubit can represent a complex combination of 0 and 1. This superposition allows quantum computers to perform certain calculations more efficiently than classical computers.

FQ16. With entangled qubits you can send information faster than the speed of light.

Entanglement is a quantum phenomenon where the properties of two particles become correlated in such a way that the state of one particle instantaneously affects the state of another, regardless of the distance between them. However, this doesn't allow for faster-than-light communication.

Here is why:
1. Measurement outcomes of the entangled particles are random and you cannot control which state you get.
2. The results of the measurements are correlated, but there is no way to send a specific message. The correlation comes after the comparison, which needs a classical communication channel.
3. No-Faster-Than-Light causality: even though the effect is instantaneous, no actual information is transmitted and causality is preserved.

It's worth noting that quantum entanglement has potential applications in the field of quantum communication (like quantum key distribution) and quantum computing, but it doesn't provide a way around the speed-of-light barrier for communication.

FQ18. The cat in Schrödinger's thought experiment really died.

   Thankfully no cat was harmed in this thought experiment of Erwin Schrödinger to illustrate some of the counterintuitive aspects of quantum mechanics. 😽

FQ19. Quantum computers promise infinite speedup for any computation.

   While quantum computers have the potential to provide significant speedup for certain types of computations compared to classical computers, they do not offer infinite speedup for all computations. They excel in specific areas, such as simulating quantum systems, optimization problems, and certain types of cryptography. For many everyday tasks and problems, classical computers remain more practical and efficient.

FQ20. A qubit can be stored in a hard disk or USB stick like a normal bit.

   No, qubits cannot be stored in a hard disk or USB stick like normal bits. Qubits are the fundamental units of quantum information and are distinct from classical bits, which are used in classical computers (see FQ15).

   The storage and manipulation of qubits require specialized physical systems that can maintain their quantum properties. These systems are carefully engineered to isolate qubits from their surroundings to minimize decoherence effects. Storing qubits in a conventional storage device like a hard disk or USB stick is not feasible due to the requirements for maintaining quantum properties.

FQ21. Eight qubits grouped together are a qubyte.

   No, eight qubits grouped together is not called a "qubyte". “Qubyte” is not a standard term in quantum computing. For example, a system of eight qubits is often referred to as an eight-qubit quantum register or an eight-qubit quantum state. In classical computing, the fundamental unit is a bit and eight bits grouped together are called a “byte” and 1024 bytes are called a “kilobyte”. But there is no analogous to this in quantum computing.
   
FQ22. An enterprise architect will tell me, when I have to use it. 

FQ23. Business will tell me, when I have to use it.

FQ24. I have to learn strange and new programming languages before I can use quantum computers.

   You can, if you want, but you don't have to. You can learn new languages that are specialized and developed by a certain vendor (like [Q#](https://azure.microsoft.com/en-us/resources/development-kit/quantum-computing/) by Microsoft or [Silq](https://silq.ethz.ch/) ). Additionally, you have the option to use languages like [OpenQASM](https://github.com/openqasm/) for describing quantum circuits. OpenQASM is an open-source quantum assembly language that allows you to define quantum operations and compose them into circuits.

   However, languages like Python can be used to interact with qubits. A good list of resources can befound at [awesome-quantum-software](https://github.com/qosf/awesome-quantum-software) and you will find many familiar languages.

FQ25. My SHA256, MD5,... is safe enough for the next decade 

FQ26. I don't need quantum computers, I am in the cloud and already using kubernetes.

FQ27. More qubits is all you need. 

   In quantum computing, qubits are the fundamental units of information. The number of qubits in a quantum computer directly impacts its potential computational power. More qubits allow a quantum computer to handle larger and more complex problems. There are other crucial factors that contribute to the overall performance and effectiveness of a quantum computer: quantum coherence, gate fidelity, connectivity, error rates. 
   
   All of these factors are taken and used to calculate the Quantum Volume. Quantum Volume is a metric used to measure a quantum computer’s power and complexity. For more information check out the excellent article on Wikipedia about [Quantum Volume](https://en.wikipedia.org/wiki/Quantum_volume). Wikipedia shows that a quantum computer by Honeywell with 6 qubits has the same Quantum Volume of 64 as Quantum Computer by IBM with 27 qubits.

FQ28. Quantum computers need a lots of energy to cool down the qubits to near absolut zero.

FQ29. There is nothing else then quantum circuits.

FQ30. As a developer I have to understand the full stack, from endusers UI down to cryogenic for how cool a qubit.

FQ31. Quantum computers are inexact and I don't can calculate Pi to last decimal.

FQ32. I will have a quantum computer at home.

FQ33. Quantum computing is a hoax, it does actually not exist. 

FQ34. Quantum computer will destroy the world since you can create wormwholes with it.

   No, actually not. Actually it was just a hype by media and only a simplification of what happened. See [Scott Aaronson's blog](https://scottaaronson.blog/?p=6871) for detailed explaination.

FQ35. I have to use Python to program quantum computers.  
   
   No, see quantum falsehood FQ24.

FQ36. Quantum effects only happen on small scales.

FQ37. Quantum always means “discrete”.

FQ38. Everything is uncertain in a quantum Universe.

FQ39. Moore's Law is dead.

   No. Moore's Law has been named after [Gordon Moore](https://en.wikipedia.org/wiki/Gordon_Moore), co-founder of Intel, in 1965 and "(...) is the observation that the number of transistors in an integrated circuit doubles about every two years." (https://en.wikipedia.org/wiki/Moore%27s_law).
  
   While classical computers operate on bits & bytes and transistors made of silicon, quantum computer work with qubits and use photon, ions, electrons... Moore's Law is not dead, it just doesn't work in the field of quantum computing. Moore's Law is not applicable to quantum computing.

   Quantum computing is a very new field in science, but there are already new observations like [Neven's Law or Rosen's Law](https://kjoo.be/moores-law-vs-roses-law-vs-nevens-law/).

FQ40. There’s no practical use for quantum computers.

FQ41. Austria is a too small country to make good quantum tech.

![Quantum Landscape of Austria](AIT.png) (2022, credits to [AIT](https://www.ait.ac.at/en/research-topics/enabling-digital-technologies/solutions-services/quantum-technologies) )

Licensed under [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
