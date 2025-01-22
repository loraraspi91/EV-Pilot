# Smart EV-Pilot
Pilot your EV Wallbox via WiFi (compliant with all wallbox)

Ce module vous permet de pilotez votre wallbox via une interface WEB embarqué mais aussi grace à son API REST et MQTT.

Vous pouvez donc pilotez votre wallbox avec Home Assitant ou un routeur Solaire (comme le Smart PV-Router www.smartelectromation.com)

> Smart EV Pilot: Le module Smart EV-Pilot s'intégre dans votre wallbox ou à ses cotés. 
- Une charge manuelle de votre Vehicule electrique (la puissance est spécifiée en Watt, et non en Ampère)
- Pilotez votre wallbox via votre domotique.
- Via le Smart PV-Router assure le routage de votre surplus solaire en journée 
  
*** Charge programmable (heure de démarrage, durée de charge et puissance)

> En lien avec le Routeur: `
- Il a assure une fonction de délestage
- Recharge le VE la nuit après que le ballon soit plein
- Routage solaire sur la voiture en journée.
- Puissance mininale de charge en cas d'absence de soleil
- Durée minimale pour éviter les relances intempestives de charges.

> Mode Transparent
- desactivée la prise de controle de votre wallbox par le module (le module n'agit plus sur la wallbox)
- Mode par défaut en cas de coupure de WiFi (sécurité)


