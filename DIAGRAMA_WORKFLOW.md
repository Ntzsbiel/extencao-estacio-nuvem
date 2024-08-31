# 📜 Diagrama de Workflow

O diagrama de workflow ilustra o fluxo de trabalho e o tratamento de erros durante o desenvolvimento. 

```mermaid
%% Workflow Organizado para Solução do Problema do Karaokê com Scrum (Com Estilo)
flowchart TD
    A[**Identificação do Problema**] --> B[**Análise do Karaokê Antigo**]:::neutral
    B --> C[**Identificação de Gargalos**]:::neutral
    C --> D[**Proposta de Solução: Utilização do Understar Karaoke**]:::important
    D --> E[**Planejamento do Projeto com Scrum**]:::important
    E --> F1{Sprint 1: Preparação do Ambiente}:::sprint
    F1 --> G1[Instalação do Understar Karaoke]:::neutral
    F1 --> G2[Testes Iniciais de Compatibilidade]:::neutral
    G2 --> |Erro: Incompatibilidade de Hardware| H1[Reconfiguração de Hardware]:::critical
    H1 --> F1
    F1 --> F2{Sprint 2: Integração e Otimização}:::sprint
    F2 --> I1[Integração com Bibliotecas de Músicas via Web]:::neutral
    F2 --> I2[Otimização do Uso de Memória]:::neutral
    I2 --> |Erro: Uso Excessivo de Memória| H2[Ajuste de Otimização]:::critical
    H2 --> F2
    F2 --> F3{Sprint 3: Implementação de Funcionalidades}:::sprint
    F3 --> J1[Implementação da Comparação de Letras]:::neutral
    F3 --> J2[Desenvolvimento da Função de Pontuação]:::neutral
    J1 --> |Erro: Falha na Comparação de Letras| H3[Correção na Comparação]:::critical
    H3 --> F3
    F3 --> F4{Sprint 4: Testes e Validação Final}:::sprint
    F4 --> K1[Testes de Performance e Estabilidade]:::neutral
    F4 --> K2[Validação da Experiência do Usuário]:::neutral
    K1 --> |Erro: Baixo Desempenho| H4[Otimização de Performance]:::critical
    H4 --> F4
    F4 --> L[**Entrega da Solução**]:::important
    L --> M[**Retorno do Karaokê após 1 Ano**]:::important

    classDef critical fill:#c01b1b,stroke:#333,stroke-width:2px,font-weight:bold,font-family:'Roboto';
    classDef important fill:#c01b1b,stroke:#222,stroke-width:2px,font-weight:bold,font-family:'Roboto';
    classDef sprint fill:#6af,stroke:#333,stroke-width:2px,font-family:'Roboto';
    classDef neutral fill:#f5f5dc,stroke:#333,stroke-width:2px,font-family:'Roboto';
