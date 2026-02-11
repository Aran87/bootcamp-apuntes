## Paso 1: El problema de los malos nombres (5 min)
> **Guion para la docente:**
Vamos a hablar de algo que parece tonto pero que es **crítico** en un entorno profesional.
**Ejemplos de lo que NO queremos ver:**
```bash
# ❌ Commits sin contexto
git commit -m "cambios"
git commit -m "arreglos"
git commit -m "update"
git commit -m "asdfgh"
# ❌ Ramas con nombres personales
git branch maria
git branch rama-de-laura
git branch mi-rama
git branch pruebas-pedro
# ❌ Ramas sin propósito claro
git branch nueva
git branch temporal
git branch branch1
```
**¿Qué problema tienen estos nombres?**
1. **No dicen QUÉ se cambió**
2. **No dicen PARA QUÉ es la rama**
3. **Crean propiedad personal** ("mi rama", "rama de María")
4. **Son imposibles de buscar o filtrar**