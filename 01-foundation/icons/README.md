# Иконки

- Предпочитай SF Symbols (systemImage).
- Размеры: .imageScale(.small/.medium/.large) или .font(.title2).
- Уникальные SVG из web → PDF vector в Asset Catalog, рендер как template.
- Не смешивай стили (filled/outline) в одном контексте.
- Иконка + текст: Label("Title", systemImage: "icon").
