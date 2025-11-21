# Hi, I'm Aime Cesaire

I learn by building small AI agents, security tooling, and pragmatic full-stack apps. None of these projects are perfect, but each one taught me something concrete about reliability, safety, or user-facing polish.

## What I'm focused on
- Writing classical AI agents (search, minimax, RL) and measuring how small changes affect behavior.
- Prototyping cryptography and steganography utilities to understand where attacks actually work.
- Keeping a handle on deployment basics (React/Next, Node, Hardhat, Docker, Firebase) so ideas are easy to share.
- Studying systems topics—networking, operating systems, optimization—to ground the above in reality.

## Stack I reach for
- **Languages**: Python, TypeScript, Java, C++, Solidity, Dart.
- **Frameworks**: React, Next.js, Node.js, Tailwind, Flutter.
- **AI / Data**: NumPy, Pandas, Matplotlib, scikit-learn.
- **Systems & Infra**: Hardhat, Docker, GitHub Actions, WSL, Firebase, MongoDB, MySQL.

## Recent Projects
### AI and automation
- [Pacman AI Agents](https://github.com/AimeCesaireM/AI-Projects) — Implements BFS/DFS search, heuristic planners, minimax/expectimax adversarial agents, and a small reinforcement-learning setup for the UC Berkeley Pacman framework. Includes comparison scripts to show win rates and scores per map.

### NLP and language tooling
- [Distilbert-finetuning-COPA](https://github.com/AimeCesaireM/Distilbert-finetuning-COPA) — Notebook experiments that fine-tune DistilBERT on the COPA commonsense dataset using Hugging Face trainers, with simple accuracy tracking against the untouched checkpoint.
- [Agnostic-LLM-Watermarking](https://github.com/AimeCesaireM/Agnostic-LLM-Watermarking) — Exploration of prompt-level and token-level watermarking for LLM text. I mostly run baselines and compare how BERT-style classifiers detect the marks under paraphrasing.
- [tokenization-with-regex](https://github.com/AimeCesaireM/tokenization-with-regex) — Tests how different orthographic rules impact regex-driven tokenization on small corpora so I can see failure cases before feeding data to classical NLP models.

### Data mining and large-scale analytics
- [data-mining-graph-algorithms](https://github.com/AimeCesaireM/data-mining-graph-algorithms) — Hadoop MapReduce jobs that compare multiple graph mining routines. Most runs are small, but they help me reason about workload/cluster tuning.
- [FreqItemsetsMapReduce](https://github.com/AimeCesaireM/FreqItemsetsMapReduce) — Java implementation of the SON frequent itemset algorithm on Hadoop. I use it to sanity-check lecture notes with real transaction logs.
- [TRIEST-Algorithm](https://github.com/AimeCesaireM/TRIEST-Algorithm) — Streaming triangle-counting implementation (both BASE and IMPROVED variants). Good for understanding how approximate counting behaves as edge rates change.

### Security, cryptography, and steganography
- [Phase 1 — Steganography Detector](https://github.com/AimeCesaireM/Steganography-Detector) — CLI utility that reads PNG/BMP carriers, extracts least-significant-bit payloads, and reconstructs hidden text or images. Useful for coursework demos and basic forensic drills.
- [ouispar — Elliptic Curve Cryptography](https://github.com/AimeCesaireM/ecc-cryptography) — Straightforward Python implementation of finite-field arithmetic, point addition/multiplication, and key exchange helpers. I use it to step through ECC math instead of treating it as a black box.
- [Error Detection on Network Data Link Layers](https://github.com/AimeCesaireM/CRC) — Java simulator for CRC-based framing. It handles start/stop flags, byte stuffing, and bit-flip injection so I can visualize how resilient a frame format is before writing firmware-level code.

### Full stack and systems delivery
- [Mammoth Rumble — Decentralized Voting](https://github.com/AimeCesaireM/Decentralized-Voting) — Solidity contracts plus a React dashboard that run on Hardhat, ethers.js, and IPFS. The live demo at [34.16.36.118](http://34.16.36.118) is bare-bones but walks through registration, ballot casting, and tallying on test networks.
- [portfolio-website](https://aimecesairem.github.io/portfolio-website/) — Personal site built with vanilla HTML/CSS/JS. It doubles as a lab for layout experiments and accessibility tweaks.

## How to reach me
- [LinkedIn](https://www.linkedin.com/in/aime-cesaire-mugishawayo/)
- [Handshake](https://amherst.joinhandshake.com/profiles/u6e8s3)

## Coursework
- Algorithms
- Data Structures
- Machine Learning
- Computer Systems
- Computer Networks
- Artificial Intelligence
- Abstract Algebra
- Number Theory
- Cryptography
- Computer Security

## Always open to chatting about
- Practical AI/ML projects (especially ones with tight resource limits)
- Math-heavy security problems
- Student-friendly systems or infrastructure work

## Fun fact
I'm named after Aimé Césaire, the poet, author, and statesman from Martinique. If you have reading recs from his era, I’m all ears. Thanks for visiting.
