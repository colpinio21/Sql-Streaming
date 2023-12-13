# Site de streaming
--
# Requête permettant de générer la bdd
<ul>
<li>
Générer les tables: 

CREATE TABLE actors (
    firstName VARCHAR (20),
    name VARCHAR (20),
    birthDate DATE,
    created_at DATETIME,
    updated_at DATETIME,
),

CREATE TABLE director (
    firstName VARCHAR (20),
    name VARCHAR (20),
    created_at DATETIME,
    updated_at DATETIME,
),

--

Ajouter un acteur :

INSERT INTO actors (
    firstName,
    name,
    created_at_,
    birthDate
) VALUES (
    'Jean',
    'Dujardin',
    1702483090,
    '1972-06-19'
)

--


</li>
</ul>