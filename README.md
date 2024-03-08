
crear el repositorio 

crear el proyecto 

npm init vite@latest basic


en vite.config.ts agregar la base

export default defineConfig({
  plugins: [react()],
  base:'https://<USER_NAME>.github.io/basic/'
})


crear el pages y publicarlo

https://vitejs.dev/guide/static-deploy
