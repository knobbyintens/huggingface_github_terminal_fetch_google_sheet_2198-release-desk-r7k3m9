# NimbusQA-Synth-Chat

Release card for the synthetic dialogue package in the NimbusQA family.

## Summary

Synthetic multi-turn question/answer pairs written by an instruction-tuned
checkpoint and filtered for answer consistency.

## Provenance

Generation checkpoint: Hugging Face model `Qwen/Qwen2.5-7B-Instruct` (intake
ledger entry `nimbusqa-synth-chat`). Prompts were authored in-house; outputs
are machine generated and reviewed for formatting only.

## Files

- `data/train-00000.parquet`

## Provenance notes

Each record carries the prompt template identifier used at generation time.