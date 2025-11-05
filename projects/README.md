# 📡 Reto Semana #1 — El Maestro de la Terminal (Dominando Linux)

## Resumen

La preparación ha finalizado y los laboratorios están operativos. Este reto transforma a los participantes de usuarios comunes a agentes de campo: la herramienta principal es **la terminal de Linux**. La misión evalúa la capacidad para navegar, crear, manipular y buscar información únicamente desde la línea de comandos.

---

## Objetivo

Al completar esta misión, cada agente deberá:

* Ejecutar operaciones con archivos y directorios con confianza.
* Comprender la lógica y las opciones de comandos básicos e intermedios.
* Aplicar técnicas para optimizar el trabajo en terminal (velocidad y precisión).

---

## Protocolo — Pasos (ejecutar desde el directorio `~`)

> Cada comando corresponde a un paso en la misión.

### Fase 1 — Reconocimiento y preparación

1. Leer el manual de `ls`:

```bash
man ls
```

* Buscar opciones con `/`. Investigar `-l`, `-a`, `-h`, `-R`.
* Salir con `q`.

2. Crear la base de operaciones:

```bash
mkdir MisionAvanzada
cd MisionAvanzada
mkdir Informes_Clasificados Comunicaciones
```

### Fase 2 — Creación y manipulación de inteligencia

1. Generar 5 archivos de informe:

```bash
touch informe_{01..05}.txt
```

2. Escribir y actualizar comunicados:

```bash
echo "Agente en posición. Objetivo a la vista." > comunicado_urgente.txt
echo "Esperando nuevas instrucciones." >> comunicado_urgente.txt
```

* `>` sobrescribe; `>>` añade.

3. Inspección rápida del contenido:

```bash
cat comunicado_urgente.txt
head -n 1 comunicado_urgente.txt
tail -n 1 comunicado_urgente.txt
```

### Fase 3 — Clasificación y búsqueda avanzada

1. Mover informes al directorio correspondiente:

```bash
mv informe_*.txt Informes_Clasificados/
```

2. Copia de seguridad del comunicado:

```bash
cp comunicado_urgente.txt Comunicaciones/
```

3. Crear archivo oculto y buscar archivos:

```bash
touch .archivo_secreto
find . -type f -name "*.txt"
```

---

## Entregable (Flag 🚩)

1. Instalar `tree` y generar la estructura de directorios:

```bash
sudo apt install tree
# (contraseña: kali)
cd MisionAvanzada
tree
```

2. **Evidencia:** captura de pantalla de la terminal mostrando `tree` y el árbol generado. Si no puede instalar `tree`, usar `ls -R`.

---

## Reglas y soporte

* **Fecha límite:** Domingo, 19 de octubre de 2025 — 10:00 PM.
* **Soporte:** Preguntas en el canal correspondiente. Indique qué intentó y cuál fue el resultado.

Buena suerte. La terminal es su mejor herramienta: domínenla. 🧭

---

*Fin del README.*
