```bib
@inproceedings{10.1145/3735452.3735536,
  author = {Lagudu, Guna and Sharma, Vinayak and Shrivastava, Aviral},
  title = {LUCI: Lightweight UI Command Interface},
  year = {2025},
  isbn = {9798400719219},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3735452.3735536},
  doi = {10.1145/3735452.3735536},
  abstract = {Modern embedded systems are powered by increasingly powerful hardware and are increasingly reliant on Artificial Intelligence (AI) technologies for advanced capabilities. Large Language Models (LLMs) are now being widely used to enable the next generation of human-computer interaction. While LLMs have shown impressive task orchestration capabilities, their computation complexity has limited them to run on the cloud – which introduces internet dependency and additional latency. While smaller LLMs (< 5𝐵 parameters) can run on modern embedded systems such as smartwatches and phones, their performance in UI-interaction and task orchestration remains poor. In this paper we introduce LUCI:Lightweight UI Command Interface. LUCI follows a separation of tasks structure by using a combination of LLM agents and algorithmic procedures to accomplish sub-tasks while using a high-level level LLM-Agent with rule-based checks to orchestrate the pipeline. LUCI addresses the limitations of previous In-Context learning approaches by incorporating a novel semantic information extraction mechanism that compresses the frontend code into a structured intermediate Information-Action-Field (IAF) representation. These IAF representations are then used by an Action Selection LLM. This compression allows LUCI to have a much larger effective context window along with better grounding due to the context information in IAF. Pairing our multi-agent pipeline with our IAF representations allows LUCI to achieve similar task success rates as GPT-4Von the Mind2Web benchmark, while using 2.7B parameter text-only PHI-2 model. When testing with GPT 3.5, LUCI shows a 20\% improvement in task success rates over the state-of-the-art (SOTA) on the same benchmarks.},
  booktitle = {Proceedings of the 26th ACM SIGPLAN/SIGBED International Conference on Languages, Compilers, and Tools for Embedded Systems},
  pages = {182–191},
  numpages = {10},
  keywords = {Embedded Systems, LLM, System Automation},
  location = {Seoul, Republic of Korea},
  series = {LCTES '25}
}
```