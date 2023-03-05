# Project : 
Hello world! 🌎🌍🌏 <br>
Here is a project carried out as part of a course where we were able to discover Strapi and Nuxt.<br>
This project is presented in the form of a Portfolio.

<hr>

## Project installation and run the project:
### Strapi installation:
<code>cd headless-strapi</code><br>
<code>yarn</code>

### Nuxt installation:
<code>cd headless-nuxt</code><br>
<code>yarn</code>

### Configure environment:
Configure the .env in <code>/headless-strapi</code>
### Run strapi:
<code>cd headless-strapi</code><br>
<code>yarn develop</code>
### Run Nuxt:
<code>cd headless-nuxt</code><br>
<code>yarn dev</code>

<hr>

## Database schema:
### Project Table:
<table>
  <tr>
    <th>Name</th>
    <th>Type</th>
  </tr>
  <tr>
    <td>text</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>image</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>slug</td>
    <td>UID</td>
  </tr>
  <tr>
    <td>description</td>
    <td>Rich text</td>
  </tr>
  <tr>
    <td>link</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>types</td>
    <td>Enumeration</td>
  </tr>
  <tr>
    <td>technos</td>
    <td>Relation with Techno</td>
  </tr>
</table>


### Techno Table:
<table>
  <tr>
    <th>Name</th>
    <th>Type</th>
  </tr>
  <tr>
    <td>technos</td>
    <td>Enumeration</td>
  </tr>
  <tr>
    <td>projects</td>
    <td>Relation with Project</td>
  </tr>
  <tr>
    <td>logo</td>
    <td>Media</td>
  </tr>
</table>

<hr>

## Features :
### Objectifs
- Portoflio
- Différents types de projet : École IIM, Professionel & Personnel 
- Les projets sont triés par leur type
- Une page par projet
### Objectifs pour aller plus loin
- Typescript est utilisé
- Système de filtre selon les languages des projets
- Boutons pour aller au projet précédent ou suivant 
- Bouton "back to home"

<hr>

## Technologies :
- NuxtJs 3
- Strapi

<hr>

## Other:
And our the teacher for this week: LOZACH Antoine
