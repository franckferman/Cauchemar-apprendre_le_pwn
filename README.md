---
description: >-
  Apprendre le Pwn : guide libre et complet, sous GNU AGPLv3.0, pour débuter et
  maîtriser les fondamentaux de l'exploitation de binaires.
icon: skull-crossbones
---

# Cauchemar — Apprendre le Pwn

<figure><img src=".gitbook/assets/Banner-Cauchemar-Apprendre_le_Pwn.png" alt="Bannière futuriste pour le cours &#x22;Apprendre le Pwn — Les fondamentaux de l&#x27;exploitation de binaires&#x22;, avec un grand logo en arrière-plan sur un fond hexagonal violet et des éléments graphiques géométriques."><figcaption><p>Apprendre le Pwn : Découvrez les fondamentaux de l'exploitation de binaires.</p></figcaption></figure>

***

### \[**TLP**:**CLAIR**] (_DIFFUSION PUBLIQUE_)

Le présent document est la propriété exclusive de M. **Franck FERMAN** et est classé **TLP**:**CLAIR**, autorisant ainsi une diffusion étendue et publique, sous réserve du respect des règles de droit d'auteur standard.

Les informations contenues dans ce document sont déclarées non sensibles et peuvent être librement partagées ou diffusées publiquement sans nécessité de mesures de protection spécifiques.

***

### \[**GNU Affero General Public License v3.0**] (**GNU AGPLv3.0**)

Le présent document, un projet de documentation et d'apprentissage du Pwn (_de l'exploitation de binaires_), est distribué sous la licence **GNU Affero General Public License v3.0** (**GNU AGPLv3.0**).

Conformément aux termes de cette licence, vous êtes autorisé à utiliser, étudier, modifier et distribuer cette documentation ainsi que les exercices qu'elle contient. Si vous apportez des modifications à ce matériel, vous êtes tenu de mettre ces modifications à la disposition des utilisateurs finaux. Ces modifications doivent être partagées dans un format qui autorise une utilisation, une étude, une modification et une distribution similaires à celles permises par cette licence. Cette obligation demeure, que les modifications aient été effectuées pour des raisons personnelles ou dans le cadre d'un service en ligne.

Pour plus d'informations sur la licence GNU Affero General Public License v3.0, vous pouvez consulter le lien suivant : \[GNU AGPLv3.0]\(https://www.gnu.org/licenses/agpl-3.0.html)

***

> _Copyright (C) 2023 Franck FERMAN_
>
> "_**Cauchemar - Apprendre le Pwn**_" is a project initiated by Mr. **Franck FERMAN** with the aim of introducing the fundamentals of binary exploitation. It provides clear explanations and practical examples to help learners master the basics of binary exploitation. _Copyright (C) 2023 Franck FERMAN_
>
> This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
>
> This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.
>
> You should have received a copy of the GNU Affero General Public License along with this program. If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).

***

<figure><img src=".gitbook/assets/Cauchemar-Apprendre_le_Pwn-Logo_Animation-Franck_FERMAN.gif" alt="Logo animé &#x22;Apprendre le Pwn&#x22; réalisé par Franck FERMAN, avec des effets de distorsion et de glitch numérique sur fond noir."><figcaption><p>"Cauchemar - Apprendre le Pwn" — Création originale de Franck FERMAN.</p></figcaption></figure>

***

_Ce document a été créé le 07/12/2023 à Saint-Quentin-en-Yvelines (78180) par M. Franck FERMAN. Il s'agit d'un document évolutif qui peut être sujet à des modifications et révisions ultérieures._

Les commentaires sur le présent document sont à adresser à :

> _<mark style="background-color:red;">M. Franck FERMAN</mark>_ <mark style="background-color:red;"></mark><mark style="background-color:red;">Adresse électronique : contact@franckferman.fr</mark>
