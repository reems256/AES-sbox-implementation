# AES S-Box Implementation
Python implementation of the AES S-Box and inverse S-Box using finite field arithmetic (GF(2⁸)) and affine transformations.


## Overview

This project implements the AES (Advanced Encryption Standard) S-Box and inverse S-Box from first principles using Python. Instead of relying on precomputed lookup tables, the S-Box is constructed mathematically using finite field arithmetic over GF(2⁸) followed by the affine transformation defined in the AES standard (FIPS-197).

The project also verifies the correctness of the generated S-Box by comparing it with the official AES specification and validating important cryptographic properties.

---

## Features

- Generate multiplicative inverses in GF(2⁸)
- Apply the AES affine transformation
- Generate the AES S-Box
- Generate the inverse S-Box
- Verify against the official AES S-Box
- Test one-to-one mapping
- Demonstrate the S-Box non-linearity property
- Interactive console testing for user-provided hexadecimal values

---

## Technologies

- Python
- Galois
- Rich

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/aes-sbox-implementation.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
python src/aes_sbox.py
```

---

## Project Structure

```
src/
    aes_sbox.py

screenshots/

README.md
requirements.txt
```

---

## Validation

The implementation was validated by:

- Comparing the generated S-Box with the official AES S-Box
- Generating and verifying the inverse S-Box
- Confirming one-to-one mapping
- Demonstrating the non-linearity property
- Performing manual substitution and inverse substitution tests

---
## Sample Output

A complete example execution of the program, including the generated lookup tables,
validation results, and interactive tests, is available in:

`output/sample_output.txt`<img width="390" height="172" alt="final_AES_sbox_ss" src="https://github.com/user-attachments/assets/1fa428ab-8c23-4657-86fe-11931d94943c" />


## Learning Outcomes

This project strengthened my understanding of:

- AES internals
- Finite field arithmetic
- Affine transformations
- Cryptographic validation techniques
- Secure algorithm implementation

---

## Acknowledgements

This project was developed as part of a university cryptography course.

Contributors:

- Reem Sukkari
- Aryam Mansour
- Aseel Khalid
- Razan Hamchou
