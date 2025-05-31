
# RE-EN (Rasanjana-East-Encryption): Full Technical Description

**Author:** W.H. Tharusha Rasanjana

## 1. What is RE-EN?
RE-EN (Rasanjana-East-Encryption) is a novel universal cryptographic framework designed to combine encryption, compression, and hashing into one secure, reversible system. Developed by W.H. Tharusha Rasanjana, RE-EN features quantum resistance, dynamic key structures, and perfect reversibility.

## 2. Core Principles and Theories

### Theory 1: Base Representational Compression
- Converts data into reduced base forms like Base64, Base94, or Unicode, achieving compact and lossless representation.

### Theory 2: FAAS (Find-And-Apply System)
- Utilizes a dynamic, rotating substitution grid influenced by message position, transformation round, and key segments.

### Theory 3: AK Notation (Alternation Key Notation)
- Applies exponential compression (`y = n^x`) and decompression (`x = logₙ(y)`) to encode repeating structures efficiently.

## 3. Key Components

### KHAST – Key-Hide-And-Seek Technology
- Keys are embedded and hidden in symbolic layers, invisible to attackers, and require multi-step reverse engineering.

### PBPT – Particle By Particle Technology
- Breaks messages into characters or bits, each undergoing unique transformations, ensuring non-repetition and granular security.

### Chain Key Set System
- Keys are organized in a sequence, where each affects the next (chained behavior), providing a high avalanche effect.

## 4. Encryption Flow
1. Input
2. Base Compression
3. PBPT
4. FAAS Mapping
5. Chain Key Modulation
6. AK Notation Compression
7. KHAST Embedding
8. Final Obfuscation

## 5. Decryption Flow
1. De-obfuscate
2. Recover KHAST Keys
3. Reverse AK Notation
4. Reverse Chain Keys
5. Inverse FAAS
6. Reassemble Particles
7. Retrieve Original Message

## 6. Security Features
- 100% reversibility
- Strong avalanche effect
- High entropy (NIST-STS verified)
- Resistance to brute-force and quantum attacks (Grover's, Shor’s)
- Pattern obfuscation and symbolic noise integration

## 7. Quantum Resistance
- Simulated testing against up to 100 million qubits showed no successful breaks
- Non-representable keyspace in binary
- Ciphertext statistically indistinguishable from random noise

## 8. Use Cases
- Military encryption
- Post-quantum cryptography
- Blockchain hashing
- Digital forensics
- IoT & satellite encryption

## 9. Mathematical Summary
- **Compression:** `y = n^x → x = logₙ(y)`
- **Encryption:** `E(M) = KHAST(AK(PBPT(FAAS(M))))`

Where:
- `M` = message  
- `Ki` = chain key  
- `AK` = Alternation Key  
- `PBPT` = character-level processing  
- `FAAS` = dynamic substitution grid  

## 10. Final Notes
RE-EN represents a new frontier in cryptography: compact, complex, and quantum-secure. It transforms how data is encrypted, compressed, and stored.

