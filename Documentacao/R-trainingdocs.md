# 📘 Documentação R-training  
## Validação da Plataforma Moodle para Treinamentos de Auditoria

---

### 🏢 Empresa
*RENOVA SOLUÇÕES EM TECNOLOGIA LTDA*  

### 👤 Responsável
**Marcos Vinicius**

### 📅 Período de Execução
*Setembro a Outubro de 2025*

---

## 1. 🎯 Objetivo do Projeto
Validar a plataforma **Moodle** como ferramenta oficial para fornecimento de treinamentos corporativos voltados à preparação dos colaboradores para auditorias **internas e externas**.  
O projeto visa assegurar que o sistema atenda aos requisitos definidos pelo **Setor de Qualidade**, com foco em rastreabilidade, conformidade normativa (ex: **ISO 37301**) e efetividade dos treinamentos.

---

## 2. 🧭 Escopo
O escopo deste trabalho abrange:

- Criação e configuração de um **curso piloto** no Moodle;
- Instalação e testes de **plugins complementares**;
- Validação dos **requisitos funcionais e normativos**;
- Definição de **métodos de armazenamento e exibição de vídeos**;
- Implementação de **avaliação pós-treinamento** e emissão de certificados automáticos.

---

## 3. 📋 Requisitos Avaliados e Soluções Implementadas

| Nº | Requisito | Descrição | Solução Implementada | Status |
|----|------------|------------|----------------------|--------|
| 1 | Controle de Progresso do Treinamento | O vídeo não deve permitir avanço manual; o colaborador precisa assistir por completo. | Utilização do módulo **H5P (Vídeo Interativo)**, configurado para desabilitar avanço por barra de rolagem. | ✅ Atende |
| 2 | Bloqueio de Tela Ativo | O progresso deve ser pausado se o colaborador alternar de janela. | Configuração do **H5P** com pausa automática ao perder o foco da aba. | ✅ Atende |
| 3 | Geração Automática de Certificado | O sistema deve emitir certificado personalizado após conclusão. | Plugin **Custom Certificate**, instalado manualmente. | ✅ Atende |
| 4 | Registro Automatizado de Presença | Gerar lista de presença com data, horário e identificação. | Plugin **Attendance (Presença)**, configurado no curso. | ✅ Atende |
| 5 | Avaliação Pós-Treinamento | Prova com nota mínima 6 e até 3 tentativas. | **Atividade de Questionário (Quiz)** do Moodle, configurada com critérios de aprovação. | ✅ Atende |

---

## 4. ⚙️ Ações Executadas

- Criação de **curso-teste** na plataforma Moodle para validação das funcionalidades.  
- Instalação e configuração dos plugins:
  - **Attendance (Presença)** – para controle automatizado de presença;
  - **Custom Certificate** – para geração de certificados personalizados;
  - **H5P** – para vídeos interativos com controle de progresso.
- Solicitação de **atualização da plataforma Moodle** para compatibilidade de plugins.
- Solicitação de **instalação manual** do plugin de certificado (erro de upload resolvido via suporte técnico).
- Criação de **canal corporativo no YouTube** para hospedagem dos vídeos de treinamento, visando:
  - Reduzir carga no servidor Moodle;
  - Facilitar carregamento e distribuição dos vídeos.
- Upload e integração dos vídeos do canal YouTube nos módulos do curso.
- Configuração de **avaliação final** (Questionário) com nota mínima 6 e limite de 3 tentativas.
- Testes completos de todas as funcionalidades e simulações de uso por diferentes perfis de usuário.

---

## 5. 📈 Resultados Obtidos

- Todos os requisitos técnicos e funcionais foram **atendidos com sucesso**.  
- A plataforma Moodle demonstrou total capacidade de:
  - Rastrear progresso individual;
  - Registrar presença automaticamente;
  - Emitir certificados condicionados à aprovação;
  - Garantir conformidade com normas de rastreabilidade (ISO 37301 e correlatas).  
- Os vídeos integrados via **YouTube + H5P** funcionaram sem sobrecarga do servidor.  
- O ambiente está **pronto para uso nos treinamentos de auditoria** e preparado para expansão futura a outros tipos de capacitação corporativa.

---

## 6. 🧩 Considerações Finais

A validação realizada confirma que o **Moodle** atende plenamente às exigências de rastreabilidade, controle de presença e comprovação de conclusão dos treinamentos corporativos.  

### Recomendações:
- Documentar detalhadamente a **configuração de cada plugin** em arquivos separados (README específicos);  
- Criar um **modelo padrão de curso** com todas as configurações replicáveis;  
- Registrar os **processos de geração de certificados e listas de presença** para auditoria futura;  
- Incluir monitoramento de **logs de acesso e conclusão** dos usuários para evidências de conformidade.

---

## 7. 📎 Anexos e Evidências (opcional)
- Capturas de tela do curso e dos plugins instalados;  
- Modelos de certificado gerado;  
- Exemplo de relatório de presença automatizado;  
- Logs de conclusão e progresso.  

---

## 8. 🧠 Próximos Passos (opcional)
- Expandir uso do Moodle para treinamentos de **segurança, compliance e integração**;  
- Desenvolver **painel de relatórios personalizados** para acompanhamento de desempenho;  
- Implementar **envio automático de certificados por e-mail** via SMTP;  
- Integrar dados de conclusão com sistemas internos de RH.  

---

> **Documento criado por:** Marcos Vinicius  
> **Data:** 28/10/2025  
> **Versão:** 1.0  
> *(Última atualização manual via Markdown)*
