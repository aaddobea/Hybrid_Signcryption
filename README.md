# 🔐 Formal Verification of the Proposed Signcryption Protocol using Verifpal

> **Security validation and symbolic verification framework for the proposed lightweight hybrid signcryption protocol**

---

## 📌 Overview

This repository presents a **comprehensive formal security verification** of the proposed signcryption protocol described in our manuscript submitted to *Computer Standards & Interfaces*.

The protocol has been rigorously modeled and analyzed using **Verifpal**, a symbolic formal verification tool designed for cryptographic protocol analysis.

The objective of this repository is to provide:

- 🔍 **formal symbolic verification**
- 🔐 **security property validation**
- 📊 **reproducible protocol analysis**
- 🧪 **experimental performance evaluation support**

Verifpal was employed to assess the protocol against symbolic adversarial models and validate its resistance to common cryptographic attacks.

🌐 Official Verifpal website:  
https://verifpal.com

---

## 📖 Research Abstract

The emergence of blockchain technology has accelerated the adoption of public-key cryptographic mechanisms for protecting on-chain data. However, many existing approaches remain unsuitable for blockchain-based deployment due to their computational complexity, which further intensifies scalability challenges.

In addition, storing large volumes of medical data directly on-chain significantly worsens storage overhead and network scalability.

To address these limitations, this work proposes a **lightweight hybrid signcryption scheme** for securing patient medical records.

The proposed framework integrates:

- 🔗 **blockchain-based verification**
- ☁️ **decentralized off-chain storage**
- 🔐 **lightweight signcryption**
- 🏥 **secure medical data exchange**

The off-chain storage mechanism manages large-scale medical datasets and generates a cryptographic hash that securely links off-chain content to the blockchain.

Subsequently:

1. The patient signcrypts and uploads the protected data
2. A smart contract stores the associated verification reference
3. The doctor validates the integrity and authenticity of the received data

A rigorous **formal verification analysis using Verifpal** is conducted to validate the protocol’s security guarantees.

Furthermore, extensive experiments are performed to evaluate:

- computational efficiency
- communication overhead
- scalability performance
- decentralized storage latency

The proposed approach is also benchmarked against existing relevant schemes.

---
## 🔍 Verifpal Model Overview

<p align="center">
  <img src="signcryptpub.jpeg" alt="Verifpal Model" width="700"/>
</p>

## 🗂 Repository Structure

```bash
.
├── src/            # Verifpal protocol models and verification scripts
├── docs/           # Documentation, findings, and analysis reports
├── experiments/    # Performance evaluation scripts (optional)
├── README.md
└── LICENSE.md
```

---

## ⚙️ Installation

Please install Verifpal from the official documentation:

🔗 https://verifpal.com/software/

Choose the appropriate version for your operating system.

---

## 🚀 Running the Verification

After installation, execute the verification model using:

```bash
./verifpal verify <model_to_verify.vp>
```

Example:

```bash
./verifpal verify src/signcryption_protocol.vp
```

---

## 🖥 Development Environment

The symbolic verification models were developed and tested in:

- **Visual Studio Code**
- **macOS environment**
- **Verifpal latest stable version**

Ensure the environment is properly configured before execution.

---

## 🔬 Security Analysis Goals

The verification focuses on validating the following security properties:

- 🔐 confidentiality
- ✍️ authenticity
- 🛡 integrity
- 👤 sender non-repudiation
- 🧾 ciphertext correctness
- 🔄 resistance to replay attacks
- 🔓 resistance to key compromise attacks
- ⚠️ symbolic adversary resistance

---

## 🤝 How to Contribute

Contributions are highly welcome.

If you identify:

- potential vulnerabilities
- protocol weaknesses
- optimization opportunities
- formal modeling improvements

please follow the standard GitHub workflow:

1. Fork the repository
2. Create a feature branch
3. Commit your modifications
4. Submit a pull request with detailed explanations

---

## ⚠️ Disclaimer

This repository represents an **active and evolving formal verification study**.

The models and analyses may be updated as:

- new attack vectors emerge
- improved symbolic assumptions are introduced
- reviewer feedback is incorporated
- journal revisions are completed

Community contributions and peer feedback are strongly encouraged.

---

## 📜 License

This project is licensed under the **MIT License**.

See the [LICENSE.md](LICENSE.md) file for details.

---

## 👩‍🔬 Authors

- **Abigail Akosua Addobea**
- **QianMu Li**
- **Isaac Obiri Amankona**
- **Jun Hou**

---

## 📚 Citation

If you use this repository in your research, please cite the associated manuscript.

```bibtex
@article{addobea2026signcryption,
  title={Lightweight Hybrid Signcryption Scheme for Secure Blockchain-Based Medical Data Sharing},
  author={Addobea, Abigail Akosua and Li, QianMu and Amankona, Isaac Obiri and Hou, Jun},
  journal={Computer Standards \& Interfaces},
  year={2026}
}
```

---
