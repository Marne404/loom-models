# loom-models

Model files for [Loom](https://github.com/Marne404), an Android app that keeps everything you save
searchable on your device. Loom downloads these files when you turn on *Smarte Suche*
(meaning-based search); nothing is sent anywhere, the model runs locally.

## EmbeddingGemma 300M (release `embeddinggemma-300m-v1`)

| File | Size |
|---|---|
| `embeddinggemma-300M_seq512_mixed-precision.tflite` | 179 MB |
| `sentencepiece.model` | 4.7 MB |

Unmodified copies of [litert-community/embeddinggemma-300m](https://huggingface.co/litert-community/embeddinggemma-300m)
(LiteRT, 512-token context, mixed int4/int8). Loom verifies size and SHA-256 of both files after
downloading.

## License

Gemma is provided under and subject to the Gemma Terms of Use found at
[ai.google.dev/gemma/terms](https://ai.google.dev/gemma/terms). By downloading or using these files
you agree to those terms, including the use restrictions of Section 3.2 and the
[Gemma Prohibited Use Policy](https://ai.google.dev/gemma/prohibited_use_policy).
A copy of the terms is in [GEMMA_TERMS_OF_USE.md](GEMMA_TERMS_OF_USE.md); see also [NOTICE](NOTICE).
