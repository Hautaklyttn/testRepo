# HiL-Application-Wiki
Wiki for articles and information to share within the HiL Application teams ww  

https://github.geo.conti.de/pages/VED-CarMaker-HIL/HiL-Application-Wiki/

&nbsp;

***

&nbsp;

## How to Contribute to this Wiki  

As this Wiki is created with *Python Sphinx*, we need some additional installation on your local system.

#### ToDo once

1. If not already done, install [Python](https://www.python.org/downloads/) (3.8 or higher) on your local system 
2. Add the Python folder to your Windows environment variables ('PATH') if not already done during the Python installation.
2. Install the required python packages  
    ```   
      >> pip install sphinx_rtd_theme
      
      >> pip install sphinx_markdown_tables

      >> pip install sphinx_git

      >> pip install recommonmark
    ```
3. Clone the Wiki repo to your local system

&nbsp;
#### ToDo every time before push to GitHub

1. Update the Wiki in the */source* folder
2. Save your changes.
3. Open Windows command line and navigate to the root folder of the repository
4. Enter `make release`  
   &rarr; This creates the HTML code, the search code, etc and copies everything to the */docs* folder
5. Push your changes to GitHub

&nbsp;

## Local Preview

In case you want to have a local preview of your changes, you can do the following:

1. Update the Wiki in the */source* folder
2. Save your changes
3. Open Windows command line and navigate to the root folder of the repository
4. Enter `make build_html`  
   &rarr; This creates the HTML code, etc
5. Inside your repo navigate to */build/html* and double-click on `index.html`
6. This will open the Wiki page locally containing your changes

&nbsp;

## Please keep in mind:

- You can add code in ``Markdown`` or in ``RestructuredText``, both are supported.  
  &rarr; but don't mix the two inside one file, a file can contain the one or the other
- The *table of contents* is created automatically using the headlines (in markdown: #, ##, ###)  
  &rarr; Check the **Content** navigation bar on the left if your headlines are set correctly after implementing your changes



