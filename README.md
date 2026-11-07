# Ubuntu Mono Ligaturized — historical font asset bundle

A set of **Ubuntu Mono font files with programming ligatures** produced by [Ligaturizer](https://github.com/ToxicFrog/Ligaturizer#automatic), with [`ubuntu-mono-ligaturized.css`](ubuntu-mono-ligaturized.css) based on CSS from [Fira Code](https://github.com/tonsky/FiraCode).

This repository exists to provide font assets for demos and code samples. It is a **static asset bundle**, not a VizHub application or its currently shipped typography system.

## Using the assets

Review [`ubuntu-mono-ligaturized.css`](ubuntu-mono-ligaturized.css) and host the referenced font assets at the paths expected by that stylesheet. Import the CSS in a page or build system that serves those files, then select the declared font family in the consuming editor or code block.

The repository includes regular, bold, italic and bold-italic `.ttf` assets and a separate [`arrowized/`](arrowized/) directory. Verify visual rendering, licensing requirements and font loading behavior before reuse.

## Development and licensing

- The root `package.json` defines no build pipeline. Its `npm test` is a **placeholder that fails intentionally**, not a working test suite.
- Check the provided [LICENSE](LICENSE) and upstream font/Ligaturizer terms before distributing or modifying the assets.
- No font files or generated binaries need to change for documentation maintenance.
