This repository contains my blog that uses [Jekyll](https://jekyllrb.com/) based on the [Long Haul](https://github.com/brianmaierjr/long-haul) theme. I have made some customizations to the Long Haul theme with changes in fonts and content alignment. The SASS, Gulp, BrowserSync and Autoprefixer integration still exists. I have also added Sourcemaps support.

## Installation

1. Install ruby on your system if not already installed. For Ubuntu, you could use the following commands:

   ```
   sudo apt install ruby
   ```

2. Run the gem command as follows to install all Ruby dependencies including Jekyll:

   ```
   gem install
   ```

3. Run the following to install gulp and other dependencies:

   ```

   npm install
   ```

4. To start the local webserver and start serving content, run the following command:

   ```
   gulp
   ```
5. Point your browser to http://localhost:3000 to see your blog content locally.

## Site Settings

The main settings can be found inside the `_config.yml` file:

- **title:** title of your site
- **description:** description of your site
- **url:** your url
- **paginate:** the amount of posts displayed on homepage
- **navigation:** these are the links in the main site navigation
- **social** diverse social media usernames (optional)
- **google_analytics** Google Analytics key (optional)

## License

The following directories and their contents are copyrighted by Leander Perera:

- _posts/
- images/

You may not reuse any of the above directories without my permission.

All other directories and files are under the [MIT](LICENSE).
