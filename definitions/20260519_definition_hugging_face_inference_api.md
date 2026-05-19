---
title: 'Hugging Face Inference API'
description: 'A hosted API for running machine learning models from the Hugging Face ecosystem.'
date: 2026-05-19
author: 'Manuel Sampedro'
---

# Hugging Face Inference API

## Definition

The Hugging Face Inference API is a hosted interface for running machine
learning models through authenticated HTTP requests. Developers use it to call
tasks such as automatic speech recognition, text generation, embeddings, image
classification, and other model-backed workflows without operating the model
infrastructure themselves.

## Context and Usage

In a Daytona workspace, the Hugging Face Inference API is useful when an
application needs a reproducible development environment plus access to a
managed model endpoint. Secrets such as access tokens should stay in local
workspace environment variables, while the application code should keep model
IDs, request construction, retry behavior, and output parsing under version
control.
