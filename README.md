# **Homomorphic Encryption of Iris Using Hashing**  

## **Overview**  
This repository contains research on **Homomorphic Encryption of Iris Using Hashing**. The study proposes a privacy-preserving biometric authentication system that integrates **homomorphic encryption** and **SHA-256 hashing** to ensure secure iris recognition. The system extracts iris features using **Gabor filters**, encrypts them using the **Brakerski-Fan-Vikram (BFV) scheme** via **TenSEAL**, and authenticates users using **Hamming distance** calculations.  

## **Key Features**  
✔ **Feature Extraction** – Uses **Gabor filters** to obtain unique iris patterns.  
✔ **Homomorphic Encryption** – Encrypts iris data using the **BFV encryption scheme** via **TenSEAL**.  
✔ **Secure Hashing** – Protects data integrity with **SHA-256 hashing**.  
✔ **Efficient Authentication** – Uses **Hamming distance** for identity verification.  
✔ **Dataset** – Evaluated on the **IIT Delhi Iris Dataset**.  

## **Methodology**  
1. **Preprocessing** – Gabor filters extract iris features.  
2. **Encryption** – BFV homomorphic encryption secures feature vectors.  
3. **Hashing** – SHA-256 hashes the encrypted iris data.  
4. **Matching** – Hamming distance determines user identity.  

## **Results & Discussion**  
- The proposed system achieves **high accuracy** while ensuring **privacy preservation**.  
- Homomorphic encryption allows computations on encrypted iris data without decryption.  
- The Hamming distance threshold is optimized to reduce **false positives and false negatives**.  

## **Future Scope**  
🔹 Implement **Fully Homomorphic Encryption (FHE)** for more secure processing.  
🔹 Improve feature extraction using **deep learning models**.  
🔹 Extend the system to support **multi-modal biometric authentication**.  


