---
title: First Kubernetes Deployment
date: 2019-02-01
tags: ["kubernetes", "code"]
---

# Aplikasi Pertama di Kubernetes Menggunakan Kubernetes Deployments

Panduan ini menunjukkan cara menjalankan aplikasi pertama di Kubernetes dengan menggunakan Kubernetes deployments.

<!--more-->

## Jalankan Deployment

Jalankan perintah berikut untuk membuat deployment:

```bash
kubectl run kubernetes-bootcamp --image=gcr.io/google-samples/kubernetes-bootcamp:v1 --port=8080
