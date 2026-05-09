---
layout: page
permalink: /projects/
title: Projects
---

Here is a non-exhaustive list of my non-research projects. My research work can be found <a href="/research">here</a>. You can also check out my Github profile <a href="#">here</a> for a complete list of my projects.

<ul>
	<li style="display: flex; align-items: flex-start; margin-bottom: 2em; width: 100%;">
		<img src="/images/eggplant.gif" alt="Failure Prediction for Generative Robot Policy" style="width: 180px; height: 180px; object-fit: cover; border-radius: 8px; margin-right: 2em;" />
		<div style="flex: 1;">
			<b>Failure Prediction for Generative Robot Policy</b><br>
			<span>Technologies: PyTorch, Transformers, GRU, TCN, Hydra, Weights & Biases, SLURM, Big Red 200 (HPC)</span><br>
			Worked on mechanistic interpretability and runtime failure prediction for Vision-Language-Action (VLA) robotic policies by studying how successful executions evolve in latent feature space over time. Extended the SAFE (NeurIPS 2025) framework with GRU, Transformer, and TCN temporal models, building large-scale HPC evaluation pipelines on Indiana University's Big Red 200 cluster for zero-shot failure detection, trajectory analysis, and architecture ablation studies across robotic manipulation tasks.<br>
			<a href="https://github.com/dsatyam09/Failure-Prediction-for-Generative-Robot-Policy" target="_blank"><div class="color-button">Code</div></a>
		</div>
	</li>
	<li style="display: flex; align-items: flex-start; margin-bottom: 2em; width: 100%;">
		<img src="/images/neuramind.png" alt="NeuraMind" style="width: 180px; height: 180px; object-fit: cover; border-radius: 8px; margin-right: 2em;" />
		<div style="flex: 1;">
			<b>NeuraMind</b><br>
			<span>March 2026 (Claude Builder Club Hackathon @ IU – 1st Prize)</span><br>
			<span>Technologies: Swift (macOS), Claude AI (MCP), SQLite, Core ML, Accessibility APIs, Screen Recording APIs</span><br>
			Built a privacy-first macOS ambient memory system that captures and reconstructs work context using real-time activity signals and Claude AI. Enables focus tracking, context recovery, and AI-generated workflow summaries with a local-first architecture and optional semantic reasoning layer.<br>
			<a href="https://github.com/dsatyam09/NeuraMind" target="_blank"><div class="color-button">Code</div></a>
			<a href="https://www.youtube.com/watch?v=z3_eFS4P9w8" target="_blank"><div class="color-button">Demo</div></a>
		</div>
	</li>
	<li style="display: flex; align-items: flex-start; margin-bottom: 2em; width: 100%;">
		<img src="/images/agenticaudit.png" alt="Agentic AI Compliance Monitoring System" style="width: 180px; height: 180px; object-fit: cover; border-radius: 8px; margin-right: 2em;" />
		<div style="flex: 1;">
			<b>Agentic AI Compliance Monitoring System</b><br>
			<span>Technologies: LangGraph, FastAPI, Qwen3 (local LLM), ChromaDB, SQLite, RAG (Sentence Transformers), Cross-Encoders, Jinja2, PyMuPDF</span><br>
			Built an agentic compliance auditing system using multi-agent debate (Advocate, Challenger, Arbiter) to evaluate enterprise policies against GDPR, HIPAA, and NIST standards, generating audit-ready POA&M reports. Designed a full RAG pipeline with vector retrieval and cross-encoder reranking for clause-level compliance detection across 1K+ policy sections. Integrated adaptive regulation monitoring, semantic drift detection, and fully local LLM execution for zero-cost, fully auditable reasoning with end-to-end traceability.<br>
			<a href="https://github.com/dsatyam09/Agentic_Audit" target="_blank"><div class="color-button">Code</div></a>
			<a href="https://www.youtube.com/watch?v=RZcnRnm9KA4&feature=youtu.be" target="_blank"><div class="color-button">Demo</div></a>
		</div>
	</li>
	<li style="display: flex; align-items: flex-start; margin-bottom: 2em; width: 100%;">
		<img src="/images/enigma.gif" alt="Dynamic Leaderboard Ranking" style="width: 180px; height: 180px; object-fit: cover; border-radius: 8px; margin-right: 2em;" />
		<div style="flex: 1;">
			<b>Dynamic Leaderboard Ranking</b><br>
			<span>Technologies: FastAPI, PostgreSQL, Redis, Docker, React (Vite), TypeScript, AWS EC2, Vercel</span><br>
			Built a real-time scalable leaderboard system in 24 hours simulating chess-scale ranking workloads with high read/write concurrency. Designed a hybrid architecture using FastAPI + Postgres for durability, an in-memory skip list for O(log N) ranking and percentile computation, and Redis caching for low-latency reads. Applied system design principles like write-ahead logging, separation of read/write paths, async processing, and cache-aside strategy to ensure scalability, consistency, and performance under heavy load.<br>
			<a href="https://github.com/dsatyam09/Enigma" target="_blank"><div class="color-button">Code</div></a>
			<a href="https://www.youtube.com/watch?v=avmymBZX5AY" target="_blank"><div class="color-button">Demo</div></a>
		</div>
	</li>
	<li style="display: flex; align-items: flex-start; margin-bottom: 2em; width: 100%;">
		<img src="/images/Novanewz.png" alt="NovaNewz" style="width: 180px; height: 180px; object-fit: cover; border-radius: 8px; margin-right: 2em;" />
		<div style="flex: 1;">
			<b>NovaNewz</b><br>
			<span>December 2025</span><br>
			<span>Technologies: Cloudflare (Workers, Vectorize, D1, Workers AI), Next.js, TypeScript, Python</span><br>
			Built a serverless AI news engine using Cloudflare's edge stack to deliver fast, context-aware summaries with a RAG pipeline powered by Vectorize retrieval and Llama 3 generation. Developed a scalable ingestion and indexing pipeline using Workers AI for embeddings and D1 for storage, enabling continuous updates and a smooth user search and reading experience.<br>
			<a href="https://github.com/dsatyam09/NovaNewz" target="_blank"><div class="color-button">Code</div></a>
		</div>
	</li>
	<li style="display: flex; align-items: flex-start; margin-bottom: 2em; width: 100%;">
		<img src="/images/Profile.png" alt="DocSpot" style="width: 180px; height: 180px; object-fit: cover; border-radius: 8px; margin-right: 2em;" />
		<div style="flex: 1;">
			<b>DocSpot</b><br>
			<span>May 2024</span><br>
			<span>Technologies: ElasticSearch, FAISS, Langchain, MongoDB, React, Flask</span><br>
			Built a multilingual academic research assistant using Gemini-powered reasoning and Retrieval-Augmented Generation (RAG) architecture. Enabled real-time chat, translation, and document insights. Reduced average search latency by 43% by integrating ElasticSearch (keyword search) with FAISS (semantic search). Incorporated a T5-small summarization pipeline to convert complex research papers into concise, digestible summaries.<br>
			<a href="https://github.com/dsatyam09/DocSpot.git" target="_blank"><div class="color-button">Code</div></a>
		</div>
	</li>
	<li style="display: flex; align-items: flex-start; margin-bottom: 2em; width: 100%;">
		<img src="/images/architecture.png" alt="SecureGANs" style="width: 180px; height: 180px; object-fit: cover; border-radius: 8px; margin-right: 2em;" />
		<div style="flex: 1;">
			<b>SecureGANs</b><br>
			<span>April 2024</span><br>
			<span>Technologies: GANs, Flask, React, U-Net</span><br>
			Designed a full-stack web system to restore masked or occluded facial features using a GAN-based image inpainting model. Employed a dual-path U-Net ensemble architecture, achieving PSNR of 22.25 and SSIM of 0.874. Project results were published in the Journal of Electronic Systems (JES).<br>
			<a href="https://github.com/dsatyam09/Image-Inpainting-for-Missing-Facial-Data-Recovery-in-Security-Settings" target="_blank"><div class="color-button">Code</div></a>
			<a href="https://www.youtube.com/watch?v=0LLw30HHPl0" target="_blank"><div class="color-button">Demo</div></a>
		</div>
	</li>
	<li style="display: flex; align-items: flex-start; margin-bottom: 2em; width: 100%;">
		<img src="/images/connect4.gif" alt="Connect-4 AI" style="width: 180px; height: 180px; object-fit: cover; border-radius: 8px; margin-right: 2em;" />
		<div style="flex: 1;">
			<b>Connect-4 AI</b><br>
			<span>January 2024</span><br>
			<span>Technologies: Python, DQN, Reinforcement Learning</span><br>
			Developed an AI for Connect-4 using Deep Q-Learning, comparing exploration strategies like epsilon-greedy and Upper Confidence Bound (UCB). Created an evaluation framework to benchmark 5+ DQN variants against minimax-based opponents. Achieved a 78% win rate in simulations against baseline algorithms.<br>
			<a href="https://github.com/dsatyam09/Connect-4-ReinforceBot/tree/main" target="_blank"><div class="color-button">Code</div></a>
		</div>
	</li>
</ul>