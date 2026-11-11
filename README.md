# Hi, I'm Vamsi Kattera

AI engineer based in Glasgow, open to roles anywhere in the UK. MSc Advanced Computer Science, University of Strathclyde.

I build LLM and retrieval systems and measure them against labelled data before I call them done.

**Portfolio:** https://vamsi-kattera.github.io/portfolio/

## What I'm proud of most

**[Obelus](https://github.com/Vamsi-Kattera/Obelus)** is a contract-review tool. It finds a clause, quotes the exact text, checks that the quote really exists in the contract, and says "not found" when it can't. I measured it on 510 expert-labelled contracts and ran the final test once, on 102 contracts it had never been tuned on: it matched 59% to 75% of the experts' text, up from 22% to 46% for keyword search. One number got worse, and the README says so.
[Live demo](https://huggingface.co/spaces/VamsiKattera/obelus) · Python, FastAPI, BM25, Gemini API, Docker, GitHub Actions

**[GOV.UK RAG assistant](https://huggingface.co/spaces/VamsiKattera/govuk-rag)** answers questions about UK visas, right to work and employment rights from 129 GOV.UK pages, with citations, and refuses when the pages don't cover the question. 95% of answers judged correct on a hand-reviewed set, and all 10 out-of-scope questions refused.
Hybrid retrieval (vector search and BM25), a cross-encoder reranker, FastAPI, Streamlit, Docker

## Other projects

More are on my [portfolio](https://vamsi-kattera.github.io/portfolio/): an AI traffic-monitoring system (YOLOv8, ByteTrack, FastAPI and a React dashboard), an AI-or-real image detector, an adaptive coding practice app, and a voice assistant.

## What I work with

Python, FastAPI, Docker, GitHub Actions, pytest, Gemini and OpenAI APIs, retrieval (BM25, vector search, reranking), structured output with Pydantic, evaluation against labelled data, computer vision (YOLOv8), scikit-learn.

## How I work

- Decide how I'll measure it before I build it.
- Keep a test set I don't touch until the end.
- Read the failures before changing the model.
- Report what got worse, not only what improved.
