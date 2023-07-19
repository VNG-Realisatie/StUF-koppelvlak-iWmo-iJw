---
layout: page-with-side-nav
title: Documentatie StUF-koppelvlak iWmo-iJw
folder_files:
  - title: Foutcodes asynchroon berichtenverkeer ISD-keten 2.1 patch 04 revisie 3
    path: documenten/Foutcodes_asynchroon_berichtenverkeer_ISD-keten_2.1_patch_04_revisie_3.pdf
    group: 21
    versie: 2.1.04 versie 3
    status: 
    omschrijving: 
  - title: Schema, wsdl en voorbeeldberichten StUF-GGk 2.1 patch 04 versie 3
    path: documenten/Ggk0210_patch_04-versie3.zip
    group: 21
    versie: 2.1.04 versie 3
    status: 
    omschrijving: 
  - title: Specificaties GGk0210-v2.1.04 - versie 4.pdf
    path: documenten/Specificaties_GGk0210-v2.1.04_-_versie_4.pdf
    group: 21
    versie: 2.1.04 versie 4
    status: Definitief
    omschrijving: 
---

# Documentatie

## StUF-GGk berichtenvelop
<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 21 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
