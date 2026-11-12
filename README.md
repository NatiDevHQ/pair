# Pair Collaboration & Development

A structured repository for pair programming sessions, collaborative engineering workflows, and Git co-authorship standards.

## 👥 Contributors

- **Owner:** [NatiDevHQ](https://github.com/NatiDevHQ) (`natigech35@gmail.com`)
- **Collaborator:** [eyob-030](https://github.com/eyob-030) (`eyobt030@gmail.com`)

## 🎯 Purpose & Overview

This repository serves as a centralized hub for practicing and documenting pair programming and collaborative development. It establishes consistent patterns for:
- Synchronous and asynchronous code review.
- Multi-author commit attribution following GitHub's co-author standard.
- Pull request workflows with structured documentation and session tracking.

## 📁 Repository Structure

```
├── badges/              # Milestones, badge tracking, and achievement documentation
│   └── yolo.md         # Deployment and rapid merge session logs
├── pair/                # Pair programming session notes and summaries
│   └── session-*.md    # Individual session logs with participants and timestamps
└── README.md            # Repository overview, conventions, and collaboration guide
```

## 🤝 Co-Authorship Conventions

When committing collaborative work, attribute all participants using standard Git trailers in the commit message body:

```bash
git commit -m "Commit headline describing the change" \
  -m "Co-authored-by: NatiDevHQ <natigech35@gmail.com>" \
  -m "Co-authored-by: eyob-030 <eyobt030@gmail.com>"
```

### Trailer Rules
1. Separate the commit title from the trailers with at least one blank line.
2. Format each trailer as `Co-authored-by: Name <email>`.
3. Ensure the email matches the verified primary or public email on the contributor's GitHub account.

## 🚀 Workflow

1. **Branch:** Create a focused feature branch from `main`.
2. **Develop:** Implement changes following pair programming patterns (Driver / Navigator).
3. **Commit:** Include co-author trailers in all collaborative commits.
4. **Pull Request:** Open a PR against `main` for review.
5. **Merge:** Integrate into `main` after checks and reviews pass.
