# ES

# Implementación de la Serie de Taylor para la Estimación de Tasas de Interés Efectivas en Python

Este proyecto implementa un programa en Python que permite calcular el nuevo precio estimado de un bono después de una variación en la tasa de interés. El cálculo se realiza utilizando la duración y convexidad del bono mediante la serie de Taylor.

## Variables Solicitadas para la Ejecución
Para ejecutar el programa, es necesario proporcionar los siguientes valores a través de la función obtener_datos_usuario():

Valor Nominal del Bono (VN):

    Tipo: Float
    Descripción: El valor nominal o valor facial del bono.

Tasa de Interés Contractual (C):

    Tipo: Float
    Descripción: La tasa de interés contractual del bono, expresada en formato decimal.

Frecuencia de Capitalización por Año (n):

    Tipo: Integer
    Descripción: La cantidad de veces que la tasa de interés se capitaliza por año.

Plazo Total del Bono en Años (T):

    Tipo: Float
    Descripción: El plazo total del bono en años.

Precio Después de la Comisión (P):

    Tipo: Float
    Descripción: El precio del bono después de aplicar la comisión.

Tasa de Interés Inicial (R):

    Tipo: Float
    Descripción: La tasa de interés inicial del bono, expresada en formato decimal.

Variación en la Tasa de Interés (dR):

    Tipo: Float
    Descripción: La variación en la tasa de interés que se desea analiza


## Ejemplo de Inserción de Datos:

    1. Valor Nominal del Bono (VN): 1000.0
    2. Tasa de Interés Contractual (C): 0.05 (equivalente al 5%)
    3. Frecuencia de Capitalización por Año (n): 2
    4. Plazo Total del Bono en Años (T): 5.0
    5. Precio Después de la Comisión (P): 950.0
    6. Tasa de Interés Inicial (R): 0.03 (equivalente al 3%)
    7. Variación en la Tasa de Interés (dR): 0.01 (equivalente al 1%)


--------


# EN

# Implementation of Taylor Series for Effective Interest Rate Estimation in Python

This project implements a Python program that calculates the estimated new price of a bond after a change in the interest rate. The calculation is performed using bond duration and convexity through the Taylor series.


# Variables Required for Execution

To run the program, it is necessary to provide the following values through the obtener_datos_usuario() function:

Nominal Value of the Bond (VN):

    Type: Float
    Description: The nominal or face value of the bond.

Contractual Interest Rate (C):

    Type: Float
    Description: The contractual interest rate of the bond, expressed in decimal format.

Capitalization Frequency per Year (n):

    Type: Integer
    Description: The number of times the interest rate is compounded per year.

Total Term of the Bond in Years (T):

    Type: Float
    Description: The total term of the bond in years.

Price After Commission (P):

    Type: Float
    Description: The price of the bond after applying the commission.

Initial Interest Rate (R):

    Type: Float
    Description: The initial interest rate of the bond, expressed in decimal format.

Interest Rate Variation (dR):

    Type: Float
    Description: The variation in the interest rate to be analyzed.


# Example Data Insertion:

    1. Nominal Value of the Bond (VN): 1000.0
    2. Contractual Interest Rate (C): 0.05 (equivalent to 5%)
    3. Capitalization Frequency per Year (n): 2
    4. Total Term of the Bond in Years (T): 5.0
    5. Price After Commission (P): 950.0
    6. Initial Interest Rate (R): 0.03 (equivalent to 3%)
    7. Interest Rate Variation (dR): 0.01 (equivalent to 1%)


    
