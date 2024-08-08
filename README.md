# Public Immutable Actions Consumer Tests

This public repo workflow aims to test Immutable Actions end to end. This includes:

* The ability to resolve Action Packages of internal or public visibility
* The ability to resolve Action Repositories (i.e. the "existing" flow)
* Authorization of Action Packages
* Security - i.e. the lack of "fallback" to Action Repositories

Tests are structured as workflow files which can be executed to test that aspect of the feature. There are a number of actions with packages in the immutable-actions org to test against, each set up with the appropriate packages, versions and tags to exercise the feature as needed.

Each workflow should contain a comment at the top of the file containing a detailed breakdown of what is being tested and what result we expect. That way we can check the results manually by running each workflow using `workflow_dispatch`. 

