# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Drupal कंसोल परियोजना के बारे मे प्रारंभिक जानकारी दिखाएँ
[chain](chain.md) | कमाण्डो को श्रंखला में चलायें।
[check](check.md) | System requirement checker
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | Execute an external command.
[help](help.md) | एक कमांड के लिए मदद प्रदर्शित करता है
[init](init.md) | उपयोगकर्ता के होम डायरेक्टरी के लिए कॉन्फ़िगरेशन फाइल कॉपी किया है।
[list](list.md) | कमांड की सूची
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | PHP निर्मित वेब सर्वर चलायॆ
**cache**  |
[cache:rebuild](cache-rebuild.md) | सभी साइट caches को पुनर्निर्माण और साफ़ करें।
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | आउटपुट विन्यास आइटम है कि एक डायरेक्टरी के साथ तुलना में सक्रिय कॉन्फ़िगरेशन में अलग हैं।
[config:edit](config-edit.md) | चयनित व्यवस्था को बदलें।
[config:export](config-export.md) | मौजूदा एप्लीकेशन कॉन्फ़िगरेशन एक्सपोर्ट करे।
[config:export:content:type](config-export-content-type.md) | एक विशिष्ट कंटेंट टाइप और अपने फ़ील्ड्स में एक्सपोर्ट करें।
[config:export:single](config-export-single.md) | yml फाइल के रूप में सिंगल कॉन्फ़िगरेशन एक्सपोर्ट करे।
[config:export:view](config-export-view.md) | अन्य वेबसाइट में पुन: उपयोग करने के लिए एक प्रोवाइडेड मॉड्यूल के अंदर YAML फॉर्मेट में एक व्यू एक्सपोर्ट करे।
[config:import](config-import.md) | वर्तमान अनुप्रयोग में व्यवस्था आयात करें।
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | व्यवस्था निधि को सक्रिय डायरेक्टरी में चढ़ा दें।
[config:validate](config-validate.md) | Validate a drupal config against its schema
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी कमेंट्स बनाएँ।
[create:nodes](create-nodes.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी नोड्स बनाएँ।
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी टर्म्ज़ बनाएँ।
[create:users](create-users.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी यूजरस बनाएँ।
[create:vocabularies](create-vocabularies.md) | अपने Drupal 8 एप्लीकेशन के लिए डमी वोकैब्युलरीस बनाएँ।
**cron**  |
[cron:execute](cron-execute.md) | क्रॉन लागू करने वाले किसी विशेष मोड्यूल को चलायें या सारे क्रॉन चलायें
[cron:release](cron-release.md) | क्रॉन चलाने के लिए क्रॉन प्रणाली का लॉक को मुक्त करें
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | लॉन्च एक DB क्लाइंट अगर यह उपलब्ध है
[database:connect](database-connect.md) | लॉन्च एक DB क्लाइंट अगर यह उपलब्ध है
[database:drop](database-drop.md) | एक दिए गए डेटाबेस में सभी टेबल्स ड्राप।
[database:dump](database-dump.md) | डंप संरचना और MYSQL का कंटेंट डेटाबेसेस और टेबल्स
[database:log:clear](database-log-clear.md) | DBLog टेबल से इवेंट्स निकालें, फिल्टर उपलब्ध हैं
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | MYSQL डाटाबेस और टेबल्स ले कंटेंट और संरचना को रिस्टोर करे
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Displays breakpoints available in application
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | श्रृंखला फ़ाइलें की सूचि उपलब्द।
[debug:config](debug-config.md) | वर्तमान व्यवस्था को दिखाएँ।
[debug:config:settings](debug-config-settings.md) | सेटिंग्स फाइल पर वर्तमान key:value दिखाता है।
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | अनुप्रयोग की वर्तमान सर्विसेज़ को दिखाएँ।
[debug:cron](debug-cron.md) | क्रॉन लागू करने वाले मोड्यूलों की सूचि
[debug:database:log](debug-database-log.md) | एप्लीकेशन के लिए वर्तमान लॉग इवेंट्स को प्रदर्शित करे
[debug:database:table](debug-database-table.md) | एक दिए गए डेटाबेस में सभी टेबल्स दिखाएँ.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | वर्तमान इवेंट्स को प्रदर्शित करें
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | साइट पर इमेज स्टाइल की सूची
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | अनुप्रयोग के मौजूदा प्रवसन को दिखाएँ
[debug:module](debug-module.md) | अनुप्रयोग के उपलब्ध मोड्यूलो को दिखाएँ
[debug:multisite](debug-multisite.md) | सभी उपलब्ध multisites की सूची|
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
[debug:queue](debug-queue.md) | Display the queues of your application
[debug:rest](debug-rest.md) | आवेदन के लिए मौजूदा REST संसाधन को प्रदर्शित करें
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | अनुप्रयोग के वर्तमान मार्गों को दिखाएँ
[debug:settings](debug-settings.md) | यूजर Drupal कंसोल सेटिंग्स की सूची
[debug:site](debug-site.md) | सभी ज्ञात स्थानीय और दूरस्थ साइटों की सूची दें।
[debug:state](debug-state.md) | वर्तमान स्टेट कीस दिखाएँ।
[debug:test](debug-test.md) | अनुप्रयोग की सारी उपलब्ध परिक्षण यूनिटो को दिखाएँ।
[debug:theme](debug-theme.md) | एप्लीकेशन के लिए वर्तमान थीम्स को प्रदर्शित करता है
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | अनुप्रयोग के उपलब्ध नवीनीकरणो को दिखाएँ
[debug:user](debug-user.md) | एप्लीकेशन के लिए करंट यूजरस को प्रदर्शित करता है
[debug:views](debug-views.md) | अनुप्रयोग के वर्तमान व्यूज साधनो को दिखाएँ
[debug:views:plugins](debug-views-plugins.md) | Display current views plugins for the application
**devel**  |
[devel:dumper](devel-dumper.md) | commands.devel.dumper.messages.change-devel-dumper-plugin
**docker**  |
[docker:init](docker-init.md) | Create a docker-compose.yml file
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Delete an specific entity
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:ajax:command](generate-ajax-command.md) | Generate & Register a custom ajax command
[generate:authentication:provider](generate-authentication-provider.md) | प्रमाणन प्रदाता उत्पन्न करें
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | कंसोल के लिए कमाण्डो को उत्पन्न करें।
[generate:controller](generate-controller.md) | एक कंट्रोलर को उत्पन्न और पंजीकृत करें
[generate:entity:bundle](generate-entity-bundle.md) | एक नया कंटेंट प्रकार उत्पन्न करें (नोड/एंटिटी बंडल)
[generate:entity:config](generate-entity-config.md) | एक नया कॉन्फिग एंटिटि उत्पन्न करे
[generate:entity:content](generate-entity-content.md) | एक नई कंटेंट एंटिटि बनाए
[generate:event:subscriber](generate-event-subscriber.md) | एक घटना ग्राहक उत्पन्न करें
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | एक hook_form_alter() या hook_form_FORM_ID_alter कार्यान्वयन उत्पन्न करें
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | मोड्यूल उत्पन्न करें।
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | प्लगिन खंड उत्पन्न करें
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | CKEditor बटन प्लगइन उत्पन्न करें।
[generate:plugin:condition](generate-plugin-condition.md) | प्लगिन नियम उत्पन्न करें।
[generate:plugin:field](generate-plugin-field.md) | खाना प्रकार, विजेट और formatter प्लगिन उत्पन्न करें।
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | खाना formatter प्लगिन उत्पन्न करें
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | खाना प्रकार प्लगिन उत्पन्न करें
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | खाना विजेट प्लगिन उत्पन्न करें
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | छवि प्रभाव प्लगिन उत्पन्न करें
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | छवि formatter प्लगिन उत्पन्न करें
[generate:plugin:mail](generate-plugin-mail.md) | एक प्लगइन मेल उत्पन्न करें
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | प्लगिन रेस्ट साधन उत्पन्न करें
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | प्लगिन रुल प्रक्रिया उत्पन्न करें
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | प्लगिन प्रकार युक्त अननोटेशन प्रकाशन उत्पन्न करें
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | प्लगिन प्रकार युक्त YAML प्रकाशन उत्पन्न करें
[generate:plugin:views:field](generate-plugin-views-field.md) | विशेष प्लगिन व्यू खाना उत्पन्न करें
[generate:post:update](generate-post-update.md) | Generate an implementation of hook_post_update_NAME()
[generate:profile](generate-profile.md) | प्रोफाइल उत्पन्न करे.
[generate:routesubscriber](generate-routesubscriber.md) | RouteSubscriber उत्पन्न करे.
[generate:service](generate-service.md) | सर्विस उत्पन्न करें
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | एक नया थीम उत्पन्न करें।
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | एक भाषा को जोड़े जो आप के साइट द्वारा सपोर्ट होना है
[locale:language:delete](locale-language-delete.md) | आपकी साइट के द्वारा समर्थित एक भाषा को हटाएँ
[locale:translation:status](locale-translation-status.md) | सूची उपलब्ध अनुवाद अपडेट
**migrate**  |
[migrate:execute](migrate-execute.md) | अनुप्रयोग के उपलब्ध माइग्रेशन को चलाएं
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | विरासत डेटाबेस के लिए प्रासंगिक माइग्रेशन बनायें और लोड करें
**module**  |
[module:dependency:install](module-dependency-install.md) | Install dependencies module in the application
[module:download](module-download.md) | मोड्यूल या मोड्यूलो को डाउनलोड करें
[module:install](module-install.md) | मोड्यूल या मोड्यूलो को अनुप्रयोग में स्थापित करें
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | अनुप्रयोग में मॉड्यूल की स्थापित रद्द करें |
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:disable](rest-disable.md) | अनुप्रयोग में REST संसाधन अक्षम करें|
[rest:enable](rest-enable.md) | अनुप्रयोग के रेस्ट साधन को चालू करे
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | अनुप्रयोग के मार्ग पथ को पुनर्निर्माण करें
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Drupal कंसोल कॉन्फिग फाइल में एक विशिष्ट सेटिंग मूल्य बदलें
**site**  |
[site:import:local](site-import-local.md) | Import/Configure एक मौजूदा स्थानीय Drupal परियोजना
[site:install](site-install.md) | एक Drupal परियोजना स्थापित करें
[site:maintenance](site-maintenance.md) | साइट को मेंटेनेंस मोड में बदले
[site:mode](site-mode.md) | प्रणाली की कार्य-निष्पादन व्यवस्था को बदलें
[site:statistics](site-statistics.md) | वेबसाइट के मौजूदा आंकड़े बताते हैं।
[site:status](site-status.md) | वर्तमान Drupal स्थापना के स्थिति को देखें
**state**  |
[state:delete](state-delete.md) | स्टेट हटाना।
[state:override](state-override.md) | स्थिति की मौलिक को ओवरराइड करे
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | अनुप्रयोग के उपलब्ध परीक्षणों मे से परिक्षण यूनिट को चलायें
**theme**  |
[theme:download](theme-download.md) | आवेदन में विषय डाउनलोड करे
[theme:install](theme-install.md) | इंस्टॉल विषय या विषयों के आवेदन में
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | विषय की स्थापना रद्द करें या विषयों के आवेदन में
**update**  |
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | मोड्यूल के किसी विशेष नवीनीकरण N फंक्शन को चलायें या सभी को चलायें।
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | एप्लीकेशन के लिए यूजरस को हटाये
[user:login:clear:attempts](user-login-clear-attempts.md) | किसी अकाउंट की असफल लोगिन प्रयासो को साफ़ करें।
[user:login:url](user-login-url.md) | एक बार काम करने वाली उपभोग्ता लोगिन URL देता है।
[user:password:hash](user-password-hash.md) | सरल पासवर्ड से हैश उत्पन्न करें।
[user:password:reset](user-password-reset.md) | किसी विशेष उपभोगता का पासवर्ड रिसेट करें
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:disable](views-disable.md) | एक व्यू बंद करें
[views:enable](views-enable.md) | एक व्यू चालू करें

## Available options
Option | Details
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
--debug | Switches on debug mode
--learning | शब्दबहुल कोड उत्पन्न करें।
--generate-chain | निष्पादन विकल्प में प्रिंट और तर्क को YAML आउटपुट के रूप में श्रृंखला कमांड में इस्तेमाल किया जाएगा
--generate-inline | निष्पादन विकल्प में प्रिंट और तर्क को इनलाइन कॉल के रूप में भविष्य में उपयोग किया जाएगा
--generate-doc | कमाण्ड विकल्पों और तर्क जैसा नीचे निशान
--target | साइट का नाम आप (स्थानीय या दूरस्थ साइटों के लिए ) के साथ बातचीत करना चाहते हैं
--uri | Drupal यूआरआई साइट का(एकाधिक वातावरण के लिए या एक वैकल्पिक port पर चलते समय ) का उपयोग करे
--yes | स्किप कन्फर्मेशन और आगे बढ़ें

## Available arguments
Argument | Details
---------|-------------
command | The command to execute
