# altv-typescript-strict

## Prerequisite
This template prepare a dev environment for alt:V GTA Multiplayer.  
Warning : Typescript is strict
```json
{
	"strict": true,
	"noFallthroughCasesInSwitch": true,
	"noImplicitReturns": true,
	"noUncheckedIndexedAccess": true,
	"noUnusedLocals": true,
	"noUnusedParameters": true,
}
```

## Usage
Clone this repository and move inside the folder
```sh
npm install
```

The build command will lint, build and then copy all the non .t s files of the src/ folder
```sh
npm run build #npm run lint && npx tsc && npm run copy
npm run lint #npx eslint . --ext .js,.jsx,.ts,.tsx
```

Build output directory is **dist/**
