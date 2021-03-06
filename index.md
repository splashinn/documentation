## Welcome to Libraries.io :tada:
Here you'll find guidance for contributors to the Libraries.io project as a whole.

### Assumptions
We have made the following assumptions in our guidance and documentation:

* that the reader has a basic understanding of the collaborative coding platform [GitHub](https://help.github.com/),
* that the reader has a working understanding of the distributed revision control system [Git](https://git-scm.com/docs/gittutorial),
* that the reader is able to communicate, in writing, in English.

## Why Build Libraries.io?
_Our goal is to raise the quality of all software._

We do this by tackling three problems:

* Discovery: _Helping developers make faster, more informed decisions about the software that they use._
* Maintainability: _Helping maintainers understand more about the software they depend upon and the consumers of their software._
* Sustainability: _Supporting undervalued software by highlighting shortfalls in contribution and funneling support to them._

If you'd like to know why we think this is the right approach then check out [our strategy](/strategy.md).

## Who is Libraries.io For?

Libraries.io currently caters for the needs of three groups:

* Google: is hungry for your linked datas so she can serve you up search traffic
* Searcher: is a developer with a problem, she is looking for something to help solve it.
* Maintainer: has a project that is used within and/or incorporates open dependencies. She needs to ensure her project(s) are working as expected for users.
* Extender: has her own ideas. She wants access to the raw data so that she can mash up her own service and offer it to the world.


These groups have been expanded into [personas](/personas.md) for contributors to reference.

## How Does Libraries.io Work?
Libraries.io collects data about software and the frameworks, plugins and tools they depend upon which we collectively call libraries.

Everything in Libraries.io begins with [package managers](/packagemanagers.md), on a regular basis background tasks find new or updated libraries from each of those packages managers. Each library is stored as a project alongside any data we can gleam from the package manager. If the package manager provides a link to a hosted revision control service like GitHub then Libraries.io fetches yet more data from there.

Using the data collected we then calculate the [SourceRank](/overview#sourcerank), this value is used to index the project in search results. Next we highlight any issues regarding updates, deprecated versions, yanked or deleted libraries, license incompatibilities etc. to maintainers who depend on a given library. Finally we highlight undervalued and under-supported libraries, guiding maintainers toward projects that they could contribute to that would have a direct benefit on their own work.

If you'd like an overview of the project, including a description of each of the repositories in the Libraries.io organisation and how they work together then check out our [overview](/overview.md).

## How Can I Help?
If you wish to contribute to Libraries.io must agree to our [code of conduct](/CODE_OF_CONDUCT.md). In short they say: be excellent to one another. If you're able to abide by those terms then check out our [contributor's handbook](/contributorshandbook.md).

## Improving This Document
You can view the source for this document and the rest of our documentation [on GitHub](https://github.com/librariesio/documentation). You can also view, comment upon and create new issues concerning this documentation [on our issue tracker](https://github.com/librariesio/documentation). For more information about contributing to Libraries.io please read our [contributor's handbook](/contributorshandbook.md).
