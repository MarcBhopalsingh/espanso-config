# Espanso Configuration

This repository contains custom configuration files for [Espanso](https://espanso.org/), a text expander for increased productivity.

## Setup

1. Ensure Espanso is installed on your system.  
2. Place files inside the Espanso config directory:  
   - **macOS:** `~/Library/Application Support/espanso/`  
3. Restart Espanso to apply changes:

   ```sh
   espanso restart
   ```

## Custom Matches

- `base.yml`: General text replacements.
- `git.yml`: Git command shortcuts.
- Additional configuration files can be added and imported into `default.yml`.

## Troubleshooting

- Check Espanso’s logs for errors:

  ```sh
  espanso status
  ```

- If changes are not applied, restart Espanso.

## More Information

For full documentation, visit [Espanso’s official site](https://espanso.org/docs/).
