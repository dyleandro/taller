public class arbol {
    public String nombre;
   public String color;
   public String decoracion;
   public String altura;
   public String descripcion;
   public arbol(){
}
   public void armar(){
       System.out.print("se buscan las piezaspara armar");
   }
 
    public void desarmar(){
       System.out.print("se desarman las piezas");
   }
     public void decorar(){
       System.out.print("se buscan las decoraciones");
   }
       public void buscar(){
       System.out.print("se busca el arbol de navidad");
   }
       public void guardar(){
       System.out.print("se guardan las piezas en su caja");
   } 
    public String getNombre() {
        return nombre;
    }
 
    public void setNombre(String nombre) {
        this.nombre = nombre;
    }
 
    public String getColor() {
        return color;
    }
 
    public void setColor(String color) {
        this.color = color;
    }
 
    public String getDecoracion() {
        return decoracion;
    }
 
    public void setDecoracion(String decoracion) {
        this.decoracion = decoracion;
    }
 
    public String getAltura() {
        return altura;
    }
 
    public void setAltura(String altura) {
        this.altura = altura;
    }
 
    public String getDescripcion() {
        return descripcion;
    }
 
    public void setDescripcion(String descripcion) {
        this.descripcion = descripcion;
    }
}
