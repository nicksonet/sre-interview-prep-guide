# Site Reliability Engineer (SRE) Interview Preparation Guide

This repository is an attempt to consolidate useful resources for Site Reliability Engineer (SRE) interview preparation.

## Basics

* [What happens when you type google.com into your browser's address box and press enter?](https://github.com/alex/what-happens-when)
* [What happens when you type in ‘www.cnn.com’ in your browser?](https://syedali.net/2013/08/18/what-happens-when-you-type-in-www-cnn-com-in-your-browser)

## Linux

### Boot Process

* [An introduction to the Linux boot and startup processes](https://opensource.com/article/17/2/linux-boot-and-startup)
* [What happens when we turn on computer?](https://www.cdn.geeksforgeeks.org/what-happens-when-we-turn-on-computer)
* [What happens when we turn on computer?](https://leetcode.com/discuss/interview-question/125107/What-happens-when-we-turn-on-computer)
* [From Power up to login prompt](http://www.scott-a-s.com/files/linux_boot.pdf)

### Filesystem

* [Understanding Inodes](https://syedali.net/2015/02/08/understanding-inodes)
* [Understand UNIX / Linux Inodes Basics with Examples](https://www.thegeekstuff.com/2012/01/linux-inodes)
* [Understanding proc filesystem](https://syedali.net/2013/08/20/understanding-proc-filesystem)
* [Common Mount Options](https://syedali.net/2015/01/06/common-mount-options)
* [Understanding Linux filesystems: ext4 and beyond](https://opensource.com/article/18/4/ext4-filesystem)

### Kernel

* [Explain the basics of Linux kernel](http://learnlinuxconcepts.blogspot.com/2014/03/explain-basics-of-linux-kernel.html)
* [Kernel Space and User Space](http://learnlinuxconcepts.blogspot.com/2014/02/kernel-space-and-user-space.html)
* [Linux Kernel Process Management](http://learnlinuxconcepts.blogspot.com/2014/03/process-management.html)
* [Linux Addressing](http://learnlinuxconcepts.blogspot.com/2014/02/linux-addressing.html)
* [Linux Kernel Memory Management](http://learnlinuxconcepts.blogspot.com/2014/02/linux-memory-management.html)
* [STACK AND HEAP](http://learnlinuxconcepts.blogspot.com/2014/02/stack-and-heap.html)
* [Paging and Segmentation](http://learnlinuxconcepts.blogspot.com/2014/02/paging-and-segmentation.html)
* [Linux Kernel System Calls](http://learnlinuxconcepts.blogspot.com/2014/02/system-calls.html)
* [The Virtual Filesystem](http://learnlinuxconcepts.blogspot.com/2014/10/the-virtual-filesystem.html)
* [Concurrency and Race Conditions](http://learnlinuxconcepts.blogspot.com/2014/07/concurrency-and-race-conditions.html)
* [Memory Leak](https://stackoverflow.com/questions/312069/the-best-memory-leak-definition)
* [What is a kernel Panic?](http://learnlinuxconcepts.blogspot.com/2014/07/what-is-kernel-panic.html)

### Troubleshooting

* [Linux troubleshooting tools](https://syedali.net/2013/08/20/linux-troubleshooting-tools)
* [Linux Performance Analysis in 60,000 Milliseconds](https://medium.com/netflix-techblog/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)

## Networking

* [Network protocols for anyone who knows a programming language](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=97d3ba4c24d21147)
* [Introduction to Linux interfaces for virtual networking](https://developers.redhat.com/blog/2018/10/22/introduction-to-linux-interfaces-for-virtual-networking)
* [Multi-tier load-balancing with Linux](https://vincent.bernat.ch/en/blog/2018-multi-tier-loadbalancer)
* [Introduction to modern network load balancing and proxying](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236)
* [Load Balancing Algorithms](https://syedali.net/2013/08/22/load-balancing-algorithms)

## Containers

* [Introduction to Docker and Containers](http://container.training/intro-selfpaced.yml.html)
* [Containers Patterns](https://l0rd.github.io/containerspatterns)
* [Docker Container Anti Patterns](http://blog.arungupta.me/docker-container-anti-patterns)

## Kubernetes

* [Deploying and Scaling Microservices with Docker and Kubernetes](http://container.training/kube-selfpaced.yml.html)
* [What happens when ... Kubernetes edition!](https://github.com/jamiehannaford/what-happens-when-k8s/blob/master/README.md)
* [Kubernetes Production Patterns](https://github.com/gravitational/workshop/blob/master/k8sprod.md)

## Infrastructure as code / Configuration management

* [Terraform](https://learn.hashicorp.com/terraform)
* [Ansible](https://github.com/leucos/ansible-tuto)

## CI/CD

* [Pattern and anti-pattern CI/CD](https://www.gronau-it-cloud-computing.de/pattern-and-anti-pattern-cicd)
* [Six Strategies for Application Deployment](https://medium.com/@joaogabriellima/six-strategies-for-application-deployment-351579f7aa62)

## Programming

### Go (Golang)

* [A tour of Go](https://tour.golang.org)
* [Go by Example](https://gobyexample.com)
* [Getting up and running with Go](http://www.golangprograms.com)
* [Effective Go](https://golang.org/doc/effective_go.html)
* [Go Design Patterns](https://github.com/tmrts/go-patterns)
* [Go Memory Management](https://povilasv.me/go-memory-management)

### Big O Notation, Algorithms and Data Structures

* [AlgoExperts](https://www.algoexpert.io)
* [Hacking a Google Interview – Handout 1](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_1.pdf)
* [Hacking a Google Interview – Handout 2](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_2.pdf)
* [Hacking a Google Interview – Handout 3](http://courses.csail.mit.edu/iap/interview/Hacking_a_Google_Interview_Handout_3.pdf)

## AI/ML Patterns & Infrastructure

### AI/ML Design Patterns

* [Machine Learning Design Patterns (O'Reilly)](https://www.oreilly.com/library/view/machine-learning-design/9781098115777/)
* [AI Design Patterns — Sam Witteveen (GitHub)](https://github.com/samwit/ai-design-patterns)
* [Google Cloud ML Design Patterns](https://cloud.google.com/architecture/ml-design-patterns)
* [Emerging Architectures for LLM Applications (a16z)](https://a16z.com/emerging-architectures-for-llm-applications/)

### MLOps & Model Serving

* [MLOps: Continuous delivery and automation pipelines in ML (Google)](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning)
* [Made With ML — MLOps Course](https://madewithml.com/)
* [Serving ML Models at Scale — Lessons Learned (Uber)](https://www.uber.com/blog/scaling-michelangelo/)
* [BentoML: Unified Model Serving Framework](https://docs.bentoml.com)
* [MLflow — An open source platform for the ML lifecycle](https://mlflow.org/docs/latest/index.html)

### LLM Deployment & Inference Patterns

* [LLM Inference Performance Engineering (Databricks)](https://www.databricks.com/blog/llm-inference-performance-engineering-best-practices)
* [vLLM: Easy, Fast, and Cheap LLM Serving](https://docs.vllm.ai)
* [Ollama — Run LLMs Locally](https://ollama.com)
* [RAG (Retrieval-Augmented Generation) Pattern Overview (AWS)](https://docs.aws.amazon.com/sagemaker/latest/dg/jumpstart-foundation-models-customize-rag.html)
* [Patterns for Building LLM-based Systems & Products](https://eugeneyan.com/writing/llm-patterns/)

### AI Infrastructure & GPU Management

* [NVIDIA GPU Operator for Kubernetes](https://docs.nvidia.com/datacenter/cloud-native/gpu-operator/latest/overview.html)
* [Run:ai — GPU Orchestration & Scheduling](https://www.run.ai/guides/gpu-architecture)
* [Training Large Language Models on GPU Clusters (Hugging Face)](https://huggingface.co/docs/transformers/perf_train_gpu_many)
* [Kubernetes for ML Workloads (Kubeflow)](https://www.kubeflow.org/docs/)

### AI Observability & Monitoring

* [Monitoring ML Models in Production (Google SRE)](https://sre.google/resources/practices-and-processes/evaluating-where-sre-intervenes/)
* [Evidently AI — ML Monitoring & Observability](https://docs.evidentlyai.com)
* [Arize AI — ML Observability Platform](https://docs.arize.com/arize)
* [Fiddler AI — Model Performance Management](https://docs.fiddler.ai)
* [Prometheus Metrics for ML Model Monitoring](https://prometheus.io/docs/practices/instrumentation/)

### AI Safety & Responsible AI

* [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
* [NIST AI Risk Management Framework](https://www.nist.gov/artificial-intelligence/executive-order-safe-secure-and-trustworthy-artificial-intelligence)
* [Google Responsible AI Practices](https://ai.google/responsibility/responsible-ai-practices/)
* [Prompt Injection and LLM Security (OWASP)](https://owasp.org/www-project-top-10-for-large-language-model-applications/)

## System design

* The most useful course: [Grokking the System Design Interview](https://www.educative.io/collection/5668639101419520/5649050225344512)
* [The System Design Primer](https://github.com/donnemartin/system-design-primer)
* [Crack the System Design Interview](https://www.puncsky.com/blog/2016/02/14/crack-the-system-design-interview)
* [System design interview for IT companies](https://github.com/checkcheckzz/system-design-interview)
* [Web Architecture 101](https://engineering.videoblocks.com/web-architecture-101-a3224e126947)
* [What's in a Production Web Application?](https://stephenmann.io/post/whats-in-a-production-web-application)

## Monitoring

* [SLOs & You: A Guide To Service Level Objectives](https://www.circonus.com/2018/07/a-guide-to-service-level-objectives)

## Processes

* [Incident Response](https://response.pagerduty.com)
* [Postmortems](https://postmortems.pagerduty.com)

## Interview

### SRE interview process

* [How to hire talent](https://syedali.net/2014/04/01/how-to-hire-talent)
* [Recruitment process for a Google job (SRE, Site Reliability Engineer)](http://lambda-startup.com/recruitment-process-for-a-google-job-sre-site-reliability-engineer)

### Interview Questions

* [A collection of questions to practice with for SRE interviews](https://github.com/michael-kehoe/sre-interview)
* [SRE Interview Questions](https://syedali.net/engineer-interview-questions)
* [Sysadmin Test Questions](https://github.com/trimstray/test-your-sysadmin-skills)
* [Kubernetes job interview questions](https://enterprisersproject.com/article/2019/2/kubernetes-job-interview-questions-how-prepare)

### AI/ML Interview Questions

* [Machine Learning Systems Design (Chip Huyen)](https://github.com/chiphuyen/machine-learning-systems-design)
* [MLOps Interview Questions & Answers](https://mlstack.cafe/blog/mlops-interview-questions)
* [LLM Interview Questions for Engineers](https://www.datacamp.com/blog/top-llm-interview-questions)

### Blogposts

* [SRE Interviews in Silicon Valley](http://blog.marc-seeger.de/2015/05/01/sre-interviews-in-silicon-valley)
* [Preparing the SRE interview](https://blog.balthazar-rouberol.com/preparing-the-sre-interview)
* [How to Get Into SRE](https://blog.alicegoldfuss.com/how-to-get-into-sre)

## Books

### SRE books

* [Site Reliability Engineering](https://landing.google.com/sre/sre-book/toc/index.html)
* [The Site Reliability Workbook](https://landing.google.com/sre/workbook/toc/)
* [Seeking SRE](https://books.google.ru/books?id=tmhqDwAAQBAJ)

### Linux

* [Linux Kernel Development (3rd Edition)](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468)
* [UNIX and Linux System Administration Handbook (5th Edition)](https://www.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0134277554)
* [Linux Pocket Guide, 3rd Edition](http://shop.oreilly.com/product/0636920040927.do)

### AI/ML

* [Designing Machine Learning Systems (Chip Huyen)](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)
* [Building LLM Powered Applications (Valentina Alto)](https://www.packtpub.com/product/building-llm-powered-applications/9781835462317)
* [Machine Learning Engineering (Andriy Burkov)](http://www.mlebook.com/wiki)

### Networking

* [TCP/IP Illustrated, Volume 1](https://www.amazon.com/TCP-Illustrated-Protocols-Addison-Wesley-Professional/dp/0321336313)

## Courses

* [Site Reliability Engineering: Measuring and Managing Reliability](https://www.coursera.org/learn/site-reliability-engineering-slos)
* [Machine Learning Engineering for Production (MLOps) — Andrew Ng (Coursera)](https://www.coursera.org/specializations/machine-learning-engineering-for-production-mlops)
* [Full Stack LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/)
* [Stanford CS 329S: Machine Learning Systems Design](https://stanford-cs329s.github.io)
