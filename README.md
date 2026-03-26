## Marketing Site

Static, simple, and template-free. Open to any and all customizability!

Note that any files stored in this repo are publicly accessible.

### Running the Site Locally

Because CORS are always blocked when attempted from a file on disk (e.g. via the file:// protocol), and we rely on GCS for storage of images and other assets, we must locally host these web pages using a web server for testing purposes. And, because they're super lightweight, anything from the npm or Pythonic ecosystems will suffice. For example, consider use of the following command:

`python3 -m http.server 9999`

Then, you can navigate to localhost:9999 on your browser to our marketing site.