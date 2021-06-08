# Calculadora - Main test
Descripcion

# DEPENDENCIAS:
* UI_v2.msa: initdis, clrdis, println, waitkey, outchar, numForm
* string.msa: int4str, str2int
* math_ops.msa: op_suma, op_rest, op_div, op_mul
* utils.msa: delay, push_L, push_R
>
* str_hand.def (string handlers)
* op_hand.def (operation handlers)
* flowctrl.def (flow control macros)

#
Para LINKEAR:
```
link11_2 maintest,UI_v2,string,math_ops,utils
```



#
## Casos de error

Casos en los que las operaciones matematicas dan error

|  OPERACION          |  ERROR  	|
|---------------|-----------------------|
|suma		| result > 999
|resta          | result < 0
|mult          	| result > 999
|div          	| div = 0

#

### Editar markdown online
https://stackedit.io/app#