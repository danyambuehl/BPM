BPMN 2.0
=========

# Pools and Lanes 

**Um so die verschiedenen Prozessteilnehmer abzubilden, werden Pools und Lanes genutzt**

**Pools**

![Pool](images/bpmn-pool.svg)  Pools repräsentieren einen der Lanes übergeordneten Prozessteilnehmer

**Lanes**

![Pool](images/bpmn-lane.svg)  Lanes können Organisationseinheiten oder Rollen sein. Sie werden in Pools gruppiert.

# Ereignisse

**Ereignisse werden genutzt um den Start, das Ende oder den Ablauf eines Prozesses zu kennzeichnen.**

> Eingetretene Ereignisse sind Zustände, die durch einen externen Auslöser erzeugt werden

> Ausgelöste Ereignisse sind Zustände, die vom Prozess selbst erzeugt wurden

**Regel:** Es müssen immer alle aktiven Pfade je Prozessebene bendet werden.

**Start Ereignisse**

![Start Ereignisse](images/bpmn-start-event.svg) Das Startereignis löst den Sequenzfluss eines Prozesses aus.

**Zwischenergenis Ereignisse**

![Zwischenergenis Ereignisse](images/bpmn-intermediate-event.svg) Ein Zwischenereignis unterbricht den Sequenzfluss temporär.

**End Ereignisse**

![End Ereignisse](images/bpmn-end-event.svg) Endereignisse beenden den Sequenzfluss.

**Ereignis-definition**

![Ereignis-definition](images/erreignissdefinition.png)Es kann jedes Erreignis mit einem Symbol / definition ergänzt werden. 

# Gateway 

**Gateway's werden benötigt um Aufspaltungen und Zusammenführungen eines Sequensfluss darzustellen.**

**exklusive Gateways**

![exklusive Gateways](images/bpmn-2-exclusive-gateway.svg) wenn genau eine Bedingung eintreffen darf **(„entweder/oder“)**

**Zusammenführung:** muss genau **ein** eingehender Prozesspfad erfüllt sein.

--------

**Paralleles Gateway**

![Paralleles Gateway](images/bpmn-2-parallel-gateway.svg) Es müssen alle ausgehenden Prozesspfade verfolgt werden **(„und“)**

**Zusammenführung:** alle eingehenden Pfade erfüllt sind, darf der Prozessfluss fortgesetzt werden.

---------

**Inklusives Gateway**

![Inklusives Gateway](images/bpmn-2-inclusive-gateway.svg) Wenn einem oder mehreren Prozesspfade gefolgt werden kann **(„und/oder“)**

**Zusammenführung:** muss auf alle zuvor ausgelösten Pfade gewartet werden

-----------

**Ereignis-basiertes Gateway**

![Ereignis-basiertes Gateway](images/bpmn-2-event-based-gateway.svg) Bei ereignis-basierten Gateways wird derjenige Sequenzfluss verflogt, dessen Ereignis zeitlich als **erstes eintritt**.


# Aktivitäten 

**Abbildung von einzelnen Prozessschritten**

***Aktivität***

![Aktivität](images/bpmn-activity.svg) Stellt einen Arbeitsschritt dar und wird aktiv formuliert.

***Teilprozess***

![Aktivität](images/bpmn-subprocess.svg) Stellt eine Prozess mit mehreren unter aktivitäten dar.

***Task-definition***

![Task-definition](images/Taskdefinition2.png) Aktivitäten können mit einem Symbol / definition ergänzt werden.

# Sequenzfluss 
Fluss Lienien / Lienien zwischen erregnissen. 
Reienfolge wird definiert



*** Link-Ereignis***

Weiterleitung 

> Symbole = dicker Pfeil
