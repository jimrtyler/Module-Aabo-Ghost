# 👻 Modulu Aabo Ghost
**Irinṣẹ Ṣiṣe Aabo Windows ati Azure ti o da lori PowerShell**

> **Ṣiṣe aabo ti o ṣaaju fun awọn endpoints Windows ati awọn ayika Azure.** Ghost n pese awọn iṣẹ ṣiṣe aabo ti o da lori PowerShell ti o le ṣe iranlọwọ lati dinku awọn ọna ikọlu ti o wọpọ nipa piparẹ awọn iṣẹ ati awọn ilana ti ko ṣe pataki.

## ⚠️ Awọn Ikede Pataki

**IDANWO JẸ DANDAN**: Nigbagbogbo ṣe idanwo Ghost ni ayika ti kii ṣe iṣelọpọ ni akọkọ. Piparẹ awọn iṣẹ le ni ipa lori awọn iṣẹ iṣowo to tọ.

**KO SI IDANILOJU**: Botilẹjẹpe Ghost n dojukọ awọn ọna ikọlu ti o wọpọ, ko si irinṣẹ aabo ti o le dena gbogbo awọn ikọlu. Eyi jẹ apakan ti ilana aabo pipe.

**IPA IṢẸ-ṢIṢE**: Diẹ ninu awọn iṣẹ le ni ipa lori iṣẹ ṣiṣe eto naa. Ṣe ayẹwo gbogbo eto ni pẹkipẹki ṣaaju ki o to gbe sipo.

**IGBELEWỌN ALAMỌDAJU**: Fun awọn ayika iṣelọpọ, bá awọn alamọdaju aabo sọrọ lati rii daju pe awọn eto naa baamu pẹlu awọn aini ti ajọ rẹ.

## 📊 Ilẹ Aabo

Awọn ibajẹ ransomware de **$57 billion ni 2025**, iwadii n fihan pe ọpọlọpọ awọn ikọlu aṣeyọri n lo awọn iṣẹ Windows ipilẹ ati awọn eto ti ko tọ. Awọn ọna ikọlu ti o wọpọ pẹlu:

- **90% ti awọn iṣẹlẹ ransomware** ni ilowosi RDP ninu
- **Awọn ailera SMBv1** jẹ ki awọn ikọlu bii WannaCry ati NotPetya ṣẹlẹ
- **Awọn makiro iwe** n tẹsiwaju lati jẹ ọna ifijiṣẹ malware akọkọ
- **Awọn ikọlu ti o da lori USB** n tẹsiwaju lati dojukọ awọn nẹtiwọọki ti o ni aafo
- **Ilokulo PowerShell** ti pọ si ni pataki ni awọn ọdun aipẹ

## 🛡️ Awọn Iṣẹ Aabo Ghost

Ghost n pese **awọn iṣẹ ṣiṣe aabo Windows 16** ati **isopọ aabo Azure**:

### Ṣiṣe Aabo Endpoint Windows

| Iṣẹ | Idi | Awọn Ironu |
|----------|---------|----------------|
| `Set-RDP` | Ṣakoso wiwọle Remote Desktop | O le ni ipa lori iṣakoso latọna jijin |
| `Set-SMBv1` | Ṣakoso ilana SMB atijọ | O nilo fun awọn eto ti o ti gbó pupọ |
| `Set-AutoRun` | Ṣakoso AutoPlay/AutoRun | O le ni ipa lori irọrun olumulo |
| `Set-USBStorage` | Ṣe ihamọ awọn ẹrọ ipamọ USB | O le ni ipa lori lilo USB to tọ |
| `Set-Macros` | Ṣakoso ṣiṣe makiro Office | O le ni ipa lori awọn iwe ti o ni makiro |
| `Set-PSRemoting` | Ṣakoso PowerShell remoting | O le ni ipa lori iṣakoso latọna jijin |
| `Set-WinRM` | Ṣakoso Windows Remote Management | O le ni ipa lori iṣakoso latọna jijin |
| `Set-LLMNR` | Ṣakoso ilana ipinnu orukọ | Igbagbogbo o jẹ ailewu lati pa |
| `Set-NetBIOS` | Ṣakoso NetBIOS lori TCP/IP | O le ni ipa lori awọn ohun elo atijọ |
| `Set-AdminShares` | Ṣakoso awọn ipin alakoso | O le ni ipa lori wiwọle faili latọna jijin |
| `Set-Telemetry` | Ṣakoso gbigba data | O le ni ipa lori awọn agbara ayẹwo |
| `Set-GuestAccount` | Ṣakoso akọọlẹ alejo | Igbagbogbo o jẹ ailewu lati pa |
| `Set-ICMP` | Ṣakoso awọn idahun ping | O le ni ipa lori ayẹwo nẹtiwọọki |
| `Set-RemoteAssistance` | Ṣakoso Remote Assistance | O le ni ipa lori awọn iṣẹ tẹẹbulu iranlọwọ |
| `Set-NetworkDiscovery` | Ṣakoso wiwa nẹtiwọọki | O le ni ipa lori ṣiṣawari nẹtiwọọki |
| `Set-Firewall` | Ṣakoso Windows Firewall | O ṣe pataki fun aabo nẹtiwọọki |

### Aabo Cloud Azure

| Iṣẹ | Idi | Awọn Ibeere |
|----------|---------|--------------|
| `Set-AzureSecurityDefaults` | Mu aabo Azure AD ipilẹ ṣiṣẹ | Awọn ààyè Microsoft Graph |
| `Set-AzureConditionalAccess` | Ṣeto awọn eto imulo wiwọle | Ìwé-àṣẹ Azure AD P1/P2 |
| `Set-AzurePrivilegedUsers` | Ṣe ayẹwo awọn akọọlẹ anfani | Awọn ààyè Global Admin |

### Awọn Aṣayan Gbigbe sipo Ile-iṣẹ

| Ọna | Iṣẹlọ Lilo | Awọn Ibeere |
|--------|----------|--------------|
| **Ṣiṣe Taara** | Idanwo, awọn ayika kekere | Awọn ẹtọ admin agbegbe |
| **Group Policy** | Awọn ayika domain | Admin domain, iṣakoso GP |
| **Microsoft Intune** | Awọn ẹrọ ti a ṣakoso cloud | Ìwé-àṣẹ Intune, Graph API |

## 🚀 Ibẹrẹ Ni Iyara

### Igbelewọn Aabo
```powershell
# Ṣii modulu Ghost
IEX(Invoke-WebRequest 'https://raw.githubusercontent.com/jimrtyler/Ghost/main/Ghost.ps1')

# Ṣayẹwo ipo aabo lọwọlọwọ
Get-Ghost
```

### Ṣiṣe Aabo Ipilẹ (Ṣe Idanwo Ni Akọkọ)
```powershell
# Ṣiṣe aabo pataki - ṣe idanwo ni ayika yàrá-ìwádìí ni akọkọ
Set-Ghost -SMBv1 -AutoRun -Macros

# Ṣe ayẹwo awọn iyipada
Get-Ghost
```

### Gbigbe Sipo Ile-iṣẹ
```powershell
# Gbigbe sipo Group Policy (awọn ayika domain)
Set-Ghost -SMBv1 -AutoRun -GroupPolicy

# Gbigbe sipo Intune (awọn ẹrọ ti a ṣakoso cloud)
Set-Ghost -SMBv1 -RDP -USBStorage -Intune
```

## 📋 Awọn Ọna Fifi Sori

### Aṣayan 1: Gbigba Taara (Idanwo)
```powershell
IEX(Invoke-WebRequest 'https://raw.githubusercontent.com/jimrtyler/Ghost/main/Ghost.ps1')
```

### Aṣayan 2: Fifi Sori Modulu
```powershell
# Fi sori lati PowerShell Gallery (nigbati o ba wa)
Install-Module Ghost -Scope CurrentUser
Import-Module Ghost
```

### Aṣayan 3: Gbigbe Sipo Ile-iṣẹ
```powershell
# Ṣe ẹda si ipo nẹtiwọọki fun gbigbe sipo Group Policy
# Ṣeto awọn iwe afọwọkọ PowerShell Intune fun gbigbe sipo cloud
```

## 💼 Awọn Apẹẹrẹ Iṣẹlọ Lilo

### Iṣowo Kekere
```powershell
# Aabo ipilẹ pẹlu ipa kekere
Set-Ghost -SMBv1 -AutoRun -Macros -ICMP
```

### Ayika Itọju Ilera
```powershell
# Ṣiṣe aabo ti o dojukọ HIPAA
Set-Ghost -SMBv1 -RDP -USBStorage -AdminShares -Telemetry
```

### Awọn Iṣẹ Inawo
```powershell
# Eto aabo giga
Set-Ghost -RDP -SMBv1 -AutoRun -USBStorage -Macros -PSRemoting -AdminShares
```

### Ajọ Cloud-Akọkọ
```powershell
# Gbigbe sipo ti a ṣakoso Intune
Connect-IntuneGhost -Interactive
Set-Ghost -SMBv1 -RDP -AutoRun -Macros -Intune
```

## 🔍 Awọn Alaye Iṣẹ

### Awọn Iṣẹ Ṣiṣe Aabo Ipilẹ

#### Awọn Iṣẹ Nẹtiwọọki
- **RDP**: Da wiwọle desktop latọna jijin duro tabi ṣe port ni aiduroṣinṣin
- **SMBv1**: Pa ilana pipin faili atijọ
- **ICMP**: Dena awọn idahun ping fun iwakiri
- **LLMNR/NetBIOS**: Da awọn ilana ipinnu orukọ atijọ duro

#### Aabo Ohun Elo
- **Macros**: Pa ṣiṣe makiro ninu awọn ohun elo Office
- **AutoRun**: Dena ṣiṣe adaṣe lati media ti o yọ kuro

#### Iṣakoso Latọna Jijin
- **PSRemoting**: Pa awọn igba PowerShell latọna jijin
- **WinRM**: Da Windows Remote Management duro
- **Remote Assistance**: Da awọn asopọ iranlọwọ latọna jijin duro

#### Iṣakoso Wiwọle
- **Admin Shares**: Pa awọn ipin C$, ADMIN$
- **Guest Account**: Pa wiwọle akọọlẹ alejo
- **USB Storage**: Ṣe ihamọ lilo ẹrọ USB

### Isopọ Azure
```powershell
# Sopọ si tenant Azure
Connect-AzureGhost -Interactive

# Mu awọn aiyipada aabo ṣiṣẹ
Set-AzureSecurityDefaults -Enable

# Ṣeto wiwọle ipo
Set-AzureConditionalAccess -BlockLegacyAuth -RequireMFA

# Ṣe ayẹwo awọn olumulo anfani
Set-AzurePrivilegedUsers -AuditOnly
```

### Isopọ Intune (Tuntun ni v2)
```powershell
# Sopọ si Intune
Connect-IntuneGhost -Interactive

# Gbe sipo nipasẹ awọn eto imulo Intune
Set-IntuneGhost -Settings @{
    RDP = $true
    SMBv1 = $true
    USBStorage = $true
    Macros = $true
}
```

## ⚠️ Awọn Ironu Pataki

### Awọn Ibeere Idanwo
- **Ayika Yàrá-ìwádìí**: Ṣe idanwo gbogbo eto ni ayika ti o yapa ni akọkọ
- **Gbigbe Sipo Ni Ipele**: Gbe jade ni diẹdiẹ lati ṣe idanimọ awọn iṣoro
- **Eto Ipadasẹhin**: Rii daju pe o le yi awọn iyipada pada bi o ba nilo
- **Iwe Akọsilẹ**: Kọ silẹ eto wo ti o ṣiṣẹ fun ayika rẹ

### Ipa Ti O Ṣeeṣe
- **Iṣelọpọ Olumulo**: Diẹ ninu awọn eto le ni ipa lori awọn ilana iṣẹ ojoojumọ
- **Awọn Ohun Elo Atijọ**: Awọn eto atijọ le nilo awọn ilana kan pato
- **Wiwọle Latọna Jijin**: Ronu ipa lori iṣakoso latọna jijin to tọ
- **Awọn Ilana Iṣowo**: Rii daju pe awọn eto ko ba awọn iṣẹ pataki jẹ

### Awọn Idiwọn Aabo
- **Aabo Ni Ijinlẹ**: Ghost jẹ ipele aabo kan, kii ṣe ojutu pipe
- **Iṣakoso Lọwọlọwọ**: Aabo nilo aṣoju ati awọn imudojuiwọn nigbagbogbo
- **Ikẹkọ Olumulo**: Awọn iṣakoso imọ-ẹrọ gbọdọ jẹ pọ pẹlu mimọ aabo
- **Itankalẹ Irokeke**: Awọn ọna ikọlu tuntun le kọja awọn aabo lọwọlọwọ

## 🎯 Awọn Apẹẹrẹ Oju-iṣẹlẹ Ikọlu

Botilẹjẹpe Ghost n dojukọ awọn ọna ikọlu ti o wọpọ, iyipada kan pato dale lori imuse to tọ ati idanwo:

### Awọn Ikọlu Aṣa WannaCry
- **Idinku**: `Set-Ghost -SMBv1` pa ilana ti o ni ailera
- **Ironu**: Rii daju pe ko si eto atijọ ti o nilo SMBv1

### Ransomware Ti O Da Lori RDP
- **Idinku**: `Set-Ghost -RDP` da wiwọle desktop latọna jijin duro
- **Ironu**: O le nilo awọn ọna wiwọle latọna jijin miiran

### Malware Ti O Da Lori Iwe
- **Idinku**: `Set-Ghost -Macros` pa ṣiṣe makiro
- **Ironu**: O le ni ipa lori awọn iwe makiro to tọ

### Awọn Irokeke Ti A Fi Ranṣẹ USB
- **Idinku**: `Set-Ghost -USBStorage -AutoRun` ṣe ihamọ iṣẹ ṣiṣe USB
- **Ironu**: O le ni ipa lori lilo ẹrọ USB to tọ

## 🏢 Awọn Ẹya Ile-iṣẹ

### Atilẹyin Group Policy
```powershell
# Lo awọn eto nipasẹ registry Group Policy
Set-Ghost -SMBv1 -RDP -AutoRun -GroupPolicy

# Awọn eto lo kaakiri domain lẹhin isọdọtun GP
gpupdate /force
```

### Isopọ Microsoft Intune
```powershell
# Ṣẹda awọn eto imulo Intune fun awọn eto Ghost
Set-IntuneGhost -Settings $GhostSettings -Interactive

# Awọn eto imulo gbe sipo laifọwọyi si awọn ẹrọ ti a ṣakoso
```

### Ijabọ Ibamu
```powershell
# Ṣẹda ijabọ igbelewọn aabo
Get-Ghost | Export-Csv -Path "SecurityAudit-$(Get-Date -Format 'yyyy-MM-dd').csv"

# Ijabọ ipo aabo Azure
Get-AzureGhost | Out-File "AzureSecurityReport.txt"
```

## 📚 Awọn Iṣe Ti O Dara Julọ

### Ṣaaju Gbigbe Sipo
1. **Kọ Ipo Lọwọlọwọ**: Ṣiṣẹ `Get-Ghost` ṣaaju awọn iyipada
2. **Ṣe Idanwo Kedere**: Jẹrisi ni ayika ti kii ṣe iṣelọpọ
3. **Ṣe Eto Ipadasẹhin**: Mọ bi o ṣe le yi eto kọọkan pada
4. **Atunyẹwo Alakopa**: Rii daju pe awọn ẹka iṣowo fọwọsi awọn iyipada

### Lakoko Gbigbe Sipo
1. **Ọna Ipele**: Gbe sipo si awọn ẹgbẹ awakọ ni akọkọ
2. **Ṣe Aṣoju Ipa**: Wo awọn ẹdun olumulo tabi awọn iṣoro eto
3. **Kọ Awọn Iṣoro Silẹ**: Kọ eyikeyi iṣoro fun itọkasi ọjọ iwaju
4. **Sọ Awọn Iyipada**: Sọ fun awọn olumulo nipa awọn ilọsiwaju aabo

### Lẹhin Gbigbe Sipo
1. **Igbelewọn Deede**: Ṣiṣẹ `Get-Ghost` ni ọlọrọọkan lati jẹrisi awọn eto
2. **Ṣe Imudojuiwọn Iwe Akọsilẹ**: Jẹ ki awọn eto aabo wa lọwọlọwọ
3. **Ṣe Atunyẹwo Iṣẹ Ṣiṣe**: Ṣe aṣoju fun awọn iṣẹlẹ aabo
4. **Ilọsiwaju Lọwọlọwọ**: Ṣatunṣe awọn eto da lori ilẹ irokeke

## 🔧 Yanju Iṣoro

### Awọn Iṣoro Ti O Wọpọ
- **Awọn Aṣiṣe Ààyè**: Rii daju igba PowerShell ti a gbe soke
- **Awọn Igbẹkẹle Iṣẹ**: Diẹ ninu awọn iṣẹ le ni awọn igbẹkẹle
- **Ibamu Ohun Elo**: Ṣe idanwo pẹlu awọn ohun elo iṣowo
- **Asopọ Nẹtiwọọki**: Rii daju pe wiwọle latọna jijin tun n ṣiṣẹ

### Awọn Aṣayan Imularada
```powershell
# Tun mu awọn iṣẹ kan pato ṣiṣẹ ti o ba nilo
Set-RDP -Enable
Set-SMBv1 -Enable
Set-AutoRun -Enable
Set-Macros -Enable
```

## 👨‍💻 Nipa Onkọwe

**Jim Tyler** - Microsoft MVP fun PowerShell
- **YouTube**: [@PowerShellEngineer](https://youtube.com/@PowerShellEngineer) (10,000+ alabapin)
- **Newsletter**: [PowerShell.News](https://powershell.news) - Ọgbọn aabo ọsẹ kọọkan
- **Onkọwe**: "PowerShell for Systems Engineers"
- **Iriri**: Awọn ọgọrun ọdun ti adaṣe PowerShell ati aabo Windows

## 📄 Iwe-aṣẹ ati Ikede

### Iwe-aṣẹ MIT
A pese Ghost labẹ Iwe-aṣẹ MIT fun lilo ọfẹ, iyipada, ati pinpin.

### Ikede Aabo
- **Ko Si Idaniloju**: A pese Ghost "bi o ti jẹ" laisi idaniloju eyikeyi
- **Idanwo Jẹ Dandan**: Nigbagbogbo ṣe idanwo ni awọn ayika ti kii ṣe iṣelọpọ ni akọkọ
- **Itọsọna Alamọdaju**: Bá awọn alamọdaju aabo sọrọ fun awọn gbigbe sipo iṣelọpọ
- **Ipa Iṣẹ-Ṣiṣe**: Awọn onkọwe ko ni iduro fun idiwọ iṣẹ-ṣiṣe eyikeyi
- **Aabo Pipe**: Ghost jẹ apakan ti ilana aabo pipe

### Atilẹyin
- **Awọn Ọran GitHub**: [Jabo awọn kokoro tabi beere awọn ẹya](https://github.com/jimrtyler/Ghost/issues)
- **Iwe Akọsilẹ**: Lo `Get-Help <function> -Full` fun iranlọwọ alaye
- **Agbegbe**: Awọn ọja agbegbe PowerShell ati aabo

---

**🔒 Mu ipo aabo rẹ lera pẹlu Ghost - ṣugbọn nigbagbogbo ṣe idanwo ni akọkọ.**

```powershell
# Bẹrẹ pẹlu igbelewọn, kii ṣe awọn ifura
Get-Ghost
```

**⭐ Ti Ghost ba ṣe iranlọwọ lati mu ipo aabo rẹ pọ si, fun ibi ipamọ yii ni irawọ!**