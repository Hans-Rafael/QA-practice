# QA-practice

Practical Quality Assurance (QA) Exercises

## Formato de Datos

EL FORMATO JSON CON LA EXTENSIÓN `.jsonc` (permite valores explícitos)

Crear un código comenzando con algún formato elegido (JSON/XML), y traducirlo al formato que no se haya elegido.

## Story Telling: Terrabusi

Necesitamos una API el cual contenga como mínimo 5 marcas asociadas a la empresa "Terrabusi".

### Datos requeridos del producto:

1. **Producto**: valor
2. **Sabor**: valor
3. **Peso**: [paquete chico, paquete grande]
4. **Vencimiento**: valor
5. **TACC**: valor
6. **Ingredientes**: 
   ```json
   [
     {
       "clave": "valor",
       "clave": "valor",
       "clave": "valor"
     }
   ]
   ```
7. **Precio**: valor

### Datos requeridos de la empresa:

1. **Empresa**: valor
2. **Ciudad origen**: valor
3. **Dirección**: valor
4. **Correo**: valor
5. **Teléfono**: valor
6. **Inauguración**: valor

Para instalar el servidor json hacer npm install