# Validator für XBildung

Mit diesem Validator können Sie XML-Nachweise, die für die Standards XHochschule, XSchule oder XBerufsbildung erstellt wurden, validieren. Es erfolgt sowohl eine Überprüfung der Schema- als auch der Schematron-Konformität.

Die Prüfungen der Konformität bauen aufeinander auf, ein erfolgreiches Validieren der vorigen Prüfebene ist Grundlage für die darauffolgenden Prüfschritte.

1. XML-Konformität: XML Wellformedness (Sind alle Tags geschlossen, gibt es ein root-Element?)
2. XSD-Konformität: Sind die Angaben gemäß der XML Schemadefinition (Reihenfolgen, Pflichtfelder, Enumeration) konform?
3. ISO Schematron-Konformität: Werden die formulierten Geschäftsregeln eingehalten?
4. Spezifikationskonformität: lässt sich nicht automatisiert prüfen, kann nur durch menschlichen Einsatz geprüft werden

---

Dieser Dienst wird durch das [**EU Interoperability Test Bed**](https://joinup.ec.europa.eu/solution/interoperability-test-bed) ermöglicht, deren Komponenten - nicht die Artefakte aus diesem Repository - unter [EUPL 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12) veröffentlicht werden. [Hier erhalten Sie weitere Informationen.](https://interoperable-europe.ec.europa.eu/collection/interoperability-test-bed-repository/solution/interoperability-test-bed/detailed-information#licencing)