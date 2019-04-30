# Implementação OpenMP para memórias transacionais (experimental)

## O que há por aqui?
Arquivos C++ com as (pseudo) implementações em OpenMP utilizando a cláusula `transaction` para controlar o acesso a variáveis dentro das regiões paralelas

Fontes da propostas disponíveis no diretório cowichan/cowichan_openmp_transaction

#### Benchmarks com implementação realizada:
- hull
- norm
- outer
- sor
- thresh
- vecdiff
- winnow (somente quick_sort)

#### Fontes originais do cowichan:
Disponível em: https://code.google.com/archive/p/cowichan/

#### Implementações OpenMP originas cowichan:
Fontes disponíveis no diretório cowichan/cowichan_openmp

#### Implementações Nebelung:
- [Milovanovic et al. 2008] Nebelung:  Execution environment for transactional OpenMP. International Journal of Parallel Programming, 36(3):326–346.

Fontes disponíveis no diretório cowichan/cowichan_openmp_nebelung

#### Implementações Wong:
- [Wong et al. 2014] Towards transactional memory for OpenMP. Using and Improving OpenMP for Devices, Tasks, and More, pages 130–145, Cham. Springer International Publishing.

Fontes disponíveis no diretório cowichan/cowichan_openmp_wong

