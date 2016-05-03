# उपलब्ध Drupal Console कमांड

**नोट:** Drupal Console कमांड को एक Drupal 8 इंस्टालेशन की रुट से चलाया जाना चाहिए.

Drupal Console कमाण्ड | विवरण
------------ | -------------
[about](about.md) | Drupal कंसोल परियोजना के बारे मे प्रारंभिक जानकारी दिखाएँ
[chain](chain.md) | कमाण्डो को श्रंखला में चलायें।
[check](check.md) | commands.check.description
[help](help.md) | एक कमांड के लिए मदद प्रदर्शित करता है
[init](init.md) | commands.init.description
[list](list.md) | कमांड की सूची
[self-update](self-update.md) | कंसोल को नवीनतम संस्करण में अवगत करें
[server](server.md) | PHP निर्मित वेब सर्वर चलायॆ
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | commands.breakpoints.debug.description
**cache**  |
[cache:rebuild](cache-rebuild.md) | सभी साइट caches को पुनर्निर्माण और साफ़ करें।
**chain**  |
[chain:debug](chain-debug.md) | List available chain files.
**config**  |
[config:debug](config-debug.md) | वर्तमान व्यवस्था को दिखाएँ।
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | आउटपुट विन्यास आइटम है कि एक डायरेक्टरी के साथ तुलना में सक्रिय कॉन्फ़िगरेशन में अलग हैं।
[config:edit](config-edit.md) | चयनित व्यवस्था को बदलें।
[config:export](config-export.md) | मौजूदा एप्लीकेशन कॉन्फ़िगरेशन एक्सपोर्ट करे।
[config:export:content:type](config-export-content-type.md) | किसी विशेष कंटेंट टाइप और उनके खानो का एक्सपोर्ट करें।
[config:export:single](config-export-single.md) | एक कॉन्फिग को yml फाइल के जैसे निर्यात करें।
[config:export:view](config-export-view.md) | एक व्यू को YAML संरूप में एक्सपोर्ट करें ताकि वो किसी दूसरे वेबसाइट में पुनर्प्रयोग किया जाये।
[config:import](config-import.md) | वर्तमान अनुप्रयोग में व्यवस्था आयात करें।
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | व्यवस्था निधि को सक्रिय डायरेक्टरी में चढ़ा दें।
[config:settings:debug](config-settings-debug.md) | सेटिंग्स फाइल पर वर्तमान key:value दिखाता है।
**container**  |
[container:debug](container-debug.md) | अनुप्रयोग की वर्तमान सर्विसेज़ को दिखाएँ।
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी नोड्स बनाएँ।
[create:terms](create-terms.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी टर्म्ज़ बनाएँ।
[create:users](create-users.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी यूजरस बनाएँ।
[create:vocabularies](create-vocabularies.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी वोकैब्युलरीस बनाएँ।
**cron**  |
[cron:debug](cron-debug.md) | क्रॉन लागू करने वाले मोड्यूलों की सूचि
[cron:execute](cron-execute.md) | क्रॉन लागू करने वाले किसी विशेष मोड्यूल को चलायें या सारे क्रॉन चलायें
[cron:release](cron-release.md) | क्रॉन चलाने के लिए क्रॉन प्रणाली का लॉक को मुक्त करें
**database**  |
[database:client](database-client.md) | लॉन्च एक DB क्लाइंट अगर यह उपलब्ध है
[database:connect](database-connect.md) | लॉन्च एक DB क्लाइंट अगर यह उपलब्ध है
[database:drop](database-drop.md) | एक दिए गए डेटाबेस में सभी टेबल्स ड्राप।
[database:dump](database-dump.md) | डंप संरचना और MYSQL का कंटेंट डेटाबेसेस और टेबल्स
[database:log:clear](database-log-clear.md) | DBLog टेबल से इवेंट्स निकालें, फिल्टर उपलब्ध हैं
[database:log:debug](database-log-debug.md) | एप्लीकेशन के लिए वर्तमान लॉग इवेंट्स को प्रदर्शित करे
[database:restore](database-restore.md) | MYSQL डाटाबेस और टेबल्स ले कंटेंट और संरचना को रिस्टोर करे
[database:table:debug](database-table-debug.md) | एक दिए गए डेटाबेस में सभी टेबल्स दिखाएँ.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | प्रमाणन प्रदाता उत्पन्न करें
[generate:command](generate-command.md) | कंसोल के लिए कमाण्डो को उत्पन्न करें।
[generate:controller](generate-controller.md) | एक कंट्रोलर को उत्पन्न और पंजीकृत करें
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Generate a printable cheatsheet for Commands
[generate:doc:dash](generate-doc-dash.md) | डैश के लिए  DrupalConsole.docset पैकेज उत्पन्न करें
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | कमाण्डो के लिए डॉक्युमेंटेशन्स उत्पन्न करें
[generate:entity:bundle](generate-entity-bundle.md) | एक नया कंटेंट प्रकार उत्पन्न करें (नोड/एंटिटी बंडल)
[generate:entity:config](generate-entity-config.md) | एक नया कॉन्फिग एंटिटि उत्पन्न करे
[generate:entity:content](generate-entity-content.md) | एक नई कंटेंट एंटिटि बनाए
[generate:event:subscriber](generate-event-subscriber.md) | एक घटना ग्राहक उत्पन्न करें
[generate:form](generate-form.md) | एक नया FormBase उत्पन्न करें
[generate:form:alter](generate-form-alter.md) | एक hook_form_alter() या hook_form_FORM_ID_alter कार्यान्वयन उत्पन्न करें
[generate:form:config](generate-form-config.md) | एक नया ConfigFormBase उत्पन्न करें
[generate:module](generate-module.md) | मोड्यूल उत्पन्न करें।
[generate:permissions](generate-permissions.md) | मोड्यूल अनुमतियां उत्पन्न करें
[generate:plugin:block](generate-plugin-block.md) | प्लगिन खंड उत्पन्न करें
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | प्लगिन नियम उत्पन्न करें।
[generate:plugin:field](generate-plugin-field.md) | खाना प्रकार, विजेट और formatter प्लगिन उत्पन्न करें।
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | खाना formatter प्लगिन उत्पन्न करें
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | खाना प्रकार प्लगिन उत्पन्न करें
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | खाना विजेट प्लगिन उत्पन्न करें
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | छवि प्रभाव प्लगिन उत्पन्न करें
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | छवि formatter प्लगिन उत्पन्न करें
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | प्लगिन रेस्ट साधन उत्पन्न करें
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | प्लगिन रुल प्रक्रिया उत्पन्न करें
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | प्लगिन प्रकार युक्त अननोटेशन प्रकाशन उत्पन्न करें
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | प्लगिन प्रकार युक्त YAML प्रकाशन उत्पन्न करें
[generate:plugin:views:field](generate-plugin-views-field.md) | विशेष प्लगिन व्यू खाना उत्पन्न करें
[generate:profile](generate-profile.md) | प्रोफाइल उत्पन्न करे.
[generate:routesubscriber](generate-routesubscriber.md) | RouteSubscriber उत्पन्न करे.
[generate:service](generate-service.md) | सर्विस उत्पन्न करें
[generate:theme](generate-theme.md) | एक नया थीम उत्पन्न करें।
**image**  |
[image:styles:debug](image-styles-debug.md) | List image styles on the site
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**libraries**  |
[libraries:debug](libraries-debug.md) | commands.libraries.debug.description
**locale**  |
[locale:language:add](locale-language-add.md) | एक भाषा को जोड़े जो आप के साइट द्वारा सपोर्ट होना है
[locale:language:delete](locale-language-delete.md) | आपकी साइट के द्वारा समर्थित एक भाषा को हटाएँ
[locale:translation:status](locale-translation-status.md) | सूची उपलब्ध अनुवाद अपडेट
**migrate**  |
[migrate:debug](migrate-debug.md) | अनुप्रयोग के मौजूदा प्रवसन को दिखाएँ
[migrate:execute](migrate-execute.md) | अनुप्रयोग के उपलब्ध माइग्रेशन को चलाएं
[migrate:setup](migrate-setup.md) | विरासत डेटाबेस के लिए प्रासंगिक माइग्रेशन बनायें और लोड करें
**module**  |
[module:debug](module-debug.md) | अनुप्रयोग के उपलब्ध मोड्यूलो को दिखाएँ
[module:download](module-download.md) | मोड्यूल या मोड्यूलो को डाउनलोड करें
[module:install](module-install.md) | मोड्यूल या मोड्यूलो को अनुप्रयोग में स्थापित करें
[module:uninstall](module-uninstall.md) | अनुप्रयोग में मॉड्यूल की स्थापित रद्द करें |
**multisite**  |
[multisite:debug](multisite-debug.md) | सभी उपलब्ध multisites की सूची|
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**rest**  |
[rest:debug](rest-debug.md) | आवेदन के लिए मौजूदा REST संसाधन को प्रदर्शित करें
[rest:disable](rest-disable.md) | अनुप्रयोग में REST संसाधन अक्षम करें|
[rest:enable](rest-enable.md) | अनुप्रयोग के रेस्ट साधन को चालू करे
**router**  |
[router:debug](router-debug.md) | अनुप्रयोग के वर्तमान मार्गों को दिखाएँ
[router:rebuild](router-rebuild.md) | अनुप्रयोग के मार्ग पथ को पुनर्निर्माण करें
**settings**  |
[settings:debug](settings-debug.md) | यूजर Drupal कंसोल सेटिंग्स की सूची
[settings:set](settings-set.md) | Drupal कंसोल कॉन्फिग फाइल में एक विशिष्ट सेटिंग मूल्य बदलें
**site**  |
[site:debug](site-debug.md) | सभी ज्ञात स्थानीय और दूरस्थ साइटों की सूची दें।
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | एक Drupal परियोजना स्थापित करें
[site:maintenance](site-maintenance.md) | साइट को मेंटेनेंस मोड में बदले
[site:mode](site-mode.md) | प्रणाली की कार्य-निष्पादन व्यवस्था को बदलें
[site:new](site-new.md) | एक नया Drupal परियोजना बनाएँ
[site:statistics](site-statistics.md) | वेबसाइट के मौजूदा आंकड़े बताते हैं।
[site:status](site-status.md) | वर्तमान Drupal स्थापना के स्थिति को देखें
**state**  |
[state:debug](state-debug.md) | वर्तमान स्टेट कीस दिखाएँ।
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | स्थिति की मौलिक को ओवरराइड करे
**test**  |
[test:debug](test-debug.md) | अनुप्रयोग की सारी उपलब्ध परिक्षण यूनिटो को दिखाएँ।
[test:run](test-run.md) | अनुप्रयोग के उपलब्ध परीक्षणों मे से परिक्षण यूनिट को चलायें
**theme**  |
[theme:debug](theme-debug.md) | एप्लीकेशन के लिए वर्तमान थीम्स को प्रदर्शित करता है
[theme:download](theme-download.md) | आवेदन में विषय डाउनलोड करे
[theme:install](theme-install.md) | इंस्टॉल विषय या विषयों के आवेदन में
[theme:uninstall](theme-uninstall.md) | विषय की स्थापना रद्द करें या विषयों के आवेदन में
**translation**  |
[translation:cleanup](translation-cleanup.md) | क्लीनअप ट्रांसलेशन फाइल्स
[translation:pending](translation-pending.md) | पेंडिंग ट्रांसलेशन स्ट्रिंग को एक भाषा में या एक स्पेसिफिक फाइल को एक भाषा में निर्धारण करें
[translation:stats](translation-stats.md) | ट्रांसलेट स्टैट्स उत्पन्न
[translation:sync](translation-sync.md) | सींक ट्रांसलेशन फाइल्स
**update**  |
[update:debug](update-debug.md) | अनुप्रयोग के उपलब्ध नवीनीकरणो को दिखाएँ
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | मोड्यूल के किसी विशेष नवीनीकरण N फंक्शन को चलायें या सभी को चलायें।
**user**  |
[user:debug](user-debug.md) | एप्लीकेशन के लिए करंट यूजरस को प्रदर्शित करता है
[user:delete](user-delete.md) | एप्लीकेशन के लिए यूजरस को हटाये
[user:login:clear:attempts](user-login-clear-attempts.md) | किसी अकाउंट की असफल लोगिन प्रयासो को साफ़ करें।
[user:login:url](user-login-url.md) | एक बार काम करने वाली उपभोग्ता लोगिन URL देता है।
[user:password:hash](user-password-hash.md) | सरल पासवर्ड से हैश उत्पन्न करें।
[user:password:reset](user-password-reset.md) | किसी विशेष उपभोगता का पासवर्ड रिसेट करें
**views**  |
[views:debug](views-debug.md) | अनुप्रयोग के वर्तमान व्यूज साधनो को दिखाएँ
[views:disable](views-disable.md) | एक व्यू बंद करें
[views:enable](views-enable.md) | एक व्यू चालू करें
[views:plugins:debug](views-plugins-debug.md) | Display current views plugins for the application
**yaml**  |
[yaml:diff](yaml-diff.md) | दो YAML फाइल का अंतर देखने के लिये उनकी तुलना करें
[yaml:merge](yaml-merge.md) | एक या एक से ज़्यादा YAML फाइलो को एक YAML फाइल में विलय करें। नवीनीकरण निधि सुरक्षित रहेंगे।
[yaml:split](yaml-split.md) | इंडेंट द्वारा विभाजन मानदंड से एक YAML फाइल को अलग करें।
[yaml:update:key](yaml-update-key.md) | YAML फाइल में YAML कुंजी को बदले।
[yaml:update:value](yaml-update-value.md) | YAML फाइल में किसी विशेष कुंजी के निधि को अवगत करें।

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | <info>%s</info> संस्करण <comment>%s</comment>
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | पर्यावरण का नाम।
--root | कमाण्ड चलाने के लिए Drupal रूट परिभाषित करें
--no-debug | डिबग विधि को बंद कर देता है।
--learning | शब्दबहुल कोड उत्पन्न करें।
--generate-chain | निष्पादन विकल्प में प्रिंट और तर्क को YAML आउटपुट के रूप में श्रृंखला कमांड में इस्तेमाल किया जाएगा
--generate-inline | निष्पादन विकल्प में प्रिंट और तर्क को इनलाइन कॉल के रूप में भविष्य में उपयोग किया जाएगा
--generate-doc | कमाण्ड विकल्पों और तर्क जैसा नीचे निशान
--target | साइट का नाम आप (स्थानीय या दूरस्थ साइटों के लिए ) के साथ बातचीत करना चाहते हैं
--uri | Drupal यूआरआई साइट का(एकाधिक वातावरण के लिए या एक वैकल्पिक port पर चलते समय ) का उपयोग करे
--yes | स्किप कन्फर्मेशन और आगे बढ़ें

## उपलब्ध तर्कों
तर्क | विवरण
---------|-------------
command | The command to execute
