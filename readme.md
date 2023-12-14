# Site de streaming
--
# Requête permettant de générer la bdd
<ul>
<li>

# Générer les tables: 

CREATE TABLE actors (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    firstName VARCHAR (50),
    name VARCHAR (50),
    birthDate DATE,
    created_at TEXT DEFAULT (strftime('%d-%m-%Y')),
    updated_at TEXT DEFAULT (strftime('%H:%M:%S'))
);

CREATE TABLE director (
    firstName VARCHAR (20),
    name VARCHAR (20),
    created_at DATETIME,
    updated_at DATETIME,
);

--

# Ajouter un acteur :

INSERT INTO actors (
    firstName,
    name,
    age
) VALUES (
    'Ryan',
    'Gosling',
    '43'
);

--

# Modifier un acteur :

UPDATE actors SET name = 'Test'
WHERE firstName = 'James';

--

# Supprimer un acteur :

DELETE FROM actors
WHERE ID = Numéro de l'ID

--

# Afficher les 3 derniers acteurs ajoutés :

SELECT * FROM actors
ORDER BY id DESC LIMIT 3

--

# Afficher les noms, prénoms et âges des cateurs/actrices de plus de 30 ans dans l'ordre aphabétiques (prénom d'abord, puis nom) :

SELECT firstName, name, age
FROM actors
WHERE age > 30
ORDER BY firstName ASC, name ASC

--

#
</li>
</ul>