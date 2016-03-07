### Resume built with http://jsonresume.org/getting-started/ and https://github.com/hacksalot/HackMyResume generator

### Build process
1. [sudo] npm install hackmyresume -g
2. Install [wkhtmltopdf](http://wkhtmltopdf.org/downloads.html)
3. sudo npm install -g resume-cli
4. run `hackmyresume BUILD resume.json TO out/resume.all -t node_modules/jsonresume-theme-flat`
5. Test by checking files in `/out` folder
6. Publish by running `resume publish`
