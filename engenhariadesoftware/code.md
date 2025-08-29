
# Sorveteria
```code
import java.util.LinkedList;
import java.util.List

public class Sorveteria {
    private List<Sorvete> sorvetes = new LinkedList<Sorvete>();
    public void addSorvete (Sorvete sorvete){
        sorvetes.add(sorvete);
    }
    public List<Sorvete> getSorvetes{
        return sorvetes;
    }
    
    private List<Cobertura> coberturas = new LinkedList<Cobertura>();
    public void addCobertura (Cobertura cobertura){
        coberturas.add(cobertura);
    }
    public List<Cobertura> getCobertura{
        return coberturas;
    }
}
```
# Sorvete
```code

public class Sorvete {
    private String sabor;
    private float preço;

    public Sorvete(String sabor, float preço) {
        this.sabor = sabor;
        this.preço = preço;
    }

    public String getSabor(){
        return sabor;
    }
}

```
# Cobertura
```code

public class Cobertura {
    private String sabor;
    private float preço;

    public Cobertura(String sabor, float preço) {
        this.sabor = sabor;
        this.preço = preço;
    }

    public String getSabor(){
        return sabor;
    }
}

```
