# Mestres do Design Gráfico

Site editorial em português sobre designers que transformaram a comunicação visual no mundo e no Brasil.

## Executar localmente

O projeto é um site estático. Sirva a pasta `dist` com um servidor HTTP local:

```powershell
python -m http.server 4173 --directory dist
```

Depois, acesse `http://127.0.0.1:4173`.

## Estrutura

- `dist/index.html`: conteúdo e estrutura da página
- `dist/styles.css` e arquivos complementares: estilos visuais e responsivos
- `dist/script.js` e `dist/work-selector.js`: interações e galeria de obras
