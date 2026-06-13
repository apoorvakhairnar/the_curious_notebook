# GitHub Copilot agent profiles

These `.agent.md` files are converted from the Codex `.toml` agent files.

Copy the `.github/agents/` folder into the root of your repository:

```text
THE_CURIOUS_NOTEBOOK/
  .github/
    agents/
      *.agent.md
```

In VS Code Copilot Chat, select one of these custom agents from the agent picker or invoke it by name if your Copilot setup supports that.

Example prompts:

```text
@quarto-template-component-builder Create basic .qmd skeleton files with TODO placeholders only.
```

```text
@writing-refiner Refine this paragraph without changing the meaning.
```

```text
@prc-evaluator Review this PRC evaluation code for train/test leakage and weak baselines.
```

Keep your existing root `AGENTS.md` and local `dynamics_that_compute/AGENTS.md` files. These `.agent.md` files are the role-specific profiles.
