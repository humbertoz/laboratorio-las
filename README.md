# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** José Humberto Zúniga Aguilar
- **Carné:** 04234017-9
- **Correo institucional:**  humberto.zng@gmail.com
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