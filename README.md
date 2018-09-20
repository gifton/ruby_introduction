# ruby_introduction
An introduction of ruby
# Downloads

* [Download ruby](https://www.ruby-lang.org/en/documentation/installation/)
* [Download sqlite3](https://www.tutorialspoint.com/sqlite/sqlite_installation.htm)

# helpful links

* [Ruby in 20 minutes](https://www.ruby-lang.org/en/documentation/quickstart/)
* [rails cheatsheat](https://gist.github.com/mdang/95b4f54cadf12e7e0415)
* [rails pipeline walkthrough](https://guides.rubyonrails.org/asset_pipeline.html)
* [rendering and layouts](https://guides.rubyonrails.org/layouts_and_rendering.html)
* [forms](https://guides.rubyonrails.org/form_helpers.html)

# Structre breakdown

### Structure

| Folder               | Description         |
| ----------------- | ------------------- |
| app/                  | Contains the controllers, models, views, helpers, mailers, channels, jobs and assets for your application. You’ll focus on this folder for the remainder of this guide. |
| bin/                   | Contains the rails script that starts your app and can contain other scripts you use to setup, update, deploy or run your application. |
| config/              | Configure your application’s routes, database, and more. This is covered in more detail in  [Configuring Rails Applications](https://guides.rubyonrails.org/configuring.html) . |
| db/                    | Contains your current database schema, as well as the database migrations. |
| Gemfile, Gemfile.lock | These files allow you to specify what gem dependencies are needed for your Rails application. These files are used by the Bundler gem. For more information about Bundler, see the  [Bundler website](https://bundler.io/) . |
| lib/                     | Extebded modules for your application |
| log/                    | Application log files |
| package.json     | This file allows you to specify what npm dependencies are needed for your Rails application. This file is used by Yarn. For more information about Yarn, see the  [Yarn website](https://yarnpkg.com/lang/en/) . |
| public/                | The only folder seen by the world as-is. Contains static files and compiled assets. |
| Rakefile              | This file locates and loads tasks that can be run from the command line. The task definitions are defined throughout the components of Rails. Rather than changing Rakefile, you should add your own tasks by adding files to the lib/tasks directory of your application. |
| test/                    | Unit tests, fixtures, and other test apparatus. These are covered in  [Testing Rails Applications](https://guides.rubyonrails.org/testing.html) . |
| tmp/                    | Temporary files (like cache and pid files). |
| vendor/               | A place for all third-party code. In a typical Rails application this includes vendored gems. |

