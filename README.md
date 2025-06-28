Aqui deberia ir una descripción
from pathlib import Path

readme_content = """
# 👋 ¡Hola! Soy Cristofer Damián Camilo Ordoñez Osa

![GitHub Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Bienvenidos%20a%20mi%20perfil%20🚀&fontSize=30&fontAlignY=40)

🎓 Soy estudiante de **Ingeniería en Sistemas y Computación** en la Universidad Nacional de Colombia, actualmente cursando el **tercer semestre** con un promedio destacado de **4.8 / 5.0**.

💼 Actualmente realizo una **pasantía en 1C-Soft**, donde sigo perfeccionando mis habilidades en desarrollo empresarial.

---

## ✨ Sobre mí

🧩 Me apasiona resolver problemas, programar y aprender continuamente.  
🧠 También disfruto mucho de retos mentales, ¡como armar el cubo Rubik! 🟩🟦🟥🟨🟧⬜  
🌐 Me encanta participar en competencias de programación y trabajar en proyectos de impacto.

---

## 🏆 Logros destacados

- 🥈 **Medalla de Plata** en la categoría **Automatización de Procesos Empresariales** en el evento **BRICS Future Skills Challenge 2024**.
- 🥉 **Premio en la Olimpiada Internacional de Programación 1C** – [Más información aquí](https://1c-dn.com/news/colombian_student_wins_prize_at_global_1c_international_programming_contest/).

---

## 💻 Lenguajes de Programación

![Java](https://img.shields.io/badge/Java-red?style=flat&logo=java)
![Python](https://img.shields.io/badge/Python-blue?style=flat&logo=python)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript)
![Shell](https://img.shields.io/badge/Shell-black?style=flat&logo=gnu-bash)
![Assembly](https://img.shields.io/badge/Assembly-777?style=flat)
![XML](https://img.shields.io/badge/XML-FF6600?style=flat)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex)
![1C Script](https://img.shields.io/badge/1C--Script-yellow?style=flat)

---

## 🧰 Plataformas y Herramientas

![NetBeans](https://img.shields.io/badge/NetBeans-1B6AC6?style=flat&logo=apache-netbeans-ide)
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat&logo=android-studio)
![1C Enterprise](https://img.shields.io/badge/1C%20Enterprise-orange?style=flat)
![OnlineGDB](https://img.shields.io/badge/OnlineGDB-blue?style=flat)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github)

---

## 🧠 Proyectos relevantes

- 🛡️ **Zypher** – Encriptador de texto por sustitución de vocales.  
- 💰 **Finance Pal** – App Android para control de finanzas personales.  
- 🎭 **Bocu** – App para la promoción de eventos culturales en Bogotá.  
- 📦 **Gestión empresarial 1C** – Aplicación para automatizar pedidos y administración.

---

## 🗣️ Idiomas

- 🇪🇸 Español: Nativo  
- 🇬🇧 Inglés: Intermedio (certificación ICFES)  
- 🇩🇪 Alemán: Intermedio (curso *English Dot Works 5*, SENA)

---

## 📬 Contacto

📧 cristodamian24@gmail.com  
📞 +57 304 255 9680  
🌍 Bogotá, Colombia  

---

## 📊 GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=cristoferOrdonez&layout=compact&theme=radical)
![GitHub stats](https://github-readme-stats.vercel.app/api?username=cristoferOrdonez&show_icons=true&theme=radical)

---

> _"El mejor código es el que no se escribe, pero si lo escribes, ¡hazlo con pasión!"_ 💡

---

¡Gracias por visitar mi perfil! 🙌  
🔗 [Portafolio en GitHub](https://github.com/cristoferOrdonez)
"""

# Guardar como archivo markdown
output_path = Path("/mnt/data/README_cristoferOrdonez.md")
output_path.write_text(readme_content, encoding="utf-8")
output_path.name

