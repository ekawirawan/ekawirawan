```java
public class Main {
  private String name;
  private String location;

  public Main(String name, String location) {
    this.name = name;
    this.location = location;
  }

  public static void main(String[] args) {
    Main myProfile = new Main("I Putu Eka Wirawan", "Bali - Indonesia");
    System.out.println("Hello there, my name is " + myProfile.name + ", from " + myProfile.location);
  }
}

```
