<h1 align="center">Davi Nunes</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3500&pause=900&color=36BCF7&center=true&vCenter=true&width=620&lines=%24+sudo+resolva-o-neg%C3%B3cio+--com-ia+--ou-sem;It's+not+DNS.+There's+no+way+it's+DNS...+It+was+DNS.;There's+no+place+like+127.0.0.1+%F0%9F%8F%A0;Already+tried+turning+it+off+and+on+again%3F" alt="typing"/>
</p>

<p align="center">
  <b>Consultor de Tecnologia para Empresas · Fundador da Axisnetworks</b><br>
  Tecnologia que resolve o negócio, com IA ou sem: do diagnóstico à operação.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/idavinunes/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:idavinunes@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>
  <a href="https://api.whatsapp.com/send?phone=5521965528916"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
</p>

```bash
davi@axis:~$ whoami
consultor de tecnologia · fundador da axisnetworks · dev nas horas vagas (que não existem)

davi@axis:~$ uptime
+20 empresas atendidas · 0 clientes reféns · load average: café, café, café ☕

davi@axis:~$ cat /etc/motd
"Any sufficiently advanced technology is indistinguishable from magic." — Arthur C. Clarke
   ...mas aqui a mágica vem documentada no vault. 🧙‍♂️

davi@axis:~$ ping producao -c 1
64 bytes from producao: icmp_seq=1 ttl=64 time=0.42 ms · 🟢 tudo no ar

davi@axis:~$ sudo rm -rf /problemas-do-cliente
[sudo] senha para davi: ********
removido: 'planilha-que-ninguem-entende.xlsx'
removido: 'ramal-que-toca-no-vazio'
removido: 'backup-acho-que-tem'
```

---

### 🧭 O que eu faço <sub>(main quest)</sub>
**Consultoria de tecnologia para empresas, com IA ou sem.** Entro, entendo como o negócio funciona e resolvo onde a tecnologia trava o dinheiro, o tempo ou o atendimento:

1. **Diagnóstico**: olho a operação real antes de propor qualquer ferramenta
2. **Plano**: prioridades por impacto e custo, com usar o que já existe antes de construir
3. **Implantação**: eu mesmo executo, de ponta a ponta
4. **Operação**: acompanho, documento e mantenho funcionando

### 🗺️ Mapa do mundo <sub>(onde já atuei)</sub>
**+20 empresas** atendidas pela **Axisnetworks**, em segmentos bem diferentes:

| Segmento | O que entreguei |
|---|---|
| 🩺 **Saúde**: clínicas, laboratório, academia | Atendimento de pacientes no WhatsApp com IA, agendamento e cobrança automáticos, telefonia em nuvem |
| 💳 **Crédito e consignado** | Assinatura digital de contratos, migração de arquivos para nuvem própria com backup, telefonia |
| 🛒 **Varejo**: lojas físicas, redes | Integração com ERP (Bling), redes multi-link, Wi-Fi gerenciado, gestão de manutenção |
| 🏗️ **Construção** | App de gestão de obras em campo, com relatórios e integração financeira |
| 🏢 **Empresas em geral** | VPN corporativa, firewall, servidores, sites institucionais |

**📊 Stats do personagem:**
- **7 empresas** numa central telefônica em nuvem única, migradas de sistemas legados
- **90 acessos VPN** trocados de OpenVPN para WireGuard
- **Anos de arquivos** tirados do Dropbox para nuvem própria, com backup automático

### 🏆 Boss fights <sub>(achievements desbloqueados)</sub>
> Problemas reais, resolvidos em produção. Nenhum deu mensagem de erro, e é por isso que eram chefes.

- 🐉 **A chamada que morria sempre aos 32 segundos**: a mensagem SIP passava do tamanho do pacote (MTU) e se fragmentava no caminho. Derrotado encolhendo o SDP.
- 🔇 **A URA que falava pro nada**: codec G.729 em passthrough deixava anúncio e gravação mudos. Loot: regra permanente de só PCMA/PCMU.
- 👻 **28% das mensagens invisíveis**: WhatsApp no celular e API oficial ao mesmo tempo. O que saía do celular chegava por um evento que ninguém escutava.
- 🕳️ **A API que mudou de endereço sem avisar**: o host antigo do ERP virou 403, e o espelho local fazia tudo *parecer* normal. Só a escrita quebrava.
- 🧟 **O `except: pass`**: o erro que não dá erro é o mais caro. Hoje todo silêncio loga, avisa e tenta de novo.
- 🌐 **It was DNS.** Sempre é.

### 🩺 Praxys Med <sub>(party de dois: um dev e um médico)</sub>
Sociedade com um médico para tirar o peso operacional do consultório. Três softwares que se somam:
- **Atende Praxys**, a porta: CRM e atendimento no WhatsApp
- **FlowHub**, o motor: bot que agenda consulta e cobra via Pix
- **Praxys Advisor**, a cabeça: assistente de gestão que cruza agenda, pagamentos e banco

### 🚀 Side quests que viraram produto
| Produto | O que resolve | Status |
|---|---|---|
| **Atende** | Atendimento no WhatsApp com agentes de IA, multiempresa, com CRM e filas | Em produção |
| **AssinaturaMaster** | Assinatura digital de contratos com cobrança integrada | Em produção |
| **WorkLyons** | Gestão de obras: fases, visitas, relatórios | Em implantação |
| **Fluxus** | Ordem de serviço virando pedido no ERP Bling, para varejo | Em implantação |

### 📜 Como eu trabalho <sub>(as Leis da Robótica versão Axis)</sub>
- **O problema vem antes da ferramenta**: IA só onde ela resolve melhor que um processo simples
- **Integrar, não duplicar**: se o sistema do cliente já faz, eu uso o que já existe
- **A regra fica no código, não no prompt**: IA opera, humano supervisiona
- **Produção é sagrada**: nada irreversível sem validação e ambiente de teste. `rm -rf` só com OK por escrito
- **Tudo documentado**: o cliente nunca fica refém de quem implantou. Sem "funciona na minha máquina"

---

### 🧰 Arsenal
<sub>*"It's dangerous to go alone! Take this."* 🗡️</sub>

**☁️ Infra, cloud e containers**<br>
<img src="https://skillicons.dev/icons?i=linux,debian,ubuntu,windows,apple,docker,nginx,aws,azure,gcp,cloudflare,raspberrypi&perline=12" />

**💻 Código e dados**<br>
<img src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,nextjs,react,tailwind,prisma,python,bash,powershell,postgres,redis,mysql,supabase&perline=15" />

**🛠️ Ferramentas do dia a dia**<br>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode,vim,obsidian,grafana,prometheus,vercel&perline=12" />

**🌐 Redes, VoIP, virtualização e IA**<br>
![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=for-the-badge&logo=mikrotik&logoColor=white)
![UniFi](https://img.shields.io/badge/UniFi-0559C9?style=for-the-badge&logo=ubiquiti&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=for-the-badge&logo=pfsense&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=for-the-badge&logo=opnsense&logoColor=white)
![FusionPBX](https://img.shields.io/badge/FusionPBX-1E88E5?style=for-the-badge&logo=voipdotms&logoColor=white)
![FreeSWITCH](https://img.shields.io/badge/FreeSWITCH-0B6E99?style=for-the-badge)
![Asterisk](https://img.shields.io/badge/Asterisk-F68F1E?style=for-the-badge&logo=asterisk&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Hyper-V](https://img.shields.io/badge/Hyper--V-0078D4?style=for-the-badge)
![Coolify](https://img.shields.io/badge/Coolify-6B16ED?style=for-the-badge)
![Nextcloud](https://img.shields.io/badge/Nextcloud-0082C9?style=for-the-badge&logo=nextcloud&logoColor=white)
![GLPI](https://img.shields.io/badge/GLPI-2F3F73?style=for-the-badge)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/idavinunes/idavinunes/output/github-snake-dark.svg" />
    <img alt="snake comendo as contribuições" src="https://raw.githubusercontent.com/idavinunes/idavinunes/output/github-snake.svg" />
  </picture>
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=idavinunes&show_icons=true&count_private=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=idavinunes&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>

<p align="center">
  <sub>🎸 Fora do terminal: guitarra, louvor e games · ↑ ↑ ↓ ↓ ← → ← → B A</sub><br>
  <sub>A resposta é 42. A pergunta geralmente é "por que caiu?" 🐧</sub><br>
  <sub>Feito com ☕, 🎸 e <code>git push --force</code> (brincadeira: nunca na main)</sub>
</p>
