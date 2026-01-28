# 🎓 Gerador de Certificados – Interface Web (MVP)

Este projeto representa a **primeira fase** de um **Gerador de Certificados Web**, com foco exclusivo na **interface do formulário** e na **definição inicial das regras de negócio**.

Nesta etapa, **não há geração de PDF nem backend**.  
O objetivo principal é validar o **fluxo do usuário**, a **experiência de uso (UX)** e a **estrutura visual** da aplicação.

---

## 🎯 Objetivo da Fase Atual

- Construir uma interface **limpa, clara e profissional**
- Definir com precisão os **dados necessários** para a geração de certificados
- Preparar a base para **integração futura** com o template oficial do certificado

---

## 🖥️ Funcionalidades Implementadas

- Campo para **nome do aluno**
- **Seleção de curso**
- Exibição automática da **carga horária** (campo bloqueado)
- Seleção de **data inicial** do treinamento
- Seleção de **data final** do treinamento
- Interface preparada para aplicar a regra de **máximo de 8 horas por dia**
- Botão de ação **“Gerar Certificado”** (fluxo visual)

> ⚠️ **Importante:**  
> Nesta fase, o botão **não gera PDF**. Ele representa apenas o **encerramento visual do fluxo do formulário**.

---

## 🧠 Regras Conceituais Já Definidas

- A **carga horária** será determinada automaticamente com base no curso selecionado
- O período do treinamento deverá respeitar o limite máximo de **8 horas por dia**
- O **conteúdo programático** será vinculado internamente ao curso e **não será editável** pelo usuário
- O formulário foi projetado para **reduzir erros humanos** e garantir clareza antes da geração do certificado

---

## 🧩 Escopo Atual  
### (O que ESTE repositório faz)

✅ Interface do formulário  
✅ Estrutura visual e hierarquia de campos  
✅ UX focado em **simplicidade e clareza**  
✅ Preparação para regras de negócio  

### Fora do escopo nesta fase

❌ Geração de PDF  
❌ Integração com template do certificado  
❌ Backend  
❌ Persistência de dados  

---

## 📌 Status do Projeto

🚧 **Em desenvolvimento — Fase 1 (Interface / MVP)**

### Próximas fases planejadas

- Definição da **tabela de cursos**
- Aplicação completa das **regras de datas (8h/dia)**
- Integração com **template HTML do certificado**
- Geração e exportação em **PDF**

---

## 📄 Licença

Projeto em fase inicial, destinado a **uso corporativo e interno**.

A licença pertence à **GrupoMed**, que autorizou a divulgação do processo de construção deste sistema.
