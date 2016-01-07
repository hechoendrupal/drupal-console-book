# उपलब्ध Drupal कंसोल कमाण्डें

**नोट:** Drupal कंसोल कमाण्डें Drupal 8 के स्थापना रूट से चलायी जाए.

Drupal कंसोल कमाण्ड | विवरण
------------ | -------------
[about](about.md) | Drupal कंसोल परियोजना के बारे मे प्रारंभिक जानकारी दिखाएँ
[chain](chain.md) | कमाण्डो को श्रंखला में चलायें।
[help](help.md) | Displays help for a command
[init](init.md) | व्यवस्था फाइलो को उपभोगक्ता के होम डायरेक्टरी में प्रतिरुप करें।
[list](list.md) | Lists commands22
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | सभी साइट caches को पुनर्निर्माण और साफ़ करें।
**config**  |
[config:debug](config-debug.md) | वर्तमान व्यवस्था को दिखाएँ।
[config:edit](config-edit.md) | चयनित व्यवस्था को बदलें।
[config:export](config-export.md) | Export current application configuration.
[config:export:content:type](config-export-content-type.md) | किसी विशेष कंटेंट प्रकार और उनके खानो का निर्यात करें।
[config:export:single](config-export-single.md) | एक व्यवस्था को yml फाइल के जैसे निर्यात करें।
[config:export:view](config-export-view.md) | एक व्यू को YAML संरूप में निर्यात करें ताकि वो किसी दूसरे वेबसाइट में पुनर्प्रयोग किया जाये।
[config:import](config-import.md) | वर्तमान अनुप्रयोग में व्यवस्था आयात करें।
[config:import:single](config-import-single.md) | चयनित व्यवस्था आयात करें।
[config:override](config-override.md) | व्यवस्था निधि को सक्रिय डायरेक्टरी में चढ़ा दें।
**container**  |
[container:debug](container-debug.md) | अनुप्रयोग की वर्तमान सर्विसेज़ को दिखाएँ।
**create**  |
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy vocabularies for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:debug](cron-debug.md) | क्रॉन लागू करने वाले मोड्यूलों की सूचि
[cron:execute](cron-execute.md) | क्रॉन लागू करने वाले किसी विशेष मोड्यूल को चलायें या सारे क्रॉन चलायें
[cron:release](cron-release.md) | क्रॉन चलाने के लिए क्रॉन प्रणाली का लॉक को मुक्त करें
**database**  |
[database:client](database-client.md) | Launch a DB client if it's available
[database:connect](database-connect.md) | Launch a DB client if it's available
[database:dump](database-dump.md) | Dump structure and contents of MySQL databases and tables
[database:log:clear](database-log-clear.md) | Remove events from DBLog table, filters are available
[database:log:debug](database-log-debug.md) | Display current log events for the application
[database:restore](database-restore.md) | Restore structure and contents of MySQL databases and tables
[database:table:debug](database-table-debug.md) | commands.database.table.debug.description
[database:table:drop](database-table-drop.md) | commands.database.table.drop.description
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | प्रमाणन प्रदाता उत्पन्न करें
[generate:command](generate-command.md) | कंसोल के लिए कमाण्डो को उत्पन्न करें।
[generate:controller](generate-controller.md) | एक कंट्रोलर को उत्पन्न और पंजीकृत करें
[generate:doc:dash](generate-doc-dash.md) | डैश के लिए  DrupalConsole.docset पैकेज उत्पन्न करें
[generate:doc:gitbook](generate-doc-gitbook.md) | कमाण्डो के लिए प्रलेखन उत्पन्न करें
[generate:entity:bundle](generate-entity-bundle.md) | एक नया कंटेंट प्रकार उत्पन्न करें (नोड/एंटिटी बंडल)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | एक घटना ग्राहक उत्पन्न करें
[generate:form](generate-form.md) | एक नया FormBase उत्पन्न करें
[generate:form:alter](generate-form-alter.md) | एक hook_form_alter() या hook_form_FORM_ID_alter कार्यान्वयन उत्पन्न करें
[generate:form:config](generate-form-config.md) | एक नया ConfigFormBase उत्पन्न करें
[generate:module](generate-module.md) | मोड्यूल उत्पन्न करें।
[generate:permissions](generate-permissions.md) | मोड्यूल अनुमतियां उत्पन्न करें
[generate:plugin:block](generate-plugin-block.md) | प्लगिन खंड उत्पन्न करें
[generate:plugin:condition](generate-plugin-condition.md) | प्लगिन नियम उत्पन्न करें।
[generate:plugin:field](generate-plugin-field.md) | खाना प्रकार, विजेट और formatter प्लगिन उत्पन्न करें।
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | खाना formatter प्लगिन उत्पन्न करें
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | खाना प्रकार प्लगिन उत्पन्न करें
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | खाना विजेट प्लगिन उत्पन्न करें
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | छवि प्रभाव प्लगिन उत्पन्न करें
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | छवि formatter प्लगिन उत्पन्न करें
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | प्लगिन रेस्ट साधन उत्पन्न करें
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | प्लगिन रुल प्रक्रिया उत्पन्न करें
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | प्लगिन प्रकार युक्त अननोटेशन प्रकाशन उत्पन्न करें
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | प्लगिन प्रकार युक्त YAML प्रकाशन उत्पन्न करें
[generate:plugin:views:field](generate-plugin-views-field.md) | विशेष प्लगिन व्यू खाना उत्पन्न करें
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | सर्विस उत्पन्न करें
[generate:theme](generate-theme.md) | एक नया थीम उत्पन्न करें।
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | DElete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:debug](migrate-debug.md) | अनुप्रयोग के मौजूदा प्रवसन को दिखाएँ
[migrate:execute](migrate-execute.md) | अनुप्रयोग के उपलब्ध प्रवसन को चलाएं
[migrate:setup](migrate-setup.md) | विरासत डेटाबेस के लिए प्रासंगिक माइग्रेशन बनायें और लोड करें
**module**  |
[module:debug](module-debug.md) | अनुप्रयोग के उपलब्ध मोड्यूलो को दिखाएँ
[module:download](module-download.md) | मोड्यूल या मोड्यूलो को डाउनलोड करें
[module:install](module-install.md) | मोड्यूल या मोड्यूलो को अनुप्रयोग में स्थापित करें
[module:uninstall](module-uninstall.md) | अनुप्रयोग में मॉड्यूल की स्थापित रद्द करें |
**multisite**  |
[multisite:debug](multisite-debug.md) | सभी उपलब्ध multisites की सूची|
**rest**  |
[rest:debug](rest-debug.md) | आवेदन के लिए मौजूदा REST संसाधन को प्रदर्शित करें
[rest:disable](rest-disable.md) | अनुप्रयोग में REST संसाधन अक्षम करें|
[rest:enable](rest-enable.md) | अनुप्रयोग के रेस्ट साधन को चालू करे
**router**  |
[router:debug](router-debug.md) | अनुप्रयोग के वर्तमान मार्गों को दिखाएँ
[router:rebuild](router-rebuild.md) | अनुप्रयोग के मार्ग पथ को पुनर्निर्माण करें
**site**  |
[site:debug](site-debug.md) | सभी ज्ञात स्थानीय और दूरस्थ साइटों की सूची दें।
[site:install](site-install.md) | Install a Drupal project
[site:maintenance](site-maintenance.md) | साइट को अनुरक्षरण विधि में बदले
[site:mode](site-mode.md) | प्रणाली की कार्य-निष्पादन व्यवस्था को बदलें
[site:new](site-new.md) | एक नया Drupal परियोजना बनाएँ
[site:status](site-status.md) | वर्तमान Drupal स्थापना के स्थिति को देखें
**state**  |
[state:debug](state-debug.md) | Show the current State keys.
[state:override](state-override.md) | Show the current State keys.
**test**  |
[test:debug](test-debug.md) | अनुप्रयोग की सारी उपलब्ध परिक्षण यूनिटो को दिखाएँ।
[test:run](test-run.md) | अनुप्रयोग के उपलब्ध परीक्षणों मे से परिक्षण यूनिट को चलायें
**theme**  |
[theme:debug](theme-debug.md) | Displays current themes for the application
[theme:download](theme-download.md) | Download theme in application
[theme:install](theme-install.md) | Install theme or themes in the application
[theme:uninstall](theme-uninstall.md) | Uninstall theme or themes in the application
**update**  |
[update:debug](update-debug.md) | अनुप्रयोग के उपलब्ध नवीनीकरणो को दिखाएँ
[update:execute](update-execute.md) | मोड्यूल के किसी विशेष नवीनीकरण N फंक्शन को चलायें या सभी को चलायें।
**user**  |
[user:debug](user-debug.md) | Displays current users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | किसी अकाउंट की असफल लोगिन प्रयासो को साफ़ करें।
[user:login:url](user-login-url.md) | एक बार काम करने वाली उपभोग्ता लोगिन URL देता है।
[user:password:hash](user-password-hash.md) | सरल कूटशब्द से हैश उत्पन्न करें।
[user:password:reset](user-password-reset.md) | किसी विशेष उपभोगता का कूटशब्द रिसेट करें
**views**  |
[views:debug](views-debug.md) | अनुप्रयोग के वर्तमान व्यूज साधनो को दिखाएँ
[views:disable](views-disable.md) | एक व्यू बंद करें
[views:enable](views-enable.md) | एक व्यू चालू करें
**yaml**  |
[yaml:diff](yaml-diff.md) | दो YAML फाइल का अंतर देखने के लिये उनकी तुलना करें
[yaml:merge](yaml-merge.md) | एक या एक से ज़्यादा YAML फाइलो को एक YAML फाइल में विलय करें। नवीनीकरण निधि सुरक्षित रहेंगे।
[yaml:split](yaml-split.md) | इंडेंट द्वारा विभाजन मानदंड से एक YAML फाइल को अलग करें।
[yaml:update:key](yaml-update-key.md) | YAML फाइल में YAML कुंजी को बदले।
[yaml:update:value](yaml-update-value.md) | YAML फाइल में किसी विशेष कुंजी के निधि को अवगत करें।

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--help | इस सहायता संदेश को दिखाएँ
--quiet | कोई संदेश ना दिखाएँ
--verbose | संदेशों के शब्दाडंबर को बढ़ाएं: सामान्य निर्गम के लिए १, अधिक शब्दबहुल के लिए २ और डिबग के लिए ३
--version | अनुप्रयोग संस्करण दिखाएँ
--ansi | ANSI परिणाम अनिवार्य करें
--no-ansi | ANSI निगम अक्षम करें
--no-interaction | कोई वार्तालाप प्रशन ना पूछें
--root | कमाण्ड चलाने के लिए Drupal रूट परिभाषित करें
--env | पर्यावरण का नाम।
--no-debug | डिबग विधि को बंद कर देता है।
--learning | शब्दबहुल कोड उत्पन्न करें।
--generate-chain | निष्पादन विकल्प में प्रिंट और तर्क को YAML आउटपुट के रूप में श्रृंखला कमांड में इस्तेमाल किया जाएगा
--generate-inline | निष्पादन विकल्प में प्रिंट और तर्क को इनलाइन कॉल के रूप में भविष्य में उपयोग किया जाएगा
--generate-doc | application.console.arguments.generate-doc
--target | application.console.arguments.target
--uri | URI of the Drupal site to use (for multisite environments or when running on an alternate port)

## उपलब्ध तर्कों  
तर्क | विवरण
---------|-------------
command | चलने वाली कमाण्ड
