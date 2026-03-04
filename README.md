# Hi, I'm Bowen 👋

I'm a Machine Learning Engineer based in Toronto, Canada, focused on taking models from notebooks to **production** – especially in recommendation systems, search, and LLM-powered applications. I care about clean infrastructure, observability, and building systems that are reliable and maintainable.

- 🔭 Currently working on:  
  - Two-tower recommendation systems (from training → deployment → monitoring)  
  - ML infrastructure for reliable model serving and evaluation  
  - Content and tooling that make it easier to ship ML products

- 🌱 Learning more about:  
  - Kubernetes, scalable inference, and production observability  
  - LLM applications, retrieval, and ranking  
  - How to turn side projects into real, revenue-generating products

- 🧰 Tech I use:  
  - Python, PyTorch, FastAPI  
  - TensorFlow/TFX (where it makes sense)  
  - Docker, Kubernetes, CI/CD  
  - Postgres, Redis, vector search tools

---

## Featured project: Instacart Two-Tower Recommender

**From purchase history to ranked product recommendations on a 50K+ item catalog.**

- Built a two-tower recommendation model using a distilled sentence-transformer over the Instacart dataset to generate user and item embeddings from purchase history.  
- Trained on ~1.2M interactions under tight hardware constraints, reaching solid ranking quality (e.g., NDCG@10 ≈ 0.43 after 1 epoch) while keeping inference practical for real-world use.  
- Designed the system with production in mind: containerized FastAPI service, clear interfaces for online serving, and monitoring/feedback hooks for continuous improvement.  
- Wrote an accompanying blog series walking through training, serving, and deployment of the system end-to-end.

👉 Repo: `[chen-bowen/instacart_next_order_recommendation](https://github.com/chen-bowen/instacart_next_order_recommendation)`  
👉 Model: published on Hugging Face Hub as `chenbowen184/instacart-two-tower-sbert`

---

## What I’m interested in

- Recommender systems and ranking (two-tower models, retrieval + re-ranking, embeddings)  
- ML infra: deployment, orchestration, observability, and evaluation loops  
- LLM-powered products: retrieval, summarization, and agent-like workflows that plug into production systems  
- Practical ML projects that connect directly to business value

---

## Freelance & collaboration

I’m open to:  
- Helping teams turn existing ML prototypes into production services  
- Designing recommendation or personalization systems for e-commerce, content, or marketplaces  
- Collaborating on open-source tooling for ML deployment and monitoring

If you’re working on ML infra, recsys, or a meaningful ML product, I’d love to chat.

📫 **How to reach me**  
- Email: chenbowen184@gmail.com  
- LinkedIn: https://www.linkedin.com/in/chen-bowen/
- Blog:  [Medium](https://medium.com/@bowenchen)

