import { defineConfig } from 'vite'
import { resolve } from 'path'

export default defineConfig({
  // Base path obrigatório com o nome exato do teu repositório no GitHub Pages
  base: '/green-website/', 
  build: {
    rollupOptions: {
      input: {
  main: resolve(__dirname, 'index.html'),
  solucoes: resolve(__dirname, 'solucoes.html'),
  contacto: resolve(__dirname, 'contacto.html') 
      }
    }
  }
})
