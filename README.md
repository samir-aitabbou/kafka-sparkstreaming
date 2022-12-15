# kafka-sparkstreaming
<p> Traitement temps réel des données, afin d'alimenter un modéle entrainé pour prédire les diabétiques ,avec Spark stream </p>
<p> c'est un cluster d'un master et 2 slaves (Spark) , avec Kafka (Producer et Cansumer) implémenté  dans le master et ce dernier se charge de distrubier les taches sur les 2 Slaves  </p>

Analyse à faire
1. Lancer puis lire en temps réel les données du fichier diabète.txt
2. Faire des calcul statistiques en temps réel sur les données Ex : (Calcul de moyenne
Age, moyenne masse .. , écart type)
3. En utilisant des modèles machine Learning, et après avoir faire un entrainement sur
80% de données (traning) , prédire en temps réel si le patient est atteint ou non de
diabète sur les 20% de données (test)

Outils
• Apache Kafka Stream
• Langage : Java …
• Editeurs : IntelliJ IDEA ou Eclipse …
• Systèmes : Unix, MacOS ou Windows …
• Plateformes : Cloudera ou HDP … 
<h1> DOCKER IMAGE :       aitabbou/kafka-sparkstreaming:kafka_spark_cluster   </h1>
