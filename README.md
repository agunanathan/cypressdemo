# cypressdemo

Repo Installation Steps:
1. clone repo
2. Run "npm install"

Running Percy Demo:  (NOTE!!:  The PERCY_TOKEN here is from a free Percy Test Account for demonstration purpose.  When you have your own PERCY_TOKEN for your own project make sure that you hide them in some sort of a configuration file which is not committed to your codebase for security reasons)

1. set percy token by pasting "export PERCY_TOKEN=42a8d0a3e2f42dee7c2dc142ce44ff2811e9aa4fcfd7eb1d52770cc42e30ddf5" on command line
2. npx percy exec -- cypress run --spec cypress/e2e/visual-tool-demos/navigation-percy-demo.cy.js
