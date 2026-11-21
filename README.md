# 🧠 Guia de Estudos: Tópicos Avançados em Engenharia Social

Este repositório documenta os principais conceitos, técnicas, princípios psicológicos e estratégias de defesa abordados no módulo de **Engenharia Social**, compreendendo a exploração do "fator humano" como o vetor mais crítico na segurança da informação.

---

## 🎯 1. O que é Engenharia Social?

Engenharia Social é a arte de manipular pessoas para que realizem ações voluntárias ou divulguem informações confidenciais (credenciais, dados bancários, acessos internos), explorando vieses cognitivos e falhas comportamentais em vez de vulnerabilidades de software.

> *"O fator humano é frequentemente considerado o elo mais vulnerável da cadeia de segurança (The Human Element)."*

---

## 🎭 2. Gatilhos Psicológicos Universais (Princípios de Cialdini)

Os invasores utilizam táticas de persuasão psicológica para desarmar a cautela da vítima:

| Gatilho | Como funciona o ataque | Exemplo Prático |
|---|---|---|
| **Autoridade** | Fingir ser alguém de cargo superior, auditor ou polícia. | *"Aqui é da Diretoria de TI, preciso do seu token agora."* |
| **Urgência / Medo** | Criar pressão de tempo para impedir o raciocínio lógico. | *"Sua conta será bloqueada em 30 minutos se não atualizar."* |
| **Escassez** | Simular oportunidades únicas ou restritas. | *"Últimas 5 vagas para o bônus corporativo neste link."* |
| **Reciprocidade** | Oferecer uma ajuda falsa para exigir algo em troca. | *"Resolvi seu problema no sistema, só me confirme sua senha."* |
| **Afeição / Simpatia** | Construir rapport e amizade antes de pedir o favor malicioso. | Abordagens amigáveis em redes sociais (LinkedIn/WhatsApp). |
| **Consenso / Prova Social** | Dizer que outros já fizeram o mesmo para validar a ação. | *"Todo o departamento financeiro já preencheu este formulário."* |

---

## 🚨 3. Principais Técnicas e Vetores de Ataque

### Digitais / Comunicação
* **Phishing Genérico:** Disparos massivos por e-mail com iscas comuns.
* **Spear Phishing:** Ataque altamente customizado para uma vítima ou empresa específica (baseado em OSINT).
* **Whaling:** Phishing direcionado ao topo da hierarquia (CEOs, Diretores, membros da diretoria).
* **Vishing (Voice Phishing):** Golpes via chamadas telefônicas persuasivas (muitas vezes com clonagem de voz por IA).
* **Smishing (SMS Phishing):** Mensagens de texto com links maliciosos simulando bancos ou transportadoras.
* **Pretexting:** Criação de um pretexto elaborado e convincente para justificar a solicitação de dados confidenciais.

### Físicos / Presenciais
* **Tailgating (Piggybacking):** Aproveitar a porta aberta por um colaborador autorizado para entrar em áreas restritas.
* **Shoulder Surfing:** Espiar a tela ou o teclado de alguém para capturar senhas ou dados sensíveis.
* **Baiting (Isca Digital):** Deixar pendrives propositalmente infectados em estacionamentos ou recepções esperando alguém plugar.
* **Dumpster Diving:** Vasculhar lixo físico em busca de documentos impressos não triturados com senhas, relatórios ou dados de clientes.

---

## 🛡️ 4. Mecanismos de Defesa e Mitigação

Técnicas puramente de software não são suficientes contra engenharia social. A defesa exige um tripé:

1. **Cultura de Segurança e Treinamento Contínuo:**
   * Campanhas periódicas de simulação controlada de phishing.
   * Não punir quem clica, mas capacitar e educar.
2. **Políticas Claras e Processos Verificáveis:**
   * Regra de "Confirmação por Segundo Canal" (ex: se o diretor pedir transferência urgente por WhatsApp, ligue no ramal oficial dele para confirmar).
   * Uso de crachás obrigatórios e política de "Porta Fechada".
   * Política de mesa limpa (*Clean Desk Policy*) e trituração de papel.
3. **Controles Técnicos Complementares:**
   * Autenticação multifator (MFA/2FA) resistente a phishing (ex: chaves FIDO2/WebAuthn).
   * Filtros avançados de e-mail (SPF, DKIM, DMARC e antispam com IA).
   * Desativação de portas USB em computadores corporativos.

---

## 💡 5. Conexão com o Mercado
O profissional de segurança moderno não atua apenas como "caçador de bugs", mas como facilitador de **Conscientização em Segurança (Security Awareness)**, área em alta demanda dentro de governança e Blue Teams.
