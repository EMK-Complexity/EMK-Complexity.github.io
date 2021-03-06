---
layout: page
title: About
permalink: about/
---

The EMK Complexity Group has been working for over 20 years, with organisations in the private and public sectors to address practical complex problems. In the process it has developed a theory of complex social systems and an integrated methodology using both qualitative and quantitative tools and methods.

## Organisations we have worked with

AstraZeneca, BT, BAe Systems, Cabinet Office, Citibank (New York & London), Defra (Dept for Environment, Food & Rural Affairs), DWP (Dept for Work and Pensions), Dutch Ministry of the Interior, ECOWAS (Economic Community of West African States) Commission, European Commission, GlaxoSmithKline, Health & Safety Executive, the Humberside TEC, Legal & General, Ministry of Defence, Mondragon Cooperative Corporation (Basque Country), the National Health Service, Norwich Union Life, Rolls-Royce (Aerospace & Marine), Royal British Legion, Shell (International, Finance & Shell Internet Works), Suffolk County Council, the World Bank (Washington DC) and several companies in the aerospace industry.

## EMK Complexity Group Director

{% assign eve = site.people | where:"title","Professor Eve Mitleton-Kelly" %}
{% assign eve = eve[0] %}
{% include team_member.html member=eve %}
   
## About the EMK Complexity Group

Those working on different aspects of the Research Programme, make up the EMK Complexity Group. The Group includes the researchers involved in the individual projects as well as several associate researchers, a modelling expert, an artist, psychologists, and academics from different disciplines. Professor John Casti (SFI) and Roger Lewin (author of ‘Complexity’) are also associate members of the Group. Associated with the Group is a Network of academics within a variety of disciplines (including: anthropology, biology, economics, information systems, mathematics, physics, psychology, sociology, philosophy) from the following Universities: Cambridge, Durham, Glasgow, Hertfordshire, Lancaster, Lincoln, OU, Sheffield, Warwick. The EMK Complexity Group also has strong links with the Santa Fe Institute, New Mexico, which is the centre for complex adaptive systems research in the natural sciences, and a number of universities and research institutions world-wide.

One of the objectives of the EMK Complexity Programme is to help create a community of interest and a community of researchers in the UK, studying complex social systems at different scales: at the individual, organisational, economic, and societal levels. The series of Study Group meetings, conferences, colloquia, etc. over the past few years have helped create this community and future efforts will ensure that the community is maintained and further developed.

The Research Partners, are therefore indirectly also helping to create and support this community which will develop the new discipline of the study of complex social systems.

More specifically, the EMK Research Programme is attempting to:

1.  Contribute to the development of a theory of complex social systems and organisations.
2.  Explore and develop models, tools and methods to help organisations understand and cope with complexity.
3.  Develop a method of discourse of complexity, within an organisational context.

**​COMPLEXITY PROVIDES AN EXPLANATORY FRAMEWORK AND A LANGUAGE, WHICH OFFER A DIFFERENT WAY OF THINKING AND SEEING THE WORLD.**

The Research Partners take an active role in the research projects and help fund the Research Programme. The current membership fee is £15,000 p.a. (plus 40% overhead) and Research Partners are expected to support the Programme for a minimum of three years, with an annual review. The longer-term relationship ensures that the RP derives maximum benefit from the relationship and the Group is provided with the necessary financial support to continue its work.

## Team members

<div>
{% assign group_names = "Director|Senior Research Fellow|Senior Research Associate" | split:"|" %}
{% for group in group_names %}
  <h2>{{ group }}</h2>
  {% assign people_in_group = site.people | where:"job", group %}
  {% for person in people_in_group %}
    {% include team_member.html member=person %}
  {% endfor %}
{% endfor %}
</div>
