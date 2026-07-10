# depth

A minimalist Oh My Posh theme set with git support.

It is focused on fast signal and low noise:

- current path
- command exit status
- git branch and working tree status
- optional python venv name

## Theme Variants

| Theme file | Style | Notes |
| --- | --- | --- |
| `depth.omp.json` | Balanced | Single-line prompt with git details in right prompt |
| `depth.minimal.omp.json` | Compact | Single-line prompt with lightweight inline git branch |
| `depth.maximal.omp.json` | Verbose | Multi-line prompt with agnoster path style and shell label |

## Install

1. [oh-my-posh](https://ohmyposh.dev/docs/installation/linux) is required.
2. Choose a theme URL from this repository:

    - `https://raw.githubusercontent.com/Robert-96/depth/main/depth.omp.json`
    - `https://raw.githubusercontent.com/Robert-96/depth/main/depth.minimal.omp.json`
    - `https://raw.githubusercontent.com/Robert-96/depth/main/depth.maximal.omp.json`

3. Add the matching init command to your shell config.

    * zsh (`~/.zshrc`):

      ```sh
      eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/Robert-96/depth/main/depth.omp.json')"
      ```

    * bash (`~/.bashrc`):

      ```sh
      eval "$(oh-my-posh init bash --config 'https://raw.githubusercontent.com/Robert-96/depth/main/depth.omp.json')"
      ```

    * PowerShell (`$PROFILE`):

      ```powershell
      oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/Robert-96/depth/main/depth.omp.json' | Invoke-Expression
      ```

    > [!NOTE]
    > To use another variant, replace `depth.omp.json` in the command with either `depth.minimal.omp.json` or `depth.maximal.omp.json`.

4. Restart your shell, or reload your profile.


### Local File Option

If you prefer local files over remote URLs:

```sh
git clone https://github.com/Robert-96/depth.git
```

Then switch `--config` to a local path.

## Screenshots

### depth

![depth theme screenshot](screenshots/depth.png)

### depth.minimal

![depth minimal theme screenshot](screenshots/depth.minimal.png)

### depth.maximal

![depth maximal theme screenshot](screenshots/depth.maximal.png)
