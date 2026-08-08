# Log-classification-system---AI-based
# AI-Powered Hybrid Log Classification System

An AI-driven log classification system designed to automatically categorize application and system logs using a hybrid combination of rule-based classification, semantic machine learning, and Large Language Models (LLMs).

## Overview

Modern applications generate thousands of log messages containing errors, warnings, system events, and operational information. Manually analyzing these logs can be time-consuming and difficult to scale.

This project provides an automated classification pipeline that combines multiple approaches to identify and categorize log messages efficiently.

### Classification Pipeline

```text
                         Log Message
                              |
                              v
                    +-------------------+
                    | Log Classification |
                    +---------+---------+
                              |
              +---------------+---------------+
              |               |               |
              v               v               v
        Regex Engine    Transformer + ML    LLM Classifier
              |               |               |
              +---------------+---------------+
                              |
                              v
                     Classification Result
