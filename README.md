# alpha — squelette d'application mobile Ionic

Point de départ d'une application mobile **Ionic React + Capacitor** (modèle « tabs » :
trois onglets), prête à être compilée pour Android et iOS.

- Ionic React 8, React 19, React Router 5
- Capacitor 8 (app, haptics, keyboard, status-bar)
- Tests unitaires Vitest, tests end-to-end Cypress

## Lancement

```bash
npm install
npm run dev            # navigateur
npm run build && npx cap sync   # puis ouvrir dans Android Studio / Xcode
npm run test.unit
npm run test.e2e
```

> Statut : modèle de démarrage, pas encore de fonctionnalités métier.
