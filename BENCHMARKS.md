# Measurement protocol — Wonek Video Studio

Status: protocol only; no runs or comparative performance claims are published yet.

## What to measure

Transcription accuracy, subtitle timing, processing time, export time and output size. Use permission-cleared source media and a manually checked transcript. Record source duration, codec, dimensions, frame rate, model/version, language and export settings.

## Reproducible procedure

1. Record app version/build, date, OS, hardware, available memory, power mode and relevant settings.
2. Identify every input by filename and SHA-256 hash. Use only synthetic or permission-cleared data.
3. Record the exact actions, model/provider versions and network conditions. Separate local and cloud operations.
4. Run a warm-up separately, then at least five measured repetitions with the same inputs. Distinguish cold-start and warm-start runs.
5. Keep raw per-run measurements, failures and verification evidence. Report the median and range; never report only the best run.
6. Validate output correctness before interpreting speed. Record defects as well as successful outputs.
7. When comparing tools, publish their exact versions, equivalent settings and limitations. Do not infer rankings from untested products.

Use [RESULT_TEMPLATE.md](RESULT_TEMPLATE.md). Leave unmeasured fields blank or mark them not measured. A proposed test is not a completed benchmark.
