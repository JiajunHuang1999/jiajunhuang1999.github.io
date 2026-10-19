# Repository Notes

- When updating website-facing academic content such as news, selected publications, awards, deadlines, talks, or service, update the corresponding CV-facing content in the same change when applicable.
- When updating CV-facing academic content, mirror the relevant website-facing page or collection entry in the same change when applicable.
- After every website change, build and render a local preview, inspect the changed page, and open the preview for the user. Include the local preview URL in the handoff. Do not push or deploy unless explicitly requested.
- Local preview command: `BUNDLE_USER_HOME=local/bundler BUNDLE_PATH=vendor/bundle bundle exec jekyll serve --host 127.0.0.1 --port 4000`. Reuse a running server when available; the default preview URL is `http://127.0.0.1:4000/`.
