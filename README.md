# Slovenian Python Syntax Highlighting

## Syntax

```py
| Slovenian   | English   |
|-------------|-----------|
| definiraj   | def       |
| za          | for       |
| v           | in        |
| dokler      | while     |
| vključi     | import    |
| iz          | from      |
| vrni        | return    |
| natisni     | print     |
| obseg       | range     |
| kot         | as        |
| vnos        | input     |
| če          | if        |
| drugače     | else      |
| drugačeče   | elif      |
| in          | and       |
| ali         | or        |
| razred      | class     |
| preveri     | assert    |
| zlomi       | break     |
| nadaljuj    | continue  |
| izbriši     | del       |
| razen       | except    |
| Ne          | False     |
| Da          | True      |
| končno      | finally   |
| globalno    | global    |
| je          | is        |
| Nič         | None      |
| nelokalen   | nonlocal  |
| ne          | not       |
| brez        | pass      |
| dvigni      | raise     |
| poskusi     | try       |
| z           | with      |
| dajaj       | yield     |
```

## Example

```
vključi random kot r

ugib = int(vnos("Vnesi št od 1-10: "))

naključna = r.randrange(1, 10)

dokler ugib != naključna:
    če ugib > naključna:
        natisni("Preveč")
    drugače:
        natisni("Premalo")
    ugib = int(vnos("Vnesi št od 1-10: "))
natisni(f"Bravo, naključna št je bila {naključna}")
```

## Transpiler

To use this "language" you need a transpiler. You can find it on [Github](https://github.com/Anzlc/slovenian-python/)

If you find any issues follow instructions in repo.
