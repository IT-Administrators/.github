# CONTRIBUTING

Contributions are always welcome, no matter how large or small. Before contributing,
please read the [code of conduct](CODE_OF_CONDUCT.md).

Some thoughts to help you contribute to this project.

## Recommended Communication Style

1. Always leave screenshots for visual changes.
1. Always leave a detailed description in the pull request. Leave nothing ambiguous for the reviewer.
1. Always review your code first. Do this by leaving comments in your coding noting questions, or interesting things for the reviewer.
1. Always communicate. Whether it is in the issue or the pull request, keeping the lines of communication helps everyone around you.

## Setup (forks are preferred).

See documentation on how to [fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) a repo.

## Building / Installation

The build/ installation part differs from repo to repo. You will always find a chapter for installation/ build in the repositories readme file.

Example command:
```sh
$ g++ <file> -o exe
```

## Testing

Test the project by running the provided tests and your newly added tests. 
Create test evidences to provide them in the pull request.

## Pull Requests

### _We actively welcome your pull requests, however linking your work to an existing issue or feature request is preferred._

1. Fork the repo and create your branch using the following pattern:
    
    | Keyword | Featurename | NamingSyntax |
    |---------|-------------|--------------|
    | Add, Change, Remove | Description of the feature to be added, changed or removed. | Use CamelCase or separate words by underscore or hyphen. |
1. If you've added code that should be tested, add tests.
1. If you've changed APIs, update the documentation.
1. If you make visual changes, screenshots are required.
1. Ensure the test suite passes.
1. Make sure you address any lint warnings.
1. If you make the existing code better, please let us know in your PR description.
1. A PR description and title are required. The title is required to begin with: "Add:", "Change:", or "Remove:", depending on what you did.
1. [Link to an issue or feature request](https://help.github.com/en/github/writing-on-github/autolinked-references-and-urls) in the project. Unsolicited code is welcomed, but an issue or feature request is required to announce your intentions. 
PR's without a linked issue or feature request will be marked invalid and closed.

*Note for maintainers: All pull requests need a label to assist automation.*

### Pull Request Validation

A PR is only valid, if it contains the above mentioned points. If for example a dedicated branch is missing
or the code is not commented and the documentation adjusted, the PR is not valid and will be closed.

See the [Documentation Guide](DOCUMENTATION_GUIDE.md), to check if documentation is following the standards.

### Work in progress

GitHub has support for draft pull requests, which will disable the merge button until the PR is marked as ready for merge.

## Issues

If you plan to contribute a change based on an open issue, please assign yourself by commenting on the following word `.take`. 
Issues that are not assigned are assumed open and to avoid conflicts, please assign yourself before beginning work on any issues.

If you would like to contribute to the project for the first time, please consider joining checking the bug reports
for the repo.

Also, all questions are welcomed. 

## Funding

## Community

## License

By contributing to any project, you agree that your contributions will be licensed
under the repositories license.