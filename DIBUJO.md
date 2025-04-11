public class dibujo {
    public String forma;
    public String nombre;
    public String  colores;
    public String movimiento;
    public String galaxia;
    
    

    
    public void girar(){
        System.out.print("rotacion");
    }
    
     public void temperatura(){
        System.out.print("clima");
    }
     
     public void energia(){
        System.out.print("solar");
    }
    
     public void velocidad(){
        System.out.print("tiempo");
    }
     
     public void movimiento(){
        System.out.print("traslacion");
    }
   
     
    
    public String getForma() {
        return forma;
    }

    public void setForma(String forma) {
        this.forma = forma;
    }

    public String getNombre() {
        return nombre;
    }

    public void setNombre(String nombre) {
        this.nombre = nombre;
    }

    public String getColores() {
        return colores;
    }

    public void setColores(String colores) {
        this.colores = colores;
    }

    public String getMovimiento() {
        return movimiento;
    }

    public void setMovimiento(String movimiento) {
        this.movimiento = movimiento;
    }

    public String getGalaxia() {
        return galaxia;
    }

    public void setGalaxia(String galaxia) {
        this.galaxia = galaxia;
    }
    
}
