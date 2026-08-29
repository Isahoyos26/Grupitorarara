# 🍕 Grupitorarara

**Proyecto académico de trading e inversión** construido con [uv](https://docs.astral.sh/uv/) y [Streamlit](https://streamlit.io/).

> La meta declarada del curso: aprender a operar el mercado y, al final del semestre, usar ese conocimiento para comprar una pizza. Todo lo demás en este repo existe para llegar ahí.

---

## 📌 Sobre el proyecto

Este es un proyecto **académico**, no asesoría financiera ni un producto de trading en producción. Nace como espacio de práctica dentro de un semestre de clases, con dos objetivos que se retroalimentan:

1. **Aprender a operar el mercado**: entender instrumentos financieros, leer datos de precios, probar estrategias y construir herramientas simples para analizarlas.
2. **Aplicar ese conocimiento a una meta concreta y divertida**: llegar a fin de semestre con suficiente entendimiento (idealmente, ganancias) como para comprar una pizza gracias a lo aprendido.

La pizza es el criterio de éxito informal del semestre — si el grupo entiende el mercado lo suficiente como para financiarla con lo aprendido, el proyecto cumplió su propósito.

## 🎯 Objetivos de aprendizaje

- Comprender conceptos base de mercados financieros (precios, volatilidad, órdenes, riesgo).
- Practicar con datos reales o simulados a lo largo del curso.
- Construir una interfaz interactiva simple para visualizar y experimentar con esos datos.
- Iterar en equipo, documentando qué funciona y qué no.
- Cerrar el semestre con una demostración tangible del aprendizaje: la pizza.

## 🛠️ Stack técnico

| Herramienta | Uso |
|---|---|
| [Python](https://www.python.org/) | Lenguaje base del proyecto |
| [uv](https://docs.astral.sh/uv/) | Gestión del entorno virtual y dependencias |
| [Streamlit](https://streamlit.io/) | Interfaz web interactiva |

## 📂 Estructura del repositorio

```
Grupitorarara/
├── app.py                     # App principal de Streamlit
├── pyproject.toml             # Configuración del proyecto y dependencias
├── uv.lock                    # Lockfile de dependencias (uv)
├── src/
│   └── grupitorarara/
│       └── __init__.py
├── LICENSE
└── README.md
```

## 🚀 Cómo correrlo

### Requisitos

- [uv](https://docs.astral.sh/uv/getting-started/installation/) instalado.

### Pasos

```bash
# Clonar el repositorio
git clone https://github.com/Isahoyos26/Grupitorarara
cd Grupitorarara

# Instalar dependencias (crea el entorno virtual automáticamente)
uv sync

# Correr la app
uv run streamlit run app.py
```

La app quedará disponible en `http://localhost:8501`.

## 🗺️ Roadmap del semestre

- [x] Setup inicial del proyecto (uv + Streamlit)
- [ ] Ingesta de datos de mercado (histórico o en vivo)
- [ ] Panel de visualización de precios e indicadores
- [ ] Simulación/backtesting de estrategias simples
- [ ] Registro de aprendizajes y resultados del grupo
- [ ] 🍕 Compra de la pizza de fin de semestre

## ⚠️ Disclaimer

Este proyecto tiene fines **exclusivamente educativos**. Nada de lo que contiene es recomendación de inversión. Cualquier decisión financiera basada en este código es responsabilidad de quien la tome.

## 👥 Autoría

Proyecto de grupo — curso académico, 2026.

## 📄 Licencia

Este proyecto está bajo licencia [MIT](LICENSE).
