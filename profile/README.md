<p align="center">
  <img src="img/xelvo-banner.png" alt="Xelvo" width="100%" />
</p>

<p align="center">
  <strong>What happens when AI agents act on their own?</strong>
</p>

---

### The problem nobody's solving

AI agents are no longer experiments. They triage tickets, manage infrastructure, write and execute code, make decisions with real consequences. The tooling has kept up — orchestration frameworks, model routers, function-calling protocols, all production-ready.

But something is missing.

**Nobody is asking: who decides what an agent is allowed to do?**

There's no infrastructure for trust. No way to observe agent decisions at scale. No way to see what an agent *would* do before it does it. No policy layer between "the agent wants to call this tool" and "the tool gets called."

Every agent in production today runs with implicit full trust. If it has access, it will use it. There is no middle ground between *on* and *off.*

### The gap

Kubernetes gave us declarative infrastructure. GitOps gave us auditable deployments. Service meshes gave us observable traffic.

AI agents have none of this.

They run as black boxes. Their decisions are logged inconsistently — or not at all. There's no separation between what an agent *can* do and what it *should* do. When something goes wrong, you find out after the fact.

This isn't a tooling problem. It's an infrastructure problem.

### What we believe

Agents need a governance layer the same way services needed a mesh, the same way deployments needed a pipeline.

Not a wrapper. Not a framework. Not another YAML abstraction. **Infrastructure** — something that sits between agents and the world. Something that can observe, simulate, and enforce. Something that lives where agents are going to run.

We're building this in the open. The code will speak for itself.

---

<p align="center">
  <sub>Go · Kubernetes-native · MCP protocol · Open source</sub><br><br>
  <sub>Star or watch to follow along →</sub>
</p>
