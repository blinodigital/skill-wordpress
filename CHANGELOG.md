# Changelog — Skill WordPress

Todas as alterações notáveis deste projeto serão documentadas aqui.

Formato baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/)
Versionamento baseado em [Semantic Versioning](https://semver.org/lang/pt-BR/)

---

## [1.4.0] - 2026-06-11

### Adicionado
- Regra obrigatória de compatibilidade PHP 7.4 em todos os arquivos gerados
- Proibição explícita de: union types, match expression, constructor property promotion, tipo `mixed`, nullsafe operator e named arguments
- Exemplos de código ERRADO vs CORRETO para cada caso PHP 8.0+
- Verificação PHP 7.4 adicionada ao checklist de entrega
- Causa raiz documentada: servidores como Hostinger rodam PHP 7.x — usar PHP 8.0+ causa parse error fatal em todos os arquivos com a sintaxe incompatível

---

## [1.3.0] - 2026-06-11

### Corrigido
- Primeira resposta agora é SOMENTE `NOME DO PROJETO:` sem introdução — auto-start real sem precisar enviar mensagem
- ZIP gerado automaticamente ao final de toda entrega, sem precisar solicitar
- ZIP agora lê `memory/project.md` para obter slug e versão correta antes de gerar
- Sistema de licença removido do padrão — criado SOMENTE se o cliente solicitar explicitamente
- Adicionada regra obrigatória de leitura de toda a memória antes de criar qualquer arquivo ou código

---

## [1.2.0] - 2026-06-11

### Alterado
- Plugin gerado agora fica dentro de uma pasta com o slug do projeto (ex: `meu-plugin/`)
- Arquivo principal do plugin gerado com o nome correto (`meu-plugin.php`)
- Memória, docs, releases e tests permanecem na raiz do projeto
- README atualizado com estrutura correta

---

## [1.1.0] - 2026-06-11

### Adicionado
- `CLAUDE.md` — ativação automática sem necessidade de digitar slash command
- Detecção de primeiro uso via `memory/project.md`
- Fluxo de onboarding automático ao abrir o projeto

### Corrigido
- Skill não criava mais pasta raiz com o nome do projeto — agora cria tudo no diretório atual
- Instruções de instalação simplificadas no README

---

## [1.0.0] - 2026-06-11

### Adicionado
- Skill inicial: WordPress SaaS Senior Developer
- Fluxo obrigatório de início de projeto (Nome + Descrição)
- Sistema de memória permanente (/memory/)
- Padrão de estrutura de projeto completo
- Sistema de licença (Manager, Validator, API Client, Storage, Middleware)
- Versionamento semântico obrigatório
- Geração de ZIP após alterações
- Padrão de caminhos Linux (/)
- Arquitetura preparada para VPS futura
- Checklist obrigatório de entrega
- Suporte a SOLID, Clean Code, Clean Architecture, PSR
- Estrutura GitHub com commits semânticos
- README com instruções de instalação
