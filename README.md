# CyberAppCert

CyberAppCert est une application Python conçue pour analyser et vérifier des certificats numériques.
Elle permet aux utilisateurs de vérifier rapidement l’authenticité, la validité et l’émetteur des certificats, et de générer des rapports détaillés.

L’application peut être exécutée directement en Python ou comme un exécutable Windows pour un usage simple et rapide.

Fonctionnalités
✅ Vérification automatique des certificats numériques (.pem, .crt, .cer)
✅ Analyse rapide et fiable des informations des certificats
✅ Génération de rapports clairs et structurés
✅ Interface simple et intuitive
✅ Compatible Windows et Linux (script Python)
Installation
Prérequis
Python 3.10 ou supérieur
Modules Python nécessaires (installer via pip) :
pip install -r requirements.txt
Télécharger et exécuter
Clonez le dépôt ou téléchargez les fichiers.
Pour exécuter le script Python :
python cyberappcert.py
Pour exécuter le fichier Windows (.exe) :
Double-cliquez sur dist\cyberappcert.exe
Suivez les instructions à l’écran
Génération de l’exécutable Windows

Pour créer un .exe avec PyInstaller :

python -m pip install pyinstaller
python -m PyInstaller --onefile cyberappcert.py
L’exécutable sera dans le dossier dist\cyberappcert.exe.
Utilisation
Lancez l’application (script ou .exe).
Saisissez le chemin du certificat à analyser.
L’application analysera le certificat et affichera les résultats.
Les résultats peuvent être enregistrés dans un fichier pour consultation ultérieure.
Exemple de sortie
Bienvenue dans CyberAppCert !
Veuillez entrer le chemin du certificat à analyser : C:\Users\Exemple\cert.pem
Analyse en cours...
✔ Certificat valide
✔ Expiration : 2026-12-31
✔ Émetteur : DigiCert
Rapport généré : C:\Users\Exemple\rapport_certificat.txt
Capture d’écran

<img width="1507" height="931" alt="image" src="https://github.com/user-attachments/assets/9a573005-c0bc-4a8e-a472-180aaae1c672" />


###FAQ

Q : Puis-je utiliser CyberAppCert sur Linux ?
R : Oui, le script Python fonctionne sur Linux, mais l’exécutable .exe est uniquement pour Windows.

Q : Quels types de certificats sont supportés ?
R : .pem, .crt, et .cer.

Q : Comment générer un exécutable Windows ?
R : Avec PyInstaller comme indiqué ci-dessus.

Contribution

Les contributions sont les bienvenues :

Fork le projet
Créez une branche (git checkout -b feature/ma-nouvelle-fonction)
Commit vos changements (git commit -am 'Ajout d’une nouvelle fonction')
Push sur la branche (git push origin feature/ma-nouvelle-fonction)
Ouvrir une Pull Request
Licence

MIT – voir le fichier LICENSE pour plus de détails.
