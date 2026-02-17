# Simulador de examenes básico:
## Instrucciones de Despliegue
### Actualizar el codigo
```
git checkout main
# editas archivos
git add .
git commit -m "Actualizo contenido"
git push origin main
```

### Realizar despliegue
```
npm run build
npm run deploy
```

### Error con "npm run deploy"
Si no se reconoce el comando, entonces instalar la siguiente libreria
```
npm install --save-dev typescript
```