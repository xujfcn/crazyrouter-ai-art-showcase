# 🎨 Crazyrouter AI Art Showcase

Daily AI-generated art using [Crazyrouter API](https://crazyrouter.com) — one API key, all models.

## Series

### 🔥 Model Battle
Same prompt, different AI models. See how each interprets the same idea.
- **Models:** gpt-image-2 / nano-banana-2 / grok-4-image

### 🖼️ Daily AI Art
One stunning image per day, rotating through top models.

### 🎬 AI Video
Text-to-video generation with kling-v3 and veo-3.1.

## Structure

```
├── prompts/          # All prompts used (markdown)
├── images/
│   ├── model-battle/ # Multi-model comparison outputs
│   └── daily-art/    # Single model daily outputs
├── videos/           # Generated video outputs
└── gallery.md        # Full gallery with prompts + results
```

## Models Used

| Type | Models |
|------|--------|
| Image | gpt-image-2, nano-banana-2, grok-4-image |
| Video | kling-v3, veo-3.1 |

## API

All content generated via [Crazyrouter](https://crazyrouter.com) — unified API for 200+ AI models.

```bash
curl -X POST https://crazyrouter.com/v1/images/generations \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{"model":"gpt-image-2","prompt":"...","size":"1024x1024"}'
```

## Follow

Twitter: [@metaviiii](https://x.com/metaviiii)

---

*New content added daily. Star ⭐ to follow along!*
