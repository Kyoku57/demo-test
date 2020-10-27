# demo-test

## Etape 1 : Réaliser une simple service API REST

```
POST {endpoint}/add
{ 
    "a": integer, 
    "b": integer 
}
```

avec pour résultat 
```
{ 
    "result": a + b 
}
```


## Etape 2 : Faire un CRUD en API REST

```
GET
POST
PUT
DELETE 

{endpoint}/documents 
{endpoint}/documents/{docid}
```

Peut être fait en mémoire (pas de DB nécessaire)
