# curso-tailwind-ferrante-2025

## 1. Build Básico (com modo watch)
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
Gera o arquivo CSS final a partir do input.css e continua observando mudanças.

## 2. Build Simples (sem watch)
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css
```
Compila o CSS uma vez, sem observar mudanças.

## 3. Build com minificação (produção)
```
npx @tailwindcss/cli -i ./src/input.css -o ./dist/output.css --minify
```
Gera o CSS final e minifica o resultado para produção.

## 4. Criar arquivo de configuração
```
npx tailwindcss init
```
Cria um arquivo `tailwind.config.js` básico.

## 5. Criar config com conteúdo padrão (extended)
```
npx tailwindcss init -p
```
Cria `tailwind.config.js` e `postcss.config.js` com presets básicos.

## 6. Iniciar projeto com template completo
```
npx create-tailwindcss
```
Gera uma estrutura de projeto Tailwind já configurada (Tailwind v4).

## 7. Atualizar para Tailwind v4 (se aplicável)
```
npm install -D tailwindcss@latest
```
Atualiza o pacote do Tailwind para a última versão.