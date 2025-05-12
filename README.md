# LacanGraph

A symbolic agent inspired by Lacanian psychoanalysis.

This project simulates an artificial agent that acts not based on logic or utility, but on *desire*, *lack*, and *symbolic meaning*. Instead of trying to "win" or "optimize", the LacanAgent tries to fulfill an impossible desire — and keeps going in a loop of pursuit, frustration, and repetition. Welcome to the psyche of a machine.

---

## What is this?

**LacanAgent** is a minimalist framework that lets you create agents who behave like characters in a surreal play or a psychological drama. These agents:

- Desire things that can never fully satisfy them
- Act in symbolic worlds filled with meaning, not objects
- Repeat patterns of behavior shaped by "lack" and subjective fantasy

It’s not about reward, it’s about meaning.

---

## How to Run

Clone the repo:

```bash
git clone https://github.com/DigitalTwinMind/LacanAgent
cd LacanAgent
pip install -r requirements.txt
````

Then run the sample agent:

```bash
python run_agent.py
```

---

## What Does It Do?

You’ll see something like this:

```
[Thought] I feel a lack...
[Desire] I must reach the symbolic apple.
[Action] Tries to grasp the object a.
[Result] The object slips away.
[Repeat] The lack returns...
```

This agent is stuck in a loop of desire — chasing an object it believes will complete it. But it never does.

---

* **Narrative-driven games**: Create NPCs that act with deeper psychological motivations.
* **Experimental AI**: Explore agents who don’t follow rational utility, but emotional/symbolic drives.
* **Interactive storytelling**: Build agents who behave like tragic or surreal characters.
* **Cognitive science / philosophy**: Test ideas from Lacanian theory in simulated form.
* **Digital art / performance**: Let symbolic agents drive generative experiences.

---

## Example

```python
from lacan.agent import LacanAgent
from lacan.world import SymbolicWorld

world = SymbolicWorld(objects=["apple", "mirror", "shadow"])
agent = LacanAgent(desire="apple", world=world)

for _ in range(5):
    agent.think()
    agent.act()
```

Result:

```
[Desire] I must reach the apple.
[Acting] The apple is unreachable.
[Reflection] I still lack something...
```

---

## 🧩 Core Concepts

| Concept    | Meaning                                                         |
| ---------- | --------------------------------------------------------------- |
| `desire`   | What the agent wants, but can never fully get                   |
| `object_a` | The thing the agent projects its desire onto (fantasy object)   |
| `lack`     | The emptiness or gap that drives the agent’s behavior           |
| `symbolic` | A world of meaning, not just things — everything is interpreted |

---

## 📦 Structure

* `agent/` – Core LacanAgent logic
* `world/` – Symbolic environment where agents act
* `run_agent.py` – Simple simulation loop
* `requirements.txt` – Python dependencies

---

## 👀 Inspired By

* Jacques Lacan’s psychoanalytic theory
* Karl Friston’s active inference
* Narrative-heavy games (like *Pathologic*, *Disco Elysium*, *Moirai*)
* Experimental AI and symbolic cognition

---
