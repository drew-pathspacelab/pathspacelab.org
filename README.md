# pathspacelab.org

Source for the Pathspace Lab website, served by GitHub Pages at <https://pathspacelab.org>.

Built with Jekyll and the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) remote theme, using a custom `pathspace` skin.

Research code lives separately in [time-path-fragility](https://github.com/drew-pathspacelab/time-path-fragility).

## Local preview

```sh
bundle install        # installs into vendor/bundle (see .bundle/config)
bundle exec jekyll serve
```

## Layout

```text
_config.yml                   Site config
_data/                        Navigation and author data
_includes/, _sass/            Theme overrides and the pathspace skin
assets/artifact-<NN>/         Published figures for each research artifact
assets/writings/              Org sources for essays
assets/reference/             Brand palette references
*.md                          Pages, essays, and artifact write-ups
```

## Publishing artifact figures

Figures are generated in the code repo (`notebooks/figures/`) and copied by hand into
`assets/artifact-<NN>/` so the site has stable image paths independent of local notebook output.
