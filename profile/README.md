<p align="center">
    <img src="hhttps://raw.githubusercontent.com/Xelvo-Infra/.github/refs/heads/main/profile/img/xelvo-banner.png" alt="Xelvo" width="100%" />
</p>

<p align="center">
  <strong>Governance for Kubernetes AI Agents</strong><br>
  <sub>Policy enforcement · Simulation mode · Audit trails · Cost controls</sub>
</p>

<p align="center">
  <code>helm install xelvo xelvo/xelvo</code>
</p>

---

Deploy AI agents as CRDs. Enforce what they can do. See what they *would* do before production.

```yaml
apiVersion: xelvo.io/v1alpha1
kind: Agent
spec:
  mode: simulate
  policy: triage-policy
```

**Three modes, zero risk:**

| Mode | Behavior |
|------|----------|
| `observe` | Forward everything, log what policy *would* do |
| `simulate` | Return mock responses, audit "would-have-done" |
| `enforce` | Policy enforced — allow or deny |

---

<sub>Open source · Go · Kubernetes-native · MCP protocol</sub>
