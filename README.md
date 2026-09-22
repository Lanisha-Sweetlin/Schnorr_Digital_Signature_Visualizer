# Schnorr Digital Signature Visualizer

An interactive web-based visualizer for understanding the Schnorr Digital Signature scheme step by step.

This project makes the mathematical process behind Schnorr signatures easier to understand by visually demonstrating key generation, nonce generation, commitment, challenge, response, and verification.

---

## Features

- Modern dark cryptography-themed UI
- Purple and pink animated visual design
- Animated Schnorr cryptography visualization
- Public and private key demonstration
- Nonce generation visualization
- Commitment calculation
- SHA-256 based challenge generation
- Signature response calculation
- Signature verification
- Live signature console
- Six-step signing animation
- Responsive design
- No backend required

---

## Schnorr Digital Signature Flow

The visualizer demonstrates the following process.

### 1. Key Generation

A secret value `x` is selected.

The public key is calculated as:

```text
y = g^x mod p
