# Data Model: Football Role Guide Static Website

## Entity: Role
- **name**: string (e.g., "Left/Right Back", "Center Back", "Striker")
- **image**: string (URL or asset path)
- **description**: array of sections
  - **sectionTitle**: string
  - **sectionBody**: string

## Relationships
- Each role is independent; no direct relationships between roles.

## Validation Rules
- All roles must have a name, image, and at least one description section.
- Images must be valid URLs or static asset paths.
- Description sections must have non-empty titles and bodies.
