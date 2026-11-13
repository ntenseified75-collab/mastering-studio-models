# Mastering Studio – models

Backup copies of the separation models used by **Mastering Studio Pro by Dalgren**.

The files are published as release assets (`htdemucs-6s-v1`) so the program can download them if the
original sources are unavailable. They are byte-for-byte identical to the originals, and the program checks
their SHA-256 before using them.

| File | Size | SHA-256 |
|---|---|---|
| `htdemucs_6s_fp16weights.onnx` | 136 428 532 bytes | `7ce55792e2231c93fbf92de95f5fd5b3a5e6c89f7db690dfd693e8f1dce56869` |
| `UVR_MDXNET_KARA_2.onnx` | 52 786 726 bytes | `bf32e15105a09c0f7dddd2b67346146334d6f3ecb399ed7638eba2ab07cbf5f4` |

## Origin and license

- HT-Demucs 6s – source code and pretrained weights by Meta AI Research,
  https://github.com/facebookresearch/demucs (MIT License)
- ONNX export with fp16 weights: StemSplitio/htdemucs-6s-onnx on Hugging Face (MIT),
  revision `49df9b6989cf2150840ea65b0bef77a2e471b678`
- UVR-MDX-NET Karaoke 2 (lead/backing vocals) – trained by the developers of Ultimate Vocal Remover
  (Anjok07, aufr33 and contributors), https://github.com/Anjok07/ultimatevocalremovergui, MIT License.
  Credit to UVR and its developers, as they ask.

Redistributed unchanged under the MIT License – see [LICENSE](LICENSE).
