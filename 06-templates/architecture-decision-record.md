# ADR-[NÚMERO] — [TÍTULO DA DECISÃO]

**Status:** [Proposed | Accepted | Deprecated | Superseded by ADR-XXX]  
**Date:** [DATA]  
**Deciders:** [Lista de pessoas envolvidas na decisão]  
**Tags:** [ex: cloud, security, architecture, infrastructure]

---

## Context

> Descreva o problema ou situação que motivou esta decisão. Inclua o contexto técnico, de negócio ou regulatório relevante. Seja objetivo — 3 a 5 parágrafos no máximo.

[Exemplo: A organização está migrando workloads críticos para cloud. Precisamos definir a estratégia de autenticação para sistemas SaaS e IaaS de forma centralizada, garantindo conformidade com políticas de acesso e requisitos LGPD.]

---

## Decision

> Descreva a decisão tomada de forma clara e direta.

**Decidimos:** [ex: Implementar SSO centralizado via Azure Active Directory com MFA obrigatório para todos os acessos a sistemas críticos, integrando via SAML 2.0 / OIDC.]

---

## Options Considered

### Option A — [Nome da opção] ✅ **(Chosen)**

**Description:** [Descrição da opção]

**Pros:**
- [Pro 1]
- [Pro 2]

**Cons:**
- [Con 1]
- [Con 2]

**Cost estimate:** [ex: Incluído no licenciamento M365 existente]

---

### Option B — [Nome da opção]

**Description:** [Descrição da opção]

**Pros:**
- [Pro 1]

**Cons:**
- [Con 1]
- [Razão pela qual foi descartada]

**Cost estimate:** [ex: R$ XX,XXX/ano adicional]

---

### Option C — [Nome da opção]

**Description:** [Descrição da opção]

**Pros / Cons / Reason rejected:** [Breve justificativa]

---

## Consequences

### Positive
- [ex: Reduz superfície de ataque — credenciais únicas gerenciadas centralmente]
- [ex: Facilita onboarding e offboarding — acesso revogado em único ponto]
- [ex: Auditoria centralizada de acessos]

### Negative / Trade-offs
- [ex: Dependência do Azure AD — plano de continuidade necessário]
- [ex: Esforço de integração para sistemas legados sem suporte SAML]

### Risks
- [ex: Falha no IdP paralisa acesso a todos os sistemas — mitigação: contas de break-glass documentadas]

---

## Implementation Notes

- [ex: Fase 1: Sistemas críticos (ERP, financeiro) — Q1 2026]
- [ex: Fase 2: Sistemas de suporte — Q2 2026]
- [ex: Documentar contas de emergência (break-glass) em cofre físico seguro]
- [ex: Validar compatibilidade com sistemas legados antes da migração]

---

## Related Documents

- [Link para política de acesso]
- [Link para arquitetura de referência]
- [ADR relacionado]

---

## Review

This ADR should be reviewed if:
- A significant change occurs in the cloud strategy
- A security incident related to IAM is identified
- A new regulatory requirement changes the compliance posture

**Next review date:** [DATA]
