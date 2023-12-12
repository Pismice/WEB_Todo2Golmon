# App Todo avec VueJS
## Description
App sous forme de Kanban (comme Trello).

Le but de cette app étant de pouvoir se lancer des sessions de travail (dans notre cas avec le principe de pomodoro).

En + de ça l utilisateur pourra se rendre compte du temps passé sur chaque tâche et sur chaque catégorie -> l utilisateur aura accès à des graphes permettant de voir ou il a passé son temps, quand, comment, ...

https://www.google.com/search?q=pomodoro+timer&tbm=isch&ved=2ahUKEwivx-CJkYqDAxUk5wIHHRUMAsIQ2-cCegQIABAA&oq=pomodoro+timer&gs_lcp=CgNpbWcQAzIECCMQJzIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDoKCAAQgAQQigUQQ1C9AViaBGCBBWgAcAB4AYABnAGIAbEEkgEDNi4xmAEAoAEBqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=dXF4Ze-4AqTOi-gPlZiIkAw&bih=979&biw=1920#imgrc=JanGGna31RhBHM

Utilisation de pb simple (pocketbase ou supabase)

## Différentes entités
- Catégories (chaque tâche peut avoir 1 ou plusieurs catégories, les catégories peuvent avoir des catégories, ex: HEIG, TB, WEB, ...)
- Tâches (unité de base de notre app, elles ont notamment un nom et une variable stockant le nombre de temps passée sur cette dernière, ainsi que facultativement le temps requis pour "terminer" cette tâche)
- Utilisateurs

