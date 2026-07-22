# Semantic Ping-Pong Tennis Test

A small, behavior-preserving refactoring exercise for evaluating semantic ping-pong. The target is [`src/TennisGame1.ts`](src/TennisGame1.ts): improve how the tennis-scoring concepts are represented without changing its public API or observable behavior.

## Run

```bash
npm install --ignore-scripts --no-audit --no-fund --no-package-lock
npm test -- --runInBand
```

## Behavioral constraint

Do not fix the deliberately hard-coded player-name behavior. Literal `"player1"` scores for player one; every other input scores for player two. Existing score strings must remain unchanged.

## Attribution

Extracted from [Emily Bache's Tennis Refactoring Kata](https://github.com/emilybache/Tennis-Refactoring-Kata), `typescript-jest/` implementation. The original project is distributed under the MIT License; see [`LICENSE`](LICENSE).
