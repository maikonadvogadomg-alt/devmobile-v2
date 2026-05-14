# 📋 Plano do Projeto: DevMobile-v2.8.0-completo

**Gerado em:** 14/05/2026 14:59:15

---

## 📊 Visão Geral

| Item | Valor |
|------|-------|
| Total de arquivos | 80 |
| Total de linhas | 34.444 |
| Linguagens | 8 |
| Rotas de API | 49 |

---

## 🌳 Árvore de Arquivos

```
📄 .easignore
📄 .env
📄 .env.example
📄 build-apk-eas.yml
📄 build-apk-local.yml
📄 .gitignore
📄 .npmrc
📄 artifact.toml
📋 app.json
🔷 _layout.tsx
🔷 _layout.tsx
🔷 ai.tsx
🔷 browser.tsx
🔷 editor.tsx
🔷 index.tsx
🔷 plugins.tsx
🔷 pwa.tsx
🔷 settings.tsx
🔷 tasks.tsx
🔷 terminal.tsx
🔷 +not-found.tsx
📄 icon.png
🟡 babel.config.js
🔷 capacitor.config.ts
📝 COMO_BUILDAR.md
📝 COMO-BUILDAR-APK.md
🔷 AIChat.tsx
🔷 AIMemoryModal.tsx
🔷 APKBuilderModal.tsx
🔷 CampoLivreModal.tsx
🔷 CheckpointsModal.tsx
🔷 CodeEditor.tsx
🔷 CombinarAppsModal.tsx
🔷 DatabasePanel.tsx
🔷 ErrorBoundary.tsx
🔷 ErrorFallback.tsx
🔷 FileSidebar.tsx
🔷 FloatingAI.tsx
🔷 GitHubModal.tsx
🔷 HtmlPlayground.tsx
🔷 KeyboardAwareScrollViewCompat.tsx
🔷 LibrarySearch.tsx
🔷 ManualModal.tsx
🔷 MessageRenderer.tsx
🔷 MonacoEditor.tsx
🔷 PreviewPanel.tsx
🔷 ProjectOverviewModal.tsx
🔷 ProjectPlanModal.tsx
🔷 SystemStatus.tsx
🔷 Terminal.tsx
🔷 VoiceAssistant.tsx
🔷 VSCodeView.tsx
🔷 VSCodeWebModal.tsx
🔷 XTermWebView.tsx
🔷 colors.ts
🔷 AppContext.tsx
🔷 featuredProjects.ts
📋 eas.json
🔷 expo-env.d.ts
📝 GERAR-APK.md
🔷 useApiBase.ts
🔷 useColors.ts
📝 MANUAL-COMPLETO.md
🟡 metro.config.js
📋 package.json
📝 PLANO.md
🟡 withTermuxIntent.js
🟡 build.js
🟡 serve.js
🟠 landing-page.html
🔷 apiBase.ts
🔷 githubService.ts
🔷 localSQLite.ts
🔷 previewService.ts
🔷 runtimeMode.ts
🔷 storageService.ts
🔷 terminalService.ts
📋 tsconfig.json
🔷 projectPlan.ts
🔷 zipUtils.ts
```

---

## 🗣️ Linguagens

🔷 typescript: 56 arquivos
📄 plaintext: 6 arquivos
🟡 javascript: 5 arquivos
📝 markdown: 5 arquivos
📋 json: 4 arquivos
📄 yaml: 2 arquivos
📄 toml: 1 arquivo
🟠 html: 1 arquivo

---

## 🚀 Pontos de Entrada

  Nenhum ponto de entrada detectado

---

## 🔌 Rotas de API Detectadas

  `GET /api/saude` — index.tsx
  `GET /api/usuarios` — index.tsx
  `GET /api/usuarios/:id` — index.tsx
  `POST /api/usuarios` — index.tsx
  `PUT /api/usuarios/:id` — index.tsx
  `DELETE /api/usuarios/:id` — index.tsx
  `GET /api/saude` — index.tsx
  `GET /api/usuarios` — index.tsx
  `GET /api/usuarios/:id` — index.tsx
  `POST /api/usuarios` — index.tsx
  `PUT /api/usuarios/:id` — index.tsx
  `DELETE /api/usuarios/:id` — index.tsx
  `GET /` — index.tsx
  `GET /api/itens` — index.tsx
  `POST /api/itens` — index.tsx
  `GET /api/itens/{item_id}` — index.tsx
  `DELETE /api/itens/{item_id}` — index.tsx
  `GET /api/healthz` — settings.tsx
  `POST /api/terminal/exec` — settings.tsx
  `POST /api/chat` — featuredProjects.ts
  `GET /api/saude` — featuredProjects.ts
  `POST /api/chat` — featuredProjects.ts
  `GET /api/saude` — featuredProjects.ts
  `POST /api/chat` — featuredProjects.ts
  `GET /api/saude` — featuredProjects.ts
  `POST /api/chat` — featuredProjects.ts
  `GET /api/provedores` — featuredProjects.ts
  `GET /api/saude` — featuredProjects.ts
  `/USER /user` — githubService.ts
  `/USER/REPOS?AFFILIATION=OWNER&SORT=UPDATED&PER_PAGE=100&PAGE=${PAGE} /user/repos?affiliation=owner&sort=updated&per_page=100&page=${page}` — githubService.ts
  `/REPOS/${OWNER}/${REPO} /repos/${owner}/${repo}` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/TREES/${TREESHA}?RECURSIVE=1 /repos/${owner}/${repo}/git/trees/${treeSha}?recursive=1` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/REF/HEADS/${DEFAULTBRANCH} /repos/${owner}/${repo}/git/ref/heads/${defaultBranch}` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/CONTENTS/${ITEM.PATH}?REF=${DEFAULTBRANCH} /repos/${owner}/${repo}/contents/${item.path}?ref=${defaultBranch}` — githubService.ts
  `/USER/REPOS /user/repos` — githubService.ts
  `/REPOS/${OWNER}/${REPO} /repos/${owner}/${repo}` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/REF/HEADS/${BRANCH} /repos/${owner}/${repo}/git/ref/heads/${branch}` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/BLOBS /repos/${owner}/${repo}/git/blobs` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/BLOBS /repos/${owner}/${repo}/git/blobs` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/TREES /repos/${owner}/${repo}/git/trees` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/COMMITS /repos/${owner}/${repo}/git/commits` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/REFS/HEADS/${ACTUALBRANCH} /repos/${owner}/${repo}/git/refs/heads/${actualBranch}` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/PAGES /repos/${owner}/${repo}/pages` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/PAGES /repos/${owner}/${repo}/pages` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/PAGES /repos/${owner}/${repo}/pages` — githubService.ts
  `/REPOS/${OWNER}/${REPO} /repos/${owner}/${repo}` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/GIT/TREES/${BRANCH}?RECURSIVE=1 /repos/${owner}/${repo}/git/trees/${branch}?recursive=1` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/ACTIONS/WORKFLOWS/${WORKFLOWFILE}/DISPATCHES /repos/${owner}/${repo}/actions/workflows/${workflowFile}/dispatches` — githubService.ts
  `/REPOS/${OWNER}/${REPO}/CONTENTS/${PATH} /repos/${owner}/${repo}/contents/${path}` — githubService.ts

---

## 💡 Sugestões de Melhoria

  📝 Adicionar README.md com instruções do projeto
  🧪 Criar testes automatizados para as funcionalidades principais
  📖 Documentar as rotas de API com exemplos de uso
  📁 Organizar arquivos em subpastas por funcionalidade
  🔷 Migrar arquivos .js para TypeScript para maior segurança de tipos

---

## 📖 Descrição

Importado de DevMobile-v2.8.0-completo.zip — 80 arquivo(s)

---

*Gerado pelo DevMobile IDE*
