# Testing Guidelines

## Principles
- **Single assertion per test**
- **No shared state**: Avoid `setUp`/`tearDown`
- **Random inputs**: Use non-ASCII strings, edge cases

## Best Practices
- **Isolation**: Each test prepares its own state
- **No mocks**: Prefer fakes/stubs
- **Timeout**: Always set a timeout for waits