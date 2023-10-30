# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: *SU2*

*SU2 is a suite of software tools written in C++ to numerically solve partial differential equations and perform PDE constrained optimization on unstructured meshes. The primary applications are computational fluid dynamics (CFD) and aerodynamic shape optimization, but it has been extended to solve problems in electrodynamics, chemical flows and other fields. The tool now has application in multiple industries including aeronautical, automotive, ship, and renewable energy. [Source: https://su2code.github.io] *

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | https://github.com/su2code |
| Main/documentation website | https://su2code.github.io |
| Year project was started | 2013 |
| Number of contributors in the past year | 55 (with some duplicates) |
| Number of contributors in the lifetime of the project | 343 (with some duplicates)  |
| Number of distinct affiliations | >10 |
| Where do development discussions take place? | GitHub issues  |
| Typical number of emails/comments per week? | 5 |
| Typical number of commits per week? | 15 |
| Typical commit size | 1-2 files, 5-10 lines |
| How does the project accept contributions? | Pull requests |
| Does the project have an automated test suite? | Yes |
| Does the project use continuous integration? | Yes (Travis CI) |
| Are any legal/licensing steps required to contribute? | No |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [X] I have installed the software
- [X] I have run at least one example
- [X] I have run the test suite
- [ ] The test suite passes

### Notes/concerns/risks

No significant risk at this time. The project seems to be very well managed with documentation, tutorials and pointers for new developers who want to contribute. I have run a few examples and tutorials from the package and downloaded the test repository. The next step is to run the test suite. Only slight concern would be lack of domain knowledge in most of the problems and tutorials being discussed (CFD related), but this is also presents an opportunity to get exposed to the field and the terminology.

Some tests from the test suite are failing on a fresh software install. I have adressed some issues in python test scripts but the full suite is still not passing. Next I will check if some configurations need to be modified from default for building the package.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
