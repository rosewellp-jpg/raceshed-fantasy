# Race Shed Fantasy V19

Race Day Broadcast Edition for the Race Shed TV.

## How to use

1. Upload this whole folder to a new GitHub repo.
2. Add your real RaceShed logo to the `public` folder.
3. Name the logo file exactly:

```txt
raceshed-logo.png
```

4. In Vercel, import the GitHub repo.
5. Vercel should detect Vite automatically.
6. Build command:

```txt
npm run build
```

7. Output directory:

```txt
dist
```

## Edit the dashboard

Open this file:

```txt
src/main.jsx
```

Update these sections:

- `currentRace`
- `lastWinner`
- `standings`
- `weeklyPicks`

That is it.
