# 📘 Planejamento da Configuração

## 🧩 Itens de Configuração
- Código-fonte: `index.html`, `style.css`, `script.js`
- Documentação: `README.md`, `RELATORIO_FINAL.md`
- Scripts e arquivos auxiliares: `docs/configuracao.md`

---

## 🧱 Convenções de Nomeação
- **Branches:**  
  - `main` → versão estável  
  - `branch-a`, `branch-b` → simulação de desenvolvimento e conflito
- **Commits:** padrão *Conventional Commits*  
  Exemplo: `feat(ui): alterar título principal`
- **Tags:** `vMAJOR.MINOR.PATCH`  
  Exemplo: `v1.0.0`

---

## 🏷️ Política de Versionamento
Usa-se o padrão **SemVer (Semantic Versioning)**:  
- **MAJOR:** mudanças incompatíveis  
- **MINOR:** novas funcionalidades  
- **PATCH:** correções de bugs  

Primeira versão estável: `v1.0.0`

---

## 🌿 Política de Branching
- `main` → versão estável do projeto  
- `branch-a` e `branch-b` → desenvolvimento e simulação de conflito  

---

## 💾 Estratégia de Backup e Recuperação
- Backup automático via GitHub (histórico completo de commits)
- Clones locais servem como cópias de segurança  
- Para restaurar:  
  ```bash
  git clone https://github.com/<seu-usuario>/simulacao-gcs-joaomoura.git
  git checkout <tag ou commit específico>
