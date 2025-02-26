# Chall - AI Leaky Relu

> A difficult challenge that mixes reverse engineering and AI.

## Type

- [ ] **OFF**line
- [X] **ON**line

## Designer(s)

- Hugo Kermabon

## Description

In this challenge, participants are presented with a weird neural network model source code. The model uses a lot of a different activation functions all based on ReLU, and variations. At the same time, participants can upload a set of weights for the model on a webserver, which then executes the model on a set of input.
The goal is to leak the hidden inputs. To that end, participants have to reverse engineering how the model works, upload specific weights, so that the output of the model is a perfect reflection of the output. Then, they can leak the input of the model, which eventually contains the flag.

**IMPORTANT:** This description will **NOT** be shared with participants.

## Category(ies)

- `re`
- `ai`
