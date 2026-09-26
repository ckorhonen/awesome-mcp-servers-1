# Awesome MCP servers catalog guide

Read `CONTRIBUTING.md`. This repository consists of multilingual Markdown catalogs and supporting documentation, with no package manifest, CI, or declared build/test/lint/typecheck command. Keep server entries in the correct category and alphabetical order, using the existing repository-link plus concise-description format. Preserve the language navigation, legends, badges, and naming/case conventions; check for duplicates before adding an entry.

Validate only the affected catalog sections, Markdown links, and whitespace. Where a change claims capability or maintenance status, consult the server's primary source and state uncertainty rather than inferring behavior from a name. Catalog links and installation snippets are documentation, not authorization to install packages, configure credentials, or launch MCP servers. Don't bulk-reformat translations or claim server runtime compatibility from a catalog review.

## Completing work

Carry the authorized change through the relevant checks and repair failures it causes. Make routine, reversible implementation choices using existing patterns; ask only when missing information, a material product decision, or an authorization boundary prevents the next step. Existing authorization remains valid within its scope. If blocked, name the exact action and missing prerequisite, retain concise evidence, and continue independent work.

Choose verification proportional to the change. For instructions or prose, inspect changed paths, links, and local instruction precedence and run `git diff --check -- <changed-paths>`; don't install dependencies or run the application solely for a prose edit. For behavior changes, exercise the affected behavior and applicable checks below, then broaden only for failures or unresolved risk. Report files changed, checks actually run and their results, commands only inspected, and remaining limitations. A build or source inspection alone does not prove runtime behavior. Continue through already-authorized follow-through; stop at explicit review checkpoints or boundaries requiring new authorization.
