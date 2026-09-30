# politica-empresarial
public class PoliticaEmpresarial implements PoliticaCuenta {

    @Override
    public String obtenerTipo() {
        return "Empresarial";
    }

    @Override
    public double calcularComisionTransferencia(double monto) {
        return monto * 0.01;
    }

    @Override
    public double calcularInteresMensual(double saldo) {
        return saldo * 0.001;
    }
}
