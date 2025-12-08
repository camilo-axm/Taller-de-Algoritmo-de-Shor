# 🔐 Taller de Algoritmo de Shor

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Un taller interactivo completo sobre el **Algoritmo de Shor**, el algoritmo cuántico que revolucionó la criptografía al demostrar que la factorización de números enteros puede realizarse en tiempo polinomial usando computadoras cuánticas.

## 📚 Descripción

Este repositorio contiene un Jupyter Notebook educativo que explora el algoritmo de Shor desde sus fundamentos matemáticos hasta su implementación práctica. Ideal para estudiantes de ciencias de la computación, matemáticas, física cuántica y cualquier persona interesada en la computación cuántica.

### ¿Qué es el Algoritmo de Shor?

El algoritmo de Shor, propuesto por Peter Shor en 1994, es un algoritmo cuántico que puede factorizar números enteros en tiempo polinomial. Esta capacidad representa una amenaza potencial para los sistemas de encriptación RSA que dependen de la dificultad computacional de la factorización.

## ✨ Contenido del Taller

### 1. **Aritmética Modular**
- Operaciones módulo básicas
- Congruencias modulares
- Propiedades y ejemplos prácticos

### 2. **Exponenciación Modular**
- Cálculo de potencias modulares
- Implementación recursiva eficiente
- Visualización de patrones periódicos

### 3. **Búsqueda del Período**
- Función periódica `f(x) = a^x mod N`
- Identificación del período `r`
- Teoremas de teoría de números

### 4. **Factorización**
- Del período a los factores
- Algoritmo de Euclides (GCD)
- Verificación de resultados

### 5. **Algoritmo Cuántico**
- Representación en circuitos cuánticos
- Estados cuánticos superpuestos
- Transformada cuántica de Fourier

## 🚀 Ejercicios Resueltos

El notebook incluye soluciones completas para:

### ✅ Ejercicio 1: Verificación de Congruencias
Demostración paso a paso de:
- `1977 ≡ 1 (mod 247)`
- `16183 ≡ 15442 (mod 247)`

### ✅ Ejercicio 2: Factorización de N=247
Implementación completa del algoritmo de Shor para factorizar `N=247` usando `a=2`:
- **Período encontrado:** r = 36
- **Factores:** 13 y 19
- **Verificación:** 13 × 19 = 247 ✓

## 📊 Visualizaciones

El taller incluye múltiples gráficas interactivas que ilustran:
- Patrones periódicos en funciones modulares
- Comportamiento de diferentes valores de `a` y `N`
- Representación visual de la búsqueda del período

![Shor's Algorithm](images/shoralgorithm.jpg)

## 🛠️ Instalación y Uso

### Requisitos Previos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)

### Instalación

1. **Clonar el repositorio:**
```bash
git clone https://github.com/camilo-axm/Taller-de-Algoritmo-de-Shor.git
cd Taller-de-Algoritmo-de-Shor
```

2. **Instalar dependencias:**
```bash
pip install -r Requirements.txt
```

3. **Iniciar Jupyter Notebook:**
```bash
jupyter notebook Shors_Algorithm_Workshop.ipynb
```

### Ejecución Rápida

Si prefieres ejecutar el notebook en la nube sin instalación local:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camilo-axm/Taller-de-Algoritmo-de-Shor/blob/main/Shors_Algorithm_Workshop.ipynb)

## 📦 Dependencias

```
matplotlib >= 3.5.0  # Visualización de gráficas
numpy >= 1.21.0      # Operaciones numéricas
jupyterlab >= 3.0.0  # Entorno de notebook
```

## 🎯 Características Destacadas

- ✅ **Código completamente documentado** en español
- ✅ **Explicaciones matemáticas detalladas** con notación LaTeX
- ✅ **Ejemplos interactivos** ejecutables
- ✅ **Visualizaciones** con matplotlib
- ✅ **Ejercicios resueltos** paso a paso
- ✅ **Implementación eficiente** de algoritmos
- ✅ **Verificaciones automáticas** de resultados

## 🧮 Funciones Implementadas

```python
powersAModuloN(a, N)              # Calcula a^x mod N para x en [0, N)
powersAModuloNRecursive(a, N)     # Versión optimizada recursiva
periodoDeF(a, N)                  # Encuentra el período de f(x)
findPeriod(a, N)                  # Alias de periodoDeF
gcd(a, b)                         # Algoritmo de Euclides
computeAndDrawPowersAModuloN()    # Visualiza la función periódica
```

## 📖 Estructura del Proyecto

```
Taller-de-Algoritmo-de-Shor/
│
├── Shors_Algorithm_Workshop.ipynb  # Notebook principal del taller
├── Requirements.txt                 # Dependencias del proyecto
├── README.md                        # Este archivo
├── images/
│   └── shoralgorithm.jpg           # Diagrama del circuito cuántico
└── .gitignore                       # Archivos ignorados por git
```

## 🎓 Objetivos de Aprendizaje

Al completar este taller, serás capaz de:

1. ✅ Comprender los fundamentos de la aritmética modular
2. ✅ Implementar algoritmos de exponenciación modular eficientes
3. ✅ Encontrar el período de funciones modulares
4. ✅ Aplicar el algoritmo de Shor para factorización
5. ✅ Entender las implicaciones en criptografía RSA
6. ✅ Visualizar conceptos de computación cuántica

## 📚 Referencias y Recursos Adicionales

- **Yanofsky, N. S., & Mannucci, M. A.** - *Quantum Computing for Computer Scientists*. Cambridge University Press. (p. 217)
- **Nielsen, M. A., & Chuang, I. L.** (2010) - *Quantum Computation and Quantum Information*
- **Kaye, P., Laflamme, R., & Mosca, M.** (2007) - *An Introduction to Quantum Computing*
- [Qiskit Documentation](https://qiskit.org/documentation/) - Framework de IBM para computación cuántica
- [Shor's Algorithm - Original Paper](https://arxiv.org/abs/quant-ph/9508027) - Peter W. Shor (1995)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el taller:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/MejoraTaller`)
3. Commit tus cambios (`git commit -m 'Añade nueva explicación'`)
4. Push a la rama (`git push origin feature/MejoraTaller`)
5. Abre un Pull Request

## 📝 Notas Importantes

- **Complejidad Computacional:** El algoritmo clásico implementado aquí tiene complejidad exponencial. La ventaja cuántica real requiere hardware cuántico.
- **Propósito Educativo:** Este material está diseñado con fines educativos para entender los principios del algoritmo de Shor.
- **Limitaciones:** Para factorizar números grandes, se requiere una computadora cuántica real con suficientes qubits.

## 🌟 Próximos Pasos

Para profundizar en computación cuántica:
- Explorar [IBM Quantum Experience](https://quantum-computing.ibm.com/)
- Aprender [Qiskit](https://qiskit.org/) para programación cuántica
- Estudiar otros algoritmos cuánticos (Grover, Deutsch-Jozsa, etc.)

## 👤 Autor

**Camilo Aguirre** - [GitHub Profile](https://github.com/camilo-axm)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🙏 Agradecimientos

- Peter Shor por su revolucionario algoritmo
- La comunidad de computación cuántica
- Todos los contribuidores y estudiantes que usen este material

---

⭐ Si este taller te resultó útil, no olvides darle una estrella al repositorio!

📧 ¿Preguntas o sugerencias? Abre un [issue](https://github.com/camilo-axm/Taller-de-Algoritmo-de-Shor/issues)
