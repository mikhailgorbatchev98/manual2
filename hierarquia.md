## Estrutura Organizacional e Plano de Carreira — GSA

> ### 1. Corpo de Comando e Alta Administração

*   **Alto Comando:** Instância máxima de governança e deliberação estratégica do grupamento. É responsável por traçar diretrizes macros, gerenciar o plano de carreira e responder diretamente à Secretaria de Segurança e ao Comando Geral do 1º BPM Hardline.

*   **Comando:** Autoridade executiva máxima da unidade. Responsável por definir diretrizes operacionais imediatas, homologar promoções, aplicar sanções disciplinares, tomar decisões estratégicas e garantir o cumprimento estrito da missão institucional do GSA.

*   **Sub Comando:** Estrutura de liderança intermediária e assessoria direta. Responsável por auxiliar, executar e supervisionar o cumprimento das ordens do Comando. Funciona como o elo dinâmico entre a administração superior e as equipes operacionais, garantindo que o planejamento estratégico seja convertido em ações práticas na linha de voo.

---

> ### 2. Quadro de Pilotos (Linha de Voo / Pilotagem)

*   **Aspirante a Piloto:** Operador recém-ingressado na divisão aérea, em estágio probatório e sob rigorosa avaliação de conduta. Qualquer aplicação de advertência formal resultará no desligamento compulsório e imediato do GSA.
    *   *Restrição Operacional:* Só possui autorização para decolar ou patrulhar se estiver sob a supervisão direta de um Piloto Estagiário (ou patente superior).
      
    *   *Critério de Ascensão:* Apresentar registro audiovisual (clipe) contendo no mínimo 4 minutos de operação contínua, onde comprove proficiência técnica ao modular uma QRU de acompanhamento tático, ou em cenário de Código 5 (COD5), exercendo a função de piloto do GSA com manutenção ideal de órbita para linha de visão do atirador.

*   **Piloto Estagiário:** Membro efetivado no quadro oficial de aviação. Possui a atribuição técnica de instruir e monitorar os Aspirantes, sendo responsável por redigir relatórios de desempenho e feedbacks para a validação dos Veteranos.
    *   *Critério de Ascensão:* Demonstrar proatividade contínua e assiduidade na escala de serviço.
    
*   **Piloto Oficial:** Operador com plena autonomia de voo. Assume a responsabilidade técnica e doutrinária sobre a conduta de Aspirantes e Pilotos Estagiários, atuando como mentor para sanar dúvidas procedimentais e corrigir falhas de manobra em campo.
  
    *   *Critério de Ascensão:* Alto índice de proatividade, domínio absoluto dos POPs e capacidade comprovada de atendimento a todas as demandas do Batalhão (operações de busca, resgate, interceptações e combate de alta intensidade).
   
*   **Piloto Sênior:** Piloto de alta performance tática. Exerce a liderança operacional das patentes subalternas e detém prioridade absoluta no comando do manche em incursões de alto risco, intervenções com emprego de fogo e cenários críticos de COD5.
  
*   **Piloto Veterano:** Oficial de elevada senioridade aérea. Responsável por supervisionar a disciplina geral da linha de voo e exercer funções de gestão administrativa junto ao Comando do GSA.

---

> ### 3. Quadro de Operadores (Atiradores e Tripulação Operacional)

*   **Aspirante Operador:** Tripulante em período de formação e avaliação técnico-comportamental estrita. A aplicação de qualquer penalidade acarreta em sua remoção imediata da unidade.
    *   *Restrição Operacional:* Só poderá compor tripulação para patrulhamento se a aeronave estiver sob o comando de um Piloto Estagiário ou patente superior.
      
    *   *Critério de Ascensão:* Apresentar registro audiovisual (clipe) com tempo mínimo de 4 minutos em cenário real de COD5, comprovando atuação embarcada na função de operador do GSA, efetuando disparos de precisão e contenção tática com alinhamento correto.
*   **Tripulante Operacional:** Combatente efetivado na equipe de solo e ar do GSA. Incumbido de orientar e avaliar o desempenho técnico dos Aspirantes Operadores, repassando relatórios periódicos de proficiência aos Veteranos.

    *   *Critério de Ascensão:* Demonstração de conduta proativa e constância operacional.
      
*   **Operador Oficial:** Combatente de elite com pleno domínio das técnicas de engajamento. Torna-se coresponsável pelo aperfeiçoamento dos Aspirantes e dos Tripulantes, agindo para mitigar erros de procedimento em combate e instruir novos atiradores.
    *   *Critério de Ascensão:* Postura proativa, conhecimento exaustivo dos protocolos institucionais e versatilidade tática para operar em qualquer ecossistema de crise (fugas, varreduras ou confrontos armados).
*   **Operador Sênior:** Especialista em balística e assalto aerotático. Detém a prioridade no acionamento da linha de fogo lateral em missões de infiltração, apoio de fogo aproximado, cenários de alto risco e eventos sob Código 5 (COD5).
*   **Operador Veterano:** Tripulante Master da divisão. Encarregado da fiscalização doutrinária de todas as praças operacionais inferiores, acumulando funções de planejamento tático e rotinas administrativas junto ao Comando.

 🏛️ CADEIA DE COMANDO E HIERARQUIA OPERACIONAL

O Grupamento de Sistemas Aerotáticos segue uma estrutura hierárquica rígida e bem definida, garantindo a fluidez da comunicação e o respeito à doutrina tanto em solo quanto na linha de voo.

---

```mermaid
graph LR
    %% Configuração de Estilos das Caixas
    classDef altoComando fill:#1a4a75,stroke:#fff,stroke-width:2px,color:#fff;
    classDef comando fill:#2a5d8c,stroke:#fff,stroke-width:2px,color:#fff;
    classDef subComando fill:#3b70a3,stroke:#fff,stroke-width:2px,color:#fff;
    classDef quadros fill:#222,stroke:#f0a500,stroke-width:2px,color:#fff;
    classDef cargo fill:#2d3748,stroke:#718096,stroke-width:1px,color:#fff;

    %% Estrutura Principal de Comando
    ALTO["<b>[ ALTO COMANDO ]</b><br>Instância Máxima"] --> COMANDO
    COMANDO["<b>[ COMANDO ]</b><br>Diretrizes e Decisões"] --> SUB
    SUB["<b>[ SUB COMANDO ]</b><br>Elo Voo e Solo"] --> Q_PILOTOS
    SUB --> Q_OPERADORES

    %% Subgráfico do Quadro de Pilotos
    subgraph P ["🕹️ LINHA DE VOO (Ordem de Antiguidade: Maior para Menor)"]
        Q_PILOTOS["<b>QUADRO DE PILOTOS</b>"] --> P1["🏅 Piloto Veterano"]
        P1 --> P2["🎖️ Piloto Sênior"]
        P2 --> P3["👮 Piloto Oficial"]
        P3 --> P4["🛩️ Piloto Estagiário"]
        P4 --> P5["⚠️ Aspirante a Piloto *"]
    end

    %% Subgráfico do Quadro de Operadores
    subgraph O ["🎯 TRIPULAÇÃO (Ordem de Antiguidade: Maior para Menor)"]
        Q_OPERADORES["<b>QUADRO DE OPERADORES</b>"] --> O1["🏅 Operador Veterano"]
        O1 --> O2["🎖️ Operador Sênior"]
        O2 --> O3["👮 Operador Oficial"]
        O3 --> O4["🦅 Tripulante Operacional"]
        O4 --> O5["⚠️ Aspirante Operador *"]
    end

    %% Aplicando Estilos
    class ALTO altoComando;
    class COMANDO comando;
    class SUB subComando;
    class Q_PILOTOS,Q_OPERADORES quadros;
    class P1,P2,P3,P4,P5,O1,O2,O3,O4,O5 cargo;
