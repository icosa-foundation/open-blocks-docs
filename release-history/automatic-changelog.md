# Changelog since v0.3

[Full release details](https://github.com/icosa-foundation/open-blocks/compare/v0.3...889d956f08bd5c53c464f5b927e9f9ce14627cf2)

## 🚀 Features

- Add a new shape (icosahedron) ([PR #39](https://github.com/icosa-foundation/open-blocks/pull/39) by @andybak)

- New Modify Tool mode based on previously experimental "plane subdivide" ([PR #34](https://github.com/icosa-foundation/open-blocks/pull/34) by @andybak)


## 🐛 Fixes

- When extruding multiple faces use each face's own normal ([PR #42](https://github.com/icosa-foundation/open-blocks/pull/42) by @andybak)

- Fix extrude direction ([PR #44](https://github.com/icosa-foundation/open-blocks/pull/44) by @andybak)

- Use the original algorithm when extruding a single face ([PR #48](https://github.com/icosa-foundation/open-blocks/pull/48) by @andybak)


## 🛠️ Infrastructure

- gzip config.vdf before storing as a secret ([PR #49](https://github.com/icosa-foundation/open-blocks/pull/49) by @mikeage)

- Run the build on 'main' periodically to keep the caches alive ([PR #50](https://github.com/icosa-foundation/open-blocks/pull/50) by @mikeage)

- Combine all dependabot PRs into one ([PR #57](https://github.com/icosa-foundation/open-blocks/pull/57) by @mikeage)

- Use PAT to create releases and tags ([PR #59](https://github.com/icosa-foundation/open-blocks/pull/59) by @mikeage)

- Sync cleanup with Open Brush (most importantly, add support for ubuntu-24.04) ([PR #62](https://github.com/icosa-foundation/open-blocks/pull/62) by @mikeage)


## 📦 Dependencies / Maintenance

- Bump actions/setup-python from 5.1.1 to 5.2.0 ([PR #40](https://github.com/icosa-foundation/open-blocks/pull/40) by @dependabot[bot])

- Bump the all-actions-updates group with 2 updates ([PR #58](https://github.com/icosa-foundation/open-blocks/pull/58) by @dependabot[bot])


## 💬 Uncategorized

- Works on Linux thanks to Proton experimental ([PR #52](https://github.com/icosa-foundation/open-blocks/pull/52) by @Utopiah)

- Fix chown error in newer Alpine images [affects new builds without caches] ([PR #66](https://github.com/icosa-foundation/open-blocks/pull/66) by @mikeage)

- OpenXR and URP ([PR #67](https://github.com/icosa-foundation/open-blocks/pull/67) by @andybak)





