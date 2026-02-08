# Sundew Documentation

Documentation site for [Sundew](https://github.com/sundew-sh/sundew) — a carnivorous honeypot for AI agents.

Live at [docs.sundew.sh](https://docs.sundew.sh).

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Preview locally:

```bash
mint dev
```

View at `http://localhost:3000`.

## Structure

```
├── index.mdx                  Homepage
├── quickstart.mdx             Getting started
├── concepts/                  Core concepts
│   ├── how-it-works.mdx       Architecture overview
│   ├── persona-engine.mdx     Persona generation
│   ├── traps.mdx              Trap surfaces
│   └── fingerprinting.mdx     Behavioral analysis
├── guides/                    How-to guides
│   ├── configuration.mdx      Configuration reference
│   ├── deployment.mdx         Production deployment
│   ├── custom-personas.mdx    Building custom personas
│   └── querying.mdx           Querying captured data
├── security/                  Security docs
│   ├── threat-model.mdx       Threat model and hardening
│   └── ethical-use.mdx        Legal and ethical use
└── reference/                 Reference docs
    ├── cli.mdx                CLI commands
    ├── configuration.mdx      Full config reference
    └── contributing.mdx       Contributing guide
```

## Deploying

Changes pushed to `main` are deployed automatically via the Mintlify GitHub app.
