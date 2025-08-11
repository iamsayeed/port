# Gateremark.me - Static Mirror

This folder contains a static mirror of `https://gateremark.me/` fetched on 2025-08-11.

## Serve locally

- Python 3:
  ```bash
  cd gateremark.me
  python3 -m http.server 8000
  ```
  Then open `http://localhost:8000`.

- Node (serve):
  ```bash
  npx --yes serve@14 gateremark.me -l 8000
  ```

## Notes

- This is a static snapshot. Client-side routes or server APIs that are not directly linked from the homepage may not be included.
- If you need a framework-based rebuild (e.g., Next.js) that replicates the design and interactions, tell me and I can scaffold it.