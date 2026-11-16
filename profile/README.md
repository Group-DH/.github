<div align="center">

<img src="../assets/logo.png" width="120" height="120" alt="Group DH"/>

# Group DH

### Hosting, in every sense of the word.

We run the cloud, own the buildings and open the doors.

<br/>

<a href="https://group-dh.com"><picture><source media="(prefers-color-scheme: dark)" srcset="../assets/button-website-dark.svg"/><img src="../assets/button-website-light.svg" width="176" height="48" alt="Website"/></picture></a>&nbsp;
<a href="mailto:info@group-dh.com"><picture><source media="(prefers-color-scheme: dark)" srcset="../assets/button-contact-dark.svg"/><img src="../assets/button-contact-light.svg" width="176" height="48" alt="Contact"/></picture></a>&nbsp;
<a href="mailto:security@group-dh.com"><picture><source media="(prefers-color-scheme: dark)" srcset="../assets/button-security-dark.svg"/><img src="../assets/button-security-light.svg" width="176" height="48" alt="Security"/></picture></a>

</div>

<br/>

## How the group fits together

```mermaid
%%{init: {"theme": "base", "flowchart": {"curve": "step", "nodeSpacing": 34, "rankSpacing": 58, "padding": 18}, "themeVariables": {"fontFamily": "Roboto, Arial, sans-serif", "fontSize": "15px", "lineColor": "#829ec2", "primaryColor": "#ffffff", "primaryTextColor": "#0c0e11", "primaryBorderColor": "#4f94f0", "edgeLabelBackground": "#ffffff", "clusterBkg": "#f3f7fd", "clusterBorder": "#c9dcf7"}}}%%
flowchart TB
    ED(["<b>Elias De Hondt</b>"]):::person
    TD(["<b>Thomas Deweerdt</b>"]):::person
    EDH("<b>EDH Management BV</b><br/>management company"):::mgmt
    TDM("<b>TD Management BV</b><br/>management company"):::mgmt
    G("<b>GROUP DH BV</b><br/>holding"):::holding
    C("<b>Cloud DH BV</b><br/>hosts websites"):::company
    R("<b>Real Estate DH BV</b><br/>hosts tenants"):::company
    H("<b>Hospitality DH BV</b><br/>hosts guests"):::company
    EC(["<b>External clients</b><br/>± 99% of all clients"]):::external
    ET(["<b>External tenants</b><br/>± 95% of all tenants"]):::external

    subgraph VENUES["Venues"]
        direction LR
        V1("<b>Venue 1 BV</b>"):::venue
        V2("<b>Venue 2 BV</b>"):::venue
        V3("<b>Venue 3 BV</b>"):::venue
    end

    ED -->|100%| EDH
    TD -->|100%| TDM
    EDH -->|75%| G
    TDM -->|25%| G
    G -->|100%| C
    G -->|100%| R
    G -->|100%| H
    H -->|100%| VENUES
    C ==> EC
    R ==> ET
    R -.->|leases properties| VENUES
    C -.->|IT services| R
    C -.->|IT services| H

    classDef person fill:#ffffff,stroke:#4f94f0,stroke-width:2px,color:#0c0e11
    classDef mgmt fill:#f3f7fd,stroke:#829ec2,stroke-width:1px,color:#3d587b
    classDef holding fill:#0f54ae,stroke:#4f94f0,stroke-width:4px,color:#ffffff,font-size:17px
    classDef company fill:#4f94f0,stroke:#0f54ae,stroke-width:2px,color:#ffffff
    classDef venue fill:#ffffff,stroke:#4f94f0,stroke-width:1.5px,color:#0f54ae
    classDef external fill:#ffffff,stroke:#829ec2,stroke-width:1.5px,stroke-dasharray:6 5,color:#3d587b
    style VENUES fill:#f3f7fd,stroke:#c9dcf7,stroke-width:1px,color:#3d587b

    linkStyle 0,1,2,3,4,5,6,7 stroke:#3d587b,stroke-width:2px
    linkStyle 8,9 stroke:#4f94f0,stroke-width:3px
    linkStyle 10 stroke:#829ec2,stroke-width:2px
    linkStyle 11,12 stroke:#4f94f0,stroke-width:2px
```

<br/>

## Built by us, free for you

<table>
  <tr>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/Group-DH/DHMail"><img src="https://raw.githubusercontent.com/Group-DH/DHMail/main/App/build/icon.png" width="88" height="88" alt="DHMail"/></a>
      <h3><a href="https://github.com/Group-DH/DHMail">DHMail</a></h3>
      Mail, calendar and contacts for Windows.<br/>Your mail stays on your own computer.
    </td>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/Group-DH/DHFile"><img src="https://raw.githubusercontent.com/Group-DH/DHFile/main/App/build/icon.png" width="88" height="88" alt="DHFile"/></a>
      <h3><a href="https://github.com/Group-DH/DHFile">DHFile</a></h3>
      A tabbed file explorer for Windows<br/>with pinned folders and a PIN lock.
    </td>
    <td align="center" valign="top" width="33%">
      <a href="https://github.com/Group-DH/DHTerminal"><img src="https://raw.githubusercontent.com/Group-DH/DHTerminal/main/App/build/icon.png" width="88" height="88" alt="DHTerminal"/></a>
      <h3><a href="https://github.com/Group-DH/DHTerminal">DHTerminal</a></h3>
      Every shell and WSL distro on your PC<br/>in one tabbed terminal.
    </td>
  </tr>
</table>

<br/>

<div align="center">

<sub>💙🤍 &nbsp; © Group DH &nbsp;·&nbsp; [group-dh.com](https://group-dh.com) &nbsp;·&nbsp; [Privacy Policy](https://group-dh.com/privacypolicy) &nbsp;·&nbsp; [Legal Guidelines](https://group-dh.com/legalguidelines) &nbsp; 💙🤍</sub>

</div>
