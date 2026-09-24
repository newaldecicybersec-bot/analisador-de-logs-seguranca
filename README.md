# analisador-de-logs-seguranca
# Simulador de Análise de Logs de Segurança
# Autor: Aldeci Barbosa da Costa

def analisar_logs(caminho_arquivo):
    print("[*] Iniciando a varredura de logs de acesso...")
    # Simulação de detecção de falhas de segurança
    tentativas_falhas = 3
    
    if tentativas_falhas > 2:
        print("[!] ALERTA: Múltiplas falhas de autenticação detectadas!")
    else:
        print("[+] Nenhum comportamento suspeito encontrado.")

if __name__ == "__main__":
    analisar_logs("auth.log")
