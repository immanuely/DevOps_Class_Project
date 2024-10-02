---
title: First Kubernetes Deployment
date: 2019-02-01
tags: ["kubernetes", "code"]
---

# First Application on Kubernetes

This guide demonstrates how to deploy your first application on Kubernetes using Kubernetes deployments.

## Prerequisites

- You should have a Kubernetes cluster set up and `kubectl` configured to interact with it.
- Ensure you have access to the `gcr.io/google-samples/kubernetes-bootcamp:v1` image.

## Step 1: Deploy the Application

Run the following command to deploy the application:

```sh
kubectl run kubernetes-bootcamp --image=gcr.io/google-samples/kubernetes-bootcamp:v1 --port=8080
