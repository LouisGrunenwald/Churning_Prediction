# Entreprise Telco :

## 1) Introduction:

Le but de ce projet est de déterminer nos potentiels clients Churner. En effet, Telclo est une entreprise de
télécomunication proposant un service téléphonique mais aussi d’autres services tels qu’ un accès a internet,
un service de sauvegarde a disance , une protection des appareils, un support, et autres services… . Le but
est de cibler nos clients futurs churners afin de potentiellment d’entamer des démarches afin de les reconquérir
(offre promotionnelle,…) ou bien encore de déterminer les raisons de leurs départs afin d’établir peut-être
une offre plus adaptée à certains clients. Il n’y a dans nos données pas de dimension temporelle. Nous avons
pour ainsi dire pas de dates, on ne travaillera donc pas avec une dimension temporelle mais on aura à disposition
l’ancienneté du contrat (“tenure”) qui nous sera particulièrement utile dans l’exercice. Par commodité et
pour s’adapter aux contraintes imposées, nous augmenterons nos NA afin de pouvoir les remplacer, de plus
nous avons transformé certaines variables catégorielles binaires en variables numériques.


#### Voici la liste des variables mises à disposition:
### Customer ID : identifiant du client.
### Gender : Sexe du client (M/F).
### SeniorCitizen: Client est-il senior (1) ou non (0) ?
### Partner : Le client a-t ‘il un partenaire (Yes) ou non (No)?
### Dependents: Le client a-t ‘il des personnes à charge ou non ? (Yes, No)
### Tenure : Nombre de mois que le client a passé dans la compagnie
### PhoneService: Le client a-t ’il souscrit à un service téléphonique ? (Yes, No)
### MultipleLines: Le client a-t’il plusieurs ligne ? (Yes, No, No phone service)
### InternetService: A-t’il souscrit à un abonnement internet ? (DSL, Fiber optic, No)
### OnlineSecurity: Le client a-t‘il souscrit au service de sécurité en ligne (Yes, No, No internet service)
### OnlineBackup: Le client a-t‘il souscrit au service de sauvegarde en ligne (Yes, No, No internet service)
### DeviceProtection: Le client a-t‘il souscrit au service de protection de l’appareil(Yes, No, No internet service)
### TechSupport : Le client a-t‘il souscrit au service d’assistance ?(Yes, No, No internet service)
### StreamingTV: Service de TV? (Yes, No, No internet service)
### StreamingMovies: Service de film en streaming ?(Yes, No, No internet service)
### Contract: Durée de vie du contrat (Month-to-month, One year, Two year)
### PaperlessBilling: Facturation en papier (Yes, No)
### PaymentMethod: Le type de paiement choisi (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
### MonthlyCharges: Le montant facturé mensuellement au client
### TotalCharges: Le montant total facturé au client
### Churn: Le client a-t’il quitté l’entreprise ? (Yes or No)

***Sommaire :*** 
## I ) Churner , Churner ! Qui-est-tu ? (Analyse graphique univariée)
## II ) Etude des intéractions de variables
## III ) Analyses non supervisées
## IV ) Analyses Supervisées

## ***Conclusion :***

L’apprentissage supervisé semble plus efficace que le non supervisé. De même nous préfèrerons utiliser
un gradient boosting pour déterminer nos clients Churners. Nous avons pu voir que pour la représentation,
il est plus parlant d’utiliser une classification, cependant la régression (comme dans le gradient
boosting) pourrait nous permettre de mieux cibler nos churners. En effet, un service commercial pourrait
par exemple nous demander de sortir un nombre précis de churners par mois, tout en limitant le nombre
de faux pour ne pas passer d’appel inutile par exemple, dans ce cas la on fera varier notre probabilité
seuil pour obtenir un nombre de churner avec très peu d’erreurs. Dans ce cas la, nous cherchons utilisons
la DataScience comme vecteur de productivité

