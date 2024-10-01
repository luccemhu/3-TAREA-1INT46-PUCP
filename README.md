# 3-TAREA-1INT46-PUCP
Integrantes: Joel Huamaní y Luis Valverde

Descripción: Este estudio analiza la Base de datos de Tratados Bilaterales de Inversión de The International Centre for Settlement of Investment Disputes-[ICSID](https://icsid.worldbank.org/) de The World Bank Group. En particular, recopilamos los [tratados por año de firma desde 1996 hasta 2004:](https://icsid.worldbank.org/es/recursos/base-de-datos/base-de-datos-de-Tratados-Bilaterales-de-Inversi%C3%B3n)

| Nombre de la Variable                    | Descripción                                                                                                         | Tipo de Variable          | Ejemplo                 |
|------------------------------------------|---------------------------------------------------------------------------------------------------------------------|---------------------------|-------------------------|
| `parties`                                | Lista de países o partes involucradas en el acuerdo.                                                               | `factor` (categórica)    | "Perú - Ecuador"       |
| `sig_date`                               | Fecha de firma del acuerdo. Este campo indica cuándo se firmó oficialmente el acuerdo entre las partes.           | `datetime64[ns]`         | 2021-01-15              |
| `entry_date`                             | Fecha de entrada en vigor del acuerdo. Representa el momento en que el acuerdo comienza a tener efecto legal.     | `datetime64[ns]`         | 2021-03-01              |
| `ICSID`                                  | Referencia al Centro Internacional de Arreglo de Diferencias Relativas a Inversiones (ICSID). Este campo indica si el acuerdo tiene alguna relación con el ICSID. | `factor` (categórica)    | "Yes / No"     |

