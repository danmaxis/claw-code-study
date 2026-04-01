# Estrutura do Repositório claw-code

## Estrutura de Arquivos

```
claw-code/
├── assets/
│   ├── clawd-hero.jpeg
│   ├── instructkr.png
│   ├── omx/
│   │   ├── omx-readme-review-1.png
│   │   └── omx-readme-review-2.png
│   ├── star-history.png
│   ├── tweet-screenshot.png
│   └── wsj-feature.png
├── .claude/
│   └── sessions/
│       ├── session-1774998936453.json
│       ├── session-1774998994373.json
│       ├── session-1775007533836.json
│       ├── session-1775007622154.json
│       ├── session-1775007632904.json
│       ├── session-1775007846522.json
│       ├── session-1775009126105.json
│       ├── session-1775009583240.json
│       ├── session-1775009651284.json
│       └── session-1775010002596.json
├── .github/
│   └── FUNDING.yml
├── .gitignore
├── README.md
├── rust/
│   ├── Cargo.lock
│   ├── Cargo.toml
│   ├── .claude/
│   │   └── sessions/
│   │       ├── session-1775007453382.json
│   │       ├── session-1775007484031.json
│   │       ├── session-1775007490104.json
│   │       ├── session-1775007981374.json
│   │       ├── session-1775008007069.json
│   │       ├── session-1775008071886.json
│   │       ├── session-1775008137143.json
│   │       ├── session-1775008161929.json
│   │       ├── session-1775008308936.json
│   │       ├── session-1775008427969.json
│   │       ├── session-1775008464519.json
│   │       ├── session-1775008997307.json
│   │       ├── session-1775009119214.json
│   │       ├── session-1775009126336.json
│   │       ├── session-1775009145469.json
│   │       ├── session-1775009431231.json
│   │       ├── session-1775009769569.json
│   │       ├── session-1775009841982.json
│   │       ├── session-1775009869734.json
│   │       └── session-1775010047738.json
│   ├── .gitignore
│   ├── README.md
│   └── crates/
│       ├── api/
│       │   ├── Cargo.toml
│       │   ├── src/
│       │   │   ├── client.rs
│       │   │   ├── error.rs
│       │   │   ├── lib.rs
│       │   │   ├── sse.rs
│       │   │   └── types.rs
│       │   └── tests/
│       │       └── client_integration.rs
│       ├── commands/
│       │   ├── Cargo.toml
│       │   └── src/
│       │       └── lib.rs
│       ├── compat-harness/
│       │   ├── Cargo.toml
│       │   └── src/
│       │       └── lib.rs
│       ├── runtime/
│       │   ├── Cargo.toml
│       │   └── src/
│       │       ├── bash.rs
│       │       ├── bootstrap.rs
│       │       ├── compact.rs
│       │       ├── config.rs
│       │       ├── conversation.rs
│       │       ├── file_ops.rs
│       │       ├── json.rs
│       │       ├── lib.rs
│       │       ├── mcp.rs
│       │       ├── mcp_client.rs
│       │       ├── mcp_stdio.rs
│       │       ├── oauth.rs
│       │       ├── permissions.rs
│       │       ├── prompt.rs
│       │       ├── remote.rs
│       │       ├── sandbox.rs
│       │       ├── session.rs
│       │       ├── sse.rs
│       │       └── usage.rs
│       ├── rusty-claude-cli/
│       │   ├── Cargo.toml
│       │   └── src/
│       │       ├── app.rs
│       │       ├── args.rs
│       │       ├── init.rs
│       │       ├── input.rs
│       │       ├── main.rs
│       │       └── render.rs
│       └── tools/
│           ├── Cargo.toml
│           ├── .gitignore
│           └── src/
│               └── lib.rs
├── src/
│   ├── __init__.py
│   ├── assistant/
│   │   └── __init__.py
│   ├── bootstrap/
│   │   ├── __init__.py
│   │   └── bootstrap_graph.py
│   ├── bridge/
│   │   └── __init__.py
│   ├── buddy/
│   │   └── __init__.py
│   ├── cli/
│   │   └── __init__.py
│   ├── command_graph.py
│   ├── commands.py
│   ├── components/
│   │   └── __init__.py
│   ├── constants/
│   │   └── __init__.py
│   ├── context.py
│   ├── coordinator/
│   │   └── __init__.py
│   ├── costHook.py
│   ├── cost_tracker.py
│   ├── deferred_init.py
│   ├── dialogLaunchers.py
│   ├── direct_modes.py
│   ├── entrypoints/
│   │   └── __init__.py
│   ├── execution_registry.py
│   ├── history.py
│   ├── hooks/
│   │   └── __init__.py
│   ├── ink.py
│   ├── interactiveHelpers.py
│   ├── keybindings/
│   │   └── __init__.py
│   ├── main.py
│   ├── memdir/
│   │   └── __init__.py
│   ├── migrations/
│   │   └── __init__.py
│   ├── models.py
│   ├── moreright/
│   │   └── __init__.py
│   ├── native_ts/
│   │   └── __init__.py
│   ├── outputStyles/
│   │   └── __init__.py
│   ├── parity_audit.py
│   ├── permissions.py
│   ├── plugins/
│   │   └── __init__.py
│   ├── port_manifest.py
│   ├── prefetch.py
│   ├── projectOnboardingState.py
│   ├── query.py
│   ├── query_engine.py
│   ├── QueryEngine.py
│   ├── reference_data/
│   │   ├── __init__.py
│   │   ├── archive_surface_snapshot.json
│   │   ├── commands_snapshot.json
│   │   ├── tools_snapshot.json
│   │   └── subsystems/
│   │       ├── assistant.json
│   │       ├── bootstrap.json
│   │       ├── bridge.json
│   │       ├── buddy.json
│   │       ├── cli.json
│   │       ├── components.json
│   │       ├── constants.json
│   │       ├── coordinator.json
│   │       ├── entrypoints.json
│   │       ├── hooks.json
│   │       ├── keybindings.json
│   │       ├── memdir.json
│   │       ├── migrations.json
│   │       ├── moreright.json
│   │       ├── native_ts.json
│   │       ├── outputStyles.json
│   │       ├── plugins.json
│   │       ├── remote.json
│   │       ├── schemas.json
│   │       ├── screens.json
│   │       ├── server.json
│   │       ├── services.json
│   │       ├── skills.json
│   │       ├── state.json
│   │       ├── subsystems/
│   │       ├── types.json
│   │       ├── upstreamproxy.json
│   │       ├── utils.json
│   │       ├── vim.json
│   │       └── voice.json
│   ├── remote/
│   │   └── __init__.py
│   ├── remote_runtime.py
│   ├── replLauncher.py
│   ├── runtime.py
│   ├── schemas/
│   │   └── __init__.py
│   ├── screens/
│   │   └── __init__.py
│   ├── server/
│   │   └── __init__.py
│   ├── services/
│   │   └── __init__.py
│   ├── session_store.py
│   ├── setup.py
│   ├── skills/
│   │   └── __init__.py
│   ├── state/
│   │   └── __init__.py
│   ├── system_init.py
│   ├── task.py
│   ├── tasks.py
│   ├── Tool.py
│   ├── tool_pool.py
│   ├── tools.py
│   ├── transcript.py
│   ├── types/
│   │   └── __init__.py
│   ├── upstreamproxy/
│   │   └── __init__.py
│   ├── utils/
│   │   └── __init__.py
│   ├── vim/
│   │   └── __init__.py
│   └── voice/
│       └── __init__.py
└── tests/
    └── test_porting_workspace.py
```

## Linguagens Usadas

- **Python** - Port principal do código (diretório `src/`)
- **Rust** - Implementação alternativa de runtime (diretório `rust/`)

## Dependências Principais

### Rust
- **Cargo.toml** (workspace): `/home/ai-debian/projects/claw-code-study/claw-code/rust/Cargo.toml`
- **Cargo.lock**: `/home/ai-debian/projects/claw-code-study/claw-code/rust/Cargo.lock`

**Crates principais:**
- `rusty-claude-cli` - CLI principal (binário `claw`)
  - `crossterm` 0.28
  - `pulldown-cmark` 0.13
  - `rustyline` 15
  - `serde_json` 1
  - `syntect` 5
  - `tokio` 1 (com features rt-multi-thread, time)
- `api` - Client API e SSE
- `commands` - Comandos
- `runtime` - Runtime do sistema
- `tools` - Pool de ferramentas
- `compat-harness` - Compatibilidade

### Python
- Não foram encontrados arquivos de dependência tradicionais (`package.json`, `pyproject.toml`, `requirements.txt`)
- O projeto usa `setup.py` no diretório `src/` que não lista dependências explicitamente
- O projeto parece ser uma portação/reimplementação sem dependências externas declaradas

## Ponto de Entrada da Aplicação

### Python
```bash
python3 -m src.main <comando>
```
- Arquivo: `/home/ai-debian/projects/claw-code-study/claw-code/src/main.py`
- Comandos disponíveis:
  - `summary` - Render summary do porting
  - `manifest` - Print workspace manifest
  - `subsystems` - List subsystems
  - `commands` - List commands
  - `tools` - List tools
  - `parity-audit` - Run parity audit

### Rust
```bash
cargo run --bin claw
```
- Arquivo: `/home/ai-debian/projects/claw-code-study/claw-code/rust/crates/rusty-claude-cli/src/main.rs`
- Binário: `claw`
