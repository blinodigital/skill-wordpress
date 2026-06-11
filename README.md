# Skill WordPress — WordPress SaaS Senior Developer

Skill para Claude Code que transforma o assistente em um Desenvolvedor Full Stack Sênior especializado em WordPress SaaS.

## Como instalar

### Opção 1 — Clonar direto na pasta do projeto

Abra o terminal **dentro da pasta do seu projeto** e execute:

```bash
git clone https://github.com/blinodigital/skill-wordpress.git .skill-temp
cp .skill-temp/CLAUDE.md ./CLAUDE.md
cp -r .skill-temp/.claude ./.claude
rm -rf .skill-temp
```

### Opção 2 — Download ZIP

1. Baixe o ZIP deste repositório
2. Extraia o arquivo
3. Copie `CLAUDE.md` e a pasta `.claude/` para a **raiz do seu projeto**

### Estrutura necessária no seu projeto

```
seu-projeto/
├── CLAUDE.md         ← obrigatório
└── .claude/
    └── commands/
        └── wordpress-saas.md
```

## Como usar

Após instalar, **abra o projeto no Claude Code**.

O assistente iniciará automaticamente e fará duas perguntas:

```
NOME DO PROJETO:
```

```
DESCREVA O PROJETO:
```

Após responder, toda a estrutura profissional será criada **dentro da sua pasta atual**.

## O que é gerado automaticamente

O slug do projeto é gerado automaticamente a partir do nome (ex: "Meu Plugin" → `meu-plugin`).

```
seu-projeto/
├── meu-plugin/              ← pasta do plugin (nomeada com o slug)
│   ├── meu-plugin.php       ← arquivo principal
│   ├── admin/
│   ├── public/
│   ├── includes/
│   ├── core/
│   ├── api/
│   ├── database/
│   ├── licenses/
│   ├── templates/
│   └── assets/
├── memory/
│   ├── project.md
│   ├── features.md
│   ├── todo.md
│   ├── changelog.md
│   └── architecture.md
├── docs/
├── releases/
└── tests/
```

## Recursos incluídos

- Arquitetura desacoplada (preparada para VPS futura)
- Sistema de licença completo
- Versionamento semântico automático
- Geração de ZIP após cada entrega
- Memória permanente do projeto
- Padrões SOLID, Clean Code, PSR
- Estrutura SaaS multiusuário

## Versão

**v1.1.0**

## Changelog

Veja [CHANGELOG.md](CHANGELOG.md) para histórico completo.
