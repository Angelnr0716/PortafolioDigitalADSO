# Registro de fusiones (merges)

Este documento registra las fusiones realizadas en el repositorio y la evidencia asociada.

| # | Autor | Rama origen → destino | ¿Hubo conflicto? | Fecha de fusión | Commit |
|---|-------|----------------------:|:----------------:|:---------------:|:------:|
| 1 | Angel Reyes | feature/formulario-contacto → main | Sí — conflicto en `index.html` (resuelto) | 2026-06-28 | `9578222` |
| 2 | Angel Reyes | feature/buscador-habilidades → main | No | 2026-06-27 | `3d912a1` |
| 3 |  |  |  |  |  |
| 4 |  |  |  |  |  |

## Comandos para verificar evidencia

- Mostrar detalles de la fusión 1:

```
git show --pretty=format:"Commit:%h%nAuthor:%an%nDate:%ad%nSubject:%s%nParents:%P" -s 9578222
```

- Mostrar detalles de la fusión 2:

```
git show --pretty=format:"Commit:%h%nAuthor:%an%nDate:%ad%nSubject:%s%nParents:%P" -s 3d912a1
```

> Nota: las filas 3 y 4 se dejan vacías para completar cuando se realicen nuevas fusiones.
