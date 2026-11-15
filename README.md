# OnCue models

Model files that the OnCue app downloads at its first start. The files are in the
Releases of this repository, not in git.

## Release v1

Voices: Kokoro v1.0 (multi-lang), as packaged by sherpa-onnx (k2-fsa), unchanged. License: Apache-2.0 (see LICENSE).

| File | Size (bytes) | SHA-256 |
|---|---|---|
| model.onnx | 325560556 | b40f62b166ac8164b0627ef48a0b358eda0985e272fb03ef5252e7206305da11 |
| voices.bin | 28200960 | 1c5a5b983d3d50d8586d437a51f3faa2da7919ce76a013c081e65671a3447c29 |

Speech recognition: Moonshine base (English, int8), from
https://github.com/usefulsensors/moonshine, as packaged by sherpa-onnx (k2-fsa), unchanged.
License: MIT (see LICENSE-moonshine).

| File | Size (bytes) | SHA-256 |
|---|---|---|
| preprocess.onnx | 14077290 | ffa630d395c5ccf76f5d4954be5b882df76aaf6491519ec01fd82ea7a3819fb2 |
| encode.int8.onnx | 50311494 | 7e38770f776f2e5583a53b052936005df2ba5c833d7e09c2a5fd796b94bf73e2 |
| uncached_decode.int8.onnx | 122120451 | c01f4b35093bcac20d352d23a75a539e772964579f9d024a90e5e6f09cae9987 |
| cached_decode.int8.onnx | 99983837 | 2db74e51cedf64a8b1be3c8192e0bb5e4923af0e90bd9e87f8e8771873f8ea03 |
