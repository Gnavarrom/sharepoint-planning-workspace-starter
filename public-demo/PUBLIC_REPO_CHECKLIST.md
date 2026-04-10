# Public Repo Checklist

Use this checklist before publishing the full repository.

## Files that still contain internal context in the project root

- `README.md`
- `package.json`
- `.yo-rc.json`
- `config/package-solution.json`
- `src/webparts/planningWebPart/PlanningWebPart.ts`
- `src/webparts/planningWebPart/PlanningWebPart.manifest.json`
- `src/webparts/planningWebPart/services/SharePointService.ts`
- `src/webparts/planningWebPart/types/ITypes.ts`
- `src/webparts/planningWebPart/components/Planning.tsx`

## Replace or remove before publishing

- Real site URLs
- Real list names
- Department names
- Industry-specific terms such as `lab`, `pharmacy`, `dispensing`, `compounding`
- Real person names in seeded choices or avatar config
- Prebuilt packages in `sharepoint/solution`, `dist`, `release`, and `lib` if they still reflect internal naming

## Recommended public naming

- App: `Team Planning Workspace`
- List: `Team Planning Data`
- People: `Worker 1` to `Worker n`
- Work items: `Activity 1` to `Activity n`

## Safe publishing approach

1. Share this `public-demo/` folder for storytelling and documentation.
2. Publish screenshots only after masking real names and list titles.
3. If you want to open-source the codebase, create a sanitized branch or copy first.
4. Rebuild packages only after the sanitized naming is in source files and config files.
