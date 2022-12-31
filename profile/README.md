# copier-django-crud

Advanced Django project and app skaffolding for Django CRUD applications
with template composition using [copier](https://github.com/copier-org/copier/).

## Templating components

- Django project: [project](https://github.com/copier-django-crud/project)
- Django app: [app](https://github.com/copier-django-crud/app)

## Usage

To create components run
`copier gh:copier-django-crud/<component> <output-directory>`.

To generate a Django project into a `backend` directory run e.g. `copier gh:copier-django-crud/project backend`.

For general `copier` usage instructions refer to its
[documentation](https://copier.readthedocs.io).

For component specific usage instructions refer to `README.md` files in the corresponding GitHub repositories.

## Compatibility

- The templates are compatible with **Django 4.1** project structure.
- Templates are compatible with/have been tested with **copier v7.0.1**.

## Contribution

This project uses [conventional commits](https://www.conventionalcommits.org).
Please create a pull request for every contribution and **prefix the pull request title**
with

- `feat:` for features
- `fix:` for bug fixes
- `docs:` for documentation related additions/changes/removes

like e.g. done in this [exemplary pull request](https://github.com/copier-django-crud/project/pull/1) for a new feature.
