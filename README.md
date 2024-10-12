public class GenapGanjil {

    public static void main(String[] args) {
        int angka = 10;

        if ((angka & 1) == 0) {
            System.out.println(angka + " adalah genap.");
        } else {
            System.out.println(angka + " adalah ganjil.");
        }
    }
}
