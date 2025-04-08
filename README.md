public class Aula12 {
     public static void main(String[] args) {
        Relogio relogio = new Relogio();
        
       
        relogio.setHora(20);
        relogio.setMinuto(46);
        relogio.setSegundo(28);
        relogio.exibir();

        int horaAtual = relogio.getHora();
        int minutoAtual = relogio.getMinuto();
        int segundoAtual = relogio.getSegundo();
        System.out.println("Hora atual: " + horaAtual);
        System.out.println("Minuto atual: " + minutoAtual);
        System.out.println( "Segundo Atual: " + segundoAtual);
        
     }
}
