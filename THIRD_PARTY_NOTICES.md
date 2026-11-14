# Hinweise zu Drittanbieter-Bestandteilen

Diese Datei nennt die Bestandteile, die mit der App ausgeliefert werden oder eine ausdrückliche Namensnennung verlangen, und die Modelle. Alle Rust- und npm-Bibliotheken mit ihren Lizenztexten listet der Lizenz-Report, der bei jedem Build entsteht – in der App unter „Einstellungen“ → „Über“ → „Alle Bibliotheken und Lizenztexte anzeigen“. Einige Bibliotheken, die Tauri mitbringt, stehen unter der Mozilla Public License 2.0 (`cssparser`, `cssparser-macros`, `selectors`, `dtoa-short`, `option-ext`); sie sind unverändert, ihr Quelltext ist auf crates.io öffentlich.

## Mit der App ausgeliefert

- **Silero VAD** – © Silero Team, MIT-Lizenz. https://github.com/snakers4/silero-vad
- **ONNX Runtime** – © Microsoft Corporation, MIT-Lizenz. https://github.com/microsoft/onnxruntime
- **libopus** – © Xiph.Org Foundation und Mitwirkende, BSD-3-Clause. https://opus-codec.org
- **sherpa-onnx** (mit eigener ONNX Runtime als DLL) – © Xiaomi Corporation / k2-fsa, Apache-2.0. https://github.com/k2-fsa/sherpa-onnx
- **sonora** (WebRTC Audio Processing, Rust-Portierung) – © The WebRTC project authors und Mitwirkende, BSD-3-Clause. https://github.com/dignifiedquire/sonora
- **llama.cpp** (`llama\llama-server.exe` mit DLLs, offizielles Windows-Paket mit Vulkan b12110 = v0.9.0, unverändert) – © The ggml authors, MIT-Lizenz. Enthält weitere MIT-lizenzierte Bestandteile (u. a. cpp-httplib, nlohmann/json). https://github.com/ggml-org/llama.cpp
- **LLVM OpenMP Runtime** (`llama\libomp.dll`, Teil des llama.cpp-Pakets) – © LLVM Project, Apache-2.0 mit LLVM-Ausnahme; Lizenztext liegt als `llama\LICENSE-LLVM-OpenMP` bei. https://openmp.llvm.org
- **whisper.cpp** (`whisper\whisper-server.exe` mit DLLs, offizielles Windows-Paket b5454 = v1.9.5, unverändert) – © The ggml authors, MIT-Lizenz. Enthält weitere MIT-lizenzierte Bestandteile (u. a. cpp-httplib, nlohmann/json). Dazu `whisper\ggml-vulkan.dll` aus dem offiziellen Vulkan-Paket von llama.cpp b11429 = v0.6.0 (unverändert, gleicher ggml-Stand, MIT-Lizenz). https://github.com/ggml-org/whisper.cpp
- **oauth2** (Anmeldung bei Microsoft für den OneNote-Export) – © Alex Crichton, Florin Lipan, David A. Ramos und Mitwirkende, MIT oder Apache-2.0. https://github.com/ramosbugs/oauth2-rs
- **keyring-core** und **windows-native-keyring-store** (Windows-Anmeldeinformationsverwaltung) – © Daniel Brotsky und Mitwirkende, MIT oder Apache-2.0. https://github.com/open-source-cooperative/keyring-rs
- **docx-rs** (Word-Export) – © bokuweb, MIT-Lizenz. https://github.com/bokuweb/docx-rs
- **Sprachprobe für die Prüfung importierter Modelle** – Ausschnitt aus der Antrittsrede von John F. Kennedy (1961), gemeinfrei als Werk der US-Bundesregierung; Datei `samples/jfk.wav` aus dem whisper.cpp-Projekt.

## Modelle, die die App auf Wunsch herunterlädt

- **primeline Parakeet** – © primeline AI, basierend auf NVIDIA Parakeet-TDT, CC-BY-4.0. ONNX-Export: OpenVoiceOS. https://huggingface.co/primeline/parakeet-primeline · https://huggingface.co/OpenVoiceOS/primeline-parakeet-onnx
- **pyannote segmentation-3.0** – © CNRS, Hervé Bredin und Mitwirkende, MIT-Lizenz. ONNX-Export: k2-fsa/sherpa-onnx. https://huggingface.co/pyannote/segmentation-3.0
- **CAM++ (3D-Speaker, zh/en common advanced)** – © Alibaba DAMO Academy, Apache-2.0. ONNX-Export: k2-fsa/sherpa-onnx. https://www.modelscope.cn/models/iic/speech_campplus_sv_zh_en_16k-common_advanced
- **Qwen3.5-4B** – © Alibaba Cloud, Apache-2.0. GGUF-Export: unsloth. https://huggingface.co/unsloth/Qwen3.5-4B-GGUF
- **NVIDIA Parakeet TDT 0.6B v3** – © NVIDIA, CC-BY-4.0. ONNX-Export: istupakov. https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3 · https://huggingface.co/istupakov/parakeet-tdt-0.6b-v3-onnx
- **Whisper large-v3-turbo** – © OpenAI, MIT-Lizenz. GGML-Export: whisper.cpp. https://huggingface.co/ggerganov/whisper.cpp
- **Gemma 4 E4B** – © Google, Apache-2.0. GGUF-Export: unsloth. https://huggingface.co/unsloth/gemma-4-E4B-it-GGUF

Für selbst importierte Modelle gilt die Lizenz, die beim Import angegeben wurde; sie steht im Manifest des Modells und im Bereich „Modelle“.
