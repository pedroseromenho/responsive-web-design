# Responsive Web Design

## La problématique

**Multiplicité des écrans**  
Aujourd'hui, un même contenu peut être vu sur une télévision HD, un laptop, une montre, un smartphone. Alors que faire ? Un développement par plateforme ? Faut-il faire X versions d'un même site, X étant le nombre total d'écrans de taille différente ?

La problématique est réellement advenue avec les premiers iphone en 2007 et puis s'est amplifiée exponentiellement.  Il a fallu du temps à l'industrie pour s'adapter et trouver la "bonne" approche. En 2010, le web designer [Ethan Marcotte](https://twitter.com/beep) introduit l'expression "Responsive Web Design" (ou RWA) dans cet article sur [A List Apart](http://alistapart.com/article/responsive-web-design).  

## La solution : CSS Media Queries
Via les Media Queries, on va pouvoir dire au navigateur : si ta taille est X, utilise ces propriétés CSS ci, sinon celles là.
Le RWD a entrainé une nouvelle manière d'envisager un site, différenciant de plus en plus entre la substance (le contenu) et l'apparence (le contenant : le device).