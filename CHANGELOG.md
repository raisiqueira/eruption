# Changelog

## v1.0.0

. Eruption First Release.
༼ つ ◕_◕ ༽つ🌋

## v1.1.0

. Vite depedency updated to from v2 to v3.
. Fixed missing .sh files for husky pre-commit and commit-msg hook.
. Added missing config for promp-cli at commitlint.

## v1.2.0

. Added msw as a dev dep, but still missing default config
. Changed minor configs to match vite@latest with focus on DX

## v1.3.0

. Upgraded Node to latest LTS version, v18 (hydrogen)
. Upgraded Vite to v4.
. Changed vite-react plugin to vite-react-swc
. Bumped dev dependencies to latest

PS: Know issue on vitest/globals conflicting with testing-lib/jest-dom when running for build/preview scripts. Solutions provided were not sufficient to keep both globals working properly. As a fix, `"skipLibCheck": true,` from `tsconfig.json` was changed to `false`, in order to keep running those scripts.
