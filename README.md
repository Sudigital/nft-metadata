# SUDIGITAL NFT Metadata

NFT metadata and images for the **Super Digital** collection.

## Structure

```
├── images/    # PNG images (1.png - 66.png)
└── json/      # Metadata JSON files (1.json - 66.json)
```

## Metadata Format

Each JSON file follows the Metaplex NFT metadata standard:

- `name` — Token name
- `symbol` — `SUDIGITAL`
- `description` — `Super Digital`
- `seller_fee_basis_points` — Royalty (100 = 1%)
- `image` — Image URL
- `attributes` — Trait list (Background, Role, Race, Gender, Eyes, Clothing, Ear, Hair, etc.)
