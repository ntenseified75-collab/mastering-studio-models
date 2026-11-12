# Mastering Studio – models

Backup copy of the stem-separation model used by **Mastering Studio Pro by Dalgren**.

The file is published as a release asset (`htdemucs-6s-v1`) so the program can download it if the
original source is unavailable. It is byte-for-byte identical to the original, and the program checks
its SHA-256 before using it.

| File | Size | SHA-256 |
|---|---|---|
| `htdemucs_6s_fp16weights.onnx` | 136 428 532 bytes | `7ce55792e2231c93fbf92de95f5fd5b3a5e6c89f7db690dfd693e8f1dce56869` |

## Origin and license

- HT-Demucs 6s – source code and pretrained weights by Meta AI Research,
  https://github.com/facebookresearch/demucs (MIT License)
- ONNX export with fp16 weights: StemSplitio/htdemucs-6s-onnx on Hugging Face (MIT),
  revision `49df9b6989cf2150840ea65b0bef77a2e471b678`

Redistributed unchanged under the MIT License – see [LICENSE](LICENSE).
