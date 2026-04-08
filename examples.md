# Examples

## cURL Example

```bash
curl -X POST "https://detect.gpthumanizer.ai/api/detect_ai" \
  -H "Content-Type: application/json" \
  -d '{"text":"Your text here\nThis is the next line."}'
```

## Example Response

```json
{
  "document": {
    "full_text": {
      "ai_possibilities": 0.1742492839694023,
      "class": "human",
      "highlight": "false",
      "probabilities": {
        "ai": 0.11096608638763428,
        "ai_humanized": 0.06328319758176804,
        "human": 0.6336929202079773,
        "light_edited": 0.19205784797668457
      },
      "text": "Your text here\nThis is the next line."
    }
  }
}
```
