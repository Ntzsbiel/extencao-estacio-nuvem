# 🎤 Karaokê Modernização com UltraStar Karaoke

## 📋 Descrição do Projeto

Este projeto tem como objetivo modernizar um sistema de karaokê antigo que ocupa **900GB** de espaço em disco e causa desgaste excessivo na memória RAM, resultando em falhas constantes. Utilizando a metodologia ágil **Scrum** e a aplicação de código aberto **UltraStar Karaoke**, desenvolvemos uma solução eficiente que otimiza o uso de recursos e traz de volta a cultura do karaokê ao estabelecimento após 1 ano de inatividade.

## 📅 Plano de Trabalho

Para garantir a implementação eficaz deste projeto, detalhamos abaixo as ações a serem executadas, seus prazos e os recursos necessários.

### O que Fazer
1. **Identificação do Problema**: Analisar o sistema de karaokê atual para identificar os principais gargalos e problemas de desempenho.
2. **Proposta de Solução**: Substituir o software antigo pelo UltraStar Karaoke.
3. **Planejamento e Implementação**: Dividir o projeto em sprints utilizando Scrum, com ações específicas para preparar o ambiente, integrar as bibliotecas de músicas, otimizar o sistema, e implementar funcionalidades.
4. **Testes e Validação**: Executar testes de performance e validar a experiência do usuário.
5. **Entrega da Solução**: Implantar a solução no ambiente de produção do cliente.

### Quando Fazer
- **Início do Projeto**: Imediato
- **Conclusão das Ações**: Até **15/09**

### Como Fazer
- **Recursos Necessários**: Computador com capacidade para rodar o UltraStar Karaoke, acesso à internet para integrar com bibliotecas de músicas online, software de controle de versão (Git) para gestão do código.
- **Etapas**:
  1. **Configuração Inicial**: Instalação do UltraStar Karaoke e configuração do ambiente de teste.
  2. **Desenvolvimento em Sprints**: Divisão das tarefas em sprints para garantir uma entrega gradual e contínua.
  3. **Otimização e Testes**: Ajustes finos para otimização de recursos e testes para garantir a estabilidade do sistema.
  
### Para Quem Fazer
- **Público-Alvo**: Um microestabelecimento de cafés chamado **Café Metro**, que deseja reativar o karaokê após 1 ano de inatividade.

### Onde Fazer
- **Local**: As ações serão realizadas diretamente no **Café Metro**, garantindo que a solução seja adaptada às necessidades específicas do local.

## 🚀 Solução Proposta

O projeto consiste em substituir o software de karaokê antigo por uma solução baseada em **UltraStar Karaoke**, que acessa as bibliotecas de músicas via web, reduzindo significativamente o uso de espaço em disco e otimizando a performance. Além disso, a aplicação compara a letra da música com o que está sendo cantado e pontua o desempenho do usuário.

## 📈 Metodologia Scrum

Para garantir uma implementação ágil e organizada, utilizamos a metodologia **Scrum** dividida em quatro sprints principais:

- **Sprint 1: Preparação do Ambiente**
  - Instalação do UltraStar Karaoke.
  - Testes iniciais de compatibilidade.
  
- **Sprint 2: Integração e Otimização**
  - Integração com bibliotecas de músicas via web.
  - Otimização do uso de memória.
  
- **Sprint 3: Implementação de Funcionalidades**
  - Implementação da comparação de letras.
  - Desenvolvimento da função de pontuação.
  
- **Sprint 4: Testes e Validação Final**
  - Testes de performance e estabilidade.
  - Validação da experiência do usuário.

## 🔧 Tratamento de Erros

Durante o desenvolvimento, alguns possíveis problemas foram antecipados, incluindo:

- **Incompatibilidade de Hardware**: Reconfiguração do ambiente conforme necessário.
- **Uso Excessivo de Memória**: Ajuste contínuo de otimização.
- **Falhas na Comparação de Letras**: Correções incrementais na implementação.
- **Baixo Desempenho**: Otimizações de performance com foco na estabilidade.

## 📜 Diagrama de Workflow

O diagrama abaixo ilustra o fluxo de trabalho e o tratamento de erros durante o desenvolvimento:

```mermaid
%% Workflow Organizado para Solução do Problema do Karaokê com Scrum (Com Estilo)
flowchart TD
    %% Identificação e Planejamento
    A[**Identificação do Problema**] --> B[**Análise do Karaokê Antigo**]:::neutral
    B --> C[**Identificação de Gargalos**]:::neutral
    
    %% Proposta de Solução e Planejamento
    C --> D[**Proposta de Solução: Utilização do UltraStar Karaoke**]:::important
    D --> E[**Planejamento do Projeto com Scrum**]:::important
    
    %% Sprint 1: Preparação do Ambiente
    E --> F1{Sprint 1: Preparação do Ambiente}:::sprint
    F1 --> G1[Instalação do UltraStar Karaoke]:::neutral
    F1 --> G2[Testes Iniciais de Compatibilidade]:::neutral
    
    %% Tratamento de Erros Sprint 1
    G2 --> |Erro: Incompatibilidade de Hardware| H1[Reconfiguração de Hardware]:::critical
    H1 --> F1
    
    %% Sprint 2: Integração e Otimização
    F1 --> F2{Sprint 2: Integração e Otimização}:::sprint
    F2 --> I1[Integração com Bibliotecas de Músicas via Web]:::neutral
    F2 --> I2[Otimização do Uso de Memória]:::neutral
    
    %% Tratamento de Erros Sprint 2
    I2 --> |Erro: Uso Excessivo de Memória| H2[Ajuste de Otimização]:::critical
    H2 --> F2
    
    %% Sprint 3: Implementação de Funcionalidades
    F2 --> F3{Sprint 3: Implementação de Funcionalidades}:::sprint
    F3 --> J1[Implementação da Comparação de Letras]:::neutral
    F3 --> J2[Desenvolvimento da Função de Pontuação]:::neutral
    
    %% Tratamento de Erros Sprint 3
    J1 --> |Erro: Falha na Comparação de Letras| H3[Correção na Comparação]:::critical
    H3 --> F3
    
    %% Sprint 4: Testes e Validação Final
    F3 --> F4{Sprint 4: Testes e Validação Final}:::sprint
    F4 --> K1[Testes de Performance e Estabilidade]:::neutral
    F4 --> K2[Validação da Experiência do Usuário]:::neutral
    
    %% Tratamento de Erros Sprint 4
    K1 --> |Erro: Baixo Desempenho| H4[Otimização de Performance]:::critical
    H4 --> F4
    
    %% Entrega Final
    F4 --> L[**Entrega da Solução**]:::important
    L --> M[**Retorno do Karaokê após 1 Ano**]:::important
    
    %% Estilos
    classDef critical fill:#c01b1b,stroke:#333,stroke-width:2px,font-weight:bold,font-family:'Roboto';
    classDef important fill:#c01b1b,stroke:#222,stroke-width:2px,font-weight:bold,font-family:'Roboto';
    classDef sprint fill:#6af,stroke:#333,stroke-width:2px,font-family:'Roboto';
    classDef neutral fill:#f5f5dc,stroke:#333,stroke-width:2px,font-family:'Roboto';
