# SG_pv

This repository contains the **ProVerif formal verification code** for the following paper:

> **"A Secure and Efficient Authentication Scheme for Smart Grid Environments Using Physical Unclonable Functions (PUF) and Hash-Based Tokens"**

## 🧪 Description

The ProVerif model verifies the security properties of the proposed lightweight mutual authentication and key establishment protocol designed for smart grid environments. The protocol leverages:

- Physical Unclonable Functions (PUFs) for device-level uniqueness
- Fuzzy extractors for PUF noise tolerance
- Hash-based tokens for secure communication and session key generation

The code analyzes **mutual authentication**, **secrecy of session keys**, and **resistance to replay and impersonation attacks** using ProVerif's automated symbolic analysis.

## 📁 Files

- `SM.pv`: Main ProVerif code modeling the protocol
- `README.md`: Project description and instructions

## 🔧 Requirements

- [ProVerif](https://proverif.inria.fr/) v2.03 or higher  
  Run the tool with:

```bash
proverif puf_sg_auth.pv
