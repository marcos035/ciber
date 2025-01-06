```markdown
# **Phishing para Captura de Senhas do Facebook**

## **Descrição**
Este projeto demonstra como configurar um ambiente de phishing para capturar credenciais simuladas do Instagram utilizando o **Kali Linux** e a ferramenta **setoolkit**.  

⚠️ **Atenção:** Este material é apenas para fins educacionais. O uso indevido dessa técnica é **ilegal** e pode resultar em penalidades criminais. Utilize apenas em ambientes controlados e com permissão explícita.

---

## **Requisitos**
- **Sistema Operacional:** Kali Linux  
- **Ferramenta Necessária:** setoolkit (Social Engineering Toolkit)  

---

## **Passos para Configuração**
1. **Acesso root**  
   Acesse como superusuário:
   ```bash
   sudo su
   ```

2. **Inicie o setoolkit**  
   Execute o comando:
   ```bash
   setoolkit
   ```

3. **Configure o ataque no setoolkit:**  
   - **Tipo de ataque:** Social-Engineering Attacks  
   - **Vetor de ataque:** Web Site Attack Vectors  
   - **Método de ataque:** Credential Harvester Attack Method  
   - **Método de ataque adicional:** Site Cloner  

4. **Obtenha o IP da máquina local:**  
   Use o comando:
   ```bash
   ifconfig
   ```

5. **Informe a URL para clonar:**  
   No setoolkit, insira a URL do site que será clonado:
   ```
   http://www.instagram.com
   ```

6. **Acompanhe os resultados:**  
   O setoolkit exibirá as credenciais capturadas (se houver) no terminal.



