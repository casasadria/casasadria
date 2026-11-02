<!-- ══════════════════════════ CABECERA ══════════════════════════ -->
<p align="center">
  <img src="./header.svg" width="100%" alt="Adrià Casas · Full-Stack Web & Mobile Developer" />
</p>

<p align="center">
  <a href="https://adriacasas.es">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=3DDC84&center=true&vCenter=true&width=620&lines=PHP+%C2%B7+JavaScript+%C2%B7+Kotlin+%C2%B7+Swift;Construyo+apps+que+se+usan+en+la+calle+%F0%9F%9A%9B;AWS+%C2%B7+MySQL+8+%C2%B7+Cloudflare+%C2%B7+OpenVPN;La+seguridad+no+es+el+%C3%BAltimo+paso+%F0%9F%94%92" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://adriacasas.es"><img src="https://img.shields.io/badge/Portfolio-adriacasas.es-00C7B7?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/casasadria"><img src="https://img.shields.io/badge/LinkedIn-casasadria-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://instagram.com/casas_adria"><img src="https://img.shields.io/badge/Instagram-@casas__adria-E4405F?style=flat-square&logo=instagram&logoColor=white" /></a>
  <a href="mailto:adriacasas48@gmail.com"><img src="https://img.shields.io/badge/Email-adriacasas48-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=casasadria&style=flat-square&color=2c5364&label=visitas" />
</p>

<!-- ══════════════════════════ WHOAMI ══════════════════════════ -->

```bash
adria@banyoles:~$ whoami
```

```yaml
nombre:      Adrià Casas Llorens
rol:         Full-Stack Web & Mobile Developer
empresa:     ID·Waste  # casi 2 años · software para gestión de residuos y limpieza viaria
ubicacion:   Banyoles, Girona 📍
formacion:   [DAM, SMX]
filosofia:   "La seguridad no es un paso final, es parte de cómo construyo."
ahora_mismo: 
  - Desarrollando W·Route, W·Task, W·Link, W·Data, W·City e ID·Soft
  - Cerrando redes: de accesos abiertos a IP + VPN
  - Exprimiendo índices en MySQL 8 en producción
fun_fact:    Hice una app Android entera porque perdía el mando del ventilador 🌀
```

<!-- ══════════════════════════ STACK ══════════════════════════ -->

## 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=php,js,html,css,kotlin,swift,java,python&perline=8" /><br/>
  <img src="https://skillicons.dev/icons?i=androidstudio,mysql,firebase,mongodb,docker,linux,raspberrypi,git&perline=8" /><br/>
  <img src="https://skillicons.dev/icons?i=aws,cloudflare,nginx,bash,github,vscode,idea,arduino&perline=8" />
</p>

<!-- ══════════════════════════ ID·WASTE ══════════════════════════ -->

## 💼 Qué hago en ID·Waste

<table>
<tr>
<td width="50%" valign="top">

### 🧩 Producto
- Plataforma completa: **W·Route, W·Task, W·Link, W·Data, W·City, ID·Soft**
- **Web:** PHP + JavaScript sobre framework propio
- **Android:** Kotlin · **iOS:** Swift
- Integraciones con sistemas de empresas externas

</td>
<td width="50%" valign="top">

### 🏗️ Infraestructura
- **AWS:** EC2, RDS Aurora / MySQL 8, RDS Proxy
- Grupos de seguridad, **OpenVPN**, DNS en **Cloudflare**
- Migración de accesos abiertos a red restringida por IP + VPN
- Esquemas, queries e índices en producción real

</td>
</tr>
</table>

<details>
<summary><b>🗺️ Ver cómo pienso una arquitectura</b> (clic para desplegar)</summary>
<br/>

```mermaid
flowchart LR
    U([📱 Apps & Web]) --> CF[☁️ Cloudflare DNS]
    CF --> EC2[🖥️ EC2]
    DEV([👨‍💻 Equipo]) -- OpenVPN --> VPN[🔐 VPN]
    VPN --> EC2
    EC2 -- Security Group --> PX[🔀 RDS Proxy]
    PX --> DB[(🗄️ Aurora MySQL 8)]
    style DB fill:#2c5364,color:#fff
    style VPN fill:#203a43,color:#fff
```

Solo se habla quien tiene que hablarse. Todo lo demás, cerrado.

</details>

<!-- ══════════════════════════ PROYECTOS ══════════════════════════ -->

## 🚀 Proyectos personales

<table>
<tr>
<td width="50%" valign="top">

### 📡 IRBlast
Mando IR universal para Android. Emisor IR del móvil **o** un ESP32 por WiFi que captura las señales del mando original.

`Kotlin` `MVVM` `Room` `StateFlow` `Material 3` `ESP32`

> 19/19 botones configurados. Mando físico en el cajón para siempre.

</td>
<td width="50%" valign="top">

### 🌍 [adriacasas.es](https://adriacasas.es)
Portfolio rehecho desde cero con API REST propia, MySQL y tres idiomas (CA · ES · EN). Desplegado con Docker + Cloudflare Tunnel.

`PHP` `MySQL` `JavaScript` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🍓 Homelab
Raspberry Pi 24/7 sustituyendo un servidor dedicado: portfolio, Plex, nube privada y Pi-hole. Sin abrir puertos en el router.

`Linux` `UFW` `OpenVPN` `Cloudflared` `Pi-hole`

</td>
<td width="50%" valign="top">

### 🏆 [LearnTrack](https://www.learntrack.cat)
Ganador del **premio Jordi Pujiula** (PEHOC) en Ciencias Aplicadas y Tecnología.

`Premio` `Proyecto en equipo`

</td>
</tr>
</table>

<!-- ══════════════════════════ SNAKE ══════════════════════════ -->

## 🐍 Mis contribuciones

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/casasadria/casasadria/output/github-snake-dark.svg" />
    <img alt="Serpiente comiéndose las contribuciones" src="https://raw.githubusercontent.com/casasadria/casasadria/output/github-snake.svg" />
  </picture>
</p>

<!-- ══════════════════════════ PIE ══════════════════════════ -->

<p align="center">
  <img src="./footer.svg" width="100%" />
</p>
