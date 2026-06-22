# Vuln-Test

## Mermaid XSS Test

```mermaid
graph TD
  A["<img src=x onerror=alert('MERMAID_XSS')>"] --> B[test]
```
