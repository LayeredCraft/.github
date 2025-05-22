# Contributing to LayeredCraft

We ❤️ contributions! Whether you're fixing bugs, adding new features, improving documentation, or just sharing ideas, you're helping make LayeredCraft better for everyone.

---

## 📦 What is LayeredCraft?

LayeredCraft is a suite of modular .NET libraries designed for layered architecture, cloud-native systems, and clean development practices — including tools for AWS, Alexa skill development, distributed locking, and configuration providers.

---

## 🧪 Building and Testing

LayeredCraft projects target `.NET 8` and `.NET 9`, and use common conventions:

- Use `dotnet build` to compile
- Use `dotnet test` to run tests
- Most projects use:
  - `xUnit v3`
  - `AutoFixture` (with primary constructors)
  - `NSubstitute`
  - `AwesomeAssertions`

---

## 🔄 Git Workflow

1. **Fork** the repo (if you're not a member of the org)
2. Create a branch from `main`:
   ```bash
   git checkout -b feature/my-change
   ```
3. Make your changes
4. Add tests if appropriate
5. Run `dotnet test` and make sure all tests pass
6. Commit and push:
   ```bash
   git commit -m "Descriptive commit message"
   git push origin feature/my-change
   ```
7. Submit a **pull request** to `main`

---

## ✅ Pull Request Guidelines

- Keep PRs focused — avoid mixing unrelated changes
- Follow the code style of the existing project
- Include or update unit tests
- Link to related issues in the PR description (e.g. `Closes #42`)
- If your PR adds a new feature, consider updating the README too

---

## 📜 License

All contributions are made under the [MIT License](LICENSE). By submitting a PR, you agree to license your work under MIT.

---

Thanks for being a part of the LayeredCraft community! 👏
