# Primeros pasos
## Definición de tipos de datos
```
    int myInt = 0;
    double myDouble = 3.14;
    string myString = "string";
    char myChar = "c";
    var myVar = "Variable declared but not used";
    const my constant = "Constant, it never change";
```

## Definición de una clase
#### Necesita declararse antes de la clase toda la ejecución y llamados de la misma
```
    ClassExample classExample = new ClassExample();
    classExample.attribute = "Attribute";
```

#### El símbolo ? es usado para definir nulidad en el elemento

```
    class ClassExample 
    {
        public string? attribute = { get; set;}
        private string? attributePrivate = { get; set;}
    }
```


