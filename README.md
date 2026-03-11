# CNT.edu — Plataforma de Ensino de Ciência e Tecnologia

## 📁 Estrutura de Arquivos

```
cnt_edu/
│
├── index.html          → Página principal (notícias, acesso às disciplinas)
├── biologia.html       → Materiais de Biologia (1º ao 3º Ano EM)
├── quimica.html        → Materiais de Química (1º ao 3º Ano EM)
├── ciencias.html       → Materiais de Ciências EF (6º ao 9º Ano)
├── calculadora.html    → Calculadora científica
├── planejador.html     → Planejador de aulas (acesso com login)
├── admin.html          → Painel administrativo
│
├── README.md           → Este arquivo
│
└── cntbio/             → Pasta de arquivos compartilhados
    ├── biologia/
    │   ├── 1ano/       → Materiais Biologia 1º Ano EM
    │   ├── 2ano/       → Materiais Biologia 2º Ano EM
    │   └── 3ano/       → Materiais Biologia 3º Ano EM
    ├── quimica/
    │   ├── 1ano/       → Materiais Química 1º Ano EM
    │   ├── 2ano/       → Materiais Química 2º Ano EM
    │   └── 3ano/       → Materiais Química 3º Ano EM
    └── ciencias/
        ├── 6ano/       → Materiais Ciências 6º Ano EF
        ├── 7ano/       → Materiais Ciências 7º Ano EF
        ├── 8ano/       → Materiais Ciências 8º Ano EF
        └── 9ano/       → Materiais Ciências 9º Ano EF
```

## 🔐 Acessos

### Painel Administrativo (`admin.html`)
- **Usuário:** `admin`
- **Senha padrão:** `cnt2025`
- ⚠️ Altere a senha após o primeiro acesso (botão "🔑 Alterar Senha")

### Planejador de Aulas (`planejador.html`)
- Cadastro de professores com usuário e senha individuais
- Cada professor gerencia seus próprios planejamentos
- Suporte para múltiplas escolas (configuráveis)

## 📋 Funcionalidades

### Admin (`admin.html`)
- ✅ Gerenciar notícias científicas (publicar, editar, arquivar)
- ✅ Upload de materiais em PDF para Biologia, Química e Ciências
- ✅ Visualizador e recuperador de senha
- ✅ Conexão com Google Drive (configurar na aba Configurações)
- ✅ Gerenciar pastas `cntbio` por disciplina e ano/série
- ✅ Arquivos editáveis (.docx e .pptx via Google Drive)

### Disciplinas
- **Biologia:** 1º, 2º, 3º Ano do Ensino Médio
- **Química:** 1º, 2º, 3º Ano do Ensino Médio
- **Ciências:** 6º, 7º, 8º, 9º Ano do Ensino Fundamental

### Planejador de Aulas
- Grade semanal por escola
- Horário configurável por escola (CEJA, EE Ana Gondin, etc.)
- Exportação em `.docx` real
- Agenda de avaliações
- Plano de aula oficial

## 🗂️ Pasta `cntbio`

Os materiais compartilhados são organizados em:
- `cntbio/biologia/1ano/`, `2ano/`, `3ano/`
- `cntbio/quimica/1ano/`, `2ano/`, `3ano/`
- `cntbio/ciencias/6ano/`, `7ano/`, `8ano/`, `9ano/`

## ☁️ Integração Google Drive

1. Acesse `admin.html` → aba **⚙️ Configurações**
2. Insira o e-mail da conta Google a ser vinculada
3. A pasta `cntbio` no Drive será usada para armazenamento
4. Arquivos `.docx` e `.pptx` podem ser editados diretamente no Drive

## 💾 Armazenamento Local

Todos os dados (notícias, materiais, configurações) são salvos no `localStorage` do navegador. Os dados persistem entre sessões no mesmo navegador/dispositivo.

## 🏫 Escolas Suportadas no Planejador

- CEJA de Laguna
- E.E. Ana Gondin
- (Novas escolas podem ser adicionadas pelo professor)

---
*Desenvolvido para uso educacional — CNT.edu*
