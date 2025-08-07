# 🧪 Guia Técnico de Testes Funcionais — Side
---

## 🎯 Objetivo

Demonstrar abordagem prática e profissional para testes funcionais em um jogo mobile tipo puzzle com mecânicas match-3. Este guia simula o pensamento aplicado antes e durante a execução dos testes, respeitando as exigências da vaga da Side.

---

## 📱 Plataformas Alvo

* Android (diversas versões e resoluções)
* iOS (iPhone/iPad)
* PC (Windows)
* Consola (Nintendo Switch)

---

## 🔍 Tipos de Teste Aplicados

* Testes Funcionais
* Testes de Compatibilidade entre dispositivos
* Testes de Interface (UI)
* Testes de Progressão e Save State
* Testes de Performance Básica
* Smoke Test e Sanity Test por build

---

## 🧩 Funcionalidades Prioritárias para Validação

* Mecânica de jogo match-3 (movimentos válidos, bloqueios, boosters)
* Sistema de energia/vidas e monetização (compras in-app simuladas)
* Animações e tempo de resposta entre ações
* Save automático (nível, moedas, boosters)
* Sistema de recompensas diárias e eventos temporários
* Traduções corretas por idioma
* Integridade de HUD (placar, moedas, corações, etc.)
* Funcionalidade offline e reconexão à internet
* Comportamento ao alternar entre apps (multitarefa)

---

## 🛠️ Ferramentas Sugeridas

* **TestRail / Xray** — Documentação de testes
* **Jira** — Gestão de bugs e tarefas
* **Google Sheets / Excel** — Registo manual de progresso e evidências
* **Charles Proxy / Postman** — Inspeção de chamadas de API (se aplicável)
* **ADB / Xcode** — Logs e testes físicos

---

## 📋 Exemplo de Caso de Teste

**Funcionalidade:** Mecânica de movimento (Match-3)

**Cenário:** Jogador realiza movimento válido que gera combinação

**Passos:**

1. Iniciar o jogo até o primeiro nível disponível
2. Realizar um movimento que alinha 3 peças iguais
3. Observar comportamento de animação, score e atualização do tabuleiro

**Resultado Esperado:**

* Peças são eliminadas
* Animação ocorre sem travamentos
* Score é incrementado corretamente
* Novas peças descem corretamente

**Ambiente:**

* Android 13, iPhone iOS 17, Switch Lite, Windows 11

---

## 🔁 Testes Multiplataforma

* Comparar tempos de carregamento entre dispositivos
* Validar se layout responsivo mantém legibilidade
* Verificar sincronia de progresso entre dispositivos (se for cross-save)
* Garantir que o HUD não sobreponha conteúdo em telas pequenas

---

## 📊 Relatórios e Evidências

A qualidade da documentação e dos relatórios é um pilar essencial no meu processo de QA. Para cada build testada, mantenho evidência estruturada e legível com base nos seguintes formatos:

* **Bug Reports (Jira)**: Capturas de tela, descrição clara do comportamento observado, passos para reprodução e ambiente afetado.
* **Relatórios de Execução (Excel ou TestRail)**: Tabela com status de cada teste (Pass/Fail/Blocked), tempo de execução, comentários e links para evidências.
* **Relatórios Visuais (PDF/Slides)**: Usados em checkpoints, com resumo dos principais bugs, áreas críticas, e sugestões de mitigação.
* **Vídeos curtos de reprodução**: Para bugs intermitentes, uso gravação de tela para auxiliar devs e PMs a compreenderem o defeito.
* **Comparativo por plataforma**: Resumo por dispositivo/sistema para destacar falhas específicas de compatibilidade.

Relatórios são entregues no fim de cada ciclo com priorização por impacto, frequência e risco.

---

## 🧮 Classificação e Priorização de Bugs

Quando um bug é identificado, o processo que sigo envolve três passos essenciais:

1. **Reprodução controlada**: Confirmo se o defeito é consistente e determinístico, tentando reproduzi-lo em diferentes dispositivos ou fluxos.

2. **Classificação por severidade**:

   * **Alta**: Impede o progresso, quebra o jogo, afeta lógica ou dados.
   * **Média**: Funcionalidade parcial ou erro visual que interfere na experiência.
   * **Baixa**: Detalhes cosméticos, pequenos erros de texto, glitches não bloqueantes.

3. **Priorização por impacto e urgência**:

   * Considero o momento do ciclo de testes, frequência do bug, visibilidade para o jogador e risco de regressão.

Esse processo ajuda a entregar relatórios claros e objetivos para a equipa de desenvolvimento e QA leads, com foco em resolver o que realmente afeta a experiência do utilizador e a qualidade final do produto.

## ⚠️ Possíveis Riscos e Edge Cases

* Softlock após movimento inválido
* Perda de progresso ao fechar app abruptamente
* Botões não responsivos em resoluções específicas
* Evento recorrente não aparece após reconexão
* UI corrompida após troca de idioma

---

## 🧠 Mentalidade de Teste

* Explorar como jogador avançado que busca falhas e inconsistências
* Observar animações quadro a quadro
* Testar padrões fora do esperado: boosters combinados, vários níveis de obstáculos, etc.
* Priorizar a experiência real do jogador, não apenas os requisitos técnicos

---

## 📎 Conclusão

Este guia reflete minha abordagem prática e direta como QA funcional, voltado para jogos mobile com foco no jogador final. Não apenas aplico boas práticas de teste, mas também compreendo como cada detalhe — desde um botão mal posicionado até a falha num fluxo de recompensa — pode afetar a experiência e retenção do utilizador.

O meu diferencial está na combinação entre raciocínio técnico, mentalidade exploratória e entrega bem documentada. Atuo com autonomia, proponho soluções e mantenho comunicação objetiva com equipas técnicas.

Tenho total disponibilidade para integrar a equipa da Side presencialmente em Braga e contribuir com consistência, atenção ao detalhe e comprometimento com a qualidade final.

---

**Artur Felipe Albuquerque Portela**  
QA Tester · Manual & Automation  
GitHub: github.com/ArturMoco  
LinkedIn: Artur Albuquerque  
Email: [arturengqa@gmail.com](mailto:arturengqa@gmail.com)
