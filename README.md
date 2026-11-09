# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** José Humberto Zúniga Aguilar
- **Carné:** N/A
- **Correo institucional:**  N/A
- **Asignatura:** Lenguajes de Programación con Aspectos de Seguridad
- **Fecha:** 08 de Noviembre de 2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas, registro de eventos de autenticación y detección de incidentes, incluyendo el cálculo de las métricas MTTD y MTTR.

## 3. Estructura del proyecto

```text
laboratorio-las/
├── templates/
│   ├── login.html
│   └── registro.html
├── venv/
├── app.py
├── crearDB.py
├── detector.py
├── eventos.log
├── respuesta.log
├── usuarios.db
└── README.md
```

## 4. Ejecución del proyecto

**Paso 1.** Clonar el repositorio.

```bash
git clone URL_DEL_REPOSITORIO
```

**Paso 2.** Ingresar al proyecto.

```bash
cd repositorio/proyecto
```

**Paso 3.** Instalar las dependencias.

```bash
pip install -r requirements.txt
```

**Paso 4.** Ejecutar la aplicación.

```bash
python app.py
```
## 5. Resultados de Métricas (MTTD y MTTR)

| Prueba | MTTD (segundos) | MTTR (segundos) |
| :--- | :--- | :--- |
| **1** | 518.0 | 1356.0 |
| **2** | 518.0 | 1523.0 |
| **3** | 518.0 | 1643.0 |
| **Promedio** | **518.0** | **1507.33** |

* **MTTD promedio:** 518.0 segundos
* **MTTR promedio:** 1507.33 segundos
