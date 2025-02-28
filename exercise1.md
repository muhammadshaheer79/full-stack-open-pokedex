# 11.1 Warming up

Since Python is my language of choice for the hypothetical scenario laid out, here are the specific tools I'd deem fit as part of the CI setup:-

-> For linting, a Ruff and mypy combination. The process will be lightning quick, with pass/fail report, auto-fixes and formatting primarily thanks to Ruff along with essential type-checking performed by mypy.

-> For testing, pytest since its a complete testing framework, currently also among the best, and will most likely cover all of the project testing needs.

-> For building, pybuilders since it's a straight-forward versatile build tool and offers a lot of other features like code compilation, package management, configurability, efficiency, extensibility and testing support etc. etc.

Moving forward, there are plenty of other alternatives that can be used to set up CI besides Jenkins and Github Actions. For example, CircleCI, AzureDevOps and TravisCI to name a few. I will go ahead and pick CircleCI as it is cloud-based, reducing infrastructure management.
Highly configurable and scalable. "Orbs" provide reusable configurations and integrations. Also offers good performance, and parallel processing capabilities.

In my opinion a cloud-based environment will be suitable for the hypothetical scenario since firstly it involves only a team of 6 developers therefore classifying it as a small-to-medium software project. Secondly, this also means it probably doesn't have any special requirements (e.g. a need for a graphics card to run tests). Lastly,  it will also be a cheaper endeavor to take where configuring the environment will also be simple with less hassle or inconvenience.
