# The Earlier Advantage

**Live website: [https://1d42c4.github.io/chess10/](https://1d42c4.github.io/chess10/)**

1,000 self-contained chess lessons across 10 modules, with chessboards, exercises, answer reveals, and lesson navigation.

This repository publishes the complete contents of the supplied `The-Earlier-Advantage---1000-Chess-Lessons-main` folder, with lessons grouped into category subfolders. The root `index.html` is the website entry point.

## Start learning

- [Start the course](index.html)
- [Lesson 1](lessons/module-01/lesson-0001.html)
- [Lesson 1,000](lessons/module-10/lesson-1000.html)
- [Course manifest](course-manifest.json)

## All four chess websites

| Repository | Collection | GitHub Pages |
| --- | --- | --- |
| [chess7](https://github.com/1d42c4/chess7) | Chess Combat School | [Open site](https://1d42c4.github.io/chess7/) |
| [chess8](https://github.com/1d42c4/chess8) | OnePageLove Chess | [Open site](https://1d42c4.github.io/chess8/) |
| [chess9](https://github.com/1d42c4/chess9) | Positional Logic | [Open site](https://1d42c4.github.io/chess9/) |
| [chess10](https://github.com/1d42c4/chess10) | The Earlier Advantage | [Open site](https://1d42c4.github.io/chess10/) |

## Lesson folders

The 1,000 lessons are organized into 10 module folders containing 100 lessons each. [Browse the lesson directory](lessons/README.md). Each folder includes a README. Navigation, search, related lessons, and download instructions use the new paths.

Older GitHub Pages lesson bookmarks are recognized by the custom 404 page and redirected in the browser, preserving query strings and anchors. With JavaScript disabled, use the course-home link on that page. Original GitHub file URLs remain available in commit history.

## Files and downloads

All 1,004 original source files are included. Any existing course archives, tools, and documentation remain available. Use **Code → Download ZIP** to download this repository, or clone it with Git:

```sh
git clone https://github.com/1d42c4/chess10.git
```

`SOURCE_MANIFEST.json` records every original file, its original path when moved, and its original and current uploaded SHA-256 hashes, and the deliberate publishing changes. These include the repository README, Pages settings files, and any repaired site links.

## Check future changes

Run `python tools/check_layout.py` before publishing. It checks that every directory stays below 1,000 entries, all 1,000 lessons are present, local links resolve, and source-manifest checksums match.

## Publishing and protection

GitHub Pages serves the committed files from the root of `main`. No package installation or build step is needed to view the site. The `.nojekyll` file enables direct static-file publishing.

The repository’s active default-branch rules require pull requests, block force pushes, and block branch deletion, with no bypass actors configured. Submit future content changes through a pull request, then merge to publish them. These rules preserve branch history; an owner can still change the rules or delete the repository, and approved changes can still modify or remove files.

## Original project documentation

See [README.txt](README.txt) for the supplied project notes.
