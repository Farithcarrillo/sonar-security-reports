# 🛡️ SonarQube Security Reports Generator

Generador automático de **reportes de seguridad por proyecto** (PDF y Word) a partir de **SonarQube Community Edition**, incluyendo **gráficas**, **métricas clave** y **resumen ejecutivo**.

Pensado para entornos donde **pagar SonarQube Enterprise no es una opción**, pero se necesitan reportes formales y presentables.

---

## 🎯 Ideal para

- Auditorías de seguridad
- Reportes ejecutivos / gerencia
- Evidencias de cumplimiento
- Equipos **DevSecOps**
- Integraciones con **Azure DevOps**
- Proyectos Angular, TypeScript, Python y APIs

---

## 🚀 Características

✔️ Genera **1 PDF y 1 Word por proyecto**  
✔️ Gráficas automáticas:
- Issues por **severidad**
- Issues por **tipo**
- Issues por **estado**

✔️ Métricas de **cobertura de pruebas**  
✔️ Compatible con **SonarQube Community Edition**  
✔️ Sin licencias ni dependencias de pago  
✔️ Totalmente **self-hosted**

---

## 📁 Estructura de salida

```text
reports/
 ├─ <project-key>/
 │   ├─ <project-key>.pdf
 │   ├─ <project-key>.docx
 │   └─ charts/
 │       ├─ severidad.png
 │       ├─ tipo.png
 │       └─ estado.png
