# SpeechSEC: A Unified Multi-Task Framework for Non-Autoregressive Speech Synthesis, Editing, and Continuation

## Introduction

SpeechSEC introduces an innovative multi-task framework aimed at handling speech synthesis, speech editing, and speech continuation tasks simultaneously. By dynamically adjusting input conditions, SpeechSEC not only improves speech synthesis performance in terms of speech intelligibility, audio quality, and voice preservation but also efficiently performs editing and continuation tasks using non-autoregressive techniques.





## Directory Structure Explanation

The project demo is divided into the following main parts:

- **SpeechSEC_SpeechSynthesis**: Includes samples and results for the speech synthesis task, demonstrating how SpeechSEC framework can be used to generate speech with a specific voice.
- **SpeechSEC_SpeechEditing**: This directory contains samples and results for the speech editing task, showcasing SpeechSEC's capability to make detailed edits on speech segments while maintaining coherence and clarity.
- **SpeechSEC_SpeechContinuation**: This folder showcases the application of SpeechSEC in the speech continuation task, demonstrating how to generate natural continuations of human speech based on a given segment.

## Main Contributions

- We **improve speech synthesis performance** through multi-task joint training in aspects including speech intelligibility, voice preservation, audio quality with fast speed utilizing non-autoregressive methods.
- We propose a **multi-task audio processing framework** that can efficiently accomplish high-quality speech synthesis, speech editing and speech continuation tasks in a non-autoregressive manner through a single unified model, bringing innovation to the field of audio processing.
- We verify the **adaptability** of different discretion methods of speech processing and demonstrated that the multi-task joint training method we proposed is effective for different extractors of semantic tokens and acoustic tokens which showcases the wide applicability and robustness of our method.

