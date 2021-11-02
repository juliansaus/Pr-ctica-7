# Practica-7 Ejercicio_1
#include <stdio.h>

int main()
{
    float num;
    printf("Ingrese un  número para verificar si es positivo, negativo, o es cero.\n");
    scanf("%f", &num);
    if (num > 0)
    {
        printf("El número es positivo.\n");
    }
    if (num == 0)
    {
        printf("El número es cero.\n");
    }
    if (num < 0)
    {
        printf("El número es negativo.\n");
    }
    return 0;
}
