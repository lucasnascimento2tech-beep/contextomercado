---
brain_id: KB-07-03
note_type: conceito
domain: backoffice
knowledge_status: source_grounded_synthesis
validation_status: requer_validacao_atual_quando_aplicavel
temporal_sensitivity: media
source_basis: 257_transcricoes_contextomercado
last_reviewed: 2026-09-23
priority_for_rag: 90
tags:
- dominio/backoffice
- tipo/conceito
source_ids:
- YqwTaBUX1Do
- lOvhBIPc1vA
pack_version: v1
origin_note: 06_Backoffice/Portabilidade - controlar o estado, o tempo e a exceção.md
---

# Portabilidade: controlar o estado, o tempo e a exceção

> **Camada:** interpretação estruturada do acervo. Para regras atuais, taxas, limites, exigências ou capacidades de sistemas, validar a condição vigente antes de aplicar.

O acompanhamento apresentado pela Finanto diferencia envio, análise, solicitação de saldo, retorno, retenção, pagamento ao banco anterior, averbação e integração. Quando existe refinanciamento associado, ele constitui outra parte do processo. O horário de corte e o prazo mencionados são daquela instituição e daquele momento. [[90_FONTES/CATALOGO/YqwTaBUX1Do|fonte YqwTaBUX1Do]]

Uma aula de riscos descreve a exposição quando o saldo anterior foi quitado e a operação continua aguardando averbação. Entre as hipóteses relatadas estão demora na desaverbação, alteração de margem e ocupação da margem por outra operação. A expressão “risco banco” aparece condicionada ao cumprimento de requisitos, não como proteção automática por selecionar um rótulo. [[90_FONTES/CATALOGO/lOvhBIPc1vA|fonte lOvhBIPc1vA]]

**Síntese de controle:** status sem data, responsável e próxima ação é insuficiente para distinguir espera normal de proposta abandonada. O acervo sustenta essa necessidade de acompanhamento; não fornece um SLA único para todos os bancos.

---
**Mapa relacionado:** [[00_MODELO_MENTAL/Mapa - MOC - Backoffice]]
