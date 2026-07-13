# Hachimi Translation Repository Index

The meta file provides Hachimi with its list of selectable translation repositories.  

## Contributing

If you run a translation repo for Hachimi, create a PR or an issue to request its addition.
Only unique projects/repositories are accepted. Updates to existing repo metadata are also welcomed.

When creating a PR for a new repo, please add it after the current ones, above mirrors, and ensure no other changes to the file.
It is recommended to create an [info.json](https://hachimi.noccu.art/docs/translation-guide/repo-config#info-file) in your repo for further details.

### Fields

key | value
--- | ---
name | Name of the repo, usually the language.
short_desc | A short description of the repo to help users pick.
index | URL to the repo's `index.json`. Used by Hachimi to find files and updates.
language | An IETF BCP 47 language tag, used for some features like dynamic sorting.
region | What [region](https://github.com/kairusds/Hachimi-Edge/blob/2f6cb78c3faf4b1c69cd559937e4667df4411f99/src/core/game.rs#L16) of the game the repo is for. The repo will only show on this region. Defaults to `Japan`.
