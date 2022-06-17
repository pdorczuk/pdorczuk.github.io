---
layout: post
title:  "Linux Commands to Show PCI DSS Compliance"
date:   2022-06-17
---
As an external auditor, one of the most frequent questions that I get from clients is "How should I provide evidence?" Ask 5 administrators this question and you will get 5 different answers. Because I want to automate everything, it makes sense to standardize on evidence requests so that I get a predictable output. I have a few limitations imposed by my work and those are, 1. I can't touch the system myself, even read-only, 2. I cannot simply provide a script to run, and 3. I can't rely on any third-party tools or libraries (jq for example). So without further ado, are the commands that I request from Linux systems during a PCI engagement.
