# 📘 Desafio DIO: Criação de um Phishing com o Kali Linux
## 🛠️ Metodologia
1. **Sistema Operacional**: kali linux
2. **Ferramenta utilizada**: setoolkit
3. **Simulação**: criação de uma página de login falsa (index.html)

![Clique para ver execução](images/kali-phishing-index.html.PNG)

   ⚠️ **Aviso importante:** Nenhuma credencial real foi coletada. O desafio é estritamente educacional e não deve ser utilizado para fins maliciosos.
## ⚙️ Configuração do Ambiente
**Acesso root:** `sudo su`

**Iniciando o setoolkit:** `setoolkit`

**Tipo de ataque:** `Social-Engineering Attacks`

![Clique para ver execução](images/kali-phishing-menu-social-engineering-attacks.PNG)

**Vetor de ataque:** `Web Site Attack Vectors`

![Clique para ver execução](images/kali-phishing-menu-web-site-attack-vectors.PNG)

**Método de ataque:** `Credential Harvester Attack Method` 

![Clique para ver execução](images/kali-phishing-menu-credential-harvester-attack-method.PNG)

**Método de ataque:** `Custom Import`

![Clique para ver execução](images/kali-phishing-menu-custom-import.PNG)

**Obtendo o endereço da máquina:** `Index.html`
Informamos o caminho da criação do arquivo index.html (página de login falsa) no kali linux. Depois disso, há o direcionamento, a partir do IP da máquina, que serve a página de login falsa na porta 80.
![Clique para ver execução](images/kali-phishing-menu-copy-just-the-index.html.PNG)

## 📊 Resultados
