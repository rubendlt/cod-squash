# Prueba de Squash
# Comandos usados

## Líder
git clone URL
cd carpeta
echo "# Título" > README.md
git add .
git commit -m "Primer commit"
git push origin main

## Colaborador
git checkout -b rama-colaborador
echo "Texto" > archivo.txt
git add archivo.txt
git commit -m "Agregar línea"
...
git push origin rama-colaborador

## GitHub
Crear Pull Request
Merge -> Squash and merge
