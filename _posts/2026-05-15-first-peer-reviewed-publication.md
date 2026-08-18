---
layout: post
title: Our first peer-reviewed publication as the AI/ML team at BandLab
date: 2026-05-15 09:00:00
description: "Probing Low-Level Acoustic Attribute Encoding in CLAP Audio Embeddings, accepted to DAFx 2026"
tags: research publications
categories: news
---

A proud moment for our team: our first peer-reviewed publication as the AI/ML team at BandLab Technologies, "[Probing Low-Level Acoustic Attribute Encoding in CLAP Audio Embeddings](/publications/#probing)," accepted to DAFx 2026. Congratulations to Héctor Martel - 何可拓 on leading this work from the first probing experiment to acceptance, hosted at MIT this September.

Audio foundation models like CLAP are increasingly used off the shelf across the industry, yet we often don't fully know what they encode, or what they silently discard. One finding from this paper is a good example. Several widely used models (Wav2Vec2, WavLM, MERT) don't encode loudness at all, simply due to input normalisation. If you're building products on top of these embeddings, that's the kind of thing you want to know before shipping, not after.

This paper reflects how we work: rigorous research and production engineering under one roof. The same team that ships audio features to nearly 200M creators also asks the fundamental questions, and shares the answers openly with the research community so that everyone building on these models can benefit.

The preprint is up on [arXiv](https://arxiv.org/abs/2607.03806) now, ahead of the conference this September.

More work from the team has already been accepted for publication this year, with even more submissions on the way.
