# Wonek Video Studio — operating procedures

Use these procedures as task-oriented reference. They describe public capabilities and verification steps, not private implementation. UI labels can vary by version.

## Procedure 1: Prepare a captioned handoff

### Before you begin

Use a source clip you own and agree on output format with the recipient.

### Steps

1. Choose a self-contained section and write a brief context note.

2. Prepare subtitles and compare them against the speech, especially names and numbers.

3. Preview at the destination size to check line breaks and overlay conflicts.

4. Export one short test and verify audio, first/last frames and playback.

5. Deliver the approved export with its version, intended channel and caption copy.

### Expected result

The recipient can identify and play the correct final version without guessing which draft is approved.

### If the result differs

If captions are wrong, correct the text before exporting the full set. If playback fails, check codec and destination constraints.

## Procedure 2: Keep provider and local workflows separate

### Before you begin

Identify which operation uses a local model and which calls a provider.

### Steps

1. Prepare a non-sensitive sample and record the selected operation/model.

2. Complete any local model download before testing offline use.

3. Check whether the next action sends a prompt, image or media to a provider.

4. Review the output for unsupported product claims and pronunciation errors.

5. Record the workflow used alongside the exported version.

### Expected result

You know the processing path and can repeat the same production setup.

### If the result differs

Do not treat local project storage as proof that every AI action is local; provider operations can have separate keys, costs and network requirements.

## Report a repeatable problem

Record app/version, device/OS, selected mode, input conditions and the smallest failing step. Distinguish expected behavior from the observed result. Use synthetic examples and omit credentials or private records.

[Documentation index](README.md) · [Capabilities and limits](FEATURES_AND_LIMITS.md) · [Support and sources](PRIVACY_AND_SUPPORT.md)
