# Troubleshooting

## 503 from RSS source
- Add a Wait inside the loop (3–8 seconds)
- Lower batch size
- Best fix: self-host RSSHub or use a stable RSS provider

## Paired item data unavailable
Use only `{{$json...}}` in email fields. Avoid `$('Other Node').item.json...`.

## Code node timeouts
Reduce items (limit RSS items to latest 3–5), and run code per item.
