# Kenney Game Jam 2024

## Run game

Running your game locally is very simple:

-   Use `cargo run` to run a native dev build.
-   Use [`trunk serve`](https://trunkrs.dev/) to run a web dev build.

If you're using [VS Code](https://code.visualstudio.com/), this template comes with a [`.vscode/tasks.json`](./.vscode/tasks.json) file.

<details>
  <summary>Run release builds</summary>

-   Use `cargo run --profile release-native --no-default-features` to run a native release build.
-   Use `trunk serve --release --no-default-features` to run a web release build.

</details>

<details>
    <summary>(Optional) Improve your compile times</summary>

[`.cargo/config_fast_builds.toml`](./.cargo/config_fast_builds.toml) contains documentation on how to set up your environment to improve compile times.
After you've fiddled with it, rename it to `.cargo/config.toml` to enable it.

</details>

## Release game

This template uses [GitHub workflows](https://docs.github.com/en/actions/using-workflows) to run tests and build releases.
See [Workflows](./docs/workflows.md) for more information.

## Credits

-   [bevy_quickstart](https://github.com/TheBevyFlock/bevy_quickstart)
-   [Kenney.nl](https://kenney.nl/assets)
