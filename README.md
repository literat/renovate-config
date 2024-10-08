# renovate-config

> Literat's Renovate Sharable Configuration

For more see [Renovate Docs][renovate-config-presets].

## 🚀 Usage

Enable Renovate in your repository and just `extends` in `.renovaterc.json5`.

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>literat/renovate-config"]
}
```

## 🎛️ Presets

### Default

Default preset

```json
{
  "extends": ["github>literat/renovate-config"]
}
```

### Schedule

#### `scheduleWeeklyNonOfficeHours`

Schedule weekly non-office hours

```json
{
  "extends": ["github>literat/renovate-config/scheduleWeeklyNonOfficeHours.json5"]
}
```

[renovate-config-presets]: https://docs.renovatebot.com/config-presets/
