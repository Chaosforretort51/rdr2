```markdown
# Contributing to rdr2-mod-tool

Thank you for your interest in contributing to **rdr2-mod-tool**! This project is a mod menu for Red Dead Redemption 2, and we welcome contributions from the community. Whether you’re fixing a bug, adding a feature, or improving documentation, your help is appreciated.

Please follow the guidelines below to ensure a smooth collaboration.

---

## How to Contribute

1. **Fork the repository** – Create a fork of `rdr2-mod-tool` on GitHub.
2. **Clone your fork** – `git clone https://github.com/your-username/rdr2-mod-tool.git`
3. **Create a branch** – Use a descriptive name like `fix-hud-crash` or `add-teleport-feature`.
4. **Make your changes** – Follow the code style and ensure compatibility with Red Dead Redemption 2.
5. **Test your changes** – Verify the mod works as expected and does not introduce new issues.
6. **Commit and push** – Write clear, concise commit messages.
7. **Submit a Pull Request** – Open a PR against the `main` branch of the original repository.

---

## Code Style

- **Language**: C++ (preferred) or C# (if using Script Hook RDR2 .NET).
- **Indentation**: Use 4 spaces (no tabs).
- **Naming conventions**:
  - Classes: `PascalCase`
  - Functions: `camelCase`
  - Variables: `camelCase` or `snake_case` (be consistent)
- **Comments**: Use `//` for single-line comments, `/* */` for multi-line. Explain *why* a piece of code exists, not just *what* it does.
- **Headers**: Include a brief header comment in each file with the purpose and author.
- **Memory management**: Prefer smart pointers (`std::unique_ptr`, `std::shared_ptr`) over raw pointers when possible.
- **Game-specific**: Avoid hardcoding memory addresses; use native functions or pattern scanning where applicable.
- **Formatting**: Run code through a formatter (e.g., `clang-format` for C++) before committing.

---

## Pull Request Process

1. **Ensure your PR is up-to-date** – Rebase or merge the latest `main` branch into your feature branch.
2. **Include a clear description** – Explain what your changes do, why they are needed, and any relevant testing.
3. **Reference issues** – If your PR addresses an issue, link it (e.g., `Closes #123`).
4. **Keep changes focused** – One PR per feature or bug fix. Avoid mixing unrelated changes.
5. **Pass checks** – Ensure your code compiles without errors and does not break existing functionality.
6. **Review** – A maintainer will review your PR. Be open to feedback and make requested changes.
7. **Merge** – Once approved, a maintainer will merge your PR. You may be asked to squash commits into one.

---

## Bug Reports

If you encounter a bug while using `rdr2-mod-tool`, please report it via GitHub Issues.

### How to Report a Bug

1. **Search existing issues** – Check if the bug has already been reported.
2. **Use the bug report template** – Fill in all sections:
   - **Title**: Clear and descriptive (e.g., "Game crashes when opening weapon wheel with mod active").
   - **Description**: Steps to reproduce, expected behavior, actual behavior.
   - **Environment**: Game version (e.g., v1.0.1436.28), mod version (e.g., v1.2.0), OS (Windows 10/11), any other mods installed.
   - **Logs**: Attach any error logs from the game or mod (e.g., from `ScriptHookRDR2.log`).
   - **Screenshots/Videos** (optional): If visual, include media to help reproduce.
3. **Label appropriately** – Add labels like `bug`, `crash`, `UI`, etc.

### Bug Report Guidelines

- Be as specific as possible. “It doesn’t work” is not helpful.
- If the bug is intermittent, note any patterns.
- Do not use issues for feature requests (use the `Feature Request` template instead).

Thank you for helping make `rdr2-mod-tool` better!
```