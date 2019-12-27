
## Default Variables

### gimp_started

Restart app if already running

#### Default value

```yaml
gimp_started: true
```

### gimp_user

User to run user-specific commands

#### Default value

```yaml
gimp_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
