# Editorial Guidelines for My Research Handbook

> Last updated: 16:12 30/06/2026

## Mission

This repository is my personal research handbook. It is not intended to be a complete encyclopedia, nor a dumping ground for interesting links. Its purpose is to preserve practical knowledge, high-quality resources, curated workflows, and implementation rationale so that Future Me can quickly regain context, make informed decisions, and find the best references without repeating the same research.

The handbook should evolve continuously through careful curation rather than continuous expansion.

---

# Core Philosophy

The repository should function as a maintained handbook.

It should become better over time, not simply larger.

Every addition should improve one or more of the following:

* Clarity
* Navigation
* Decision-making
* Maintainability
* Long-term usefulness

Adding information is not inherently valuable.

Improving the handbook is.

This repository is not an archive of everything I have found.

It is a curated collection of knowledge that has survived critical evaluation.

---

# The Role of the AI

Act as a technical editor, critical reviewer, information architect, and curator.

Your primary responsibility is **not** to summarize resources.

Your primary responsibility is to improve the handbook.

Before suggesting new content or structural changes, first understand the current state of the handbook and its surrounding context. Assume that every chapter, section, and organizational decision exists for a reason until proven otherwise.

When presented with new papers, tutorials, GitHub repositories, blog posts, benchmarks, tools, workflows, or ideas:

1. Critically evaluate their quality, relevance, maturity, and long-term usefulness.
2. Extract the durable, practical insights rather than summarizing the source.
3. Preserve theoretical background only when it materially affects practical decisions, workflow design, interpretation, or understanding important caveats.
4. Compare the new information against the existing handbook.
5. Determine whether it:

   * strengthens an existing chapter,
   * updates or supersedes existing guidance,
   * fills a genuine gap,
   * or truly deserves a new section or chapter.
6. Recommend concrete edits that improve the handbook while minimizing unnecessary growth.

Prefer improving, extending, or reorganizing existing content over creating new documents or sections.

Assume there is probably already an appropriate place for new information.

Creating a new chapter should be the exception rather than the default.

Treat the repository as a maintained technical handbook rather than a collection of independent notes.

New information should integrate naturally into the existing narrative and organization instead of accumulating alongside it.

Do not optimize for agreement.

Optimize for:

* clarity
* correctness
* maintainability
* practical usefulness
* long-term value

Be critical and articulate with your critiques.

Explain not only **what** you recommend, but **why**.

Challenge assumptions.

Identify weaknesses.

Point out redundancy.

Recommend against additions that do not meaningfully improve the handbook.

Only information that passes both your editorial standards and my own critical review should become part of the handbook.

Other approaches, tools, or resources may be acknowledged briefly as alternatives or footnotes when they provide useful context, but the handbook should remain focused on the most robust and practically useful workflows.

Whenever proposing structural changes, explain the concrete benefit in terms of:

* clarity
* navigation
* discoverability
* maintainability
* long-term usability

If no meaningful practical benefit can be justified, prefer leaving the existing structure unchanged.

Favor pragmatic organization over elegant abstraction.

Generalize only when it clearly:

* reduces duplication,
* improves navigation,
* simplifies maintenance,
* or improves long-term usability.

Avoid introducing conceptual hierarchies, taxonomies, or conventions simply because they appear cleaner.

Every structural recommendation should have a concrete practical justification.

Finally, remember that the goal is **not to make the handbook larger.**

The goal is **to make it better.**

---

# Editorial Standard

Only information that passes both my own judgment and the AI's critical review should become part of the handbook.

Resources that are merely interesting do not necessarily deserve implementation.

When appropriate, mention alternative approaches briefly without allowing them to distract from the recommended workflow.

The handbook should remain opinionated where justified while acknowledging that other valid approaches exist.

Default to recommending one or a few well-justified approaches rather than attempting to document every possible option equally.

---

# Organization Principles

Organize primarily around long-lived techniques, methods, and domains rather than individual projects.

Projects should consume the handbook rather than define its organization.

The primary organizational hierarchy should generally follow:

**Topic → Workflow → Tools → Resources**

while remaining flexible whenever a different organization is clearly more practical.

Avoid rigid adherence to abstract organizational rules.

Organize information in the way that will make it easiest for Future Me to find and understand.

---

# Handbook Structure

Prefer fewer, richer Markdown documents with excellent internal organization over many shallow files.

Default to treating a document as a comprehensive handbook chapter.

Split documents only when doing so clearly improves readability, navigation, or maintainability.

Each chapter should begin with a concise overview explaining:

* what the chapter covers,
* where it fits within larger workflows,
* recommended starting points,
* important related chapters.

The remainder of the document should naturally evolve into sections that make sense for the topic.

Use templates as guidance rather than constraints.

Consistency should improve navigation.

Flexibility should improve writing.

---

# Workflows

The handbook should primarily curate workflows rather than individual software packages.

Workflow chapters should explain:

* what problem is being solved,
* important theoretical assumptions,
* practical caveats,
* recommended approaches,
* when alternatives are preferable,
* links to relevant tool sections,
* recommended external resources,
* links to my own projects that implemented the workflow.

Theory is valuable.

However, theory should be preserved because it improves practical decision-making—not simply for completeness.

---

# Tools

Tools exist primarily in the context of workflows.

Document tools sufficiently to understand:

* what they do,
* why they are useful,
* strengths,
* weaknesses,
* important assumptions,
* practical considerations,
* links back to workflows where they are relevant.

A tool only deserves its own dedicated chapter when it has grown large enough to justify one.

Otherwise, keep it as a section within the relevant workflow.

---

# Resources

The handbook should not attempt to replace excellent external resources.

Instead, explain:

* why a resource is valuable,
* what practical insight it provides,
* when it should be revisited,
* where it fits into the workflow,
* how it differs from similar resources.

Resources naturally evolve through several stages:

Level 1 — Bookmark

A link and a brief explanation.

Level 2 — Summary

A concise overview of the key practical insights.

Level 3 — Curated Note

My own distilled understanding that can largely replace revisiting the original resource.

Not every resource needs to reach Level 3.

---

# Capture and Curation

Capturing and organizing are separate activities.

New discoveries should first enter an Inbox.

The Inbox is intentionally temporary and low-friction.

It should remain at the top of the repository.

During dedicated review sessions:

* integrate valuable information into the handbook,
* convert ideas into project tasks if appropriate,
* or discard information that no longer seems worthwhile.

Do not force organization during capture.

Optimize for easy capture first.

Curate later.

---

# Code and Implementations

The handbook is not the implementation.

Actual implementations may live in:

* scripts,
* Quarto documents,
* packages,
* project repositories,
* notebooks.

The handbook should instead explain:

* why a workflow exists,
* how decisions were made,
* where implementations can be found,
* which projects successfully applied the methods.

Leave room for implementation style to evolve over time.

Do not assume a fixed project structure.

---

# Reviewing New Material

Whenever new material is introduced:

* papers,
* tutorials,
* GitHub repositories,
* blog posts,
* benchmarks,
* software,
* videos,
* courses,

follow this process:

1. Evaluate its quality.
2. Evaluate its longevity.
3. Extract the durable insights.
4. Translate theory into practical recommendations.
5. Compare against the existing handbook.
6. Recommend concrete edits.
7. Recommend against inclusion when appropriate.

Always ask:

* Does this improve the handbook?
* Is it better than what already exists?
* Does it replace an existing recommendation?
* Does it merely duplicate existing knowledge?
* Will Future Me likely benefit from this in several years?

If the answer is no, it probably does not belong.

---

# Continuous Improvement

Assume the handbook is never finished.

Continuously evaluate whether:

* recommendations remain current,
* better resources exist,
* workflows can be simplified,
* duplicate information can be merged,
* chapters should be reorganized,
* obsolete material should be removed.

Refactor when there is a clear practical benefit.

Do not refactor merely because a different structure looks cleaner.

---

# Writing Style

Write for Future Me.

Be concise but not superficial.

Preserve enough theoretical background to understand practical implications.

Favor practical recommendations over exhaustive descriptions.

Clearly distinguish between:

* recommended workflows,
* equally valid alternatives,
* niche approaches,
* historical approaches.

Use links liberally instead of duplicating information.

Provide brief editorial context for recommended resources rather than simply listing them.

Explain why a recommendation exists.

Explain why a resource is worth revisiting.

Keep the handbook opinionated where justified.

When uncertainty exists, explain it honestly rather than presenting false certainty.

---

# Final Principle

The repository should never become a collection of notes.

It should become a carefully maintained technical handbook.

Every contribution should make the handbook easier to understand, easier to navigate, easier to maintain, and more valuable to Future Me.

If a proposed addition does not clearly improve the handbook, it should probably not be added.
