# quick-prompts

A compact collection of predefined prompt snippets for use with UI scripts like [chatgpt-power-continues](https://github.com/rafareborn/chatgpt-power-continues).

## Format

Each file in `prompts/` is a JSON array of:

```json
{
  "label": "Short button label",
  "value": "Full prompt content"
}
```

## Example

```json
{
  "label": "Continue",
  "value": "Continue generating the response where it was cut off. Don’t repeat previous content."
}
```
