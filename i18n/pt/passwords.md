---
title: "Redes Auto-Contidas"
icon: material/form-textbox-password
---

Fique seguro e protegido on-line com um gerenciador de senhas criptografado e de código aberto.

[Introduction to Passwords :material-arrow-right-drop-circle:](./basics/passwords-overview.md)

!!! info

    ![logotipo KeepassXC](/assets/img/password-management/keepassxc.svg){ align=right }
    
    **KeePassXC** é um garfo comunitário do KeePassX, uma porta nativa multi-plataforma do KeePass Password Safe, com o objectivo de o alargar e melhorar com novas funcionalidades e correcções de bugs para fornecer um gestor de senhas moderno, totalmente multi-plataforma e de código aberto. [Visite keepassxc.org](https://keepassxc.org){ .md-button .md-button--primary } [Política de Privacidade](https://keepassxc.org/privacy){ .md-button }
    
    **Downloads***
    - [:fontawesome-brands-windows: Windows](https://keepassxc.org/download/#windows)
    - [:fontawesome-brands-apple: macOS](https://keepassxc.org/download/#mac)
    - [:fontawesome-brands-linux: Linux](https://keepassxc.org/download/#linux)
    - [:pg-flathub: Flatpak](https://flathub.org/apps/details/org.keepassxc.KeePassXC)
    - [:fontawesome-brands-firefox: Firefox](https://addons.mozilla.org/firefox/addon/keepassxc-browser)
    - [:fontawesome-brands-chrome: Chrome](https://chrome.google.com/webstore/detail/keepassxc-browser/oboonakemofpalcgghocfoadofidjkkk)
    - [:fontawesome-brands-github: Source](https://github.com/keepassxreboot/keepassxc)
    
    For example, the password manager in Microsoft Edge doesn't offer E2EE at all. Google's password manager has [optional](https://support.google.com/accounts/answer/11350823) E2EE, and [Apple's](https://support.apple.com/en-us/HT202303) offers E2EE by default.

## Baseado nas nuvens

These password managers sync your passwords to a cloud server for easy accessibility from all your devices and safety against device loss.

### KeepassXC

!!! nota
    Consulte o [Tabela de Hardware](https://openwrt.org/toh/start) para verificar se o seu dispositivo é suportado.

    KeepassXC armazena seus dados de exportação como [comma-separated values (CSV)](https://en.wikipedia.org/wiki/Comma-separated_values). Isto pode significar perda de dados se você importar este arquivo para outro gerenciador de senhas. Aconselhamo-lo a verificar cada registo manualmente.
    
    [:octicons-home-16: Homepage](https://bitwarden.com){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://bitwarden.com/privacy){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://bitwarden.com/help/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/bitwarden){ .card-link title="Source Code" }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=com.x8bit.bitwarden)
        - [:simple-appstore: App Store](https://apps.apple.com/app/bitwarden-password-manager/id1137397744)
        - [:simple-github: GitHub](https://github.com/bitwarden/mobile/releases)
        - [:simple-windows11: Windows](https://bitwarden.com/download)
        - [:simple-linux: Linux](https://bitwarden.com/download)
        - [:simple-flathub: Flathub](https://flathub.org/apps/details/com.bitwarden.desktop)
        - [:simple-firefoxbrowser: Firefox](https://addons.mozilla.org/firefox/addon/bitwarden-password-manager)
        - [:simple-googlechrome: Chrome](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)
        - [:simple-microsoftedge: Edge](https://microsoftedge.microsoft.com/addons/detail/jbkfoedolllekgbhcbcoahefnbanhhlh)

Bitwarden also features [Bitwarden Send](https://bitwarden.com/products/send/), which allows you to share text and files securely with [end-to-end encryption](https://bitwarden.com/help/send-encryption). A [password](https://bitwarden.com/help/send-privacy/#send-passwords) can be required along with the send link. Bitwarden Send also features [automatic deletion](https://bitwarden.com/help/send-lifespan).

You need the [Premium Plan](https://bitwarden.com/help/about-bitwarden-plans/#compare-personal-plans) to be able to share files. The free plan only allows text sharing.

Bitwarden's server-side code is [open-source](https://github.com/bitwarden/server), so if you don't want to use the Bitwarden cloud, you can easily host your own Bitwarden sync server.

**Vaultwarden** is an alternative implementation of Bitwarden's sync server written in Rust and compatible with official Bitwarden clients, perfect for self-hosted deployment where running the official resource-heavy service might not be ideal. If you are looking to self-host Bitwarden on your own server, you almost certainly want to use Vaultwarden over Bitwarden's official server code.

[:octicons-repo-16: Vaultwarden Repository](https://github.com/dani-garcia/vaultwarden ""){.md-button} [:octicons-info-16:](https://github.com/dani-garcia/vaultwarden/wiki){ .card-link title=Documentation}
[:octicons-code-16:](https://github.com/dani-garcia/vaultwarden){ .card-link title="Source Code" }
[:octicons-heart-16:](https://github.com/sponsors/dani-garcia){ .card-link title=Contribute }

### KeepassDX

!!! nota
    Consulte o [Tabela de Hardware](https://openwrt.org/toh/start) para verificar se o seu dispositivo é suportado.

    ![logotipo KeepassDX](/assets/img/password-management/keepassdx.svg){ align=right }
    
    **KeepassDX*** é um gerenciador de senhas leve para Android, permite editar dados criptografados em um único arquivo no formato KeePass e pode preencher os formulários de uma forma segura. [Contributor Pro](https://play.google.com/store/apps/details?id=com.kunzisoft.keepass.pro) permite desbloquear conteúdos cosméticos e recursos de protocolo não-padrão, mas, mais importante, ajuda e incentiva o desenvolvimento. Para mais detalhes, recomendamos que veja o seu [FAQ](https://github.com/Kunzisoft/KeePassDX/wiki/FAQ). [Visite keepassdx.com](https://www.keepassdx.com){ .md-button .md-button--primary }
    
    **Downloads***
    - [:fontawesome-brands-google-play: Google Play](https://play.google.com/store/apps/details?id=com.kunzisoft.keepass.free)
    - [:pg-f-droid: F-Droid](https://www.f-droid.org/packages/com.kunzisoft.keepass.libre)
    - [:fontawesome-brands-github: Source](https://github.com/Kunzisoft/KeePassDX)
    
    [:octicons-home-16: Homepage](https://1password.com/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://support.1password.com/1password-privacy/){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://support.1password.com/){ .card-link title=Documentation}
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=com.onepassword.android)
        - [:simple-appstore: App Store](https://apps.apple.com/app/id1511601750?mt=8)
        - [:simple-windows11: Windows](https://1password.com/downloads/windows/)
        - [:simple-apple: macOS](https://1password.com/downloads/mac/)
        - [:simple-linux: Linux](https://1password.com/downloads/linux/)

Traditionally, **1Password** has offered the best password manager user experience for people using macOS and iOS; however, it has now achieved feature-parity across all platforms. It boasts many features geared towards families and less technical people, as well as advanced functionality.

Your 1Password vault is secured with both your master password and a randomized 34-character security key to encrypt your data on their servers. This security key adds a layer of protection to your data because your data is secured with high entropy regardless of your master password. Many other password manager solutions are entirely reliant on the strength of your master password to secure your data.

One advantage 1Password has over Bitwarden is its first-class support for native clients. While Bitwarden relegates many duties, especially account management features, to their web vault interface, 1Password makes nearly every feature available within its native mobile or desktop clients. 1Password's clients also have a more intuitive UI, which makes them easier to use and navigate.

### Bitwarden

!!! nota
    Consulte o [Tabela de Hardware](https://openwrt.org/toh/start) para verificar se o seu dispositivo é suportado.

    ![Bitwarden logo](/assets/img/password-management/bitwarden.svg){ align=right }
    
    **Bitwarden** é um gerenciador de senhas gratuito e de código aberto. Visa resolver problemas de gerenciamento de senhas para indivíduos, equipes e organizações empresariais. Bitwarden está entre as soluções mais fáceis e seguras para armazenar todos os seus logins e senhas, mantendo-os convenientemente sincronizados entre todos os seus dispositivos.
    
    [:octicons-home-16: Homepage](https://psono.com){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://psono.com/privacy-policy){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://doc.psono.com){ .card-link title=Documentation}
    [:octicons-code-16:](https://gitlab.com/psono){ .card-link title="Source Code" }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=com.psono.psono)
        - [:simple-appstore: App Store](https://apps.apple.com/us/app/psono-password-manager/id1545581224)
        - [:simple-firefoxbrowser: Firefox](https://addons.mozilla.org/firefox/addon/psono-pw-password-manager)
        - [:simple-googlechrome: Chrome](https://chrome.google.com/webstore/detail/psonopw-password-manager/eljmjmgjkbmpmfljlmklcfineebidmlo)
        - [:simple-docker: Docker Hub](https://hub.docker.com/r/psono/psono-client)

Psono provides extensive documentation for their product. The web-client for Psono can be self-hosted; alternatively, you can choose the full Community Edition or the Enterprise Edition with additional features.

### Framadate

**Please note we are not affiliated with any of the projects we recommend.** In addition to [our standard criteria](about/criteria.md), we have developed a clear set of requirements to allow us to provide objective recommendations. We suggest you familiarize yourself with this list before choosing to use a project, and conduct your own research to ensure it's the right choice for you.

!!! Considere o auto-hospedagem para mitigar esta ameaça.

    ![logo PrivateBin](/assets/img/productivity/privatebin.svg){ align=right }
    
    **PrivateBin** é um pastebin online minimalista e de código aberto onde o servidor tem zero conhecimento de dados colados. Os dados são criptografados/descriptografados no navegador usando AES de 256 bits. Psono suporta compartilhamento seguro de senhas, arquivos, marcadores e e-mails.

#### Minimum Requirements

- Must utilize strong, standards-based/modern E2EE.
- Must have thoroughly documented encryption and security practices.
- Must have a published audit from a reputable, independent third-party.
- All non-essential telemetry must be optional.
- Must not collect more PII than is necessary for billing purposes.

#### Best-Case

Our best-case criteria represents what we would like to see from the perfect project in this category. Our recommendations may not include any or all of this functionality, but those which do may rank higher than others on this page.

- Telemetry should be opt-in (disabled by default) or not collected at all.
- Should be open-source and reasonably self-hostable.

## Gestores locais de senhas

These options allow you to manage an encrypted password database locally.

### Vaultwarden

!!! nota
    Consulte o [Tabela de Hardware](https://openwrt.org/toh/start) para verificar se o seu dispositivo é suportado.

    ![KeePassXC logo](assets/img/password-management/keepassxc.svg){ align=right }
    
    **KeePassXC** is a community fork of KeePassX, a native cross-platform port of KeePass Password Safe, with the goal to extend and improve it with new features and bugfixes to provide a feature-rich, cross-platform and modern open-source password manager.
    
    [:octicons-home-16: Homepage](https://keepassxc.org){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://keepassxc.org/privacy){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://keepassxc.org/docs/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/keepassxreboot/keepassxc){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://keepassxc.org/donate/){ .card-link title=Contribute }
    
    ??? downloads
    
        - [:simple-windows11: Windows](https://keepassxc.org/download/#windows)
        - [:simple-apple: macOS](https://keepassxc.org/download/#mac)
        - [:simple-linux: Linux](https://keepassxc.org/download/#linux)
        - [:simple-flathub: Flatpak](https://flathub.org/apps/details/org.keepassxc.KeePassXC)
        - [:simple-firefoxbrowser: Firefox](https://addons.mozilla.org/firefox/addon/keepassxc-browser)
        - [:simple-googlechrome: Chrome](https://chrome.google.com/webstore/detail/keepassxc-browser/oboonakemofpalcgghocfoadofidjkkk)

KeePassXC stores its export data as [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) files. This may mean data loss if you import this file into another password manager. We advise you check each record manually.

### KeePassDX (Android)

!!! nota
    Consulte o [Tabela de Hardware](https://openwrt.org/toh/start) para verificar se o seu dispositivo é suportado.

    ![KeePassDX logo](assets/img/password-management/keepassdx.svg){ align=right }
    
    **KeePassDX** is a lightweight password manager for Android, allows editing encrypted data in a single file in KeePass format and can fill in the forms in a secure way. [Contributor Pro](https://play.google.com/store/apps/details?id=com.kunzisoft.keepass.pro) allows unlocking cosmetic content and non-standard protocol features, but more importantly, it helps and encourages development.
    
    [:octicons-home-16: Homepage](https://www.keepassdx.com){ .md-button .md-button--primary }
    [:octicons-info-16:](https://github.com/Kunzisoft/KeePassDX/wiki){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/Kunzisoft/KeePassDX){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://www.keepassdx.com/#donation){ .card-link title=Contribute }
    
    ??? downloads
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=com.kunzisoft.keepass.free)
        - [:simple-github: GitHub](https://github.com/Kunzisoft/KeePassDX/releases)

### Strongbox (iOS & macOS)

!!! nota
    Consulte o [Tabela de Hardware](https://openwrt.org/toh/start) para verificar se o seu dispositivo é suportado.

    ![Strongbox logo](assets/img/password-management/strongbox.svg){ align=right }
    
    **Strongbox** is a native, open-source password manager for iOS and macOS. Supporting both KeePass and Password Safe formats, Strongbox can be used in tandem with other password managers, like KeePassXC, on non-Apple platforms. By employing a [freemium model](https://strongboxsafe.com/pricing/), Strongbox offers most features under its free tier with more convenience-oriented [features](https://strongboxsafe.com/comparison/)—such as biometric authentication—locked behind a subscription or perpetual license.
    
    [:octicons-home-16: Homepage](https://strongboxsafe.com){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://strongboxsafe.com/privacy/){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://strongboxsafe.com/getting-started/){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/strongbox-password-safe/Strongbox){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://github.com/strongbox-password-safe/Strongbox#supporting-development){ .card-link title=Contribute }
    
    ??? downloads
    
        - [:simple-appstore: App Store](https://apps.apple.com/app/strongbox-keepass-pwsafe/id897283731)

Additionally, there is an offline-only version offered: [Strongbox Zero](https://apps.apple.com/app/strongbox-keepass-pwsafe/id1581589638). This version is stripped down in an attempt to reduce attack surface.

### Linha de comando

These products are minimal password managers that can be used within scripting applications.

#### gopass

!!! nota
    Consulte o [Tabela de Hardware](https://openwrt.org/toh/start) para verificar se o seu dispositivo é suportado.

    ![gopass logo](assets/img/password-management/gopass.svg){ align=right }
    
    **gopass** is a password manager for the command line written in Go. It works on all major desktop and server operating systems (Linux, macOS, BSD, Windows).
    
    [:octicons-home-16: Homepage](https://www.gopass.pw){ .md-button .md-button--primary }
    [:octicons-info-16:](https://github.com/gopasspw/gopass/tree/master/docs){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/gopasspw/gopass){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://github.com/sponsors/dominikschulz){ .card-link title=Contribute }
    
    ??? downloads
    
        - [:simple-windows11: Windows](https://www.gopass.pw/#install-windows)
        - [:simple-apple: macOS](https://www.gopass.pw/#install-macos)
        - [:simple-linux: Linux](https://www.gopass.pw/#install-linux)
        - [:simple-freebsd: FreeBSD](https://www.gopass.pw/#install-bsd)

### Framadate

**Please note we are not affiliated with any of the projects we recommend.** In addition to [our standard criteria](about/criteria.md), we have developed a clear set of requirements to allow us to provide objective recommendations. We suggest you familiarize yourself with this list before choosing to use a project, and conduct your own research to ensure it's the right choice for you.

!!! Considere o auto-hospedagem para mitigar esta ameaça.

    ![logo PrivateBin](/assets/img/productivity/privatebin.svg){ align=right }
    
    **PrivateBin** é um pastebin online minimalista e de código aberto onde o servidor tem zero conhecimento de dados colados. Os dados são criptografados/descriptografados no navegador usando AES de 256 bits. Psono suporta compartilhamento seguro de senhas, arquivos, marcadores e e-mails.

- Must be cross-platform.

--8<-- "includes/abbreviations.pt.txt"