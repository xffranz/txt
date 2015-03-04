public class Bicicleta {
 
    // A Classe Bicicleta possui tres atributos
    public int cadencia;
    public int marcha;
    public int velocidade;
    
    // A Classe Bicicleta possui um construtor
    public Bicicleta(int cadenciaInicial, int velocidadeInicial, int marchaInicial) {
        marcha = marchaInicial;
        cadencia = cadenciaInicial;
        velocidade = velocidadeInicial;
    }
    
    // A Classe Bicicleta possui quatro metodos
    public void setCadencia(int novoValor) {
        cadencia = novoValor;
    }
    
    public void setMarcha(int novoValor) {
        marcha = novoValor;
    }
    
    public void acionaFreio(int diminui) {
        velocidade -= diminui;
    }
    
    public void aumentaVelocidade(int aumenta) {
        velocidade += aumenta;
    }
 
}
