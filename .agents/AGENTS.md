# Frontend Only & Visual Modifications Rule

When working on the BOCA project codebase (`boca/src/`):

1. **Scope Restriction - Visual/Frontend Only**:
   - All code edits must be restricted strictly to frontend presentation, UI design, CSS styling, layout structure, and visual enhancements.
   - Do NOT modify backend logic, database operations, query execution, session management, or core business rules.

2. **Preserve Form & Input Contracts**:
   - Maintain all HTML form attributes: do not rename or remove `name`, `id`, `action`, or `method` attributes in `<form>`, `<input>`, `<select>`, and `<textarea>` elements.
   - Ensure backend parameter expectations remain 100% intact.

3. **Preserve Functional Scripts**:
   - Do NOT alter or remove essential JavaScript security, hashing, or polling functions (such as `Md5.js`, `sha256.js`, or `reload.js`) beyond styling/formatting.
