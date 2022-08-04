---
name: Build
about: issues related to builds
title: "[BUILD] *issue title*"
labels: build
assignees: ''

---

**Describe the bug**
Provide a clear and concise description of the bug/issue you are experiencing.

**Theme identification**
Before submitting your request, please review past submissions to ensure that it is not a duplicate of a known issue.

If your request has been submitted previously, please add a comment to the initial request noting that you are experiencing the same bug/issue. Most importantly, do not proceed with your submission; duplicate requests make the jobs of engineering team members more difficult, and if your request is identified as a duplicate, it will be closed.

**Urgency**
Is your issue urgent? (Y or N) – 

Urgent issues fall within one of the following categories:
- Your request is related to a perceived regression in ONNX Runtime functionality (i.e., some aspect of ONNX Runtime worked previously but is no longer functional)
- Important use cases are blocked by the bug/issue you are encountering
- You have a strict project-related deadline that you are going to miss if your request is not addressed in a timely manner

If you identify that your issue is urgent, please provide more information (e.g., the regression you are experiencing, project-related deadlines you must follow, etc.).

**System information**
For each of the following line items, provide the information listed to ensure that your request is addressed in a timely manner. If your submission is missing required information, a “triage:more-info-needed” label will be applied, and you will not receive a response from the engineering team until you have made necessary updates.

- OS Platform and Distribution (e.g., Linux Ubuntu 16.04) – Android, iOS, Windows, macOS, Jetson
- ONNX Runtime Installation (source or binary) – 
- ONNX Runtime Version – 
- API (e.g., C++, C#, Java, JavaScript, Python, Rust) – 
- Execution Provider (e.g., DirectML, CUDA, NNAPI, Nuphar, OpenVINO) – 

Provide the following additional information, if applicable:
- Python Version – 
- Visual Studio Version – 
- GCC/Compiler Version – 
- CUDA/cuDNN Version – 
- GPU Model and Memory – 

**Reproducibility**
Please provide enough information/code for someone else to reproduce the behavior. If an engineering team member cannot reproduce your request when reviewing it, a “triage:more-info-needed” label will be applied, and you will not receive a response from the engineering team until you have made necessary updates to your request.

Tools like Google Colab and GitHub Codespaces can be used to more easily share and collaborate on code. If you decide to use one of these tools, please add a link to your workspace.

Attach the ONNX model to your request (where applicable) to expedite investigation.

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Additional context**
Add any other context about the problem here.

If the issue is about a particular model, please share the model type (e.g., BERT, GPT2, Hugging Face, Longformer, T5) and details to facilitate debugging.
