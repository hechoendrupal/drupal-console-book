# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Menampilkan informasi dasar mengenai proyek Drupal Console
[chain](chain.md) | Perintah eksekusi Chain
[check](check.md) | Pemeriksa kebutuhan sistem
[exec](exec.md) | Menjalankan perintah eksternal.
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Daftar perintah-perintah yang tersedia
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Bangun ulang dan bersihkan semua cache situs.
**config**  |
[config:delete](config-delete.md) | Hapus konfigurasi
[config:diff](config-diff.md) | Keluaran item konfigurasi aktif yang berbeda dibandingkan dengan pada direktori.
[config:edit](config-edit.md) | Ubah konfigurasi terpilih.
[config:export](config-export.md) | Ekspor konfigurasi aplikasi terkini.
[config:export:content:type](config-export-content-type.md) | Ekspor tipe konten tertentu dan fieldnya.
[config:export:single](config-export-single.md) | Ekspor konfigurasi tunggal sebagai berkas yml.
[config:export:view](config-export-view.md) | Ekspor sebuah view menggunakan format YAML di dalam modul yang disediakan untuk digunakan kembali pada situs web yang lain.
[config:import](config-import.md) | Impor konfigurasi terhada aplikasi terpilih.
[config:import:single](config-import-single.md) | Impor konfigurasi terpilih.
[config:override](config-override.md) | Menimpa nilai konfigurasi pada konfigurasi aktif.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**create**  |
[create:comments](create-comments.md) | Membuat contoh komentar untuk aplikasi Drupal 8 anda.
[create:nodes](create-nodes.md) | Membuat contoh node untuk aplikasi Drupal 8 anda.
[create:terms](create-terms.md) | Membuat contoh terms untuk aplikasi Drupal 8 anda.
[create:users](create-users.md) | Membuat contoh pengguna untuk aplikasi Drupal 8 anda.
[create:vocabularies](create-vocabularies.md) | Membuat contoh vocabularies untuk aplikasi Drupal 8 anda.
**cron**  |
[cron:execute](cron-execute.md) | Jalankan implementasi cron oleh modul atau jalankan semua cron-cron
[cron:release](cron-release.md) | Melepaskan kunci sistem cron untuk menjalan cron kembali
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Menjalankan klien basis data apabila tersedia
[database:connect](database-connect.md) | Menampilkan koneksi basis data
[database:drop](database-drop.md) | Hapus semua tabel pada basis data terpilih.
[database:dump](database-dump.md) | Dump struktur dan kontan dari basis data
[database:log:clear](database-log-clear.md) | Hapus events dari tabel DBlog, filter tersedia
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Mengembalikan struktur dan konten sebuah basis data.
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Tampilkan breakpoints yang tersedia pada aplikasi
[debug:cache:context](debug-cache-context.md) | Tampilkan konteks cache terkini untuk aplikasi.
[debug:chain](debug-chain.md) | Daftar berkas chain yang tersedia.
[debug:config](debug-config.md) | Tunjukkan konfigurasi terkini.
[debug:config:settings](debug-config-settings.md) | Menampilkan key:value terkini pada berkas settings.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Menampilkan servis terkini untuk aplikasi.
[debug:cron](debug-cron.md) | Daftar modul yang mengimplementasikan cron
[debug:database:log](debug-database-log.md) | Menampilkan log event terkini untuk aplikasi
[debug:database:table](debug-database-table.md) | Tunjukkan semua tabel dari basis data tertentu.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Tampilkan event terkini.
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | Display current migration available for the application
[debug:module](debug-module.md) | Display current modules available for application
[debug:multisite](debug-multisite.md) | List all multisites available in system
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
[debug:queue](debug-queue.md) | Display the queues of your application
[debug:rest](debug-rest.md) | Display current rest resource for the application
[debug:router](debug-router.md) | Displays current routes for the application
[debug:settings](debug-settings.md) | List user Drupal Console settings.
[debug:site](debug-site.md) | List all known local and remote sites.
[debug:state](debug-state.md) | Show the current State keys.
[debug:test](debug-test.md) | List Test Units available for the application.
[debug:theme](debug-theme.md) | Displays current themes for the application
[debug:update](debug-update.md) | Display current updates available for the application
[debug:user](debug-user.md) | Displays current users for the application
[debug:views](debug-views.md) | Menampilkan sumber view terkini untuk aplikasi
[debug:views:plugins](debug-views-plugins.md) | Display current views plugins for the application
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**develop**  |
[develop:contribute](develop-contribute.md) | 
[develop:example](develop-example.md) | 
[develop:example:container:aware](develop-example-container-aware.md) | 
[develop:gitbook](develop-gitbook.md) | Update gitbook
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Delete an specific entity
**extend**  |
[extend:example:one](extend-example-one.md) | Drupal Console extend example
[extend:example:two](extend-example-two.md) | Drupal Console extend example
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Hasilkan penyedia otentikasi
[generate:breakpoint](generate-breakpoint.md) | Hasilkan breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Buat perintah console baru.
[generate:controller](generate-controller.md) | Buat dan daftarkan controller
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | commands.generate.doc.cheatsheet.description
[generate:doc:dash](generate-doc-dash.md) | commands.generate.doc.dash.description
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | commands.generate.doc.gitbook.description
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Hasilkan entitas konfigurasi baru
[generate:entity:content](generate-entity-content.md) | Hasilkan sebuah entitas konten baru
[generate:event:subscriber](generate-event-subscriber.md) | Hasilkan langganan event
[generate:form](generate-form.md) | Hasilkan "%s baru"
[generate:form:alter](generate-form-alter.md) | Hasilkan implementasi dari hook_form_alter atau hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | commands.generate.form.description
[generate:help](generate-help.md) | Hasilkan implementasi dari hook_help()
[generate:module](generate-module.md) | Hasilkan modul.
[generate:module:file](generate-module-file.md) | Hasilkan sebuah berkas .module
[generate:permissions](generate-permissions.md) | commands.generate.permission.description
[generate:plugin:block](generate-plugin-block.md) | Hasilkan blok plugin
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Hasilkan tombol plugin CKEditor.
[generate:plugin:condition](generate-plugin-condition.md) | Hasilkan kondisi plugin.
[generate:plugin:field](generate-plugin-field.md) | Hasilkan tipe, widget, dan plugin pemformat untuk field.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Hasilkan plugin untuk pemformat field.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Hasilkan plugin tipe field.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Hasilkan plugin untuk field widget.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generate image effect plugin.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
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
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | Delete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | Download module or modules in application
[module:install](module-install.md) | Install module or modules in the application
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Uninstall module or modules in the application
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**quick**  |
[quick:start](quick-start.md) | Download, install and serve a new Drupal project
**rest**  |
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Enable a rest resource for the application
**router**  |
[router:rebuild](router-rebuild.md) | Rebuild routes for the application
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Pasang proyek Drupal
[site:maintenance](site-maintenance.md) | Switch site into maintenance mode
[site:mode](site-mode.md) | Switch system performance configuration
[site:new](site-new.md) | Download a new Drupal project
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | View current Drupal Installation status
**state**  |
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Override a State key.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Run Test unit from tests available for application
**theme**  |
[theme:download](theme-download.md) | Download theme in application
[theme:install](theme-install.md) | Install theme or themes in the application
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Uninstall theme or themes in the application
**translation**  |
[translation:cleanup](translation-cleanup.md) | commands.translation.cleanup.description
[translation:pending](translation-pending.md) | commands.translation.pending.description
[translation:stats](translation-stats.md) | commands.translation.stats.description
[translation:sync](translation-sync.md) | commands.translation.sync.description
**update**  |
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Execute a specific Update N function in a module, or execute all
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | Clear failed login attempts for an account.
[user:login:url](user-login-url.md) | Returns a one-time user login url.
[user:password:hash](user-password-hash.md) | Generate a hash from a plaintext password.
[user:password:reset](user-password-reset.md) | Reset password for a specific user.
[user:role](user-role.md) | Tambah/hapus peran untuk pengguna tertentu
**views**  |
[views:disable](views-disable.md) | Menonaktifkan View
[views:enable](views-enable.md) | Mengaktifkan View

## Available options
Option | Details
-------|-------------
--help | Tampilkan pesan bantuan ini
--quiet | Jangan keluarkan pesan apapun dari perintah ini
--verbose | Tingkatkan perincian dari pesan-pesan: 1 untuk keluaran normal, 2 untuk keluaran lebih rinci dan 3 untuk debug
--version | Tampilkan versi aplikasi Drupal
--ansi | Paksakan keluaran ANSI
--no-ansi | Matikan keluaran ANSI
--no-interaction | Jangan tanya pertanyaan interaktif
--env | Nama Environment
--root | Tentukan root dari Drupal untuk digunakan dalam menjalankan perintah
--debug | application.options.debug
--learning | Tampilkan hasil kode secara rinci
--generate-chain | Tampilkan opsi dan argumen dari perintah dalam format YAML untuk dipakai di chain command (perintah rentetan)
--generate-inline | Tampilkan opsi dan argumen dari perintah dalam format barisan perintah
--generate-doc | Tampilkan opsi dan argumen dari perintah dalam format markdown
--target | Nama situs untuk berinteraksi (untuk situs lokal atau situs remote)
--uri | URI dari situs Drupal (untuk instalasi multi-situs atau kalau situsnya dijalankan di port lain selain port 80)
--yes | Lewatkan konfirmasi dan lanjutkan

## Available arguments
Argument | Details
---------|-------------
command | Perintah untuk dijalankan
