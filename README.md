# Android-TP2.2 travail à faire
Question 1 :
QSi vous exécutez l'application de travail à faire avant d'implémenter onSaveInstanceState(), que se passe-t-il si vous faites pivoter le périphérique? Choisissez-en un:

R : Le compteur est réinitialisé à 0, mais le contenu de l'EditText est préservé

Question 2 : 
Q:Quelles méthodes de cycle de vie d'activité sont appelées lorsqu'un changement de configuration de périphérique (tel qu'une rotation) se produit? Choisissez-en un:

R:Android appelle immédiatement onResume().

Question 3 : 
Q:Lorsque dans le cycle de vie de l'activité, onSaveInstanceState() est appelé? Choisissez-en un:

R:OnSaveInstanceState() est appelée avant la méthode onResume().

Question 4:
Q:Quelles méthodes de cycle de vie d'Activité sont les meilleures à utiliser pour enregistrer des données avant la fin ou la destruction de l'activité? Choisissez-en un:

R:onResume() ou onCreate()
