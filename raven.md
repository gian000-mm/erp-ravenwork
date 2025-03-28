# RAVEN :
Raven è un app openSource utilizzabile con Frappe

>Version "Main"

# Openai settings

>1. Rechiamoci in **AI > Openai Settings**
![Openai Settings](/gian000-mm/erpraven/openaiSettings.png)

>2.Inserire l **API KEY e ORG-ID** presenti su https://platform.openai.com aziendale o di tua proprietà

# Creazione dei Workspace
![Dashboard di Raven](/gian000-mm/erpraven/ravenDashboard.png)


>1.Nel menù a sinistra premi su **"+"**
>2.Crea un **Workspace** per ogni azienda
>3.Inserisci **Nome**, **Descrizione** ,se disponibile un logo .In fine scegliere un **Workspace Type**

Ho creato 3 Workspace per 3 aziende presenti su **ERPNEXT**

>**ATTENZIONE : Settare il Workspace Type su Private**



Possiamo modificare il tutto appena creato premendo sull **ingranaggio in basso a sinistra**, successivamente **sezione Workspace>Workspaces**

# Creazione di un Channel
>1.Selezionare il Workspace in cui si vuole operare
>2.Nella **Sezione Channel sulla sinistra** premere su **"+"** per creare una nuova chat

![Creazione Channel](/gian000-mm/erpraven/CreateChannel.png)
>3.Inserire **Nome, Descrizione e Channel Type**

>**ATTENZIONE : Settare il Channel Type su Private**

In questo modo avremo un channel privato per le 3 aziende 

# Creazione di un AI agent
>1. Premere su **Settings** in basso a sinistra(logo con ingranaggio)

>2. Nel **Settings** segui **AI > Agents** e premiamo sul button **"Create"**

**ATTENZIONE :** 
>prima di procedere segui la sezione denominata **Openai Settings**

**ATTENZIONE :**
>Prima di creare un **Agent** passa dalla sezione chiamata **Function**

>3. Nella dashboard marcare **"Is Ai Agent"**
![createAgent.general](/gian000-mm/erpraven/createAgent.png)

>4. Impostare un **Nome**, e una **descrizione** del medesimo. Nel mio caso caso un bot creato per il testing delle funzionalità offerte dalla piattaforma

>5. Le sezioni di nostro interesse sono : **"Instructions"** e **"Function"**


# Function

> **Settings> AI > Function**
> Dashboard con la lista delle **function**
![functionDashboard](/gian000-mm/erpraven/CreateFunction1.0.png)

>1. **get_Employee** :
per prendere i dati dei dipendeti disponibili su ErpNext
>2. **get_company** : 
per prendere i dati delle varie aziende disponibili su ErpNext

> Premere sul button **"Create"** per creare una nuova function 

**Osserva la dashboard:** :
![createFunction1.1](/gian000-mm/erpraven/CreateFunction1.1.png)

>1. Seleziona il **Type**, nelle funzioni da me create è **"Get Document"**
>2. Nella sezione **Reference Type** possiamo selezioanre tutti i doctype presenti su ERPNEXT

**ATTENZIONE: vedere la sezione inerente ad ERPNEXT**
>3. Inserire il **Nome** e la **Descrizione**


# ERPNEXT :

# Company

![Home ERP](/gian000-mm/erpraven/dashboardErpCompantList.png)

>1. Cerca il doctype **"Company List"**

>**ATTENZIONE**
In questa sezione viene utilizzato un Doctype chiamato **User Group**, leggere la sezione Apposita

![CompanyList](/gian000-mm/erpraven/companyList.png)
>2. Vedremo l'elenco delle Company Create
>3. Premi il button **"Add Company"** per crearne una

>4.Premiamo **"Edilizia_giovannisrl"**

![Edilizia_giovannisrl](/gian000-mm/erpraven/Edilizia_giovannisrl.png)

>In queasta dashboard possiamo leggere tutti i dati da me inseriti precedentemente 

>Sul menù a sinistra possiamo notare **"Assigned To :"**
![AssignedTo](/gian000-mm/erpraven/AssignedTo.png)
>Qui possiamo assegnare a questa determinata **Company** un **User Group** 

# User Group

>Un user group viene inteso come un gruppo di lavoro(almeno questa è la mia definizione corretta/errata)


>Dalla **Home** di ERPNEXT , ricercare il Doctype **User Group List**
![HomeErp](/gian000-mm/erpraven/homeUsergroupList.png)

Nella dashboard seguente troviamo gli **User Group** creati precedentemente 
![dashboardUsergroup](/gian000-mm/erpraven/usergroupHome.png)


>Apriamo un **User Group** a caso , andrà bene il primo
![mittalGroup](/gian000-mm/erpraven/mittaluserGroup.png)
possiamo vedere gli **User** assegnati a questo **User Group**

>**ATTENZIONE**
**USER** è un doctype, le mail che puoi leggere provengono dal Doctype **USER**

>Per Associare gli **USER** potremmo percorrere due strade:
>1.Torniamo alla Home e cerchiamo il Doctype **User List** e creamo degli **User** da inserire in questo Doctype
>2.Possiamo continuare su questa Dashboard e creare gli **USER** da qui : 

>Sul menù a sinistra su **"Assigned To"** , puoi vedere la lista degli **USER** contenuti in quel specifico Doctype. Possiamo selezionare quelli gia contenuti in quel Doctype o Crearne uno da qui
![AssignedToUser](/gian000-mm/erpraven/assignedToUser.png)
>Quindi premere su **Create New User** e crearne uno
Premi su **Edit Full Form** e verrai ricondotto nel doctype **USER** per inserire tutti i dati 



