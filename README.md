# CE-4302-TallerOpeMP

Comandos de compilación:

## Saxpy no paralelizado

  gcc -o saxpy saxpy.c -fopenmp
  
## Saxpy paralelizado

  gcc -o saxpy_par saxpy_par.c -fopenmp
  
## Matrix paralelizado

  g++ -o matrix matrix.cpp -fopenmp
