# Dependency Upgrade Audit — React

## Upgrade summary

- **Current version:** v18.2.0
- **Target version:** v18.3.0

## Release details

| Release | Name | Published |
| --- | --- | --- |
| v18.2.0 (current) | 18.2.0 (June 14, 2022) | 2022-06-14 |
| v18.3.0 (target) | 18.3.0 (April 25, 2024) | 2024-04-26 |

## v18.3.0 highlights

- This release is identical to 18.2 but adds warnings for deprecated APIs and other changes that are needed for React 19.
- Warn for deprecated `findDOMNode` outside StrictMode.
- Warn for deprecated `test-utils` methods, including when using `act` from `test-utils`.
- Warn for deprecated Legacy Context outside StrictMode.
- Warn for deprecated string refs outside StrictMode.
- Warn for deprecated `defaultProps` for function components.
- Warn when spreading `key`.
- React DOM: warn for deprecated `unmountComponentAtNode` and `renderToStaticNodeStream`.
- See the React 19 Upgrade Guide for the full set of changes to prepare for.

## Where React is today

- Newest release as of this audit: **19.3.1** — "19.3.1 (October 14th, 2026)".
- The project has moved well past our target: from v18.3.0 to the v19.x line, with the latest being 19.3.1.
