# Gabriel Santarém

**Analista e Desenvolvedor de Sistemas**  
Manaus, AM — Brasil | Disponível para Estágio e Desenvolvedor Júnior (Presencial / Remoto)

---

## Perfil Profissional

Profissional com formação superior em **Análise e Desenvolvimento de Sistemas** e graduando em **Ciência da Computação** pela Universidade Estácio de Sá. Atuação direcionada ao desenvolvimento backend, engenharia de software e análise de processos corporativos.

Foco na concepção e implementação de sistemas orientados a regras de negócio complexas, conformidade fiscal brasileira (emissão, eventos e conciliação de NFC-e junto à SEFAZ) e integração direta com periféricos de automação comercial. Prática consolidada no desenvolvimento com linguagens compiladas e tipadas (C#/.NET, Rust, Go), aplicação de arquitetura limpa (Clean Architecture), padrões de concorrência e implementação rigorosa de testes automatizados unitários e de integração.

---

## Formação Acadêmica

* **Bacharelado em Ciência da Computação**  
  *Universidade Estácio de Sá — Manaus/AM* (Em andamento)
* **Tecnólogo em Análise e Desenvolvimento de Sistemas**  
  *Universidade Estácio de Sá — Manaus/AM* (Concluído)

---

## Competências Técnicas

### Análise de Sistemas e Regras de Negócio
* **Engenharia de Requisitos:** Mapeamento de fluxos operacionais de varejo, análise de processos de caixa (PDV), conciliação financeira e controle de turnos.
* **Legislação Fiscal e Tributária:** Implementação de mensageria para NFC-e 4.00, eventos de cancelamento SEFAZ (Evento 110111), tratamento de contingência offline e fechamento contábil mensal em formato digital.
* **Automação Comercial:** Comunicação e protocolo de hardware de varejo, decodificação de etiquetas de balança comercial com peso e preço (EAN-13), comandos térmicos ESC/POS e disparo de gavetas de numerário.
* **Políticas de Crédito:** Controle de contas a receber (crediário), algoritmos oficiais de validação de CPF/CNPJ e regras de bloqueio por inadimplência.

### Arquitetura de Software e Desenvolvimento
* **Linguagens:** C# (.NET 10), Rust, Go, TypeScript, Python.
* **Paradigmas e Padrões:** Clean Architecture, Domain-Driven Design (DDD simplificado), Inversão de Controle e Injeção de Dependências (IoC/DI), MVVM, State Machines assíncronas.
* **Bancos de Dados:** SQLite (operações transacionais atômicas e snapshots online via VACUUM INTO), PostgreSQL, modelagem relacional e mapeamento objeto-relacional com Entity Framework Core e Prisma.
* **Garantia da Qualidade:** Testes unitários e de integração (xUnit), cobertura sistemática de casos de borda e emulação de periféricos para esteiras de integração contínua sem dependência física.

---

## Projetos em Destaque

### [ComercialPro-ERP](https://github.com/GabrielSantarem/ComercialPro-ERP)
**Plataforma Comercial de ERP e Frente de Caixa (PDV) de Alta Performance**  
*Tecnologias: C# 14, .NET 10, Avalonia UI, SQLite 3, EF Core 9, Zeus Fiscal, QuestPDF, xUnit*

* **Módulo Fiscal SEFAZ:** Integração com motor de emissão de NFC-e 4.00, contingência offline automática, cancelamento de documentos regulamentares e exportação estruturada do pacote fiscal mensal para contabilidade.
* **Frente de Caixa (PDV):** Interface desenvolvida sob o paradigma *Zero Mouse*, permitindo a operação integral do checkout via atalhos de teclado com foco inteligente em caixas de diálogo.
* **Integração de Hardware:** Parser nativo para etiquetas de balança de retaguarda com identificação de tara, peso fracionado e precificação dinâmica; acionamento de gaveta via interface serial/RJ12.
* **Confiabilidade e Auditoria:** Cobertura de 243 testes automatizados (unitários e de integração) abrangendo regras tributárias, integridade do caixa, backup transacional e resiliência de dados.

---

### [rsborg](https://github.com/GabrielSantarem/rsborg)
**Interface de Terminal (TUI) para Gerenciamento de Backups Corporativos**  
*Tecnologias: Rust (Edição 2024), Ratatui, BorgBackup, Linux systemd, POSIX Shell*

* **Processamento Assíncrono:** Execução concorrente de tarefas críticas de infraestrutura (criação de arquivos, verificação de integridade, deduplicação e auditoria) sem bloqueio da interface.
* **Navegação Hierárquica:** Mecanismo de árvore de arquivos com regras de herança de seleção e suporte nativo à internacionalização (Português/Inglês).
* **Automação de Infraestrutura:** Módulo integrado para geração e instalação de unidades de serviço e temporizadores no `systemd` do Linux e comandos seguros para `cron`.

---

### [rinha_backend_2023](https://github.com/GabrielSantarem/rinha_backend_2023)
**Serviço Backend de Alta Concorrência**  
*Tecnologias: Go, HTTP Router, Bancos de Dados Relacionais*

* Implementação de API orientada a processamento com throughput elevado e controle rigoroso de recursos computacionais, memória e conexões simultâneas.

---

### [fist](https://github.com/GabrielSantarem/fist)
**Roteador HTTP Funcional**  
*Tecnologias: Gleam, BEAM/OTP*

* Biblioteca de roteamento HTTP baseada em segurança de tipos, imutabilidade e concorrência orientada a atores na plataforma Erlang/OTP.

---

## Contato e Repositórios

* **GitHub:** [github.com/GabrielSantarem](https://github.com/GabrielSantarem)
* **Codeberg:** [codeberg.org/MrTomate](https://codeberg.org/MrTomate)
