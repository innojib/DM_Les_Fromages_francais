# DM_Les_Fromages_francais


##1.Quels sont les départements qui produisent du fromage avec du lait de chèvre?
**
###a.Diagramme en barre
    <iframe style="width: 80vw; height: 50vh; border: none;" src="https://public.opendatasoft.com/explore/embed/dataset/fromagescsv-fromagescsv/analyze/?disjunctive.fromage&sort=departement&refine.lait=Ch%C3%A8vre&location=6,46.90525,5.92163&basemap=jawg.light&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImZyb21hZ2VzY3N2LWZyb21hZ2VzY3N2Iiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5mcm9tYWdlIjp0cnVlLCJzb3J0IjoiZGVwYXJ0ZW1lbnQiLCJyZWZpbmUubGFpdCI6IkNoXHUwMEU4dnJlIiwibG9jYXRpb24iOiI2LDQ2LjkwNTI1LDUuOTIxNjMiLCJiYXNlbWFwIjoiamF3Zy5saWdodCJ9fSwiY2hhcnRzIjpbeyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoiYmFyIiwiZnVuYyI6IkNPVU5UIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoiIzFCNjY5OCIsInBvc2l0aW9uIjoiY2VudGVyIn1dLCJ4QXhpcyI6ImRlcGFydGVtZW50IiwibWF4cG9pbnRzIjoxMDAsInNvcnQiOiJzZXJpZTEtMSIsInNlcmllc0JyZWFrZG93biI6IiIsInNlcmllc0JyZWFrZG93blRpbWVzY2FsZSI6IiJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D&static=false&datasetcard=false" width="600" height="450" frameborder="0"></iframe>
 > Source : [opendatasoft](https://public.opendatasoft.com/explore/)

 ###b.Carte de la production de fromage de chèvre
<iframe style="width: 80vw; height: 50vh; border: none;" src="[https://query.wikidata.org/embed.html#%23Vue%20a%C3%A9rienne%20du%20Monde%0A%23The%20Blue%20Marble%3A%20Land%20Surface%2C%20Ocean%20Color%20and%20Sea%20Ice%20%7C%20La%20bille%20bleue%20%3A%20surface%20terrestre%2C%20couleur%20de%20l'oc%C3%A9an%20et%20glaces%20maritimes%0A%23defaultView%3AImageGrid%0ASELECT%20%3Focean%20%3FoceanLabel%20%3FvueAerienne%0AWHERE%20%7B%0A%20%20%3Focean%20wdt%3AP31%20wd%3AQ9430.%20%23oc%C3%A9ans%0A%20%20%3Focean%20wdt%3AP8592%20%3FvueAerienne.%0A%20%20SERVICE%20wikibase%3Alabel%20%7Bbd%3AserviceParam%20wikibase%3Alanguage%20%22fr%22%20%7D%0A%7D%0A%0A](https://public.opendatasoft.com/map/+bfffc05397054f34/edit/)" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups"></iframe>
 > Source : [opendatasoft](https://public.opendatasoft.com/explore/)
    



Carte de la production de fromage de chèvre
    <ods-dataset-context context="fromagescsvfromagescsv" fromagescsvfromagescsv-dataset="fromagescsv-fromagescsv" fromagescsvfromagescsv-parameters="{'disjunctive.fromage':true,'sort':'departement','refine.lait':'Chèvre'}">
        <ods-map no-refit="true" scroll-wheel-zoom="false" basemap="jawg.light" location="7,46.96526,-1.79077">
            <ods-map-layer-group>
                <ods-map-layer context="fromagescsvfromagescsv" color="#0A72B5" picto="ods-circle" show-marker="true" display="clusters" function="COUNT" shape-opacity="0.7" point-opacity="1" border-color="#F9E5C5" border-opacity="0" border-size="0" border-pattern="solid" caption="true" caption-picto-icon="ods-cheese" caption-picto-color="#0A71B5" show-zoom-min="1" show-zoom-max="22" size-min="1" size-max="5" size-function="log"></ods-map-layer>
            </ods-map-layer-group>
        </ods-map>
    
    </ods-dataset-context>


#Quel est le fromage le plus produit ?

Treemap de la production de fromage en France
<iframe src="https://public.opendatasoft.com/explore/embed/dataset/fromagescsv-fromagescsv/analyze/?disjunctive.fromage&sort=departement&location=6,46.90525,5.92163&basemap=jawg.olght&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImZyb21hZ2VzY3N2LWZyb21hZ2VzY3N2Iiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5mcm9tYWdoljp0cnVlLCJzb3J0IjoiZGVwYXJ0ZW1lbnQifX0sImNoYXJ0cyI6W3siYWxpZ25Nb250aCI6dHJ1ZSwidHlwZSI6InRyZWVtYXAiLCJmdW5jIjoiQ09VTlQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20iLCJwb3NpdGlvbiI6ImNlbnRlciJ9XSwieEF4aXMiOiJmcm9tYWdoliwibWF4cG9pbnRzIjo1MCwic29ydCI6InNlcmllMS0xIiwic2VyaWVzQnJlYWtkb3duIjoiIiwic2VyaWVzQnJlYWtkb3duVGltZXNjYWxoljoiIn1dLCJ0aW1lc2NhbGUiOiIiLCJkaXNwbGF5TGVnZW5kIjp0cnVlLCJhbGlnbk1vbnRoIjp0cnVlfQ%3D%3D&static=false&datasetcard=false" width="600" height="450" frameborder="0"></iframe>

Le lait d'animal le plus utilisé en france pour la production de fromage
<iframe src="https://public.opendatasoft.com/explore/embed/dataset/fromagescsv-fromagescsv/analyze/?disjunctive.fromage&sort=departement&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImZyb21hZ2VzY3N2LWZyb21hZ2VzY3N2Iiwib3B0aW9ucyI6eyJkaXNqdW5jdGl2ZS5mcm9tYWdlIjp0cnVlLCJzb3J0IjoiZGVwYXJ0ZW1lbnQiLCJsb2NhdGlvbiI6IjYsNDYuOTA1MjUsNS45MjE2MyIsImJhc2VtYXAiOiJqYXdnLmxpZ2h0In19LCJjaGFydHMiOlt7ImFsaWduTW9udGgiOnRydWUsInR5cGUiOiJ0cmVlbWFwIiwiZnVuYyI6IkNPVU5UIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoicmFuZ2UtY3VzdG9tIiwicG9zaXRpb24iOiJjZW50ZXIifV0sInhBeGlzIjoiZnJvbWFnZSIsIm1heHBvaW50cyI6MTAwLCJzb3J0Ijoic2VyaWUxLTEiLCJzZXJpZXNCcmVha2Rvd24iOiIiLCJzZXJpZXNCcmVha2Rvd25UaW1lc2NhbGUiOiIifV0sInRpbWVzY2FsZSI6IiIsImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9&location=6,46.90525,5.92163&basemap=jawg.light&static=false&datasetcard=false" width="800" height="600" frameborder="0"></iframe>
Les Cents fromages les plus produits en France

