# LLM Verifier
LLM Verifier is a real-time performance optimization tool that integrates with iceoryx2 IPC library for low-latency verification pipelines.

## Features

* Sub-1ms latency for numerical cross-checks using iceoryx2 shared memory channels
* End-to-end verification throughput > 50k requests/sec (based on iceoryx2 v0.9 benchmarks)
* Zero-copy integration with vLLM/SGLang inference engines via IPC memory regions

## Usage

1. Install the required dependencies using `poetry install`
2. Run the verifier using `python -m llm_verifier --num_requests 1000`
