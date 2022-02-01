GreenPA Project
================

The **GreenPA** Project aim is to monitor the CO2 emissions of Italian public administrations websites.

Project Data
------------

| Field                              | Detail                                                                    |
|------------------------------------|---------------------------------------------------------------------------|
| date                               | Monitoring date                                                           |
| ipa                                | IPA - Italian Public Administration code                                  |
| url                                | The website to analyze                                                    |
| hosting_green                      | boolean - if the hosting is present in the Green Web Foundation DB        |
| co2_grams                          | The CO2 Emissions in grams                                                |
| energy_kWh                         | The energy consumed in KWD                                                |
| water_litres                       | The quantity of water to boil to emit the same quantity of CO2 in the air |
| transfer_size_bytes.total          | The data traffic total of the page to analyze (compressed)                |
| transfer_size_bytes.total_weighted | The weighted data traffic total of the page to analyze                    |
| transfer_size_bytes.html           | The HTML data traffic of the page to analyze                              |
| transfer_size_bytes.css            | The CSS data traffic of the page to analyze                               |
| transfer_size_bytes.javascript     | The JAVASCRIPT data traffic of the page to analyze                        |
| transfer_size_bytes.image          | The IMAGE data traffic of the page to analyze                             |
| transfer_size_bytes.font           | The FONT data traffic of the page to analyze                              |
| transfer_size_bytes.audio          | The AUDIO data traffic of the page to analyze                             |
| transfer_size_bytes.video          | The VIDEO data traffic of the page to analyze                             |
| transfer_size_bytes.other          | The OTHER data traffic of the page to analyze                             |
| resources_size_bytes.total         | The resources size total of the page to analyze                           |
| resources_size_bytes.html          | The HTML resources size total of the page to analyze                      |
| resources_size_bytes.css           | The CSS resources size total of the page to analyze                       |
| resources_size_bytes.javascript    | The JAVASCRIPT resources size total of the page to analyze                |
| resources_size_bytes.image         | The IMAGE resources size total of the page to analyze                     |
| resources_size_bytes.font          | The FONT resources size total of the page to analyze                      |
| resources_size_bytes.audio         | The AUDIO resources size total of the page to analyze                     |
| resources_size_bytes.video         | The VIDEO resources size total of the page to analyze                     |
| resources_size_bytes.other         | The OTHER resources size total of the page to analyze                     |

Tool
----
[Carbon Calculator](https://github.com/gpirrotta/carbon-calculator)

License
-------
[CC-BY](https://creativecommons.org/licenses/by/4.0/deed.it)

More info
---------

* [Di ecologia digitale, emissioni di carbonio e pubbliche amministrazioni (parte 1)](https://medium.com/@gpirrotta/di-ecologia-digitale-emissioni-di-carbonio-e-pubbliche-amministrazioni-parte-1-5ec5cd58a52)
* [Di ecologia digitale, emissioni di carbonio e pubbliche amministrazioni (parte 2)](https://medium.com/@gpirrotta/di-ecologia-digitale-emissioni-di-carbonio-e-pubbliche-amministrazioni-parte-2-70ff56fcf51c)
* [Di ecologia digitale, emissioni di carbonio e pubbliche amministrazioni (parte 3)](https://medium.com/@gpirrotta/di-ecologia-digitale-emissioni-di-carbonio-e-pubbliche-amministrazioni-parte-3-86aec561e303)
