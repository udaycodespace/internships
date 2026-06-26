# Graphify Report — CampusEventHub_Team4 (placeholder)

This is a small placeholder graph report generated to provide an immediate `graphify-out/` for the repository. Run the real `graphify` tool to produce a full graph and report.

God nodes
- `Auth` — central auth flows (JWT, email verification)
- `Database` — MongoDB persistence surface

Surprising connections
- `Frontend` → `Auth` → `Database` — highlights client → auth → persistent user state

Why / notes
- Key design points are extracted from code: JWT cookie auth, Mongoose models for `User` and `Event`.

Suggested questions to ask the graph
1. What connects `register` to `verify-email`?
2. Which code paths update `AdminLogs`?
3. Which endpoints modify the `Event` lifecycle?
4. Where are Cloudinary uploads referenced?

Confidence: PLACEHOLDER — run `graphify .` for an accurate report.
