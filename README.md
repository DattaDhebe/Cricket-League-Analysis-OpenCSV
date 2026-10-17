# Cricket League Analytics · Java

Java analysis of IPL 2019 batting and bowling CSV data using OpenCSV, Gson and JUnit.

**JAVA · OPENCSV · DATA-ANALYSIS**

## What is included

- Load batting, bowling or combined data through adapter classes.
- Sort player records with parameter-specific comparators.
- Export sorted results as JSON.

| Location | Purpose |
| --- | --- |
| [src/main/java/com/analyser](src/main/java/com/analyser) | Loaders, adapters, sorting and analysis |
| [src/test](src/test) | Tests and IPL 2019 CSV fixtures |
| [build.gradle](build.gradle) | Build configuration |

## Getting started

Review [build.gradle](build.gradle) first: it references a machine-local `CensusAnalyser.main.jar` that is not bundled. Restore or replace that dependency before using the test workflow.

```bash
bash gradlew test
```

Windows equivalent: `gradlew.bat test`.

## Project status

Historical analytics exercise using a fixed IPL 2019 snapshot. The current repository is not a live cricket data service.

Setup commands are documented from the repository structure; execution has not been revalidated as part of this presentation update.

---

Part of [Datta Dhebe's engineering portfolio](https://github.com/DattaDhebe).
