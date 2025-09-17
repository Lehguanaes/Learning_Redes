## 🌐 Laboratório de Redes - Switches e Hubs no Cisco Packet Tracer  

## 🎯 Objetivo  
Este projeto tem como finalidade compreender o funcionamento básico de **switches** e **hubs** em uma rede local, explorando:  
- O aprendizado da **Tabela MAC**;
- O uso do modo **Simulation** no Packet Tracer;  
- A visualização do tráfego de pacotes em rede.

---

## 📌 Topologia  
A rede montada é composta por:  
- **Switch Central (SW-Central):** ponto de conexão principal.  
- **Switch 1 (SW-1):** conectado ao Switch Central e a 5 PCs.  
- **Switch 2 (SW-2):** conectado ao Switch Central e a 5 PCs.  
- **Hub (Hub-1):** conectado ao Switch Central e a 5 PCs.  

---

## 🛠️ Passo a Passo  

1. **No Cisco Packet Tracer Adicionei e conectei os dispositivos:**  
   - 3 switches (modelo **2960**)  
   - 1 hub (**PT-HUB**)  
   - 15 computadores (**PCs**)  
2. **Renomeei os switches:**  
   - `SW-1`  
   - `SW-2`  
   - `SW-Central`
3. **Realizei os testes de entrega de pacotes e verifiquei o tráfego**  
4. **Verifiquei a tabela MAC dos switches**
    - Comando: `show mac address-tab`  
---
## 📷 Aprendizado na Prática

Vemos que os switches mandam para todas as portas só na 1° vez, depois "aprendem" o caminho.
<br></br>
<img width="959" height="503" alt="image" src="https://github.com/user-attachments/assets/6a585a26-6856-405f-b219-682f5244f100" />
<img width="959" height="505" alt="image" src="https://github.com/user-attachments/assets/266a9cc5-caf6-4118-ad8b-943a25979736" />

Ja o Hub sempre manda para todas as portas.
<br></br>
<img width="959" height="503" alt="image" src="https://github.com/user-attachments/assets/1297e7f0-fbe5-4267-b7aa-0d05a90c9fee" />

## 📷 Resultado
<img width="959" height="503" alt="image" src="https://github.com/user-attachments/assets/69b9fa5e-3a2e-4d78-b032-3678f2348a98" />

---

## 🚀 Tecnologia Utilizada
- **Cisco Packet Tracer**  
---

## 📖 Aprendizados  
- Diferença entre **Switch** e **Hub**;
- Funcionamento da **Tabela MAC**;  
- Análise de pacotes com o modo **Simulation**;

---

👩‍💻 Desenvolvido como exercício prático de redes.
