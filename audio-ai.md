# Audio
## Compression
- https://github.com/facebookresearch/encodec

## Multiple Tasks
- [Speechbrain](https://github.com/speechbrain/speechbrain) A PyTorch-based Speech Toolkit for TTS, STT, etc
- [Nvidia NeMo](https://github.com/NVIDIA/NeMo) TTS, LLM, Audio Synthesis framework
- [speech-rest-api](https://github.com/askrella/speech-rest-api) for Speech-To-Text and Text-To-Speech with Whisper and Speechbrain
- [LangHelper](https://github.com/NsLearning/LangHelper) language learning through Text-to-speech + chatGPT + speech-to-text to practise speaking assessments, memorizing words and listening tests
- [Silero-models](https://github.com/snakers4/silero-models) pre-trained speech-to-text, text-to-speech and text-enhancement for ONNX, PyTorch, TensorFlow, SSML
- [AI-Waifu-Vtuber](https://github.com/ardha27/AI-Waifu-Vtuber) AI Waifu Vtuber & is a virtual streamer. Supports multiple languages and uses VoiceVox, DeepL, Whisper, Seliro TTS, and VtubeStudio, and now also supports Twitch streaming.


## Speech Recognition
- https://github.com/openai/whisper
  - [Whisper JAX implementation](https://github.com/sanchit-gandhi/whisper-jax) runs around 70x faster on CPU, GPU and TPU
  - [whisper.cpp](https://github.com/ggerganov/whisper.cpp) C/C++ port for Intel and ARM based Mac OS, ANdroid, iOS, Linux, WebAssembly, Windows, Raspberry Pi
- [ermine-ai | Whisper in the browser using transformers.js](https://github.com/vishnumenon/ermine-ai)
- [wav2vec2 dimensional emotion model](https://github.com/audeering/w2v2-how-to)
- [MeetingSummarizer](https://github.com/rajpdus/MeetingSummarizer) using Whisper and GPT3.dd
- [Facebook MMS: Speech recognition of over 1000 languages](https://github.com/facebookresearch/fairseq/tree/main/examples/mms)

## TextToSpeech
-   [tts-generation-webui](https://github.com/rsxdalv/tts-generation-webui) for all things TTS, currently supports Bark
-   [Bark](https://github.com/suno-ai/bark) transformer-based text-to-audio model by Suno. Can generate highly realistic, multilingual speech and other audio like music, background noise and simple effects
    -   [Bark-Voice-Clones](https://github.com/nikaskeba/Bark-Voice-Clones)
    -   [Bark WebUI colab notebooks](https://github.com/camenduru/bark-colab)
    -   [bark-with-voice-clone](https://github.com/serp-ai/bark-with-voice-clone)
    -   [Bark Infinity for longer audio](https://github.com/JonathanFly/bark)
    -   [Bark WebUI](https://github.com/makawy7/bark-webui))
-   [Coqui TTS | deep learning toolkit for Text-to-Speech](https://github.com/coqui-ai/TTS)
    -   [Tutorial](https://www.youtube.com/watch?v=dfmlyXHQOwE) for Coqui VITS and Whisper to automate voice cloning and [Colab notebook](https://colab.research.google.com/drive/1Swo0GH_PjjAMqYYV6He9uFaq5TQsJ7ZH?usp=sharing#scrollTo=nSrZbKCXxalg)
-   [StyleTTS implementation](https://github.com/yl4579/StyleTTS)
  -   [StyleTTS-VC](https://github.com/yl4579/StyleTTS-VC) One-Shot Voice Conversion by Knowledge Transfer from Style-Based TTS Models
-   [Vall-E and Vall-E X](https://valle-demo.github.io/), [paper](https://arxiv.org/abs/2301.02111), [code](https://github.com/enhuiz/vall-e). Zero Shot TTS preserving emotion, expression, similarity and allows language transfer
  -  [Vall-e PyTorch Implementation](https://github.com/enhuiz/vall-e) of Vall-E based on EnCodec tokenizer
  -  [Vall-E PyTorch implementation](https://github.com/lifeiteng/vall-e)
-   [NaturalSpeech implmenetation](https://github.com/heatz123/naturalspeech)
-   [IMS Toucan, TTS Toolkit from University of Stuttgart](https://github.com/digitalphonetics/ims-toucan)
-   [YourTTS | Zero Shot Multi Speaker TTS and Voice Conversion for everyone](https://github.com/Edresson/YourTTS)
-   [PaddleSpeech | Easy to use Speech Toolkit with Self Supervised learning, SOTA Streaming with punctuation, TTS, Translation etc](https://github.com/PaddlePaddle/PaddleSpeech)
-   [Tortoise TTS | Open source multi voice TTS system](https://github.com/neonbjb/tortoise-tts)
    -   [finetune guide using DLAS DL-Art-School](https://www.youtube.com/watch?v=lnIq4SFFXWs)
    -   [DL-Art-School](https://github.com/152334H/DL-Art-School) fine tuning tortoise with DLAS GUI
    -   [tortoise-tts-fast](https://github.com/152334H/tortoise-tts-fast) fast Tortoise TTS inference up to 5x. [Video tutorial](https://www.youtube.com/watch?v=8i4T5v1Fl_M)
    -   [Tortoise mrq fork for voice cloning](https://git.ecker.tech/mrq/ai-voice-cloning)
-   [piper](https://github.com/rhasspy/piper) A fast, local neural text to speech system that sounds great and is optimized for the Raspberry Pi 4. Using VITS and onnxruntime
-   [PITS](https://github.com/anonymous-pits/pits) PyTorch implementation of Variational Pitch Inference for End-to-end Pitch-controllable TTS. [hf demo](https://huggingface.co/spaces/anonymous-pits/pits), [samples](https://anonymous-pits.github.io/pits/)
-   [VoiceCloning](https://github.com/MartinMashalov/VoiceCloning) Implementing the [YourTTS paper](https://arxiv.org/abs/2112.02418) for Zero-Shot multi-speaker Attention-Based TTS using VITS approaches
  -   [VITS-Umamusume-voice-synthesizer](https://huggingface.co/spaces/1raliopunche/VITS-Umamusume-voice-synthesizer) (Multilingual Anime TTS) Including Japanese TTS, Chinese and English TTS, speakers are all anime characters.
-   [Parallel WaveGAN implementation in PyTorch](https://github.com/kan-bayashi/ParallelWaveGAN) for high quality text to speech synthesis [paper](https://github.com/kan-bayashi/ParallelWaveGAN)


## Voice Conversion

-   [voicepaw/so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) SoftVC VITS Singing Voice Conversion Fork with realtime support and greatly improved interface. Based on so-vits-svc 4.0 (v1)
    -   [Video tutorial by Nerdy Rodent](https://www.youtube.com/watch?v=tZn0lcGO5OQ)
    -   [nateraw/so-vits-svc-fork gradio app](https://github.com/nateraw/voice-cloning) for inference of so-vits-svc-fork voice models + ([training in colab](https://colab.research.google.com/github/nateraw/voice-cloning/blob/main/training_so_vits_svc_fork.ipynb) with yt downloader and audio splitter, [hf space demo](https://hf.co/spaces/nateraw/voice-cloning))
    -   [so-vits-svc-5.0](https://github.com/PlayVoice/so-vits-svc-5.0)
    -   [LoRa svc](https://github.com/PlayVoice/lora-svc)
    -   [RVC-Project](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI) simple and easy-to-use voice transformation (voice changer) web GUI based on VITS
        -   [rvc-webui](https://github.com/ddPn08/rvc-webui) Win/Mac/Linux installer and Guide for RVC-Project
    -   [w-okada/voice-changer](https://github.com/w-okada/voice-changer) supports various models: MMVC, so-vits-svc, RVC, DDSP-SVC, can work over LAN to offload processing
    -   [DDSP-SVC](https://github.com/yxlllc/DDSP-SVC) Real-time singing voice conversion based on DDSP, training and inference uses lower requirements than diff-svc and so-vits-svc
    -   [Leader board of SOTA models](https://github.com/Anjok07/ultimatevocalremovergui/issues/344) for stem separation using model ensembles in UVR
    -   [VITS GUI to load VITS text to speech models](https://github.com/CjangCjengh/MoeGoe_GUI)
    -   [Vits-fast-fine-tuning](https://github.com/Plachtaa/VITS-fast-fine-tuning) pipeline of VITS finetuning for fast speaker adaptation TTS, and many-to-many voice conversion
-   [w-okada/voice-changer | real time voice conversion using various models like MMVC, so-vits-svc, RVC, DDSP-SVC](https://github.com/w-okada/voice-changer/blob/master/README_en.md)
-   [Diff-svc](https://github.com/prophesier/diff-svc) Singing Voice Conversion via Diffusion model
  -   [FastDiff implementation| Fast Conditional Diffusion Model for High-Quality Speech Synthesis](https://github.com/Rongjiehuang/FastDiff)
  -   [Fish Diffusion](https://github.com/fishaudio/fish-diffusion) easy to understand TTS / SVS / SVC framework, can convert Diff models
-   [Auto-synced-translated-dubs](https://github.com/ThioJoe/Auto-Synced-Translated-Dubs) Youtube audio translation and dubbing pipeline using Whisper speech-to-text, Google/DeepL Translate, Azure/Google TTS
-   [Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning) abandoned project
    -   [Real-Time-Voice-Cloning v2](https://github.com/liuhaozhe6788/voice-cloning-collab) active fork of the original
-  [Raven with voice cloning 2.0](https://huggingface.co/spaces/Kevin676/Raven-with-Voice-Cloning-2.0/tree/main) by Kevin676
-  [CoMoSpeech](https://paperswithcode.com/paper/comospeech-one-step-speech-and-singing-voice) paper, consistency model distilled from a diffusion-based teacher model, enabling high-quality one-step speech and singing voice synthesis
