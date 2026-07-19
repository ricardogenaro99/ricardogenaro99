# Política de Seguridad

## Versiones con soporte

Este es un repositorio de perfil de GitHub. Contiene:
- El `README.md` del perfil
- Workflows de GitHub Actions para automatizar la actualización de la DevCard

| Componente | Estado |
|------------|--------|
| Workflows de GitHub Actions | ✅ Mantenido activamente |

## Reportar una Vulnerabilidad

Si descubres una vulnerabilidad de seguridad (por ejemplo, un workflow que pueda ser explotado mediante inyección), por favor repórtala de forma responsable:

1. **NO abras un Issue público en GitHub** para vulnerabilidades de seguridad.
2. Contáctame directamente por correo: [genaro.choquehuanca.palli@gmail.com](mailto:genaro.choquehuanca.palli@gmail.com)
3. Incluye una descripción de la vulnerabilidad y los pasos para reproducirla.

Confirmaré tu reporte en un plazo de **48 horas** y trabajaré en una solución a la brevedad.

## Buenas Prácticas de Seguridad Aplicadas

- ✅ Las GitHub Actions usan versiones fijas (`actions/checkout@v4`)
- ✅ Los workflows usan `[skip ci]` para evitar disparadores recursivos
- ✅ Permisos mínimos: solo `contents: write` donde es necesario
- ✅ Sin secretos almacenados más allá del `GITHUB_TOKEN` integrado de GitHub
- ✅ Dependabot habilitado para mantener las Actions actualizadas
