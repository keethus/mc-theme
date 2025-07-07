# MC Home Assistant Theme

A custom theme for Home Assistant to enhance your dashboard's appearance.

## Installation

### 1. Add Themes Support to Home Assistant

Add the following to your `configuration.yaml` file (reboot required):

```yaml
frontend:
  # ... your existing configuration
  themes: !include_dir_merge_named themes
  # ... your existing configuration
```

### 2. Install the Theme

#### Option A: HACS (Recommended)
1. Go to the Community Store (HACS) in Home Assistant.
2. Search for `Template` (or the theme name if different).
3. Navigate to the theme and press **Install**.

#### Option B: Manual Installation
1. Clone or download this repository.
2. Place the `majascesis.yaml` file into your `themes/` folder (create it if it doesn't exist).

   ```sh
   mkdir -p themes
   git clone https://github.com/yourusername/mc-theme.git
   cp mc-theme/themes/majascesis.yaml themes/
   ```

## Usage

1. Restart Home Assistant after installation.
2. Go to your user profile in Home Assistant.
3. Select the "Majascesis" theme from the theme dropdown.

## Troubleshooting
- If the theme does not appear, ensure you have enabled themes in `configuration.yaml` and placed the file in the correct folder.
- Restart Home Assistant after making changes.

---

Enjoy your new Home Assistant look!