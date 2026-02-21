# Realtime Voice AI

Real-time voice AI pipeline using **OpenAI Realtime API** + **WebRTC** with <200ms latency.

## Features
- Voice Activity Detection (Silero VAD)
- Real-time speech-to-text (Whisper streaming)
- LLM response generation (GPT-4o Realtime)
- Text-to-speech (OpenAI TTS + ElevenLabs fallback)
- Sentiment analysis on conversations
- Speaker diarization

## Stack
Python · WebRTC · FastAPI · WebSockets · OpenAI Realtime API · Redis

## Latency
- End-to-end: ~180ms avg
- STT: ~40ms
- LLM: ~80ms
- TTS: ~60ms