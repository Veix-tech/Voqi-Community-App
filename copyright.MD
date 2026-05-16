(C) Copyright By Veix INC 2026c
# Dokument zgodności prawnej dla aplikacji komunikacyjnej

## UE / Wielka Brytania / USA

> Ten dokument ma charakter informacyjny i nie stanowi porady prawnej. Przed publikacją aplikacji należy skonsultować dokumentację z prawnikiem specjalizującym się w prawie technologicznym, prywatności danych i telekomunikacji.

---

# 1. Zakres aplikacji

Aplikacja umożliwia:

* komunikację tekstową,
* przesyłanie zdjęć i plików,
* komunikację w czasie rzeczywistym,
* przechowywanie danych użytkowników,
* potencjalne szyfrowanie wiadomości,
* funkcje społecznościowe.

Z tego względu aplikacja podlega regulacjom dotyczącym:

* ochrony danych,
* cyberbezpieczeństwa,
* telekomunikacji,
* moderacji treści,
* ochrony konsumenta,
* przechowywania danych użytkowników.

---

# 2. Wymagane dokumenty prawne

## Obowiązkowe

### 2.1 Polityka prywatności (Privacy Policy)

Musi zawierać:

* jakie dane są zbierane,
* cel przetwarzania danych,
* podstawę prawną przetwarzania,
* czas przechowywania danych,
* informacje o cookies i analytics,
* prawa użytkownika,
* kontakt do administratora danych,
* informacje o transferze danych poza UE.

## 2.2 Regulamin aplikacji (Terms of Service)

Powinien określać:

* zasady korzystania z aplikacji,
* ograniczenia odpowiedzialności,
* zasady blokowania kont,
* zakaz nielegalnych działań,
* prawa własności intelektualnej,
* warunki usunięcia konta.

## 2.3 Polityka cookies

Wymagana szczególnie w UE i UK.

## 2.4 Umowa przetwarzania danych (DPA)

Jeśli korzystasz z:

* Firebase,
* AWS,
* Google Analytics,
* OpenAI API,
* Stripe,
* innych usług przetwarzających dane.

---

# 3. Wymagania prawne – Unia Europejska

## 3.1 GDPR / RODO

Najważniejsze wymagania:

* zgoda użytkownika na przetwarzanie danych,
* możliwość eksportu danych,
* możliwość usunięcia konta,
* minimalizacja danych,
* szyfrowanie transmisji,
* zgłaszanie wycieków danych do 72h,
* rejestr czynności przetwarzania.

## 3.2 Digital Services Act (DSA)

Jeśli użytkownicy publikują treści:

* musisz umożliwić zgłaszanie naruszeń,
* musisz moderować nielegalne treści,
* potrzebny jest kontakt dla organów UE,
* wymagane są procedury odwoławcze.

## 3.3 ePrivacy Directive

Dotyczy:

* cookies,
* trackingów,
* marketingu,
* komunikacji elektronicznej.

## 3.4 AI Act (jeśli używasz AI)

Jeżeli aplikacja analizuje wiadomości lub generuje odpowiedzi AI:

* wymagane oznaczenie funkcji AI,
* transparentność działania modeli,
* ograniczenie ryzyka nadużyć.

---

# 4. Wymagania prawne – Wielka Brytania

## 4.1 UK GDPR

Brytyjska wersja GDPR.

Wymagane:

* lawful basis,
* data deletion,
* user consent,
* security safeguards.

## 4.2 Online Safety Act

Jeśli aplikacja ma:

* czaty publiczne,
* wiadomości,
* społeczność,
* media użytkowników,

musisz:

* przeciwdziałać nielegalnym treściom,
* posiadać system raportowania,
* chronić nieletnich,
* usuwać treści terrorystyczne i CSAM.

---

# 5. Wymagania prawne – USA

## 5.1 California Consumer Privacy Act (CCPA)

Wymagane dla użytkowników z Kalifornii.

Użytkownik musi mieć możliwość:

* poznania danych jakie zbierasz,
* usunięcia danych,
* rezygnacji ze sprzedaży danych.

## 5.2 COPPA

Jeśli aplikacja jest dla dzieci poniżej 13 lat:

* wymagana zgoda rodziców,
* dodatkowe zabezpieczenia.

## 5.3 CAN-SPAM Act

Jeśli wysyłasz:

* newslettery,
* emaile marketingowe,
* powiadomienia handlowe.

---

# 6. Szyfrowanie i bezpieczeństwo

Zalecane:

* HTTPS/TLS 1.2+,
* szyfrowanie danych w bazie,
* rate limiting,
* MFA dla administratorów,
* hashing haseł (bcrypt/argon2),
* end-to-end encryption dla wiadomości.

---

# 7. Hosting i transfer danych

## Zalecane regiony hostingu

### UE

* Frankfurt
* Warsaw
* Paris

### UK

* London

### USA

* Virginia
* Oregon

## Transfer danych poza UE

Wymagane:

* SCC (Standard Contractual Clauses),
* Data Processing Agreements,
* zgodność z GDPR.

---

# 8. App Store / Google Play wymagania

## Google Play

Wymagane:

* polityka prywatności,
* formularz bezpieczeństwa danych,
* zgłoszenie użycia uprawnień,
* zgodność z Families Policy jeśli aplikacja dla dzieci.

## Apple App Store

Wymagane:

* App Privacy Details,
* account deletion option,
* zgoda na tracking (ATT).

---

# 9. Minimalny pakiet zgodności dla startupu

## Must-have przed publikacją

* Privacy Policy
* Terms of Service
* Delete Account Function
* Export User Data
* HTTPS
* Cookie Banner
* Data Processing Agreements
* Moderation / Report System
* Contact Email for Legal Requests

---

# 10. Zalecenia techniczne

## Backend

Zalecane:

* Firebase
* Supabase
* AWS
* Cloudflare

## Autoryzacja

* OAuth2
* JWT
* MFA

## Monitoring bezpieczeństwa

* Sentry
* Cloudflare WAF
* Rate Limiting
* Audit Logs

---

# 11. Przykładowa klauzula prywatności

„Korzystając z aplikacji użytkownik wyraża zgodę na przetwarzanie danych zgodnie z Polityką Prywatności. Dane są przetwarzane wyłącznie w celu świadczenia usług komunikacyjnych i zabezpieczenia platformy.”

---

# 12. Przykładowa klauzula regulaminu

„Zabrania się wykorzystywania aplikacji do działań nielegalnych, nękania, publikacji treści zabronionych lub naruszających prawa osób trzecich.”

---

# 13. Oświadczenie firmy Veix iNC TEch

## Zgodność z przepisami

Firma Veix iNC TEch oświadcza, że dokłada wszelkich starań w celu zapewnienia zgodności aplikacji i infrastruktury z obowiązującymi przepisami prawa w:

* Unii Europejskiej,
* Wielkiej Brytanii,
* Stanach Zjednoczonych.

Firma stosuje standardy bezpieczeństwa, procedury ochrony danych oraz mechanizmy zabezpieczające zgodne z aktualnymi praktykami branżowymi.

## Ograniczenie odpowiedzialności

Veix iNC TEch nie ponosi odpowiedzialności za:

* działania użytkowników naruszające prawo,
* utratę danych wynikającą z zaniedbań użytkownika,
* używanie słabych haseł lub udostępnianie danych logowania osobom trzecim,
* ataki phishingowe wynikające z działań użytkownika,
* skutki instalacji nieautoryzowanych modyfikacji aplikacji,
* działania cyberprzestępcze osób trzecich,
* czasowe niedostępności usług wynikające z ataków DDoS, awarii operatorów lub siły wyższej.

Firma wdraża rozsądne środki ochrony infrastruktury, jednak nie gwarantuje całkowitej odporności na:

* ataki hakerskie,
* exploit zero-day,
* DDoS,
* awarie globalnych dostawców usług,
* działania poza kontrolą firmy.

## Odpowiedzialność użytkownika

Każdy użytkownik zobowiązuje się do:

* korzystania z aplikacji zgodnie z prawem,
* nieudostępniania danych logowania,
* zabezpieczenia własnego urządzenia,
* aktualizowania aplikacji,
* niepodejmowania prób naruszania bezpieczeństwa platformy.

W przypadku wykrycia naruszeń bezpieczeństwa konto użytkownika może zostać:

* tymczasowo zablokowane,
* ograniczone,
* trwale usunięte.

## Zastrzeżenie bezpieczeństwa

Firma Veix INC dokłada by system bezpieczeństwa aplikacji był jak najbardziej zabezpieczony, dzięki Zabezpieczeniom Zounitie 

# 14. Zalecenia końcowe

Przed premierą aplikacji:

* wykonaj audyt bezpieczeństwa,
* przygotuj politykę prywatności,
* wdroż moderację treści,
* przygotuj system zgłaszania naruszeń,
* zapewnij możliwość usunięcia konta i danych,
* sprawdź zgodność z GDPR/CCPA/UK GDPR.

Dla większych aplikacji zalecane:

* powołanie DPO,
* penetration tests,
* SOC2,
* ISO 27001.
