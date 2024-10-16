# Proyecto: Sistema de Registro de Notas

## Descripción del Proyecto

El **Sistema de Registro de Notas** es una aplicación web diseñada para facilitar la gestión de calificaciones de estudiantes. Permite a los docentes registrar las notas de varios exámenes para cada estudiante y calcular automáticamente su estado académico (APROBADO o DESAPROBADO) en función de un umbral definido.

## Funcionalidades

### 1. Registro de Estudiantes
- **Campos de Entrada**:
  - Nombre del estudiante.
  - Apellido del estudiante.
  - Curso en el que está inscrito el estudiante.

### 2. Registro de Notas
- **Exámenes**:
  - Permite ingresar notas para cuatro exámenes.
  - Cada examen se captura en un campo numérico, asegurando que solo se ingresen valores válidos.

### 3. Cálculo de Notas
- **Cálculo Automático**:
  - Al hacer clic en el botón "Agregar Nota", el sistema calcula automáticamente la suma de las notas de los exámenes.
  - Se determina el estado del estudiante:
    - **APROBADO**: Si el total de las notas es mayor a 13.
    - **DESAPROBADO**: Si el total es 13 o menos.

### 4. Visualización de Resultados
- **Tabla de Resultados**:
  - Los datos ingresados se presentan en una tabla que muestra:
    - Nombre y Apellido del estudiante.
    - Curso.
    - Notas de cada uno de los cuatro exámenes.
    - Total de las notas.
    - Estado académico (APROBADO o DESAPROBADO).

### 5. Interfaz de Usuario
- **Diseño Responsivo**:
  - Utiliza Bootstrap para un diseño moderno y responsivo, asegurando una buena experiencia en dispositivos móviles y de escritorio.
  
- **Accesibilidad**:
  - Los campos obligatorios son claramente identificables, y se incluye un botón para agregar las notas de forma intuitiva.

## Tecnologías Utilizadas
- **Frontend**: HTML, CSS (Bootstrap), JavaScript.
- **Interactividad**: Uso de JavaScript para manejar eventos y realizar cálculos en el cliente.

## Beneficios
- Mejora la eficiencia del proceso de registro de notas.
- Permite a los docentes llevar un control más riguroso del desempeño académico de los estudiantes.
- Facilita la identificación de estudiantes que necesitan apoyo adicional.

## Conclusiones
El Sistema de Registro de Notas es una herramienta útil para educadores que desean simplificar el proceso de registro y seguimiento de las calificaciones de sus estudiantes, mejorando así la administración educativa.
