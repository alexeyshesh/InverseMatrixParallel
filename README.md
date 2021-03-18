# InverseMatrixParallel
## Inverse of a matrix using Gauss-Jordan Elimination

You can find information about this method [here](https://en.wikipedia.org/wiki/Gaussian_elimination#Finding_the_inverse_of_a_matrix).

There is three programs that solves this problem in repo:

- in `main.cpp` you can find non-parallel solution
- in `matrix_omp.cpp` you can find parallel solution using OpenMP library
- `matrix_mpi.cpp` you can find parallel solution using MPI library

Programs were tested on Moscow State University supercomputers IBM Polus and BlueGene. Results are described in `results.pdf` file in Russian.

## Поиск обратной матрицы методом Гаусса-Жордана

Подробнее про метод можно прочитать [здесь](https://ru.wikipedia.org/wiki/%D0%9C%D0%B5%D1%82%D0%BE%D0%B4_%D0%93%D0%B0%D1%83%D1%81%D1%81%D0%B0_%E2%80%94_%D0%96%D0%BE%D1%80%D0%B4%D0%B0%D0%BD%D0%B0).

В репозитории три программы, решающие эту задачу:

- `main.cpp` - решение задачи без параллельных вычислений
- `matrix_omp.cpp` - решение с использованием библиотеки для параллельных вычислений OpenMP
- `matrix_mpi.cpp` - решение с использованием библиотеки для параллельных вычислений MPI

Программы были протестированы на суперкомпьютерах МГУ им. Ломоносова IBM Polus и BlueGene. Реузльтаты описаны в файле `results.pdf`.
