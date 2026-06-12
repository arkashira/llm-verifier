# LLM Verifier

This project provides a real-time performance optimization solution for LLM verification pipelines.

## Features
* Sub-1ms latency for numerical cross-checks
* End-to-end verification throughput > 50k requests/sec

## Usage
1. Run the verifier using `python src/llm_verifier.py --iceoryx2-shared-memory-channels channel1 channel2 --numerical-cross-checks 1.0 2.0 3.0`
2. Integrate with vLLM/SGLang inference engines using `python src/llm_verifier.py --integrate-with-vllm vLLM`
