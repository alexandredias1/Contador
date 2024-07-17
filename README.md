# Contador de 1 a 10

Este é um script em Python que conta de 1 a 10, imprimindo cada número a cada segundo. O script utiliza a função `time.sleep()` para pausar a execução entre as impressões.

## Descrição

O script inicia um contador que começa em 1 e vai até 10. A cada iteração, o número atual é impresso na tela, e o programa espera 1 segundo antes de continuar para o próximo número.

## Funcionalidades

- Contar de 1 a 10.
- Imprimir cada número com um intervalo de 1 segundo.

## Como usar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Salve o script em um arquivo com a extensão `.py` (por exemplo, `contador.py`).
3. Abra um terminal ou prompt de comando.
4. Navegue até o diretório onde o script foi salvo.
5. Execute o script com o comando `python contador.py`.

## Exemplo de uso

```python
import time

contador = 1
while contador <= 10:
    print(contador)
    time.sleep(1)
    contador = contador + 1
