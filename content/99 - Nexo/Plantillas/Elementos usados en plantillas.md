---
Area:
  - Curso
  - Interes
  - Universidad
Ocupacion:
---
# Mover nuevas notas a una carpeta especifica
<%* await tp.file.move("" + tp.file.title) -%>

# Propiedad Año
[[<% tp.date.now("YYYY") %>]]

# Propiedad Mes
[[<% tp.date.now("MMMM-YYYY") %>]]

# Propiedad Fecha de creacion
[[<% tp.date.now("DD-MM-YYYY") %>]]

# Titulo
<% tp.file.title %>