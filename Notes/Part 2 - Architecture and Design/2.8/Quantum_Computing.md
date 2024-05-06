# Quantum Computing

Computers based on quantum physics. 

**Classical Mechanics**
- qubits = exist somewhere between 1 and 0
- quantum superposition!

**Binary Calculations**
- *in short* = 4 qubits to represent 16 bits
    - typically represent 2<sup>4</sup> = 16 as seperate values
    - quantum computing represents 2<sup>4</sup> = 16 as four individual qubits
- extremely scalable
- search through large data very quickly

**Post-quantum cryptography**
- can quickly factor large prime numbers
- e.g. Peter Shor's algo to find prime factors, given integer N
- *NTRU* - use closest vector problem w/ lattice theory
    - doesnot require finding large prime factorizations

**Quantum Communication**
- if you examine the quantum bit > the quantum bit changes
- Quantum Key Distribution (QKD)
    - send random stream of qubits (key) across quantum network channel
    - both sides verify key for authenticity
    - eavesdropper would modify the datastream and violate the quantum balance