# उपलब्ध Drupal Console आदेश.

**टीप:** Drupal 8 प्रतिष्ठापन रूट पासून Drupal Console आदेश चालविणे आवश्यक आहे..

Drupal Console आदेश | तपशील
------------ | -------------
**misc**  |
[about](about.md) | Drupal Console प्रकल्पाबद्दल मूलभूत माहिती प्रदर्शित करते.
[chain](chain.md) | साखळी आदेशाची अंमलबजावणी करावी.
[check](check.md) | सिस्टम आवश्यकता तपासक.
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | बाह्य आदेश चालवा.
[help](help.md) | आदेशासाठी मदत दर्शवितो.
[init](init.md) | कॉन्फिगरेशन फायलींना वापरकर्ता होम डिरेक्ट्रीमध्ये कॉपी करा.
[list](list.md) | सर्व उपलब्ध आदेशांची यादी करा.
[shell](shell.md) | परस्परसंवादी REPL(रीड-इव्हल-प्रिंट-लूप) प्रदान करणारे शेल उघडा.
[server](server.md) | PHP मध्ये अंगभूत वेब सर्व्हर चालविते.
**cache**  |
[cache:rebuild](cache-rebuild.md) | सर्व साईट caches स्वच्छ तसेच पुन्हानिर्मित.
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | संरचना हटवा
[config:diff](config-diff.md) | एक निर्देशिका तुलनेत सक्रिय संरचना भिन्न आहेत की आउटपुट कॉन्फिगरेशन आयटम.
[config:edit](config-edit.md) | निवडलेले संरचना संपादित करा.
[config:export](config-export.md) | वर्तमान अनुप्रयोग कॉन्फिगरेशन निर्यात करा.
[config:export:content:type](config-export-content-type.md) | विशिष्ट सामग्री प्रकार आणि त्यांचे फील्ड निर्यात करा.
[config:export:single](config-export-single.md) | Yml फाइल म्हणून एकच कॉन्फिगरेशन निर्यात करा.
[config:export:view](config-export-view.md) | अन्य वेबसाइटवर पुनर्वापरासाठी प्रदान केलेल्या मॉड्यूलमध्ये YAML स्वरूपात एक दृश्य निर्यात करा.
[config:import](config-import.md) | वर्तमान अनुप्रयोगावरील कॉन्फिगरेशन आयात करा.
[config:import:single](config-import-single.md) | निवडलेले कॉन्फिगरेशन आयात करा.
[config:override](config-override.md) | सक्रिय कॉन्फिगरेशनमध्ये कॉन्फिगर मूल्य अधिशून्य करा.
[config:validate](config-validate.md) | त्याच्या स्कीमा विरूद्ध drupal कॉन्फिगरेशन प्रमाणित करा.
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | आपल्या Drupal 8 अनुप्रयोगासाठी डमी टिप तयार करा.
[create:nodes](create-nodes.md) | आपल्या Drupal 8 अनुप्रयोगासाठी डमी नोड्स तयार करा.
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | आपल्या Drupal 8 अनुप्रयोगासाठी डमी अटी तयार करा.
[create:users](create-users.md) | आपल्या Drupal 8 अनुप्रयोगासाठी डमी वापरकर्ते तयार करा.
[create:vocabularies](create-vocabularies.md) | आपल्या Drupal 8 अनुप्रयोगासाठी डमी शब्दसंग्रह तयार करा.
**cron**  |
[cron:execute](cron-execute.md) | क्रॉन लागू करणारे काही विशेष मोड्यूल चालावा अथवा सर्व क्रॉन चालवा.
[cron:release](cron-release.md) | क्रॉन चालवण्यासाठी क्रोन प्रणालीचे लॉक मुक्त करा.
**database**  |
[database:add](database-add.md) | Settings.php वर एक डेटाबेस जोडा.
[database:client](database-client.md) | DB पक्षकार उपलब्ध असेल तर सुर्वाथ करा
[database:connect](database-connect.md) | डीबी कनेक्शन दर्शविते.
[database:drop](database-drop.md) | दिलेल्या डेटाबेसमध्ये सर्व सारण्या ड्रॉप करा.
[database:dump](database-dump.md) | डंप संरचना आणि डेटाबेसची सामग्री.
[database:log:clear](database-log-clear.md) | DBLog सारणीतून कार्यक्रम काढा, फिल्टर उपलब्ध आहेत.
[database:log:poll](database-log-poll.md) | वॉचडॉगला मत द्या आणि नवीन लॉग नोंदी प्रत्येक x सेकंद प्रिंट करा
[database:query](database-query.md) | एक SQL विधान थेट वितर्क म्हणून चालवा.
[database:restore](database-restore.md) | संरचना आणि डेटाबेसची सामग्री पुनर्संचयित करा.
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | अनुप्रयोग मध्ये उपलब्ध असलेले ब्रेकपॉइंट प्रदर्शित करते.
[debug:cache:context](debug-cache-context.md) | अनुप्रयोगासाठी वर्तमान कॅशे संदर्भ प्रदर्शित करते.
[debug:chain](debug-chain.md) | उपलब्ध असलेल्या साखळी फाइल्स यादी
[debug:config](debug-config.md) | चालू संरचना दाखवा.
[debug:config:settings](debug-config-settings.md) | चालू की प्रदर्शित करते: सेटिंग्ज फाइलवरील मूल्य.
[debug:config:validate](debug-config-validate.md) | मॉड्युल प्रतिष्ठापित होण्याआधी स्कीमा अंमलबजावणी प्रमाणित करा.
[debug:container](debug-container.md) | अनुप्रयोग चालू सेवा दाखवा.
[debug:cron](debug-cron.md) | क्रॉन लागू करण्यासाठी मोड्यूलची यादी.
[debug:database:log](debug-database-log.md) | अनुप्रयोगासाठी वर्तमान लॉग इव्हेंट प्रदर्शित करा.
[debug:database:table](debug-database-table.md) | दिलेल्या डेटाबेसमध्ये सर्व सारण्या दर्शवा.
[debug:entity](debug-entity.md) | सिस्टममध्ये उपलब्ध असलेल्या डीबग घटक.
[debug:event](debug-event.md) | वर्तमान इव्हेंट प्रदर्शित करा.
[debug:features](debug-features.md) | नोंदणीकृत वैशिष्ट्ये सूचीबद्ध करा.
[debug:image:styles](debug-image-styles.md) | साइटवरील प्रतिमा शैलीची यादी
[debug:libraries](debug-libraries.md) | अनुप्रयोगात उपलब्ध असलेले लायब्ररी प्रदर्शित करते.
[debug:migrate](debug-migrate.md) | अनुप्रयोगासाठी वर्तमान स्थलांतर प्रदर्शित करा.
[debug:module](debug-module.md) | अनुप्रयोगासाठी उपलब्ध असलेले वर्तमान मॉड्यूल प्रदर्शित करा.
[debug:multisite](debug-multisite.md) | सिस्टीममध्ये उपलब्ध सर्व मल्टीसाइट्सची यादी करा.
[debug:permission](debug-permission.md) | सर्व वापरकर्ता परवानग्या प्रदर्शित करते.
[debug:plugin](debug-plugin.md) | सर्व प्लगिन प्रकार, एका विशिष्ट प्रकारच्या प्लगिनची उदाहरणे, किंवा विशिष्ट प्लगइनसाठी परिभाषित करा.
[debug:queue](debug-queue.md) | आपल्या अनुप्रयोगाचे क्यू प्रदर्शित करा.
[debug:rest](debug-rest.md) | चालू रेस्ट अर्ज संसाधन प्रदर्शित करा
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | अनुप्रयोग चालू मार्ग दाखवतो
[debug:settings](debug-settings.md) | यादी वापरकर्ता Drupal कंसोल सेटिंग्ज.
[debug:site](debug-site.md) | सर्व ज्ञात स्थानिक आणि दूरस्थ साइटची सूची करा.
[debug:state](debug-state.md) | वर्तमान अवस्था की दाखवा.
[debug:test](debug-test.md) | अनुप्रयोगासाठी उपलब्ध चाचणी आयटम्स.
[debug:theme](debug-theme.md) | अनुप्रयोगासाठी वर्तमान थीम प्रदर्शित करते.
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | ऐप्लकैशन साठी वर्तमानात उपलब्ध सुधारणा प्रदर्शित करा.
[debug:user](debug-user.md) | ऐप्लकैशनचे वर्तमान वापरकर्ते दाखवतो.
[debug:views](debug-views.md) | अनुप्रयोगासाठी वर्तमान दृश्ये प्रदर्शित करा.
[debug:views:plugins](debug-views-plugins.md) | अनुप्रयोगासाठी वर्तमान दृश्ये प्लगइन प्रदर्शित करा.
**devel**  |
[devel:dumper](devel-dumper.md) | commands.devel.dumper.messages.change-devel-dumper-plugin
**docker**  |
[docker:init](docker-init.md) | Create a docker-compose.yml file
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | एखादी विशिष्ट एंटिटी हटवा.
**features**  |
[features:import](features-import.md) | मॉड्यूल कॉन्फिगरेशन आयात करा.
**field**  |
[field:info](field-info.md) | फील्डबद्दल माहिती पहा.
**generate**  |
[generate:ajax:command](generate-ajax-command.md) | Generate & Register a custom ajax command
[generate:authentication:provider](generate-authentication-provider.md) | एक प्रमाणीकरण प्रदाता उत्पन्न करा.
[generate:breakpoint](generate-breakpoint.md) | ब्रेकपॉईंट उत्पन्न करा.
[generate:cache:context](generate-cache-context.md) | कॅशे संदर्भ उत्पन्न करा.
[generate:command](generate-command.md) | कन्सोलसाठी आदेश उत्पन्न करा.
[generate:controller](generate-controller.md) | उत्पन्न करा आणि कंट्रोलर नोंदवा
[generate:entity:bundle](generate-entity-bundle.md) | नवीन सामग्री प्रकार उत्पन्न करा (नोड / एंटिटीचे बंडल)
[generate:entity:config](generate-entity-config.md) | नवीन कॉन्फिग एंटिटी उत्पन्न करा.
[generate:entity:content](generate-entity-content.md) | एक नवीन सामग्री एंटिटी उत्पन्न करा.
[generate:event:subscriber](generate-event-subscriber.md) | एक कार्यक्रम ग्राहक उत्पन्न करा.
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Hook_form_alter() किंवा hook_form_FORM_ID_alter चा अंमलबजावणी उत्पन्न करा.
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | hook_help() चे लागूकरण उत्पन्न करा.
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | मॉड्यूल उत्पन्न करा.
[generate:module:file](generate-module-file.md) | .module फाइल उत्पन्न करा
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | प्लगइन ब्लॉक उत्पन्न करा.
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | CKEditor बटण प्लगइन उत्पन्न करा.
[generate:plugin:condition](generate-plugin-condition.md) | प्लगिन स्थिती उत्पन्न करा.
[generate:plugin:field](generate-plugin-field.md) | फील्ड प्रकार, विजेट आणि फॉर्मेटर प्लगइन उत्पन्न करा.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | फील्ड फॉर्मेटर प्लगइन उत्पन्न करा.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | फील्ड प्रकार प्लगिन उत्पन्न करा.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | फिल्ड विजेट प्लगिन उत्पन्न करा.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | प्रतिमा प्रभाव प्लगइन उत्पन्न करा.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | प्रतिमा फॉर्मेटर प्लगइन उत्पन्न करा.
[generate:plugin:mail](generate-plugin-mail.md) | एक प्लगइन मेल उत्पन्न करा.
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | एक स्थलांतर प्रक्रिया प्लगइन उत्पन्न करा.
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | माइग्रेट स्रोत प्लगइन उत्पन्न करा.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | प्लगइन उर्वरित संसाधन उत्पन्न करा.
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | प्लगिन नियम क्रिया उत्पन्न करा.
[generate:plugin:skeleton](generate-plugin-skeleton.md) | त्या प्लगिनसाठी स्केप्लेट प्लगइनची अंमलबजावणी उत्पन्न करा Drupal Console मध्ये विशिष्ट जनरेटर नाही.
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | भाष्येच्या शोधासह प्लगिन प्रकार उत्पन्न करा.
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Yaml शोधसह एक प्लगिन प्रकार उत्पन्न करा.
[generate:plugin:views:field](generate-plugin-views-field.md) | सानुकूल प्लग इन दृश्य फील्ड उत्पन्न करा.
[generate:post:update](generate-post-update.md) | Hook_post_update_NAME() चा अंमलबजावणी उत्पन्न करा.
[generate:profile](generate-profile.md) | प्रोफाइल उत्पन्न करा.
[generate:routesubscriber](generate-routesubscriber.md) | एक RouteSubscriber उत्पन्न करा.
[generate:service](generate-service.md) | सेवा उत्पन्न करा
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | थीम उत्पन्न करा.
[generate:twig:extension](generate-twig-extension.md) | एक ट्विंग विस्तार उत्पन्न करा.
[generate:update](generate-update.md) | hook_update_N() चा अंमलबजावणी उत्पन्न करा.
**image**  |
[image:styles:flush](image-styles-flush.md) | प्रतिमा शैली फ्लश कार्य अंमलात किंवा सर्व फ्लश प्रतिमा शैली कार्यान्वित.
**locale**  |
[locale:language:add](locale-language-add.md) | आपल्या साइटद्वारे समर्थित करण्यासाठी एक भाषा जोडा.
[locale:language:delete](locale-language-delete.md) | आपल्या साइटद्वारे समर्थित केलेली भाषा हटवा.
[locale:translation:status](locale-translation-status.md) | उपलब्ध अनुवाद अद्यतने सूची.
**migrate**  |
[migrate:execute](migrate-execute.md) | अनुप्रयोगासाठी उपलब्ध स्थलांतरित करा.
[migrate:rollback](migrate-rollback.md) | एक किंवा अनेक माइग्रेशन रोलबॅक करा.
[migrate:setup](migrate-setup.md) | दिलेल्या लेगसी डेटाबेससाठी संबंधित स्थानांतरण स्थापन करा आणि तयार करा.
**module**  |
[module:dependency:install](module-dependency-install.md) | अनुप्रयोगामध्ये अवलंबन मॉड्यूल स्थापित करा.
[module:download](module-download.md) | अर्ज मॉड्यूल किंवा मॉड्यूल डाउनलोड करा.
[module:install](module-install.md) | अनुप्रयोग मध्ये मॉड्यूल किंवा मॉड्यूल स्थापित.
[module:path](module-path.md) | मॉड्यूलला सापेक्ष पथ परत मिळवते (किंवा निरपेक्ष पथ).
[module:uninstall](module-uninstall.md) | अनुप्रयोगात मोड्यूल किंवा मोड्यूल्स अनइन्स्टॉल करा.
[module:update](module-update.md) | अनुप्रयोग मध्ये अद्यतन कोर, मॉड्यूल किंवा मॉड्यूल्स.
**multisite**  |
[multisite:new](multisite-new.md) | नवीन बहुउद्देशीय प्रतिष्ठापनासाठी फायली सेट करते.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | नोड प्रवेश परवानग्या पुन्हा तयार करा. पुनर्निर्माण सामग्रीसाठी सर्व विशेषाधिकार काढून टाकेल आणि वर्तमान मॉड्यूल्स आणि सेटिंग्जवर आधारित परवानग्या पुनर्स्थित करेल.
**queue**  |
[queue:run](queue-run.md) | निवडलेल्या रांगांवर प्रक्रिया करा.
**rest**  |
[rest:disable](rest-disable.md) | अर्ज REST संसाधन अक्षम.
[rest:enable](rest-enable.md) | अनुप्रयोगासाठी विश्रांती संसाधन सक्षम करा.
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | अर्ज मार्ग पुनः बिल्ड करा.
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Drupal Console कॉन्फिग फाइलमध्ये विशिष्ट सेटिंग मूल्य बदला.
**site**  |
[site:import:local](site-import-local.md) | अस्तित्वातील स्थानिक Drupal प्रोजेक्ट आयात/कॉन्फिगर करा.
[site:install](site-install.md) | एक Drupal प्रकल्प स्थापित.
[site:maintenance](site-maintenance.md) | साइटला देखभाल मोडमध्ये स्विच करा.
[site:mode](site-mode.md) | सिस्टम कार्यक्षमता कॉन्फिगरेशन स्विच करा.
[site:statistics](site-statistics.md) | वेबसाइटच्या वर्तमान आकडेवारी दर्शवा.
[site:status](site-status.md) | वर्तमान Drupal स्थापना स्थिती पहा.
**state**  |
[state:delete](state-delete.md) | स्थिती हटवा.
[state:override](state-override.md) | एखाद्या स्थिती की वर अधिशून्य करा.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | एक शब्दसंग्रह पासून वर्गीकरणातील अटी हटवा.
**test**  |
[test:run](test-run.md) | ऍप्लिकेशनसाठी उपलब्ध असलेल्या चाचण्यांमधून टेस्ट युनिट चालवा.
**theme**  |
[theme:download](theme-download.md) | अनुप्रयोगामध्ये थीम डाउनलोड करा.
[theme:install](theme-install.md) | अनुप्रयोगामध्ये थीम किंवा थीम स्थापित करा.
[theme:path](theme-path.md) | थीमवरील सापेक्ष पथ (किंवा निरपेक्ष पथ) मिळवते.
[theme:uninstall](theme-uninstall.md) | थीममध्ये थीम किंवा थीम विस्थापित करा.
**update**  |
[update:entities](update-entities.md) | अस्तित्व सुधारणा अर्ज
[update:execute](update-execute.md) | विभागाची एक विशिष्ट सुधारणा N कार्य चालवा, किंवा सर्व कार्ये चालवा.
**user**  |
[user:create](user-create.md) | अनुप्रयोगासाठी वापरकर्ते तयार करा.
[user:delete](user-delete.md) | ऐप्लकैशनचे वापरकर्ते हटवा.
[user:login:clear:attempts](user-login-clear-attempts.md) | एखाद्या खात्यासाठी अयशस्वी लॉगिन प्रयत्न साफ ​​करा.
[user:login:url](user-login-url.md) | एक-प्रयोगकर्ता लॉगिन url मिळवते.
[user:password:hash](user-password-hash.md) | साधा मजकूर पासवर्ड पासून एक हॅश उत्पन्न करा.
[user:password:reset](user-password-reset.md) | एका विशिष्ट वापरकर्त्यासाठी संकेतशब्द रीसेट करा.
[user:role](user-role.md) | दिलेल्या वापरकर्त्यासाठी भूमिका जोडते / काढते.
**views**  |
[views:disable](views-disable.md) | एक दृश्य अक्षम करा.
[views:enable](views-enable.md) | एक दृश्य सक्षम करा.

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--help | मदतीचे संदेश प्रदर्शित करा.
--quiet | कोणतेही संदेश उत्पादीत करू नये.
--verbose | संदेश पाल्हळीक्ता वाढविण्यासाठी : 1 सामान्य आउटपुट करीता, 2 अधिक पाल्हाळीक आउटपुट करीता आणि 3 डिबग मोड.
--version | अनुप्रयोग आवृत्ती प्रदर्शित करा.
--ansi | सक्षम ANSI आउटपुट.
--no-ansi | अक्षम ANSI आउटपुट.
--no-interaction | कोणत्याही परस्पर प्रश्न विचारू नका.
--env | पर्यावरणांचे नाव.
--root | आदेश चालविण्या करीता Drupal रूट परिभाषित करा.
--debug | Switches on debug mode
--learning | पाल्हाळीक कोड़ची निर्मिती कर.
--generate-chain | साखळी आदेशामध्ये yaml आऊटपुट वापरले जाते जे आदेश पर्याय आणी वितर्क आहे.
--generate-inline | आदेश पर्याय आणी वितर्क यांस इनलाइन आदेश असे दाखवा.
--generate-doc | आदेश पर्याय आणी वितर्क यांस मार्क्डोव्न असे दाखवा.
--target | साइट चे नावं आपण ( स्थानिक किंवा दूरस्थ ) संभाषण साधण्यासाठी करतो.
--uri | Drupal साइटच्या यूआरआई चा वापर ( अनेक वातावरणांसाठी किंवा एक पर्यायी port वर चालवण्यासाठी ) होते.
--yes | खात्री वगळा आणि पुढे चालू ठेवा.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
command | चालविण्याजोगी आदेश.
