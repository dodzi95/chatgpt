# chatgpt

Generative Pre-trained Transformer 3 (GPT-3) est un nouveau modèle de langage créé par OpenAI, société spécialisée dans l’IA. GPT-3 est capable de générer du texte écrit d'une qualité telle qu'il est souvent difficile de le distinguer d'un texte écrit par un humain. ChatGPT est un variant du modèle GPT-3 conçu spécialement comme  un outil conversationnel (Chatbot).

Le playground d’OpenAI, une interface en ligne qui, comme son nom l'indique, vous permet d'explorer et de créer des prototypes de solutions basées sur GPT-3. OpenAI a mis à disposition un API HTTP et un package Python permettant d'interagir avec GPT-3, rendant ainsi la tâche de migration d'une application depuis l'interface Playground facile. Vous pouvez adapter l'exemple Python à d'autres langages, mais il se peut qu'aucune bibliothèque OpenAI ne soit disponible. Ce n'est pas un problème, car l'API OpenAI est une API HTTP relativement standard à laquelle vous pouvez accéder par le biais de requêtes HTTP brutes.


# Tutoriel

Dans cet article, nous découvrirons comment travailler avec GPT-3 sur une variété de cas d'usage, de son utilisation comme assistant d'écriture à la construction d'un chatbot très sophistiqué. À la fin de cette lecture, vous saurez comment programmer GPT-3 de sorte qu'il puisse discuter avec vous de vos sujets préférés. Voici un exemple d'une courte conversation que j'ai eue avec le bot sur Python et le développement web.
Conversion d'un nombre en lettre à l'aide de l'API fourni par OpenAI

Conditions préalables
Pour suivre les exemples présentés dans ce tutoriel, la seule chose dont vous avez besoin, c'est une licence OpenAI GPT-3.

Vous pouvez voir dans la capture d'écran que l'entraînement ne correspond qu'aux deux premières lignes, dans lesquelles j'ai saisi des salutations fictives entre un humain et l'IA.


En utilisant l'extrait de code Python ci-dessus comme base, j'ai créé une fonction gpt3() qui imite le comportement de Playground. Copiez le code ci-dessous dans un fichier nommé gpt3.py.

Sur la base de la fonction gpt3() de la section précédente, nous pouvons maintenant créer une application de chat.
La discussion se termine lorsque l'utilisateur appuie sur Ctrl-C pour arrêter le script

# Conclusion
Que le voyage fut long ! J'espère que vous comprenez désormais comment fonctionne l'API OpenAI et comment travailler avec GPT-3.

Voulez-vous apprendre à utiliser GPT-3 avec Twilio et Python ? J'ai écrit un de création d'un chatbot SMS GPT-3, et mon collègue Sam Agnew a également réalisé un tutoriel de fan fiction Dragon Ball GPT-3 très amusant.

J'adorerais voir les super applications que vous construisez avec GPT-3 !
