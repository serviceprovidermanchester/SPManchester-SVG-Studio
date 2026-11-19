# Contributing to SPManchester SVG Studio

Thank you for your interest in contributing to **SPManchester SVG Studio**, an open-source initiative sponsored and engineered by **SPManchester Private Limited** ([www.spmanchester.com](https://www.spmanchester.com)).

We welcome contributions from developers worldwide to make client-side vector tooling faster, more reliable, and accessible to everyone.

---

## Code of Conduct

All contributors and participants are expected to uphold our [Code of Conduct](./CODE_OF_CONDUCT.md). Please report any unacceptable behavior to [info@spmanchester.com](mailto:info@spmanchester.com).

---

## How to Get Involved

1. **Reporting Bugs**: Check the [Issues tab](https://github.com/serviceprovidermanchester/SPManchester-SVG-Studio/issues) to verify if the issue has already been reported. If not, open a bug report using our standardized template.
2. **Suggesting Enhancements**: Propose new format encoders, UI refinements, or performance optimizations via GitHub Issues.
3. **Submitting Pull Requests**: Follow the development guidelines below.

---

## Development Workflow

### 1. Fork & Clone

```bash
git clone https://github.com/<your-username>/svg.git
cd svg
```

### 2. Branching Strategy

Create a descriptive feature branch following our naming standard:

- `feat/feature-name` (e.g., `feat/avif-encoder`)
- `fix/issue-description` (e.g., `fix/safari-canvas-scaling`)
- `docs/update-readme`
- `refactor/optimizer-cleanup`

### 3. Local Development

This project is built using zero-dependency, ultra-lightweight vanilla web standards (HTML5, CSS3, ES6+ JavaScript).

```bash
# Serve locally using npx
npx serve .

# Or using Python 3
python -m http.server 8080
```

Open `http://localhost:8080` in your web browser.

### 4. Coding Standards

- **Zero-Backend Guarantee**: Under no circumstances may code send user images or vector data to any external server or API. All processing must remain strictly client-side.
- **Pure JavaScript**: Maintain standard ES6+ with clean, modern syntax and readable comments. Avoid introducing heavy external frameworks unless approved via an RFC issue.
- **CSS Architecture**: Keep styles semantic, mobile-first, responsive, and follow the dark-mode aesthetic established in `style.css`.
- **Accessibility**: Ensure keyboard navigation and ARIA labels are maintained on all interactive elements.

### 5. Commit Message Conventions

We strictly follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat(scope): add support for AVIF export`
- `fix(png): resolve transparent background clipping on high-DPI screens`
- `docs(readme): add architectural diagram and benchmark metrics`
- `style(ui): improve hover states on converter cards`
- `refactor(core): streamline canvas blob generation helper`

---

## Submitting a Pull Request (PR)

1. Ensure all converters render properly in Chrome, Firefox, Safari, and Edge.
2. Push your branch to your GitHub fork:
   ```bash
   git push origin feat/your-feature-name
   ```
3. Open a Pull Request targeting the `main` branch of `serviceprovidermanchester/SPManchester-SVG-Studio`.
4. Fill out the PR template thoroughly.
5. The core engineering team at **SPManchester Private Limited** will review your PR within 2â€“3 business days.

---

## Enterprise Sponsorship & Inquiries

For corporate partnerships, custom feature requests, or technical enterprise consulting:
- **Company**: SPManchester Private Limited
- **Website**: [www.spmanchester.com](https://www.spmanchester.com)
- **Lead / Maintainer**: Sayed Mudassar Akbar
- **Direct Contact**: [info@spmanchester.com](mailto:info@spmanchester.com)

