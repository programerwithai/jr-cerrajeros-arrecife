# JR Cerrajeros - Landing Page MÃ³vil

Landing page optimizada exclusivamente para mÃ³viles para **JR Cerrajeros** (Arrecife, Lanzarote). DiseÃ±o mobile-first con botÃ³n flotante de urgencia en un solo toque.

## CaracterÃ­sticas

- **Mobile-first**: DiseÃ±o optimizado para telÃ©fonos mÃ³viles
- **Urgencias 24 Horas**: BotÃ³n fijo flotante "Llamar Urgencias (686 94 84 33)"
- **Llegada en menos de 30 min**: Destacado en cabecera
- **Servicios**: Apertura de puertas, cambio de cerraduras, apertura de vehÃ­culos
- **UbicaciÃ³n**: BotÃ³n "CÃ³mo llegar" a C. Tarragona, 2, Arrecife
- **Llamada directa**: Todos los CTAs con `tel:` para llamada en un solo toque

## Despliegue en GitHub Pages

### OpciÃ³n 1: Desde la interfaz de GitHub

1. Ve a [Settings > Pages](https://github.com/programerwithai/jr-cerrajeros-arrecife/settings/pages)
2. En **Source**, selecciona `Deploy from a branch`
3. En **Branch**, selecciona `main` y carpeta `/(root)`
4. Pulsa **Save**
5. La web estarÃ¡ disponible en: `https://programerwithai.github.io/jr-cerrajeros-arrecife/`

### OpciÃ³n 2: Con GitHub CLI

```bash
gh repo edit programerwithai/jr-cerrajeros-arrecife --enable-pages --pages-branch main --pages-path /
```

O desde el repositorio:

```bash
gh api -X POST repos/programerwithai/jr-cerrajeros-arrecife/pages -f source[branch]=main -f source[path]=/
```

## TecnologÃ­as

- HTML5
- CSS3 (Mobile-first, variables CSS)
- JavaScript vanilla

## Contacto

- **DirecciÃ³n**: C. Tarragona, 2, Arrecife
- **TelÃ©fono**: 686 94 84 33
- **Servicio**: 24 Horas / Urgencias
