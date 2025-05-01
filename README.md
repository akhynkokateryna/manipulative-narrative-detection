# Detecting Manipulative Narratives in Social Media

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

This repository provides the code for the Bachelor thesis.

## Overview
During the 2022 Russian invasion of Ukraine, Telegram became a crucial plat- form for both information sharing and the spread of propaganda. Its speed, reach, and minimal moderation turned it into a powerful tool not only for communication but also for influence operations targeting civilians. This situation underscored the need for effective methods to detect manipulative narratives in multilingual online environments.This thesis presents one of the top-performing solutions to the UNLP 2025 Shared Task on Detecting Manipulation in Social Media. The task focuses on detecting and classifying rhetorical and stylistic manipulation techniques used to influence Ukrainian Telegram users. For the classification subtask, we fine-tuned the Gemma 2 lan- guage model with LoRA adapters and applied a second-level classifier leveraging meta-features and threshold optimization. For span detection, we employed an XLM- RoBERTa model trained for multi-target, including token binary classification. Our approach achieved 2nd place in classification and 3rd place in span detection.

## Repository structure

