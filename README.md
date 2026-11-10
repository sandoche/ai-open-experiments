# ai-open-experiments
A bunch of experiments and small artifacts made with ai

## Experiments

| Experiment | Description | Live site |
| --- | --- | --- |
| [The Little Atlas Library](atlas-library/) | A searchable collection of 46 children's atlases in English, French, and Spanish. | [atlas-library.expt.fyi](https://atlas-library.expt.fyi/) |

## Run locally

Open `atlas-library/index.html` in a browser, or serve its folder with
`python3 -m http.server --directory atlas-library` and visit
`http://localhost:8000`. Book covers load from external sources.

Each experiment lives in its own top-level folder. The atlas is a static site
and can be deployed independently from `atlas-library/` with no build command.
