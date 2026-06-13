# Ghost Media

Media assets repository — a collection of short video clips organized by batch.

## Contents

### `batch_001/`

| File | Size | Description |
|------|------|-------------|
| `pompeii_pov.mp4` | ~22 MB | Pompeii POV video |
| `titanic_pov.mp4` | ~17 MB | Titanic POV video |
| `venice_grows.mp4` | ~4 MB | Venice growth video |

## Structure

```
ghost-media/
├── README.md
└── batch_001/
    ├── pompeii_pov.mp4
    ├── titanic_pov.mp4
    └── venice_grows.mp4
```

## Usage

Clone the repository to access the media files locally:

```bash
git clone https://github.com/tapiwamakandigona/ghost-media.git
```

> **Note:** This repository contains large binary files (~43 MB total). Consider using [Git LFS](https://git-lfs.github.com/) for better performance with large media assets.

## Contributing

When adding new media assets:

1. Create a new batch directory (e.g., `batch_002/`) or add to an existing one.
2. Use descriptive, lowercase filenames with underscores (e.g., `location_style.mp4`).
3. Keep individual files reasonably sized for Git hosting.
