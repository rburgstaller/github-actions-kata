# Task 4

Except for unit tests you also have e2e tests for your application. Add them to CI whenever the app code is changed.

## Definition of done

- [ ] Whenever code is changed for desktop-app e2e tests are run.
- [ ] Screenshots are saved from the tests that failed from the moment in which they failed with retention of 7 days

## Hints & help

<details>
<summary>Those hints will help you start</summary>

- `npm run e2e`
- [artifacts](https://docs.github.com/en/actions/using-workflows/storing-workflow-data-as-artifacts#uploading-build-and-test-artifacts)
- [paths where screenshots are saved](./paths.md)
- [running step when previous step fails](https://docs.github.com/en/actions/learn-github-actions/expressions#failure)
- To run electron e2e in github actions you need to start virtual client with screen in ubuntu. `xvfb-run --auto-servernum --server-args="-screen 0 1280x960x24" -- npm run e2e`
</details>

<details>
<summary>In case you are stuck, you can use the resources listed below. Try to first look yourself. The resources are listed in the order from minimal to full help</summary>

1. [PR with ready solution](https://github.com/Ubax/github-actions-kata/pull/5)
</details>
