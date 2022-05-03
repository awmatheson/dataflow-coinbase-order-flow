# dataflow-order-book
A [Bytewax](https://docs.bytewax.io/) dataflow that maintains an order book in real-time from the coinbase level2 data and outputs details of the spread.

Requires Python >=3.7

## Prerequisits

Install bytewax and websockets

```
pip install -r requirements.txt
```

Now run it!
```
python orderbook.py
```

```
...
(1046, ('BTC-USD', (38590.1, 0.00945844, 38596.73, 0.01347429, 6.630000000004657)))
(1047, ('BTC-USD', (38590.1, 0.00945844, 38597.13, 0.02591147, 7.029999999998836)))
(1048, ('BTC-USD', (38590.1, 0.00945844, 38597.13, 0.02591147, 7.029999999998836)))
(1049, ('BTC-USD', (38590.1, 0.00945844, 38597.13, 0.02591147, 7.029999999998836)))
(1050, ('BTC-USD', (38590.1, 0.00945844, 38597.13, 0.02591147, 7.029999999998836)))
(1051, ('BTC-USD', (38590.1, 0.00945844, 38597.13, 0.02591147, 7.029999999998836)))
...
```

[bytewax repo](https://github.com/bytewax/bytewax)
