
![Logo](https://static.wixstatic.com/media/aacf8f_ffba4c205ec04ec09101fe63ef0413bc~mv2.png)


## License

[![MIT License](https://img.shields.io/badge/License-CC--BY--SA--4.0%20-blue)](https://choosealicense.com/licenses/cc-by-sa-4.0/)

# Killing The Bear - BloodCoin
![tag0](https://img.shields.io/badge/Used%20With-OpenAI-9cf) ![tag0](https://img.shields.io/badge/Used%20With-MidJourney-9cf) 

Killing The Bear: BloodCoin is repo that allows users to collect crypto wallet addresses (mainly BTC) from ransom notes. These addresses are from real and recent attacks on services like ELK, MongoDB, and other unsecured resources, allowing researchers to be aware of the latest movements and protect themselves from future attacks. BloodCoin also collects email addresses associated with ransom notes, as well as metadata such as countries, continents, services, versions and ports. 
Events are grouped so track data along days its possible.

It is a repository focused on data storage and analysis. Data is updated every day and is available in JSON format.

Killing The Bear: BloodCoin also collects email addresses associated with ransom notes, as well as metadata such as countries, continents, services, versions and ports.
## Features

- Compilation of real and recent ransom crypto wallet addresses used in ongoing attacks. ![tag1](https://img.shields.io/badge/%F0%9F%90%BB-In%20Real%20Time-important)

- Collection of email addresses used by threat actors to stabilish comms with the victim. ![tag2](https://img.shields.io/badge/%F0%9F%90%BB-7%2F365-important)

- Collection of metadata such as countries, continents, services, versions and ports of the attacks 
![tag3](https://img.shields.io/badge/%2B-Elasticsearch-blueviolet) ![tag4](https://img.shields.io/badge/%2B-Kibana-ff69b4) ![tag5](https://img.shields.io/badge/%2B-MongoDB-success) ![tag6](https://img.shields.io/badge/%2B-MySQL-informational)

- Analysis of outgoing transactions and related wallets ![tag7](https://img.shields.io/badge/%E2%82%BF-BTC-yellow)
## 🎯 Roadmap

- Being the bad news for some mxtherf@ck*rs out there. ✅

- Deploy customized honeypots focused on hunting and studying the behavior and bruteforce dicts of these attacks, using the geographic, product, service and version statistics collected. 🔄

- Build a public-face dashboard to filter data 🔄

- Be able to send reports in bulk about wallets listed and make it public to make harder for the threat actor to catch the money from victim. 🔄
## How to use it

[Attack Wallets](https://github.com/Ud0g-Py/Killing-the-Bear-BloodCoin/attack_wallets.json)

Gathers information on recents REAL attacks

```
{
    "uuid": {
        "_id": "uuid",
        "is_wallet": boolean,
        "emails_related": ["string"],
        "tracking": [
            {
                "bytes_encrypted": long int,
                "seen_at": date (YYYY-MM-DD),
                "countries": [
                    "string
                ],
                "continents": [
                    "string"
                ],
                "services": [
                    {
                        "service": "string",
                        "version": "string"
                    }
                ],
                "ports": [
                    "string"
                ]
            }
        ],
        "observed_countries": [
            "string"
        ],
        "observed_continents": [
            "string"
        ],
        "observed_ports": [
            "string"
        ],
        "hit_services": {
            "string" (product): [
                "string" (version)
            ]
        },
        "last_seen": date (YYYY-MM-DD)
    },

```

[TX Wallets](https://github.com/Ud0g-Py/Killing-the-Bear-BloodCoin/tx_wallets.json)

Information about transactions and cash flow after an attack, related wallets used for money laundering masquerading with high confidence, etc.


```
{
    "uuid": {
    "is_valid": true,
    "hash160": "0e6a27c68d45600ca9d5df7c99a1af43bd78c97e",
    "n_transactions": 2,
    "n_unredeemed": 0,
    "total_received": 13000000,
    "total_sent": 13000000,
    "final_balance": 0,
    "sent_cash_to": [
        "bc1q4ag90l9jh97trqxktumze24xc0pn8595ty33yef0sreugr7tedeqkr2cy7",
        "1Jcd2n978MibNbTcLJrik63tueNvzRVGZM",
        "12KDdVSHvaB46gGTS7pDiBACyWtx5pv5Hs",
        "3LVMe8YgrsyEhRcpEakcyh1VRisBhs1fsM",
        "1GrwDkr33gT6LuumniYjKEGjTLhsL5kmqC"
    ],
    "last_check": "2023-01-29 21:03:14"
    },

```
## 🐻 About Me
Author of "Killing The Bear" (v2.0 WIP)

Global Cybersecurity Technology Researcher Lead

MITRE ATT&CK Defender
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://jorgetesta.tech)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jorge-testa-ciberseguridad/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://mobile.twitter.com/jrg_testa)

