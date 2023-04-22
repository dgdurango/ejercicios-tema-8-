# ejercicios-tema-8-

public class Persona {
  private int edad;
  private String nombre;
  private String telefono;
  
  // Constructor
  public Persona(int edad, String nombre, String telefono) {
    this.edad = edad;
    this.nombre = nombre;
    this.telefono = telefono;
  }
  
  // Getters y Setters
  public int getEdad() {
    return edad;
  }

  public void setEdad(int edad) {
    this.edad = edad;
  }

  public String getNombre() {
    return nombre;
  }

  public void setNombre(String nombre) {
    this.nombre = nombre;
  }

  public String getTelefono() {
    return telefono;
  }

  public void setTelefono(String telefono) {
    this.telefono = telefono;
  }
}

public static void main(String[] args) {
  Persona persona = new Persona(25, "Juan", "1234567890");
  
  persona.setEdad(30);
  persona.setNombre("Pedro");
  persona.setTelefono("0987654321");
  
  System.out.println("Nombre: " + persona.getNombre());
  System.out.println("Edad: " + persona.getEdad());
  System.out.println("Teléfono: " + persona.getTelefono());
}
