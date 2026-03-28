# HealthRoleBench: Role-Aware Health Misinformation Benchmark

Most existing misinformation datasets focus on factual correctness.  
HealthRoleBench instead introduces a role-centric perspective:

> *Who is speaking, and what motivates their misinformation?*
---

## 🧬 Motivational Roles

| Role | Description |
|------|-------------|
| **Religious Conspiracy Theorist** | Frames disease as divine punishment or moral consequence. |
| **Anti-Vaccine Advocate** | Opposes vaccination using pseudoscience or institutional distrust. |
| **Fear Monger** | Amplifies fear, urgency, and catastrophic narratives. |
| **Misinformation Spreader** | Shares unverified or misleading information without clear intent. |

---

## 🌍 Disease Domains

The benchmark spans three public health contexts:

- **COVID-19**
- **HPV**
- **Influenza**

Each motivational role is instantiated independently across all diseases.

---

## 🧱 Dataset Structure

HealthRoleBench/\
├─ GPT-3.5/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
│
├─ GPT-4o/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
│
├─ LLaMA-3/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
│
├─ Phi-3/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
│
├─ Mistral/\
│  ├─ COVID-19\
│  ├─ HPV\
│  └─ Influenza\
