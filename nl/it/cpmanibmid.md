---

copyright:

  years: 1994, 2018

lastupdated: "2018-01-10"

---

{:shortdesc: .shortdesc}
{:screen: .screen}
{:tip: .tip}
{:codeblock: .codeblock}
{:pre: .pre}
{:new_window: target="_blank"}

# Utilizzo di account ID IBM con l'infrastruttura {{site.data.keyword.BluSoftlayer_notm}}
{: #customerportal_ibmid}

L'autenticazione nell'infrastruttura {{site.data.keyword.BluSoftlayer_notm}} adesso utilizza l'ID IBM per fornire un singolo accesso in {{site.data.keyword.Bluemix_notm}}.
{:shortdesc}

Se disponi di un account SoftLayer esistente, puoi passare a un ID IBM. Una procedura guidata di migrazione può aiutarti in questo passaggio. Per ulteriori informazioni, vedi [Passaggio all'ID IBM](/docs/account/softlayerlink.html#switching-to-ibmid).

## Associazione di più account SoftLayer a un ID IBM
{: #cp_mapmultclinfrto1ibmid}

Puoi associare un ID IBM a più account SoftLayer utilizzando un indirizzo e-mail ID IBM esistente quando configuri l'account. Al singolo ID IBM è possibile associare un solo utente dell'infrastruttura {{site.data.keyword.BluSoftlayer_notm}} per ogni account. L'ID IBM deve essere univoco all'interno di ogni account SoftLayer. Tuttavia, un utente con accesso a più account SoftLayer può utilizzare un ID IBM per accedere agli account.

Un ID IBM può essere associato all'utente master negli account A e B, ad esempio, e a un altro utente negli account C e D. Uno degli account associati a tale ID IBM è l'account predefinito. Di solito, l'account predefinito è quello che è stato associato per primo all'ID IBM. Tuttavia, puoi scegliere l'account predefinito utilizzando una funzione del portale clienti per cambiare l'account.

![Associazione di account SoftLayer a un singolo ID IBM](images/ibmid-image.png)

Per un utente con un accesso ID IBM a più account con l'autenticazione a due fattori (2FA) abilitata, è richiesto un codice di verifica 2FA. Il codice di verifica viene richiesto, per ogni account, durante l'accesso all'account e quando cambi l'account predefinito.
