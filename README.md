🛡️ SonarQube Security Reports Generator

Generador automático de reportes de seguridad por proyecto (PDF + Word) a partir de SonarQube Community Edition, con gráficas y resumen ejecutivo.

Ideal para:

Auditorías de seguridad

Reportes a gerencia

Evidencias de cumplimiento

DevSecOps / Azure DevOps

🚀 Características

✔️ Un PDF y Word por proyecto
✔️ Gráficas automáticas:

Issues por severidad

Issues por tipo

Issues por estado
✔️ Cobertura de pruebas
✔️ Compatible con SonarQube Community
✔️ Sin dependencias de pago

📁 Estructura de salida
reports/
 ├─ <project-key>/
 │   ├─ <project-key>.pdf
 │   ├─ <project-key>.docx
 │   └─ charts/
 │       ├─ severidad.png
 │       ├─ tipo.png
 │       └─ estado.png

🧰 Requisitos

Python 3.9+
Acceso a SonarQube (token)

🔧 Instalación local

1️⃣ Clonar repositorio
git clone https://github.com/TU_USUARIO/sonar-security-reports.git
cd sonar-security-reports


2️⃣ Crear entorno virtual (recomendado)
python -m venv venv
source venv/bin/activate      # Linux / Mac
venv\Scripts\activate         # Windows

3️⃣ Instalar dependencias
pip install -r requirements.txt


🔐 Configuración
Edita el archivo sonar_security_report_per_project.py:
    -Configura:
        SONAR_URL = "http://tu-sonarqube"
        SONAR_TOKEN = "TU_TOKEN"


    -Y agrega los proyectos:
        PROJECT_KEYS = [
            "mi-proyecto-1",
            "mi-proyecto-2"
        ]

▶️ Ejecución
python sonar_security_report_per_project.py
