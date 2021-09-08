# BlazorFlags
Country Flags component for Blazor. A port of [vue-country-flags](https://github.com/P3trur0/vue-country-flag).

![Nuget](https://img.shields.io/nuget/v/BlazorFlags?style=flat-square)

<p align="center">
  <img src="assets/example_screenshot.png?raw=true" alt="example app screenshot"/>
</p>


## Get Started

### Add Package
```bash
Install-Package BlazorFlags -Version 1.0.0
```

### Import Namespace
```
@using UIComponents.Flags
```

### Example usage 

```html
<CountryFlag Country="@country" Size="@size" HasShadow="@hasShadow" IsRounded="@isRounded" Class="mx-3"/>
```

## Available Flags
The flags are identified using the [ISO 3166-1](https://en.wikipedia.org/wiki/ISO_3166-1) standard.  
This component currently supports **alpha-2**.

| **Country Name** | **alpha-2** |
|--------------|---------|
| Afghanistan | af | 
| Åland Islands | ax |
| Albania | al |
| Algeria | dz | 
| American Samoa | as | 
| Andorra | ad |
| Angola | ao |
| Anguilla | ai |
| Antarctica | aq | 
| Antigua and Barbuda | ag | 
| Argentina | ar |
| Armenia | am |
| Aruba | aw | 
| Australia | au | 
| Austria | at |
| Azerbaijan | az | 
| Bahamas | bs | 
| Bahrain | bh | 
| Bangladesh | bd | 
| Barbados | bb |
| Belarus | by |
| Belgium | be | 
| Belize | bz |
| Benin | bj | 
| Bermuda | bm | 
| Bhutan | bt |
| Bolivia (Plurinational State of) | bo | 
| Bonaire, Sint Eustatius and Saba | bq |
| Bosnia and Herzegovina | ba |
| Botswana | bw | 
| Bouvet Island | bv |
| Brazil | br |
| Virgin Islands (British) | vg | 
| British Indian Ocean Territory | io |
| Brunei Darussalam | bn | 
| Bulgaria | bg |
| Burkina Faso | bf |
| Burundi | bi | 
| Cambodia | kh |
| Cameroon | cm |
| Canada | ca | 
| Cabo Verde | cv | 
| Cayman Islands | ky | 
| Central African Republic | cf |
| Chad | td |
| Chile | cl | 
| China | cn |
| Hong Kong | hk | 
| Macao | mo |
| Christmas Island | cx | 
| Cocos (Keeling) Islands | cc | 
| Colombia | co | 
| Comoros | km | 
| Congo | cg |
| Congo, Democratic Republic of the | cd | 
| Cook Islands | ck | 
| Costa Rica | cr | 
| Côte d'Ivoire | ci |
| Croatia | hr | 
| Cuba | cu | 
| Curaçao | cw | 
| Cyprus | cy |
| Czechia | cz | 
| Denmark | dk |
| Djibouti | dj |
| Dominica | dm |
| Dominican Republic | do |
| Ecuador | ec |
| Egypt | eg | 
| El Salvador | sv | 
| Equatorial Guinea | gq | 
| Eritrea | er | 
| Estonia | ee | 
| Ethiopia | et | 
| Falkland Islands (Malvinas) | fk |
| Faroe Islands | fo | 
| Fiji | fj | 
| Finland | fi | 
| France | fr | 
| French Guiana | gf |
| French Polynesia | pf | 
| French Southern Territories | tf | 
| Gabon | ga | 
| Gambia | gm | 
| Georgia | ge | 
| Germany | de |
| Ghana | gh |
| Gibraltar | gi | 
| Greece | gr | 
| Greenland | gl | 
| Grenada | gd |
| Guadeloupe | gp | 
| Guam | gu | 
| Guatemala | gt |
| Guernsey | gg | 
| Guinea | gn | 
| Guinea-Bissau | gw |
| Guyana | gy | 
| Haiti | ht | 
| Heard Island and McDonald Islands | hm |
| Holy See | va | 
| Honduras | hn | 
| Hungary | hu | 
| Iceland | is |
| India | in | 
| Indonesia | id |
| Iran (Islamic Republic of) | ir | 
| Iraq | iq |
| Ireland | ie |
| Isle of Man | im |
| Israel | il | 
| Italy | it | 
| Jamaica | jm | 
| Japan | jp |
| Jersey | je | 
| Jordan | jo | 
| Kazakhstan | kz | 
| Kenya | ke |
| Kiribati | ki | 
| Korea (Democratic People's Republic of) | kp |
| Korea, Republic of | kr |
| Kuwait | kw |
| Kyrgyzstan | kg | 
| Lao People's Democratic Republic | la | 
| Latvia | lv |
| Lebanon | lb |
| Lesotho | ls | 
| Liberia | lr | 
| Libya | ly | 
| Liechtenstein | li | 
| Lithuania | lt | 
| Luxembourg | lu | 
| North Macedonia | mk | 
| Madagascar | mg |
| Malawi | mw | 
| Malaysia | my |
| Maldives | mv | 
| Mali | ml | 
| Malta | mt |
| Marshall Islands | mh | 
| Martinique | mq | 
| Mauritania | mr |
| Mauritius | mu | 
| Mayotte | yt | 
| Mexico | mx |
| Micronesia (Federated States of) | fm | 
| Moldova, Republic of | md | 
| Monaco | mc | 
| Mongolia | mn | 
| Montenegro | me |
| Montserrat | ms | 
| Morocco | ma | 
| Mozambique | mz |
| Myanmar | mm |
| Namibia | na | 
| Nauru | nr | 
| Nepal | np | 
| Netherlands | nl |
| New Caledonia | nc |
| New Zealand | nz |
| Nicaragua | ni |
| Niger | ne |
| Nigeria | ng |
| Niue | nu |
| Norfolk Island | nf | 
| Northern Mariana Islands | mp |
| Norway | no |
| Oman | om | 
| Pakistan | pk | 
| Palau | pw | 
| Palestine, State of | ps |
| Panama | pa | 
| Papua New Guinea | pg |
| Paraguay | py | 
| Peru | pe | 
| Philippines | ph | 
| Pitcairn | pn |
| Poland | pl | 
| Portugal | pt |
| Puerto Rico | pr | 
| Qatar | qa | 
| Réunion | re | 
| Romania | ro | 
| Russian Federation | ru | 
| Rwanda | rw | 
| Saint Barthélemy | bl | 
| Saint Helena, Ascension and Tristan da Cunha | sh | 
| Saint Kitts and Nevis | kn |
| Saint Lucia | lc |
| Saint Martin (French part) | mf |
| Saint Pierre and Miquelon | pm | 
| Saint Vincent and the Grenadines | vc | 
| Samoa | ws |
| San Marino | sm |
| Sao Tome and Principe | st | 
| Saudi Arabia | sa | 
| Senegal | sn | 
| Serbia | rs | 
| Seychelles | sc | 
| Sierra Leone | sl | 
| Singapore | sg |
| Sint Maarten (Dutch part) | sx | 
| Slovakia | sk | 
| Slovenia | si | 
| Solomon Islands | sb | 
| Somalia | so | som |
| South Africa | za |
| South Georgia and the South Sandwich Islands | gs |
| South Sudan | ss | 
| Soviet Union | su | 
| Spain | es |
| Sri Lanka | lk | 
| Sudan | sd |
| Suriname | sr | 
| Svalbard and Jan Mayen | sj | 
| Eswatini | sz | 
| Sweden | se |
| Switzerland | ch | 
| Syrian Arab Republic | sy | 
| Taiwan, Province of China | tw | 
| Tajikistan | tj |
| Tanzania, United Republic of | tz |
| Thailand | th | 
| Timor-Leste | tl |
| Togo | tg | 
| Tokelau | tk | 
| Tonga | to | 
| Trinidad and Tobago | tt | 
| Tunisia | tn | 
| Turkey | tr | 
| Turkmenistan | tm | 
| Turks and Caicos Islands | tc | 
| Tuvalu | tv | 
| Uganda | ug | 
| Ukraine | ua |
| United Arab Emirates | ae |
| United Kingdom of Great Britain and Northern Ireland | gb | 
| United States of America | us |
| United States Minor Outlying Islands | um | 
| Uruguay | uy | 
| Uzbekistan | uz |
| Vanuatu | vu | 
| Venezuela (Bolivarian Republic of) | ve |
| Viet Nam | vn | 
| Virgin Islands (U.S.) | vi | 
| Wallis and Futuna | wf |
| Western Sahara | eh | 
| Yemen | ye | 
| Zambia | zm |
| Zimbabwe | zw |


## Extra flags

| **Country Name** | **Flag Code** |
|--------------|---------|
| Catalonia | es-ca |
| England | gb-eng |
| Europe | eu |
| Galles | gb-wls |
| Kosovo | xk |
| Scotland | gb-sct |
| United Nations | un |

## Credits

The flags used for this components is provided by [Flag Icons CSS](https://github.com/lipis/flag-icon-css "Flag Icons CSS").

This component is a port of [vue-country-flags](https://github.com/P3trur0/vue-country-flag).