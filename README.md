# api
This repository contains the API for the ReadySetAI project

## runpod | 3rd party service to run the jobs

Description: _RunPod is a cloud computing platform, primarily designed for AI and machine learning applications. Our key offerings include GPU Instances, Serverless GPUs, and AI Endpoints._


* [docs main page](https://docs.runpod.io/docs)
* [api-docs](https://docs.runpod.io/reference/runpod-apis)

Example to run the job:
```bash
curl -X POST https://api.runpod.ai/v2/stable-diffusion-v1/run \
-H 'Content-Type: application/json'                             \
-H 'Authorization: Bearer xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'    \
-d '{"input": {"prompt": "a cute magical flying dog, fantasy art drawn by disney concept artists"}}'
```
