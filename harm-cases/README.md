# 💣 [Harm cases](../../meta/README.md#harm-cases)

Aka. attack vectors or vulnerabilities, describing the set of scenarios that lead to significantly undesirable outcomes. These can occur as the result of a malicious attack, or due to oversight or accidents.

>Note: The default technology wave we are focusing on is Web 2.0, which represents the set of modern technologies currently used on the internet.

The below sections first outline the general themes of harm enabled by the technology wave, and subsequently enumerate individual harm cases, first organized by the party that is harmed, then by the type of attack, vulnerability or disaster that initiates the harm.

## 📚 Harm themes

- **Hacked systems** - Compromised accounts, device, OS or App - Mass account hacks at the provider side are a high-scale special case
- **Value extraction** (Surveillance) (BigTech) - through prediction and selling or conversion of insights into profits (Surveillance capitalism) - a type of rent seeking
- **Customer lock-in** (monopoly behavior) (BigTech) - leads to rent seeking
- **Censorship** (platforms) (BigTech) - due to social and political pressure
- **Systematic political suppression** (Surveillance and force) (BigGov + BigTech)

### 👨‍💻 Hacked systems

### 🧛‍♂️ Value extraction

### ⛓ Customer lock-in

### 🤐 Censorship

### 🏴 Systematic political suppression

## 👩🏻 Consumer

Below we look at significant cases where the consumer as identity owner is harmed due to an attack, a security vulnerability, and/or accidental negative outcomes.

### 😧 Credential loss

There is only a single valid original copy of a credential, making it vulnerable to the loss or damage to the point of unusability.

1. User loses the credential or the credential is damaged beyond use
2. User may have also lost other supporting credentials
3. User needs to get a replacement credential

Mitigation types:

1. Issuer recovery
2. Social recovery
3. Combination of some or all of above

Mitigation steps:

1. Applying for a replacement credential from institution

![Credential loss][credential-loss]

[credential-loss]: images/credential-loss.png

### 🗃 Hacked accounts

Businesses transacting with individuals and institutions with individual members often keep a copy of their client's identity and personal information, in case of having to refer back to them on subsequent interactions.

1. Consumer connects and registers with business or institution
2. Business or institutions creates and account with identity and personal information
3. An attacker compromises client accounts en-masse and obtains copies
4. Attacker can further abuse identity and personal information - selling, further attacking, etc

![Accounts hacked][accounts-hack]

[accounts-hack]: images/accounts-hack.png

Harm:

- Privacy rights for a large number of consumers has been violated
- Further costs or risks may ensue as result of further dissemination of that information - Cost of replacing with new identity and personal info, risk of being targeted virtually or physically

Mitigation types:

1. Offline storage of account information
2. No storage of account information
3. Storage per consumer permissions
4. Combination of some or all of above

Mitigation steps:

1. Notifying those affected of the compromise.

#### 👣 Tracking

Incomplete ...

### 🧛 Value extraction

Big tech identity provider uses asymmetric strategic power position, stemming from scale, to extracts value from identity owners they provide identity services to.

- Violating privacy - Strong-arming users into giving up ownership of personal data and activity information for free, meanwhile gaslighting them by minimizing the harm incurred, in return to services that have no real market alternatives due to monopoly powers:
  - Using personal data and tracking information to produce and sell insights to advertisers, that gives them unfair advantages in influencing the user's behavior.
  - Using personal data and tracking information to gain an unfair advantage by influencing the user's behavior
User lock-in - Enforcing high switching costs on users who are leaning towards switching out of identity services bundled with other services, using leverage of scale and market power.

Incomplete ...

### 🔓 User lock-in

## 🧑‍💼 Relying party

Below we look at significant cases involving harm to a so called relaying party, that is one that relies on the correctness of a verification by a trusted party through credentials or other means.

### 🥸 Credential forgery

![Credential forgery][credential-forgery]

[credential-forgery]: images/credential-forgery.png
