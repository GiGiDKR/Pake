<h4 align="right"><a href="https://github.com/GiGiDKR/Pake/blob/master/README.md">English</a> | <strong>Français</strong> | <a href="https://github.com/tw93/Pake/blob/master/README_CN.md">简体中文</a> | <a href="https://github.com/tw93/Pake/blob/master/README_JP.md">日本語</a></h4>

<p align="center">
  <img src=https://gw.alipayobjects.com/zos/k/fa/logo-modified.png width=138/>
</p>

<h1 align="center">Pake</h1>

<p align="center"><strong>Transformez n'importe quelle page web en application de bureau avec Rust <em>en toute simplicité</em>.</strong></p>

<div align="center">
  <a href="https://twitter.com/HiTw93" target="_blank">
    <img alt="twitter" src="https://img.shields.io/badge/follow-Tw93-red?style=flat-square&logo=Twitter"></a>
  <a href="https://t.me/+GclQS9ZnxyI2ODQ1" target="_blank">
    <img alt="telegram" src="https://img.shields.io/badge/chat-telegram-blueviolet?style=flat-square&logo=Telegram"></a>
  <a href="https://github.com/tw93/Pake/releases" target="_blank">
    <img alt="GitHub downloads" src="https://img.shields.io/github/downloads/tw93/Pake/total.svg?style=flat-square"></a>
  <a href="https://github.com/tw93/Pake/commits" target="_blank">
    <img alt="GitHub commit" src="https://img.shields.io/github/commit-activity/m/tw93/Pake?style=flat-square"></a>
  <a href="https://github.com/tw93/Pake/issues?q=is%3Aissue+is%3Aclosed" target="_blank">
    <img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/tw93/Pake.svg?style=flat-square"></a>
  <a href="https://colab.research.google.com/drive/1bX345znvDZ30848xjRtpgtU8eypWwXrp?usp=sharing" target="_blank">
    <img alt="Open in Colab" src="https://colab.research.google.com/assets/colab-badge.svg"></a>
</div>

<div align="left">Pake prend en charge Mac, Windows et Linux. Consultez le README pour les <a href="#paquets-populaires">Paquets populaires</a>, l'<a href="#empaquetage-en-ligne-de-commande">Empaquetage en ligne de commande</a>, et les informations sur le <a href="#développement">Développement personnalisé</a>. N'hésitez pas à partager vos suggestions dans les <a href=https://github.com/tw93/Pake/discussions>Discussions</a>.</div>

## Caractéristiques

- 🎐 Presque 20 fois plus petit qu'un paquet Electron (environ 5M !)
- 🚀 Avec Rust Tauri, Pake est beaucoup plus léger et rapide que les frameworks basés sur JS.
- 📦 Paquet tout inclus — raccourcis, fenêtres immersives et personnalisation minimaliste.
- 👻 Pake est juste un outil simple — remplace l'ancienne approche de bundle par Tauri (bien que PWA soit suffisamment bon).

## Paquets populaires

<table>
  <tr>
    <td>WeRead <a href="https://github.com/tw93/Pake/releases/latest/download/WeRead.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/WeRead_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/WeRead_x86_64.deb">Linux</a>
    </td>
    <td>Twitter <a href="https://github.com/tw93/Pake/releases/latest/download/Twitter.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/Twitter_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/Twitter_x86_64.deb">Linux</a>
    </td>
  </tr>
  <tr>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/WeRead.jpg width=600/></td>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/Twitter.jpg width=600/></td>
  </tr>
  <tr>
    <td>ChatGPT <a href="https://github.com/tw93/Pake/releases/latest/download/ChatGPT.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/ChatGPT_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/ChatGPT_x86_64.deb">Linux</a>
    </td>
    <td>Poe <a href="https://github.com/tw93/Pake/releases/latest/download/Poe.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/Poe_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/Poe_x86_64.deb">Linux</a>
    </td>
  </tr>
  <tr>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/ChatGPT.png width=600/></td>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/Poe.png width=600/></td>
  </tr>
  <tr>
    <td>YouTube Music <a href="https://github.com/tw93/Pake/releases/latest/download/YouTubeMusic.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/YouTubeMusic_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/YouTubeMusic_x86_64.deb">Linux</a>
    </td>
    <td>YouTube <a href="https://github.com/tw93/Pake/releases/latest/download/YouTube.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/YouTube_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/YouTube_x86_64.deb">Linux</a>
    </td>
  </tr>
  <tr>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/YouTubeMusic.png width=600 /></td>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/YouTube.jpg width=600 /></td>
  </tr>
  <tr>
    <td>LiZhi <a href="https://github.com/tw93/Pake/releases/latest/download/LiZhi.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/LiZhi_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/LiZhi_x86_64.deb">Linux</a>
    </td>
    <td>ProgramMusic <a href="https://github.com/tw93/Pake/releases/latest/download/ProgramMusic.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/ProgramMusic_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/ProgramMusic_x86_64.deb">Linux</a>
    </td>
  </tr>
  <tr>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/LiZhi.jpg width=600/></td>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/ProgramMusic.jpg width=600/></td>
  </tr>
  <tr>
    <td>Qwerty <a href="https://github.com/tw93/Pake/releases/latest/download/Qwerty.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/Qwerty_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/Qwerty_x86_64.deb">Linux</a>
    </td>
    <td>CodeRunner <a href="https://github.com/tw93/Pake/releases/latest/download/CodeRunner.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/CodeRunner_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/CodeRunner_x86_64.deb">Linux</a>
    </td>
  </tr>
  <tr>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/Qwerty.png width=600/></td>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/CodeRunner.jpg width=600/></td>
  </tr>
  <tr>
    <td>Flomo <a href="https://github.com/tw93/Pake/releases/latest/download/Flomo.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/Flomo_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/Flomo_x86_64.deb">Linux</a>
    </td>
    <td>XiaoHongShu <a href="https://github.com/tw93/Pake/releases/latest/download/XiaoHongShu.dmg">Mac</a> <a href="https://github.com/tw93/Pake/releases/latest/download/XiaoHongShu_x64.msi">Windows</a> <a href="https://github.com/tw93/Pake/releases/latest/download/XiaoHongShu_x86_64.deb">Linux</a>
    </td>
  </tr>
  <tr>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/Flomo.png width=600/></td>
    <td><img src=https://raw.githubusercontent.com/tw93/static/main/pake/XiaoHongShu.png width=600/></td>
  </tr>
</table>

<details>
  <summary>🏂 Vous pouvez télécharger plus d'applications depuis <a href="https://github.com/tw93/Pake/releases">Releases</a>. <b>Cliquez ici pour développer la référence des raccourcis !</b></summary>
  <br/>

| Mac | Windows/Linux | Fonction |
| --------------------------- | ------------------------------ | ----------------------------- |
| <kbd>⌘</kbd> + <kbd>[</kbd> | <kbd>Ctrl</kbd> + <kbd>←</kbd> | Retour à la page précédente |
| <kbd>⌘</kbd> + <kbd>]</kbd> | <kbd>Ctrl</kbd> + <kbd>→</kbd> | Aller à la page suivante |
| <kbd>⌘</kbd> + <kbd>↑</kbd> | <kbd>Ctrl</kbd> + <kbd>↑</kbd> | Défilement automatique vers le haut de la page |
| <kbd>⌘</kbd> + <kbd>↓</kbd> | <kbd>Ctrl</kbd> + <kbd>↓</kbd> | Défilement automatique vers le bas de la page |
| <kbd>⌘</kbd> + <kbd>r</kbd> | <kbd>Ctrl</kbd> + <kbd>r</kbd> | Actualiser la page |
| <kbd>⌘</kbd> + <kbd>w</kbd> | <kbd>Ctrl</kbd> + <kbd>w</kbd> | Masquer la fenêtre, pas tout à fait |
| <kbd>⌘</kbd> + <kbd>-</kbd> | <kbd>Ctrl</kbd> + <kbd>-</kbd> | Zoom arrière de la page |
| <kbd>⌘</kbd> + <kbd>+</kbd> | <kbd>Ctrl</kbd> + <kbd>+</kbd> | Zoom avant de la page |
| <kbd>⌘</kbd> + <kbd>=</kbd> | <kbd>Ctrl</kbd> + <kbd>=</kbd> | Zoom avant de la page |
| <kbd>⌘</kbd> + <kbd>0</kbd> | <kbd>Ctrl</kbd> + <kbd>0</kbd> | Réinitialiser le zoom de la page |

De plus, double-cliquez sur la barre de titre pour passer en mode plein écran. Pour les utilisateurs Mac, vous pouvez également utiliser le geste pour aller à la page précédente ou suivante et faire glisser la barre de titre pour déplacer la fenêtre.

</details>

## Avant de commencer

1. **Pour les débutants** : Jouez avec les Paquets populaires pour découvrir les capacités de Pake, ou essayez d'empaqueter votre application avec [GitHub Actions](<https://github.com/tw93/Pake/wiki/Online-Compilation-(used-by-ordinary-users)>). N'hésitez pas à demander de l'aide dans les [Discussions](https://github.com/tw93/Pake/discussions) !

2. **Pour les développeurs** : L'"Empaquetage en ligne de commande" prend entièrement en charge macOS. Pour les utilisateurs Windows/Linux, cela nécessite quelques ajustements. [Configurez votre environnement](https://tauri.app/v1/guides/getting-started/prerequisites) avant de commencer.

3. **Pour les hackers** : Pour les personnes qui sont à l'aise avec le développement front-end et Rust, que diriez-vous de personnaliser davantage les fonctions de vos applications avec le [Développement personnalisé](#développement) ?

## Empaquetage en ligne de commande

Pake

**Pake fournit un outil en ligne de commande, rendant le flux de personnalisation des paquets plus rapide et plus facile. Consultez la [documentation](./bin/README.md) pour plus d'informations.**

```bash
# Installation avec npm
npm install -g pake-cli

# Utilisation de la commande
pake url [OPTIONS]...

# N'hésitez pas à jouer avec Pake ! La première fois que vous lancez Pake, la préparation de l'environnement peut prendre un certain temps.
pake https://weekly.tw93.fun --name Weekly --hide-title-bar
```

Si vous n'êtes pas familier avec la ligne de commande, vous pouvez compiler des paquets en ligne avec _GitHub Actions_. Consultez le [Tutoriel](<https://github.com/tw93/Pake/wiki/Online-Compilation-(used-by-ordinary-users)>) pour plus d'informations.

## Développement

Préparez votre environnement avant de commencer. Assurez-vous d'avoir Rust `>=1.63` et Node `>=16` (par exemple, `16.18.1`) installés sur votre ordinateur. Pour des conseils d'installation, consultez la [documentation Tauri](https://tauri.app/v1/guides/getting-started/prerequisites). Si vous n'êtes pas familier avec ces outils, il est préférable d'essayer l'outil ci-dessus pour empaqueter en un clic.

```sh
# Installer les dépendances
npm i

# Développement local [Clic droit pour ouvrir le mode debug]
npm run dev

# Empaqueter l'application
npm run build
```

## Utilisation avancée

1. Vous pouvez vous référer à la [structure du code](https://github.com/tw93/Pake/wiki/Description-of-Pake's-code-structure) avant de travailler sur Pake, ce qui vous aidera beaucoup dans le développement.

2. Modifiez les champs `url` et `productName` dans le fichier `pake.json` sous le répertoire src-tauri, le champ "domain" dans le fichier `tauri.config.json` doit être modifié de manière synchrone, ainsi que les champs `icon` et `identifier` dans le fichier `tauri.xxx.conf.json`. Vous pouvez sélectionner une `icon` dans le répertoire `icons` ou en télécharger une depuis [macOSicons](https://macosicons.com/#/) pour correspondre aux besoins de votre produit.

3. Pour les configurations des propriétés de la fenêtre, vous pouvez modifier le fichier `pake.json` pour changer la valeur de `width`, `height`, `fullscreen` (ou non), `resizable` (ou non) de la propriété `windows`. Pour s'adapter à l'en-tête immersif sur Mac, changez `hideTitleBar` à `true`, cherchez l'élément `Header`, et ajoutez la propriété `padding-top`.

4. Pour des utilisations avancées telles que la réécriture de style, la suppression de publicités, l'injection de JS, la communication de messages entre conteneurs et les raccourcis clavier définis par l'utilisateur, consultez [Utilisation avancée de Pake](https://github.com/tw93/Pake/wiki/Advanced-Usage-of-Pake).

## Développeurs

Le développement de Pake ne serait pas possible sans ces Hackers. Ils ont contribué à de nombreuses capacités pour Pake. N'hésitez pas à les suivre également ! ❤️


<!-- readme: contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/tw93">
            <img src="https://avatars.githubusercontent.com/u/8736212?v=4" width="90;" alt="tw93"/>
            <br />
            <sub><b>Tw93</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Tlntin">
            <img src="https://avatars.githubusercontent.com/u/28218658?v=4" width="90;" alt="Tlntin"/>
            <br />
            <sub><b>Tlntin</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/jeasonnow">
            <img src="https://avatars.githubusercontent.com/u/16950207?v=4" width="90;" alt="jeasonnow"/>
            <br />
            <sub><b>Santree</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/pan93412">
            <img src="https://avatars.githubusercontent.com/u/28441561?v=4" width="90;" alt="pan93412"/>
            <br />
            <sub><b>Pan93412</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/wanghanzhen">
            <img src="https://avatars.githubusercontent.com/u/25301012?v=4" width="90;" alt="wanghanzhen"/>
            <br />
            <sub><b>Volare</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/liby">
            <img src="https://avatars.githubusercontent.com/u/38807139?v=4" width="90;" alt="liby"/>
            <br />
            <sub><b>Bryan Lee</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/essesoul">
            <img src="https://avatars.githubusercontent.com/u/58624474?v=4" width="90;" alt="essesoul"/>
            <br />
            <sub><b>Essesoul</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/YangguangZhou">
            <img src="https://avatars.githubusercontent.com/u/61733195?v=4" width="90;" alt="YangguangZhou"/>
            <br />
            <sub><b>Jerry Zhou</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/AielloChan">
            <img src="https://avatars.githubusercontent.com/u/7900765?v=4" width="90;" alt="AielloChan"/>
            <br />
            <sub><b>Aiello</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/m1911star">
            <img src="https://avatars.githubusercontent.com/u/4948120?v=4" width="90;" alt="m1911star"/>
            <br />
            <sub><b>Horus</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Pake-Actions">
            <img src="https://avatars.githubusercontent.com/u/126550811?v=4" width="90;" alt="Pake-Actions"/>
            <br />
            <sub><b>Pake Actions</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/eltociear">
            <img src="https://avatars.githubusercontent.com/u/22633385?v=4" width="90;" alt="eltociear"/>
            <br />
            <sub><b>Ikko Eltociear Ashimine</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/QingZ11">
            <img src="https://avatars.githubusercontent.com/u/38887077?v=4" width="90;" alt="QingZ11"/>
            <br />
            <sub><b>Steam</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/exposir">
            <img src="https://avatars.githubusercontent.com/u/33340988?v=4" width="90;" alt="exposir"/>
            <br />
            <sub><b>孟世博</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/2nthony">
            <img src="https://avatars.githubusercontent.com/u/19513289?v=4" width="90;" alt="2nthony"/>
            <br />
            <sub><b>2nthony</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/ACGNnsj">
            <img src="https://avatars.githubusercontent.com/u/22112141?v=4" width="90;" alt="ACGNnsj"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/imabutahersiddik">
            <img src="https://avatars.githubusercontent.com/u/138387257?v=4" width="90;" alt="imabutahersiddik"/>
            <br />
            <sub><b>Abu Taher Siddik</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/kidylee">
            <img src="https://avatars.githubusercontent.com/u/841310?v=4" width="90;" alt="kidylee"/>
            <br />
            <sub><b>An Li</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/nekomeowww">
            <img src="https://avatars.githubusercontent.com/u/11081491?v=4" width="90;" alt="nekomeowww"/>
            <br />
            <sub><b>Ayaka Neko</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/turkyden">
            <img src="https://avatars.githubusercontent.com/u/24560160?v=4" width="90;" alt="turkyden"/>
            <br />
            <sub><b>Dengju Deng</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Fechin">
            <img src="https://avatars.githubusercontent.com/u/2541482?v=4" width="90;" alt="Fechin"/>
            <br />
            <sub><b>Fechin</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/ImgBotApp">
            <img src="https://avatars.githubusercontent.com/u/31427850?v=4" width="90;" alt="ImgBotApp"/>
            <br />
            <sub><b>Imgbot</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/droid-Q">
            <img src="https://avatars.githubusercontent.com/u/708277?v=4" width="90;" alt="droid-Q"/>
            <br />
            <sub><b>Jiaqi Gu</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/mattbajorek">
            <img src="https://avatars.githubusercontent.com/u/17235301?v=4" width="90;" alt="mattbajorek"/>
            <br />
            <sub><b>Matt Bajorek</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Milo123459">
            <img src="https://avatars.githubusercontent.com/u/50248166?v=4" width="90;" alt="Milo123459"/>
            <br />
            <sub><b>Milo</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/princemaple">
            <img src="https://avatars.githubusercontent.com/u/1329716?v=4" width="90;" alt="princemaple"/>
            <br />
            <sub><b>Po Chen</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Tianj0o">
            <img src="https://avatars.githubusercontent.com/u/68584284?v=4" width="90;" alt="Tianj0o"/>
            <br />
            <sub><b>Qitianjia</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/geekvest">
            <img src="https://avatars.githubusercontent.com/u/126322776?v=4" width="90;" alt="geekvest"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/houhoz">
            <img src="https://avatars.githubusercontent.com/u/19684376?v=4" width="90;" alt="houhoz"/>
            <br />
            <sub><b>Hyzhao</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/lakca">
            <img src="https://avatars.githubusercontent.com/u/16255922?v=4" width="90;" alt="lakca"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/liudonghua123">
            <img src="https://avatars.githubusercontent.com/u/2276718?v=4" width="90;" alt="liudonghua123"/>
            <br />
            <sub><b>Liudonghua</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/liusishan">
            <img src="https://avatars.githubusercontent.com/u/33129823?v=4" width="90;" alt="liusishan"/>
            <br />
            <sub><b>Liusishan</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/piaoyidage">
            <img src="https://avatars.githubusercontent.com/u/5135405?v=4" width="90;" alt="piaoyidage"/>
            <br />
            <sub><b>Ranger</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/hetz">
            <img src="https://avatars.githubusercontent.com/u/820141?v=4" width="90;" alt="hetz"/>
            <br />
            <sub><b>贺天卓</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: contributors -end -->

## Questions fréquemment posées

1. Le clic droit sur un élément image de la page pour ouvrir le menu et sélectionner "Télécharger l'image" ou d'autres événements ne fonctionne pas (courant sur les systèmes MacOS). Ce problème est dû au fait que le webview intégré de MacOS ne prend pas en charge cette fonctionnalité.

## Soutien

1. J'ai deux chats, TangYuan et Coke. Si vous pensez que Pake égaye votre vie, vous pouvez leur offrir <a href="https://miaoyan.app/cats.html?name=Pake" target="_blank"> un peu de nourriture 🥩</a>.

2. Si vous aimez Pake, vous pouvez lui donner une étoile sur GitHub. N'hésitez pas non plus à [recommander Pake](https://twitter.com/intent/tweet?url=https://github.com/tw93/Pake&text=%23Pake%20-%20Un%20outil%20simple%20en%20Rust%20pour%20empaqueter%20des%20pages%20web%20et%20générer%20des%20applications%20Mac,%20comparé%20au%20package%20Electron%20traditionnel,%20la%20taille%20est%20près%20de%2040%20fois%20plus%20petite,%20généralement%20environ%202M,%20utilisant%20Tauri%20en%20sous-couche,%20l'expérience%20de%20performance%20est%20beaucoup%20plus%20légère%20que%20les%20frameworks%20JS~) à vos amis.

3. Vous pouvez suivre mon [Twitter](https://twitter.com/HiTw93) pour obtenir les dernières nouvelles de Pake ou rejoindre notre groupe de discussion [Telegram](https://t.me/+GclQS9ZnxyI2ODQ1).

4. J'espère que vous prendrez plaisir à l'utiliser. Faites-nous savoir si vous trouvez un site web qui serait parfait pour une application Mac !
