# Cynario

**Build and play interactive branching experiences for learning and tabletop exercises—right in your browser.**

Cynario lets you create branching scenarios where people learn by making decisions, seeing the consequences, and trying another path. Free to use. No account required.

## Try it

- **[Open Cynario](https://cynar.io)**: start from the home page.
- **[Open the Builder](https://cynar.io/builder/)**: create your own scenario.
- **[Browse the Marketplace](https://cynar.io/marketplace/)**: look at starter scenarios and add one to play or remix.
- **[Explore use cases](https://cynar.io/use-cases/)**: see what the same tools can do for different kinds of learning.

## Why branching scenarios

A choice teaches more when you can see what follows from it. In a Cynario scenario, a learner picks an option, sees the result, and can go back and try something different. The situation repeats, but their understanding changes.

You can build:

- onboarding and "what would you do?" training
- classroom lessons and knowledge checks
- incident-response and tabletop exercises
- policy and compliance practice
- interactive fiction and branching stories

## How it works

1. **Author.** Lay out scenes on a visual graph and connect them with choices.
2. **Play.** Run the scenario as a focused, story-style experience.
3. **Iterate.** Test a scene or the whole path, adjust it, and play again.
4. **Share.** Export a file, send a link, or work on it with others live.

## What you can do today

**Six scene modes**, which you can mix in one scenario:

- **Decision**: narrative with one or more choices.
- **Slides**: a presentation-style deck inside a scene.
- **Quiz**: choices with grading and feedback.
- **Video**: time-based video with hotspots that can reveal content or branch.
- **Image**: an image with interactive regions.
- **Custom**: direct editing of a scene's underlying source, for authors who want full control.

**Logic.** Use variables, conditions, and effects so earlier choices change what happens later, with scoring and outcomes.

**Media.** Add images and video to your scenarios. Uploaded media is stored locally in your browser; externally hosted media stays with its provider.

**Live collaboration.** Co-author with other people in real time. Live sessions use direct browser connections or a configured relay; availability and behavior depend on the device and network.

Cynario is under active development, and the interface and features continue to evolve.

## Export and delivery

- **`.cynario`**: a portable file with your scenario's structure and content, as readable JSON, so you own your work. It does not include uploaded media.
- **`.cynario.zip`**: the scenario packaged together with its uploaded media.
- **SCORM 1.2**: export a package for a learning management system. We recommend testing a small export in your target LMS before relying on it, since LMS platforms differ in how they handle SCORM.

## Your data and privacy

Cynario is designed to be local-first. Your scenarios are stored in your browser, not in a central Cynario account. "No account required" does not mean anonymous.

- **Back up your work.** Because scenarios live in your browser, clearing site data or switching devices can lose them. Export regularly, and use `.cynario.zip` when uploaded media needs to travel with your work.
- **Sharing is explicit.** Encrypted share links protect scenario content while it travels. Treat complete share links and room links as sensitive access credentials; do not post them publicly.
- **Network providers may see metadata** such as connection times and addresses, even when content is encrypted.
- **Embedded or external media** (for example a hosted video) contacts that media provider.
- **Exported files and copied content are not automatically encrypted.** Handle them according to how sensitive the scenario is.

## Project status

Cynario is in active development and the app is available at [cynar.io](https://cynar.io).

This repository is the public home for bug reports, feature requests, and feedback. The application source code has not been published here yet. We plan to publish source in stages and make organizational self-hosting easier to adopt. No public clone-and-run setup is offered here yet.

The [LICENSE](LICENSE) file describes the license accompanying this repository's contents.

## Feedback and security

- [Report a bug](https://github.com/cybersader/cynario/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/cybersader/cynario/issues/new?template=feature_request.yml)
- [Browse open issues](https://github.com/cybersader/cynario/issues)
- **Security concerns:** please report them privately. See [SECURITY.md](SECURITY.md).

> **Issues are public.** Please do not include real procedures, sensitive scenario content, share links, room links, or passwords in a report.
