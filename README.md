# Codigo-de-discretas
Codigo de ordenamientos para matematicas discretas con el maestro Jesus Francisco

# Autor
Jorge Alejandro Montaño Gutierrez

# Descripción
Este codigo implementa y compara experimentalmente el rendimiento de siete algoritmos de ordenamiento clásicos en C++. El análisis incluye mediciones de tiempo para evaluar su eficiencia con diferentes conjuntos de datos aleatorios.

# Requisitos del Sistema
- Compilador C++ compatible con C++11 (g++ recomendado)
- 4GB de RAM mínimo
- 500MB de espacio en disco
- Sistema operativo: Windows/Linux/macOS
- Python 3.x (opcional, para visualización de gráficos)

# Compilación
g++ main.cpp -o sorting_analysis -std=c++11 -O2

# Ejecucion
./sorting_analysis

# Grafica
python3 plot_results.py

# Algoritmos

1. **Insercion** (`insertion_sort.cpp`)
2. **Burbuja** (`bubble_sort.cpp`)
3. **Seleccion** (`selection_sort.cpp`)
4. **Union** (`merge_sort.cpp`)
5. **Rapida** (`quick_sort.cpp`)
6. **Monticulos** (`heap_sort.cpp`)
7. **Shell** (`shell_sort.cpp`)

# Conclusiones
Para arreglos pequeños (n ≤ 100), Insertion Sort puede ser competitivo con algoritmos más complejos.
Quick Sort es la mejor opción general para conjuntos de datos aleatorios.
Bubble Sort debería evitarse en aplicaciones reales por su pobre rendimiento.
La elección del algoritmo debe considerar tanto el tamaño de los datos como su distribución inicial.
