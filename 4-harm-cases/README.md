# 💣 [Harm cases](../../meta/README.md#harm-cases)

Aka. attack vectors or vulnerabilities, describing the set of scenarios that lead to significantly undesirable outcomes. These can occur as the result of a malicious attack, or due to oversight or accidents.

## 👩🏻 Consumer

Below we look at significant cases where the consumer as identity owner is harmed due to an attack, a security vulnerability, and/or accidental negative outcomes.

### 😧 Credential loss

Only a single copy of every given private keys is stored in a given device, making it vulnerable to the loss of that key due to device malfunction or loss.

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

### 😱 Credential theft

![Credential theft][credential-theft]

[credential-theft]: images/credential-theft.png

## 🧑‍💼 Relying party

### 😱 Credential forgery

![Credential forgery][credential-forgery]

[credential-forgery]: images/credential-forgery.png
