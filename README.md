# api-node-typescript-typeorm





yarn init -y 
yarn add typescript ts-node-dev @types/node -D
yarn add tsconfig-paths 




npx tsc --init --rootDir src --outDir build --esModuleInterop --resolveJsonModule --lib es6 --module commonjs --allowJs true --noImplicitAny true




yarn tsc

node build\server



executar com ts-node-dev

criar o script no package.json
"scripts": {
  "dev": "ts-node-dev --inspect --transpile-only --ignore-watch node_modules src/server.ts"
}


agora rodar
yarn dev