# noa

Expo app — Android, iOS, web.

## Run

```bash
npm install
npm run web        # browser
npm start          # QR code → Expo Go on phone
```

## Check

```bash
npx tsc --noEmit   # types
npm run lint       # lint
```

## Where things live

```
src/app/          screens (file = route)
src/components/   UI pieces
src/hooks/        hooks
src/constants/    theme
assets/           images, icons
```

## Notes

- Edit `src/app/index.tsx` first.
- `*.web.tsx` = web-only version of a file.
- Android build needs `ANDROID_HOME`. iOS build needs a Mac.
- `npm run reset-project` = blank slate.

[Expo docs](https://docs.expo.dev/)
