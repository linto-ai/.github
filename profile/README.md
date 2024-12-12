<h1 align="center">LinTO AI</h1>

<h4 align="center">Open Source Ecosystem for Transcription, Collaborative Media Management, Annotation, Live Subtitling, and Summarization</h4>

<p align="center">
  <img src="https://github.com/linto-ai/linto-studio/raw/master/doc/Studio.png" alt="LinTO AI Banner" width="600">
</p>

## Overview

LinTO AI provides a powerful suite of open-source tools for transcription, collaborative media editing, annotation, live subtitling, and summarization utilizing large language models (LLMs).

<div style="text-align: center;">
  <strong>Hosted by</strong>
  <br>
  <img src="https://labs.linagora.com/wp-content/uploads/2021/02/cropped-linagora-labs-red-blue1.png" alt="LINAGORA" width="80" style="display: inline-block; margin: 10px 0;">
  <br>
  <a href="https://studio.linto.app" target="_blank" rel="noopener noreferrer" style="font-size: 18px; text-decoration: none; color: #007bff;"><strong>Try LinTO Studio</strong></a>
</div>




## Quick Start

- **LinTO Studio**: 🎤 A media management platform offering advanced tools for transcription and collaborative media editing. Key features include:
  - **Speaker identification/diarization**: Automatically segment and identify speakers.
  - **Automatic timestamp alignment**: Synchronize transcripts with media.
  - **Collaborative editing**: Work collaboratively on media annotations and transcriptions in real-time.
  - **Summarization**: Generate concise summaries of media content using LLMs.
  - **Building and syncing subtitles**: Create and synchronize subtitles for video content with ease.
  - **Live transcription from the browser**: Record and transcribe audio directly from your browser.
  - **AI Agent for videoconferences**: A bot system that joins videoconferences to capture live audio streams for transcription and subtitling. This allows LinTO Studio to act as a powerful assistant during meetings, leveraging videoconference platforms as live audio sources.

LinTO Studio leverages our other technologies, including:
  - **LinTO-STT** for speech-to-text conversion.
  - **LinTO-Diarization** for speaker segmentation and identification.
  - **LLM-Gateway** for advanced summarization.

To deploy LinTO Studio and its associated services, use the [LinTO Deployment Tool](https://github.com/linto-ai/linto), which simplifies the setup process.

## Key Projects

- **LinTO-STT**: 🗣️ An automatic speech recognition API supporting both offline and real-time transcriptions. It accommodates models like Kaldi and Whisper and can operate as a standalone service or within a microservices infrastructure. [Learn more](https://github.com/linto-ai/linto-stt)

- **Whisper-Timestamped**: ⏱️ A multilingual automatic speech recognition tool providing word-level timestamps and confidence scores. It enhances OpenAI's Whisper models to deliver more precise transcriptions with detailed timing information. [Learn more](https://github.com/linto-ai/whisper-timestamped)

- **LLM-Gateway**: 📝 A service dedicated to rolling summarization using large language models (LLMs), enabling efficient processing and summarization of extensive textual data. [Learn more](https://github.com/linto-ai/llm-gateway)

- **LinTO-Diarization**: 🔊 A speaker diarization service that segments audio streams into homogeneous segments based on speaker identity, with capabilities for speaker identification when audio samples of known speakers are provided. [Learn more](https://github.com/linto-ai/linto-diarization)

- **WebVoiceSDK**: 🌐 A JavaScript library offering lightweight and optimized building blocks for always-listening voice-enabled applications directly in the browser. It manages various aspects of voice input, including hardware microphone handling, voice activity detection, and wake word detection. [Learn more](https://github.com/linto-ai/WebVoiceSDK)

## Get Involved

LinTO AI is committed to open-source development, ensuring our tools are accessible and adaptable, fostering innovation in business-aware media transcription and summarization. For more information or to contribute, contact us at hello@linto.ai.
