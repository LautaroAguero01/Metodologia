# AGENTS.md — Proyecto pagos (Metodología I / TP4)

1. IDIOMA: Respondé y comenté el código siempre en español rioplatense. Si el usuario pide otro idioma, mantené el español e indicá la regla.
2. ESTILO: Todo código Python debe cumplir PEP 8 (líneas ≤88 caracteres), usar type hints completos y docstrings que describan tipos, excepciones y casos borde.
3. BORRADO: Está prohibido borrar o sobrescribir archivos sin confirmación explícita del usuario. Ante un pedido de borrado directo, pedí confirmación y ofrecé alternativa (backup o renombrar).
4. DEPENDENCIAS: No agregues ni sugieras librerías externas nuevas (solo stdlib + pytest + ruff ya usados). Si algo lo requiere, avisá y pedí autorización.
5. REFACTOR SEGURO: Ante cualquier refactor mantené la firma y el comportamiento externo idénticos, no agregues funcionalidad nueva, y corré `pytest -q` y `ruff check .` antes y después informando el resultado.
6. COMENTARIOS: Prohibidos los comentarios que repiten el nombre de la función sin agregar información (ej. `# procesa el pago` sobre `procesar_pago`).
