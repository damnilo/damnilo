# Danilo Nikić

Computer science student at the Faculty of Sciences, University of Novi Sad.

I work on things I can take apart: a network written line by line, a driving agent with a reward I can point at, a camera path turned into a map. The same habit shows up in the small products: a first pull request with actual steps, or a counter someone can walk to.

## What I spend time on

**Models without a framework.** A small GPT in C++ — tokenizer, tensors, transformer, training loop, checkpoints, sampling — and a CNN for the German traffic-sign benchmark, with convolution and backprop written by hand. Python handles data and the training script. pybind11 joins the two. Matrix products run as CPU loops, through cuBLAS, or through a hand-written CUDA kernel.

The GPT checkpoint is deliberately small. It continues the opening of Shakespeare and keeps the shape of a scene. It does not write a new one.

**Driving and road perception.** A Double Dueling DQN in PyTorch that learns lane following in MetaDrive, staged from straight roads to procedural maps. Separately, a monocular pipeline that places cars, people, and signs in 3D from dashcam video: detection, depth, and visual odometry, then fusion so the same object is not mapped twice.

**Products with a next step.** TypeScript and Next.js up front, Python and FastAPI behind. [FirstContrib](https://github.com/damnilo/Cursor-Hackathon) matches a beginner with a repository and turns it into a contribution plan. [NaŠalter](https://github.com/damnilo/AI4Society-Hackathon) takes a question about Serbian paperwork and returns the procedure, the documents, and the counter. Addresses come from a table, not from the model.

## Skills

[![C++, CMake, Python, PyTorch, TypeScript, Next.js, FastAPI, Docker, Linux, Git](https://skillicons.dev/icons?i=cpp,cmake,py,pytorch,ts,nextjs,fastapi,docker,linux,git&perline=5)](https://skillicons.dev)

- **Languages:** C++, Python, TypeScript, Java
- **Learning:** PyTorch, and networks written without it — convolutions, transformers, deep reinforcement learning
- **Around the model:** CMake, CUDA, pybind11, FastAPI, Docker

## Selected work

- [**GPT-2 from scratch**](https://github.com/damnilo/GPT-2-From-Scratch-Cpp) — transformer, training, and sampling in C++, plus a CUDA matmul path.
- [**Traffic signs from scratch**](https://github.com/damnilo/GTSRB-Detection-from-Scratch-Cpp) — CNN for GTSRB, including backprop, exposed to Python with pybind11.
- [**DQN driving agent**](https://github.com/damnilo/DQN-Driving-Agent) — Double Dueling DQN that learns to hold a lane in MetaDrive.
- [**Road objects in 3D**](https://github.com/damnilo/3D-Object-Perception) — one dashcam to a map of cars, people, and signs.
- [**Symptom classifier**](https://github.com/damnilo/Deploying-Disease-Prediction-Model) — a small PyTorch net behind FastAPI, packed in Docker.
- [**FirstContrib**](https://github.com/damnilo/Cursor-Hackathon) — a first open-source contribution, with the steps written out.
- [**NaŠalter**](https://github.com/damnilo/AI4Society-Hackathon) — from a question in plain language to the right counter.

## What I want to go deeper on

Larger models that I still understand because I wrote them. Kernels, not only the call into a library. Reinforcement learning where the reward matches the road. And tools that leave a person with one concrete next action.
