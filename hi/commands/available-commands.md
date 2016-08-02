# उपलब्ध Drupal Console कमांड

**नोट:** Drupal Console कमांड को एक Drupal 8 इंस्टालेशन की रुट से चलाया जाना चाहिए.

Drupal Console कमाण्ड | विवरण
------------ | -------------
[about](about.md) | Drupal कंसोल परियोजना के बारे मे प्रारंभिक जानकारी दिखाएँ
[chain](chain.md) | कमाण्डो को श्रंखला में चलायें।
[check](check.md) | System requirement checker
[help](help.md) | एक कमांड के लिए मदद प्रदर्शित करता है
[init](init.md) | उपयोगकर्ता के होम डायरेक्टरी के लिए कॉन्फ़िगरेशन फाइल कॉपी किया है।
[list](list.md) | कमांड की सूची
[self-update](self-update.md) | Update project to the latest version.
[server](server.md) | PHP निर्मित वेब सर्वर चलायॆ
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | Displays breakpoints available in application
**cache**  |
[cache:context:debug](cache-context-debug.md) | Displays current cache context for the application.
[cache:rebuild](cache-rebuild.md) | सभी साइट caches को पुनर्निर्माण और साफ़ करें।
**chain**  |
[chain:debug](chain-debug.md) | श्रृंखला फ़ाइलें की सूचि उपलब्द।
**config**  |
[config:debug](config-debug.md) | वर्तमान व्यवस्था को दिखाएँ।
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | आउटपुट विन्यास आइटम है कि एक डायरेक्टरी के साथ तुलना में सक्रिय कॉन्फ़िगरेशन में अलग हैं।
[config:edit](config-edit.md) | चयनित व्यवस्था को बदलें।
[config:export](config-export.md) | मौजूदा एप्लीकेशन कॉन्फ़िगरेशन एक्सपोर्ट करे।
[config:export:content:type](config-export-content-type.md) | किसी विशेष कंटेंट टाइप और उनके खानो का एक्सपोर्ट करें।
[config:export:view](config-export-view.md) | एक व्यू को YAML संरूप में एक्सपोर्ट करें ताकि वो किसी दूसरे वेबसाइट में पुनर्प्रयोग किया जाये।
[config:import](config-import.md) | वर्तमान अनुप्रयोग में व्यवस्था आयात करें।
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | व्यवस्था निधि को सक्रिय डायरेक्टरी में चढ़ा दें।
[config:settings:debug](config-settings-debug.md) | सेटिंग्स फाइल पर वर्तमान key:value दिखाता है।
**container**  |
[container:debug](container-debug.md) | अनुप्रयोग की वर्तमान सर्विसेज़ को दिखाएँ।
**create**  |
[create:comments](create-comments.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी कमेंट्स बनाएँ।
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
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**event**  |
[event:debug](event-debug.md) | वर्तमान इवेंट्स को प्रदर्शित करें
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Generate a printable cheatsheet for Commands
[generate:doc:dash](generate-doc-dash.md) | Generate the DrupalConsole.docset package for Dash
[generate:doc:data](generate-doc-data.md) | Generate documentations for Commands.
[generate:doc:gitbook](generate-doc-gitbook.md) | Generate documentations for Commands
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:module](generate-module.md) | Generate a module.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Generate a plugin block
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Generate a plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Generate field type, widget and formatter plugins.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generate field formatter plugin.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generate field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generate image effect plugin.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:post:update](generate-post-update.md) | commands.generate.post:update.description
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Generate service
[generate:theme](generate-theme.md) | Generate a theme.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:debug](image-styles-debug.md) | साइट पर इमेज स्टाइल की सूची
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**libraries**  |
[libraries:debug](libraries-debug.md) | Displays libraries available in application
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | Delete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:debug](migrate-debug.md) | अनुप्रयोग के मौजूदा प्रवसन को दिखाएँ
[migrate:execute](migrate-execute.md) | अनुप्रयोग के उपलब्ध माइग्रेशन को चलाएं
**module**  |
[module:debug](module-debug.md) | अनुप्रयोग के उपलब्ध मोड्यूलो को दिखाएँ
[module:download](module-download.md) | मोड्यूल या मोड्यूलो को डाउनलोड करें
[module:install](module-install.md) | मोड्यूल या मोड्यूलो को अनुप्रयोग में स्थापित करें
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | अनुप्रयोग में मॉड्यूल की स्थापित रद्द करें |
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:debug](multisite-debug.md) | सभी उपलब्ध multisites की सूची|
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**queue**  |
[queue:debug](queue-debug.md) | Display the queues of your application
[queue:run](queue-run.md) | Process the selected queue.
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
[site:import:local](site-import-local.md) | Import/Configure एक मौजूदा स्थानीय Drupal परियोजना
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
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | विषय की स्थापना रद्द करें या विषयों के आवेदन में
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clean up translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
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
[user:role](user-role.md) | Adds/removes a role for a given user
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
--version | <info>"%s"</info> संस्करण <comment>"%s"</comment>
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

## उपलब्ध तर्क
तर्क | विवरण
---------|-------------
command | The command to execute
