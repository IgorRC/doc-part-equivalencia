# Documentación de Pruebas de Partición de Equivalencia

## Validación de Contraseñas

### Requisitos de la Contraseña

La contraseña debe cumplir con los siguientes criterios:
- Tener entre 8 y 10 caracteres.
- Contener al menos una letra mayúscula.
- Contener al menos una letra minúscula.
- Contener al menos un número.
- Contener al menos un carácter especial.

### Casos de Prueba

1. **Contraseña con más de 10 caracteres**
   - **Descripción:** Verificar que una contraseña con más de 10 caracteres no sea válida.
   - **Ejemplo:** `A1!bcdefghij`

2. **Contraseña con menos de 8 caracteres**
   - **Descripción:** Verificar que una contraseña con menos de 8 caracteres no sea válida.
   - **Ejemplo:** `A1!bcde`

3. **Contraseña con entre 8 y 10 caracteres**
   - **Descripción:** Verificar que una contraseña con entre 8 y 10 caracteres pueda ser válida si cumple con todos los demás criterios.
   - **Ejemplo:** `A1!bcdefg` o `A1!bcdefgh`

4. **Verificar que exista una letra mayúscula**
   - **Descripción:** Verificar que la contraseña contenga al menos una letra mayúscula.
   - **Ejemplo:** `a1!bcdefG`

5. **Verificar que exista alguna letra**
   - **Descripción:** Verificar que la contraseña contenga al menos una letra (puede ser mayúscula o minúscula).
   - **Ejemplo:** `A1!bcdefg` o `1!@#$%^&*A`

6. **Verificar que exista un carácter especial**
   - **Descripción:** Verificar que la contraseña contenga al menos un carácter especial.
   - **Ejemplo:** `A1bcdefg!`

7. **Verificar que exista un número**
   - **Descripción:** Verificar que la contraseña contenga al menos un número.
   - **Ejemplo:** `A!bcdefg1`

8. **Verificar que exista una letra minúscula**
   - **Descripción:** Verificar que la contraseña contenga al menos una letra minúscula.
   - **Ejemplo:** `A1!bcdefG`

9. **Verificar que cumpla con todas las condiciones**
   - **Descripción:** Verificar que la contraseña cumpla con todas las condiciones de longitud, mayúsculas, minúsculas, números y caracteres especiales.
   - **Ejemplo:** `A1!bcdefg`

### Notas

- Cada caso de prueba debe ser ejecutado independientemente para validar la correcta implementación de las restricciones de contraseña.
- Las contraseñas de ejemplo proporcionadas son sólo ilustrativas y deben adaptarse según las necesidades específicas de las pruebas.

