# PreTeXt Migration Guide for GmooG

This repository now includes a PreTeXt starter layout:

- `source/main.ptx`
- `source/publication/publication.ptx`
- `source/assets/`

## Goal

Migrate the current R/bookdown manuscript (`*.Rmd`) into PreTeXt XML while keeping the original files for provenance.

## Suggested Structure

- Keep existing `*.Rmd`, `_book/`, and plot assets until migration is complete.
- Add converted PreTeXt chapters under `source/chapters/`.
- Add reusable image assets under `source/assets/images/`.

## Chapter Mapping Checklist

Use this checklist as you convert each chapter.

- [ ] `001-Preface.Rmd` -> `source/chapters/preface.ptx`
- [ ] `01-Intro.Rmd` -> `source/chapters/intro.ptx`
- [ ] `02-gapminder2.Rmd` -> `source/chapters/gapminder.ptx`
- [ ] `025-movies2.Rmd` -> `source/chapters/movies.ptx`
- [ ] `027-Democrats1912n.Rmd` -> `source/chapters/democrats-1912.ptx`
- [ ] `031-LightSpeed.Rmd` -> `source/chapters/light-speed.ptx`
- [ ] `032-OlympicsH.Rmd` -> `source/chapters/olympics.ptx`
- [ ] `033-Bertin3.Rmd` -> `source/chapters/bertin.ptx`
- [ ] `037-Chess2.Rmd` -> `source/chapters/chess.ptx`
- [ ] `038-GayRights2.Rmd` -> `source/chapters/gay-rights.ptx`
- [ ] `039-Astronauts2.Rmd` -> `source/chapters/astronauts.ptx`
- [ ] `041-Diamonds2.Rmd` -> `source/chapters/diamonds.ptx`
- [ ] `043-PsoriasisX.Rmd` -> `source/chapters/psoriasis.ptx`
- [ ] `044-ElecCars2.Rmd` -> `source/chapters/electric-cars.ptx`
- [ ] `045-DarwinFinch2.Rmd` -> `source/chapters/darwin-finches.ptx`
- [ ] `046-euros2.Rmd` -> `source/chapters/euros.ptx`
- [ ] `047-Leagues2.Rmd` -> `source/chapters/leagues.ptx`
- [ ] `048-USfuel2.Rmd` -> `source/chapters/us-fuel.ptx`
- [ ] `049-PalmerP2.Rmd` -> `source/chapters/palmer-penguins.ptx`
- [ ] `051-Malaria2X.Rmd` -> `source/chapters/malaria.ptx`
- [ ] `052-Swim2.Rmd` -> `source/chapters/swimming.ptx`
- [ ] `053-ComradM2x.Rmd` -> `source/chapters/comrades-marathon.ptx`
- [ ] `054-FacialRecog.Rmd` -> `source/chapters/facial-recognition.ptx`
- [ ] `056-Shears.Rmd` -> `source/chapters/shears.ptx`
- [ ] `057-Deer.Rmd` -> `source/chapters/deer.ptx`
- [ ] `058-Titanic.Rmd` -> `source/chapters/titanic.ptx`
- [ ] `059-BundTWahlX.Rmd` -> `source/chapters/bundestag-election.ptx`
- [ ] `064-Provenance.Rmd` -> `source/chapters/provenance.ptx`
- [ ] `065-Wrangling2.Rmd` -> `source/chapters/wrangling.ptx`
- [ ] `066-Colour2.Rmd` -> `source/chapters/colour.ptx`
- [ ] `067-SceneSet4.Rmd` -> `source/chapters/scene-setting.ptx`
- [ ] `068-SortOrder.Rmd` -> `source/chapters/sort-order.ptx`
- [ ] `070-PayAttentionX.Rmd` -> `source/chapters/pay-attention.ptx`
- [ ] `071-Spotx.Rmd` -> `source/chapters/spot-the-difference.ptx`
- [ ] `099-ConcRecs.Rmd` -> `source/chapters/conclusions.ptx`
- [ ] `20-references.Rmd` -> `source/chapters/references.ptx`

## GitHub Organization Target

Repository target:

- `https://github.com/PreTeXtBooks/GmooG`

Current remotes are configured as:

- `origin` -> `PreTeXtBooks/GmooG`
- `upstream` -> `antonr4/GmooG-book`

If push still fails with "Repository not found", an org admin must either:

- create `PreTeXtBooks/GmooG`, or
- grant your account write access to that repo.
