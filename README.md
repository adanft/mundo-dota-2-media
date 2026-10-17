# mundo-dota-2-media

Static image assets for the Mundo Dota 2 website.

## Structure

```
heroes/        Hero cosmetic images
tournaments/   Tournament images
```

## Naming

- English only, lowercase, kebab-case.
- Format: `.webp`.
- Heroes: `<hero>-<item>.webp`. Multiple views of the same item add a suffix: `-main`, `-head`, `-weapon`.

## Usage

Serve files through jsDelivr:

```
https://cdn.jsdelivr.net/gh/adanft/mundo-dota-2-media@main/heroes/<file>.webp
```

Example:

```
https://cdn.jsdelivr.net/gh/adanft/mundo-dota-2-media@main/heroes/zeus-tempest-helm-of-the-thundergod.webp
```

## Disclaimer

Dota 2 and all related assets are property of Valve Corporation.
