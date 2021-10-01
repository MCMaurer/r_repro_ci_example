# Example R project using reproducible tools and GitHub Actions

This will be an example data science project in R utilizing approaches for reproducibility and automation with GHA. 

## Components to include

- make
- `here`
- `renv`
- Docker
	- not 100% sure what approach makes the most sense here
	- seems like something to add later
- GitHub Actions
	- data validation
		- can use a path filter so GHA only runs on changes to data folder
	- run `make`?
	- could possibly use `make` to generate the DAG and detect any necessary updates, then open an issue in the repo?

## Principles

- broad structure should be R agnostic but work nicely with RStudo + .Rproj workflow
- should be able to utilize Stan models
- avoid bespoke approaches as much as possible
- try to be flexible enough to incorporate the Next Big Thing
- structures and substructures should be self-documenting as possible, but don't overdo it
- tasks should be modular and similarly structured

## Inspiration

- https://drivendata.github.io/cookiecutter-data-science/#cookiecutter-data-science
- https://bost.ocks.org/mike/make/
- https://books.ropensci.org/targets/
- https://hrdag.org/2016/06/14/the-task-is-a-quantum-of-workflow/
- https://emilyriederer.netlify.app/post/data-valid-lightweight/
